# My Calling App- A group video calling app
 This project is made as a part of the Engage Mentorship Program 2021 by Microsoft
 Live Demo : https://my-calling-app.herokuapp.com/
 
 ## A very simple application that allows us to stream audio and video to the connected device.Technology stack used:

- HTML5,CSS3 and Javascript for frontend
- Nodejs for backend - express library to server statis files like our HTML file which stands for our UI
- Socket.io library to establish a connection between two devices 
- WebRTC to allow media devices(camera and microphone) to stream audio and video between connected devices
- WebRTC mesh for group video call


### Features:

-  As soon as you click on the [link](https://my-calling-app.herokuapp.com/), an automatic link is generated which can be shared with other people and asked to join
- Supports one to many video call ,the call quality can be reduced if more than 4 people join
- Participants can switch on and off their video and audio during the meeting
- There is a chat box where participants can chat during the meeting
- Screen sharing feature is there
- A particular participant can be pinned to screen using the top square icon in the right
- For the UI ,I tried giving it a glassmorphic look


### Prerequisites:

- Node.js 8.x or above
- NPM

<div align="center">
    <img src="/imgs/img1.jpeg" width="700px"</img> 
  </div>   
  
<div align="center">
    <img src="/imgs/img2.jpeg" width="700px"</img> 
</div> 
<div align="center">
    <img src="/imgs/img3.jpeg" width="700px"</img> 
 </div>
 <div align="center">
    <img src="/imgs/img4.jpeg" width="700px"</img> 
 </div>
 <div align="center">
    <img src="/imgs/img5.jpeg" width="700px"</img> 
 </div>
 <div align="center">
    <img src="/imgs/img6.jpeg" width="700px"</img> 
</div>

### How to run this locally
- Fork this repo and then clone it
- `cd my-calling-app` and then install dependencies
- npm install
- Run the app in your localhost
- npm start



### Limitations and scope of improvement:
- The call quality gets reduced if more than three participants join
- Participants cannot chat before and after the meeting
- No user authentication added
- Thought of implementing topic wise chat rooms could not implement it due to shoratge of time


 
