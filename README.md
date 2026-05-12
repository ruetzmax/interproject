# About
In many collaborative settings that take place in a hybrid environment (i.e. real-world meeting interacting with digital content), determining spatial correspondences between the world space and the digital space are essential for solving a wide array of tasks. While this correspondence matching is fairly trivial in small setting, such as two people working in front of a single screen, this doesn't scale well to groups with more collaborators. To intuitively solve the spacial correspondence search for arbitrarily complex setting, I propose Interproject, a system allowing any number of users to perform interactions through their mobile phone display on a large (projected) display surface. Each individual user's viewport is augmented with information specific to the user. This is achieved through a mobile phone app having access to the camera feed of the image displayed by the projector, for which a conversion between these systems is performed. As a possible use case, the technique is applied as part of a room furnishing tool.

# Links
The implementation of the project is distributed over multiple components:
- A [TypeScript / ReactNative app](https://github.com/ruetzmax/interproject-app) for capturing the phone's camera feed and touch interactions, as well as displaying user-specific information
- A [Python communication layer](https://github.com/ruetzmax/interproject-server), responsible for message handling and performing coordinate system conversions using OpenCV
- A [C# / Unity app](https://github.com/ruetzmax/interproject-unity) to be displayed on a projector, containing the sample room furnishing application

# Demo Video
https://github.com/user-attachments/assets/f0cbccd0-1179-4dff-8147-8ead8793b0d4


