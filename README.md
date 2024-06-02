# JusticeForAll
Description
Justice For All is a virtual voice based courtroom game that allows players to step into the shoes of different courtroom roles such as judge, plaintiff, defendant, witnesses, and jurors. Players participate in virtual court cases, presenting evidence, and striving to achieve their objectives according to their assigned roles.

Features
Dynamic Role Assignment: Roles are randomly assigned at the beginning of each game through a spinning wheel mechanism.
Real-Time Interaction: Players can debate, discuss, and interact with each other in real-time.
Immersive Environment: A detailed courtroom setting enhances the realism and engagement of the gameplay.
Multiplayer Support: The game supports multiple players in a single session, each taking on different roles within the courtroom.

Installation
Prerequisites
Unity 2020.3 LTS or later
Photon Unity Networking for multiplayer setup
Firebase SDK for Unity (for authentication and database interactions)
Setup
Clone the repository:
git clone https://github.com/yourusername/courtroom-simulation-game.git
Open the project in Unity:

Launch Unity Hub.
Click on 'Add' and select the cloned project directory.
Open the project from the Unity Hub.
Setup Firebase:

Go to the Firebase console and create a new project.
Follow the instructions to integrate Firebase with Unity.
Import the Firebase SDK into the Unity project.
Configure the authentication and Firestore database as per the Firebase setup guide.
Setup Photon Unity Networking:

Register and create a new application on the Photon Engine website.
Obtain your Photon App ID.
In Unity, navigate to Window > Photon Unity Networking > PUN Wizard and enter your App ID.
Configure the game scenes and settings:

Ensure all scenes are properly set in the Build Settings.
Check the Photon and Firebase settings in the game objects to match your configuration.
Usage
To play the game, build and run the project within Unity. You can also export the game to different platforms supported by Unity:

Starting the Game:

Run the built application.
Use the login screen to register or sign in.
Enter a game session and wait for role assignment.
Playing the Game:

Participate in the courtroom proceedings according to your assigned role.
Use the UI buttons and interactions to present evidence, object, and influence the outcome of the case.
Contributing
Contributions to the project are welcome! To contribute:

Fork the project.
Create a new branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.
License
Distributed under the MIT License. See LICENSE for more information.

Contact
Your Name - your.email@example.com

Project Link: https://github.com/yourusername/courtroom-simulation-game
