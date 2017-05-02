### "Shoot the Hoop" Game Introduction ###

+ Your first 3D game
+ No VR device is required
+ Cardboard and Rift are optional

### Game Design Document Recap ###

+ We review the GDD format.
+ Brainstorm Concepts, Rules and Requirements.
+ Outline the scope for the section.

### Creating a 3D Scene ###

+ Introduction to the Unity Editor.
+ Adding 3D objects to a scene.
+ Moving, Scaling and Rotating.
+ Previewing our work.

### Rigidbody Physics ###

+ Introduction to Components.
+ Using the inspector.
+ Adding Rigidbody physics.
+ Making objects collide.
+ Playing with physics.

### Smart Copies with Prefabs ###

+ Brief introduction to materials.
+ Prefabs as linked copies.
+ Overriding prefab values.
+ Reverting prefab values.

### Instantiating Prefabs in Code ###

+ Creating instances programmatically.
+ The Instantiate() function.
+ Recap of if statements and GetKeyDown().

### Adding Velocity to the Ball ###

+ Accessing components in code.
+ Return values of functions.
+ GetComponent<>() function.
+ Adding velocity to a Rigidbody.

### Rotating the Camera in Code ###

+ Rotating the camera.
+ Updating transform.rotation.
+ The Quaternion type.
+ Quaternion multiplication and rotation.

### Taking Mouse Input ###

+ The Unity InputManager settings.
+ Using Input.GetAxis().
+ Updating our rotation based on mouse input.

### Creating a Camera Gimbal ###

+ Understanding rotation behaviour.
+ Parenting game objects.
+ Avoiding camera tilt in mouse look.
+ Creating a camera gimbal.

### Controlling the Camera Gimbal ###

+ Accessing components of child objects.
+ Correct script placement in a hierarchy.
+ Global rotation vs localRotation.

### Setting the Ball Spawn Location ###

+ Refactoring the BallSpawner script.
+ Setting the spawn position for prefabs.
+ Exposing fields to the designer.

### Getting the Look Direction ###

+ Recapping rotations.
+ Rotations and vectors.
+ Calculating the “look direction”.

### Collisions in Code ###

+ Collision components.
+ Introducing OnCollisionEnter().
+ Starting to keep score

### Keeping Score Globally ###

+ Creating a central score keeper.
+ Finding components globally.
+ Introduction to public methods.
+ Getting objects with FindObjectOfType<>().

### Using Multiple Scenes ###

+ Organising multiple scenes.
+ Understanding scene buildIndex.
+ Loading levels in code.

### Creating Menu Screen UI ###

+ Introducing the UI canvas.
+ Adding background images.
+ Finding uncopyrighted images.
+ Dealing with multiple screen sizes.

### UI Text and Fonts ###

+ How to find suitable fonts.
+ Adding text to UI canvas.
+ Importing fonts into Unity.

### UI Buttons and Code ###

+ Adding and styling UI buttons.
+ Connecting UI buttons to objects.
+ Calling code OnClick.
+ Writing LoadPreviousScene().

### Timing and Triggering Events ###

+ Introducing Time.deltaTime.
+ How to implement a timer.
+ Creating a default of no progression.

### Updating UI Text to Show Score ###

+ Separation of presentation and data. 
+ Updating UI text in code. 
+ Creating a HUD. 
+ Testing multiple screen resolutions. 

### Persisting Data Between Scenes ###

+ GameObject lifetime in scenes. 
+ Introduction to DontDestroyOnLoad(). 
+ Ending the lifetime manually. 
+ Displaying the score on game over.

### Converting to Oculus Rift ###

+ Installing the Oculus SDK. 
+ Enabling VR support in Unity. 
+ Converting an existing project to VR.

### UI for the Oculus Rift ###

+ Putting UI in World Space.
+ Scaling and positioning UI canvases. 
+ Creating prefabs to avoid duplication.

### Importing Assets to Build Levels ###

+ Importing Unity asset packages. 
+ Making our scene look beautiful. 
+ Playtesting the game for difficulty.

### Using Triggers to Detect Scoring Baskets ###

+ Triggers and OnTriggerEnter(). 
+ Writing a script from scratch. 
+ Revising script communication. 
+ Detecting baskets properly.

### Audio and Music ###

+ Adding Audio Sources in Unity. 
+ Properties of Audio Sources. 
+ Autoplaying and looping music.

### Triggering Sounds in Code ###

+ Audio Source components. 
+ Triggering SFX in code.
+ The AudioSource.Play() method.

### Section 3 Wrap-Up ###

+ Congratulations
+ What you learnt in this section
+ Share your creation with other students
