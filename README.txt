VRTL for Unreal Engine 5.1.0
	Thank you for purchasing our VR True Locomotion System and Thumbstick Movement System Marketplace asset!

	VRTL was developed on the Oculus Rift S and Quest 2, though most of the blueprinting will be compatible with the other HMDs. 

HANDS-FREE MODE:
	What is VR True Locomotion Hands-Free Movement?
		Instead of using a controller to achieve infinite 'smooth' locomotion in VR, VRTL uses the HMD rotational information to apply movement to the player. 
		There are three different types of movement the VRTL system can make use of:
			Forward/Backwards Translation - Walking/Running, which is controlled via the 'pitch' rotation axis.
			Right/Left Rotation - Continuous Turning, which is controlled via the 'yaw' rotation axis.
			Right/Left Translation - Strafing, which is controlled via the 'roll' rotation axis.
	
		Each function can be enabled or disabled independently, and all metrics and values can be tweaked to match your use case.

	How to play and try out VR True Locomotion Hands-Free Movement:
		Play the included Level Select Map.
		Choose the tutorial level for a stepwise walkthrough.
		Once you're familiar with the system, you can go to the unreal default VR map, and select "Hands-Free."
		Press the X Button on your Left Oculus Touch controller to toggle the system ON.
		Turn your head left and right to continuously rotate left and right.  Rotation will stop when your head rotation is back to it's original zero position.
		Tilt your head forward and backwards to walk/run forwards or backwards.
		Tilt your head towards your left or right shoulder to strafe left or right.
		Press the Left Controller X Button again to toggle the system OFF, at which point if you're standing you can play in room scale the default VR HMD functionality (once you have defined a guardian area).
		
	Hands-Free Mode Recommendations:
		There are a few variables that we recommend NOT altering (unless you are sure you understand how the system works of course). 
		The variables I recommend leaving to defaults are the “Min/Max HMD(Pitch/Roll/Yaw) Range”, as well as the “Clamped(Pitch/Yaw/Roll)Input” variables.

How to add VRTL to your existing project:
	Create and open a VRTL asset project
	In your new VRTL asset project, go to:
		"Content Drawer/Content"
		Right-click on the "VRTrueLocomotion" folder and select Migrate. This will open the Asset Report window.
		In the Asset Report window, make sure to migrate only the "VRTrueLocomotion" folder (and its contents), then click "OK", which will open Windows File Explorer.		
		Navigate to the "[YourProject]\Content" folder and click "OK" to migrate.
	
	CRITICAL STEPS:
		ENABLE INPUT MAPPINGS:
			After Migration, go to your "Project Settings\Plugins\OpenXR Input", then change OpenXR Input to "PMI_VRTL". 
		
		SET GAMEMODE:
			In the DefaultVR Template map, open World Settings window and set GAMEMODE to "TrueLocomotion_GameMode".
			(If you prefer to use your GameMode just set the character to "BP_VRTLTrueLocomotionCharacter" in your GameMode)


Keep in touch! Let us know your unique use cases and solutions! Contact AlexRogan@BlueDendrites.com.

For tech questions, support, or feature requests, contact AlexRogan@BlueDenderites.com.

P.S. Remember to "Allow Unknown Sources" In your HMD's settings or you may not be able to test with your HMD in the editor!