# QuizzBizz

QuizzBizz is a cross-platform web app which runs on Nodejs. QuizzBizz provides a fun classroom environment by engaging students through interesting quiz questions. It is a jeopardy like game where the first person to push the buzzer gets to answer.


## Installation

The instructions below allow you to download, run and continue the development process of the project. Please visit the deployment section for deployment information.

### Prerequisites

Node JS needs to be installed

```
https://nodejs.org/en/download/
```

MongoDB needs to be installed

```
https://www.mongodb.com/download-center?jmp=nav
```

### Running with Vagrant

How to start VM
```
vagrant up
```

Available on URL
```
http://localhost:5622                (locally)
http://csil-cpu470.csil.sfu.ca:5622/ (SFU Server)
https://quizbizz470.herokuapp.com/ (Heroku just in case)
```

Server runs on port 5622, 
Database runs on port 3711

### Build project

How to run the project locally

Build the client (current directory client)

```
npm run build
```

Start up MongoDB client
```
~/mongo/bin/mongod
```

Start the server
```
node server
```

## For Developers

## Features

* [x] Register / Login / Logout 
* [x] Create / Edit / Delete quizzes
* [x] Buzzer For Every Question
* [x] Cross-Platform
* [x] Start Quiz / Share Room Code
* [x] Points Tracking System

How to Start the Game

Teacher (Host)                       

1. Register / Login                   
2. Create/Edit/Delete Quizzes						  
3. Start Quiz / Share Room Code		  
4. Enable Buzzer Every Question		  

Student (Player)

1. Enter Room Code
2. Press Buzzer First
3. Gain Points for Correct Answer
4. Other Players Can steal if Wrong

## Development Members

* **Raymond Eng** - *Front End (React) / API & Database* 
* **Parmvir Johal** - *API & Database / Socket.io* 
* **Jerry Chen** - *Deployment / Front End* 


See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

