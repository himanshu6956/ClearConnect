# ClearConnect Web Application


<details>
<summary>Contents</summary>

* [Video Demonstation of Web Application](#video-demonstration-of-web-application) <br>
* [Introduction](#introduction)<br>
* [Features & Specialities](#key-features--specialities)<br>
* [Techsacks used, installation, execution](#techstacks)<br>
* [Snippets of web application](#web-application-snippets)<br>
</details>



## [Video Demonstration of Web Application]("Video Demonstration")



## Introduction


This is Node.js-based video call application that utilizes socket.io and peerjs libraries to establish peer-to-peer connections. It provides video-calling and real time chat functionality. Additionally, it offers features such as screen sharing and whiteboard sharing.



## Key Features & Specialities

* Group video and audio call
* Real time chat
* Screen share
* Audio and video controls
* View Participants
* Invite user through gmail or sharable invite message
* Google Authentication
* Sharable whiteboard
* Dedicated Leave meeting option
* Zoom facility on video/screen for better experience
* Easy to use UI


## Techstacks


### Techstacks used
* Node.js
* HTML
* CSS
* Bootstrap
* Javascript

### Libraries used

* Socket.io
* Express
* Peerjs
* Nodemailer
* Passport js
* dotenv
* uuid

### Installation

1. Clone the repository `git clone https://github.com/himanshu6956/Clear-Connect`

2. Install all packages and project dependencies `npm install`

3. To run the webapp on localhost generate your Google Oauth credentials from [Google Developer Console](https://console.cloud.google.com/ "google developer console") by creating a new project and set the URI to `localhost:8080` and callback URI `localhost:8080/google/callback`

4. Create a .env file and add your Credentials here along with your Gmail ID and Password for Invite Email message

### Execution

* Start the server `npm start` or `nodemon server.js`<br>


## Web Application Snippets


1. Google Authentication<br>

![google-authentication]()<br>

2. After google authentication user can either choose to join a new meeting or join an existing meeting either through invite mail or by entering the meeting-room ID<br>

![Start-page]()<br>

![Join-page]()<br>

3. Meeting room<br>

![Meeting-room]()<br>

NOTE: Video of participant were kept off for security reasons<br>

4. Chat facility<br>

![Chat]()<br>

5. Screen-share feature<br>

![Screen-share]()<br>

6. Whiteboard<br>

![Whiteboard]()<br>

7. Participant-list<br>

![Participant]()<br>

8. Invite user window<br>

![New-user]()<br>

9. Alert everyone in the meeting when a participant leaves the meeting<br>

![leavemeet]()<br>

10. Leave Meeting page<br>

![Leave]()<br>



>Happy Coding !!

