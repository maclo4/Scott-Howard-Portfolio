# Scott Howard Portfolio

## Fighting Game (In Progress)

This is a personal project that I've been working on in my free time since October 2020-ish. It's very much still in progress, but it's a fighting game made in Unity with C#. 

**Game Overview as of April 12 2021**

![Game Overview](https://media.giphy.com/media/zHUZ4cEaSsRiEC4eyY/giphy.gif)

**Customizable Attacks**

![Animations](https://media.giphy.com/media/XRlhIb6RHaASuKBUMV/giphy.gif)

Ive made attacks an inheritable class that allows for every attack in the game to be customized easily with little code. Set various attributes like hitstun, blockstun, set the attack to mid, overhead, or low, etc.

**Link to the full repository with more details**
https://github.com/maclo4/Fighting-Game

**List of features**
- Custom input system to allow for motion inputs similar to other fighting games (quarter circle, double tap for dashes)
- Custom hitbox and hurtbox implementations to allow for easy customization and inheritance
- Blocking attacks
- Health bars
- 1 player or 2 player
- Movement options: Walk, dash, back dash, crouch, air dash, aerial drift



**Tech Stack**
- C#
- Unity
- Krita for drawing

## Automated Indoor Mapping System

Automated Indoor Mapping System for the Misty II Robot. This was created while I was working at The Car Lab as a student research assistant. The goal of the project was basically to make a program that would allow the Misty II robot to create maps of rooms without the need for a human to manually drive her around. The best comparison is how roombas roam around and make maps as they go.
**Hazard Avoidance**

![Hazard Avoidance](https://media.giphy.com/media/DzWGP3dPzqHUSxHiQP/giphy.gif)

When using my program, Misty is able to detect and avoid obstacles in her way. For the video above, I placed objects close to her front and back to se if she would successfully find her way out.

**Full Room Roam Video**

https://youtu.be/js8Hn0BxE64

This was too long to fit into a gif, it shows what the program looks like from start to finish of making a map.

**Link to the full repository with more details**

https://github.com/maclo4/AIMS

**Tech Stack**
- C#, involves event based and asynchronous programming
- MistyII robot
- Misty robot SDK for .NET

## e.DO Manual Control using ROS2

This project allows for users to control the e.DO robotic arm from a Linux terminal. This was created for my senior project with a group of 3 other students. 

**Video tutorial demonstrating the usage of this program**

https://youtu.be/egTKGkaJMBs

**Link to the full repository with more details**

https://github.com/comau-na/edo-ROS2

**Tech Stack**
- C++
- ROS1 Melodic
- ROS2 Eloquent
- ros1_bridge package
- ncurses

## Secure S3FS


Secure S3FS builds on top of s3fs-fuse to add encryption and decryption of files stores in Amazon S3. S3fs-fuse mounts a cloud-based storage system locally so that it can be accessed and used like a regular filesystem. Secure S3FS adds the feature that all files are encrypted when uploaded to Amazon S3 and decrypted with a unique key when mounted to your local filesystem. Unfortunately, I don't have any videos of this project, as it was a couple years ago.


**Link to the full repository with more details**

https://github.com/maclo4/Secure-S3fs

**Tech Stack**
- C++
- Amazon S3
- S3fs-fuse: https://github.com/s3fs-fuse/s3fs-fuse
- OpenSSL



