# JusticeForAll
Description
Justice For All is a virtual voice based courtroom game that allows players to step into the shoes of different courtroom roles such as judge, plaintiff, defendant, witnesses, and jurors. The game offers 4 game modes such as : Random Topic Random Role, Random Topic Fixed Role, Fixed Topic Random Role and Fixed Topic Fixed Role. Justice For All enables different options to users to elevate the gaming engagement. Players participate in virtual court cases, presenting evidence, and striving to win the court while entertaining.

Features
Dynamic Role Assignment: Roles are randomly assigned at the beginning of each game through a spinning wheel mechanism.
Real-Time Interaction: Players can defend, and interact with each other by using voice based mechanism in real-time.
Immersive Environment: A detailed courtroom setting enhances the realism and engagement of the gameplay.
Real-Time Chatting : Players can chat while in the game.
Multiplayer Support: The game supports multiple players in a single session, each taking on different roles within the courtroom.

Installation:

Prerequisites
Unity 2020.3 LTS or later
Photon Unity Networking for multiplayer setup
Firebase SDK for Unity (for authentication and database interactions)
Playfab SDK
Setup
Clone the repository:
https://github.com/zeynepoykuerdem/JusticeForAll.git

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

Setup Playfab:

Register an account on the Playfab website.
Create a title for the game.
Download and integrate the PlayFab SDK into your game.
Initialize the PlayFab SDK using title ID and secret key.


Usage:

To play the game, build and run the project within Unity. You can also export the game to different platforms supported by Unity:

Playing the Game:

Run the built application.
Use the login screen to register or sign in.
After the Login Page, the game will direct you to the Starting Panel where user can see the Friends List , Invite List and a "Create Room" button. Once the user decides to create a room, they are taken to the Create Room Panel. In this panel shown in  users can enter the room name and select whether the room will be public or private. They can also specify the number of players and choose the game mode from a dropdown menu. After configuring the room settings, users can invite friends and click the "Create Room" button to finalize the creation of the room. In the Game Lobby Panel user must wait for their friends to spin the wheel for the randomly role assignment . The Topic of the Court is also randomly given after the spinning the wheel. The "START" button initiates the game , directs user to the Game Panel displays the roles of each player along with a timer. The judge is identified, and there is a clear separation of roles such as Plaintiff and Defendant.The timer is set to 2 minutes, and the sequence follows a specific order: first the judge, then the plaintiff, followed by the defendant, with the judge being the final speaker. Judge determines the winner.

We would like to hear your comments !!! 

Contact
Alper Caymaz - alpercymz@hotmail.com 
Buket Aygün - buketaygun35@gmail.com 
Kübra Akça - akca.kubra@outlook.com.tr 
Zeynep Öykü Erdem - zeynepoykuerdem@gmail.com

Project Link: https://github.com/zeynepoykuerdem/JusticeForAll
