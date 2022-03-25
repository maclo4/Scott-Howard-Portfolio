# Scott Howard Portfolio

- Scotthowy96@gmail.com
- 248-875-6072


## Rhythm-Game - https://github.com/maclo4/Rhythm-Game


The concept for this game is that you control a cursor with each analog stick of a controller and you need to hit notes on beat as they move from the center of the circle to the edge. It's pretty simple but can get difficult fast.


**Videos**

https://youtu.be/tA04m_2d-A0 - Most recent version as of 2/21/2022
- Can now specify using the left or right cursor for each note
- Made loading songs much more dynamic by reading metadata and notemap from a special file format
- Removed clicking noise when hitting a note and added buzzer noise when failing (I may revert this)
- Some UI changes




https://youtu.be/iFzs5d51aK8 - 9/29/2021
- First video demonstrating the basic mechanics
- Checks if you hit the notes on beat or not
- Reads notemap from file but not metadata such as bpm, title, or artist

## 24/7 lofi marble simulator to relax/study/sleep to


Easily my favorite thing I've made. It's a marble course that I made with Unity and Blender that goes forever. I sometimes stream it on twitch with lofi beats playing in the background. I want to make it actually run 24/7 but it's very expensive to find a computer that can stay on at all times simulating this and streaming at the same time.

https://www.youtube.com/watch?v=FhbVI-nyivI&t=379s&ab_channel=scotthoward

https://www.twitch.tv/maclo6


## Fighting Game - https://github.com/maclo4/Fighting-Game

This was the first game I ever worked on- I love fighting games and aliens so I had a lot of fun learning Unity while doing this. I ended up putting it aside because I wanted to focus on a game that I could finish in a reasonable amount of time while working full time. The idea for this was to make a very free-form fighting game with mechanics similar to Under Night: In-Birth, except with more air mobility and defensive options.

**Game Overview as of April 12 2021**

![Game Overview](https://media.giphy.com/media/zHUZ4cEaSsRiEC4eyY/giphy.gif)

**Customizable Attacks**

![Animations](https://media.giphy.com/media/XRlhIb6RHaASuKBUMV/giphy.gif)

I've made attacks an inheritable class that allows for every attack in the game to be customized easily with little code. Set various attributes like hitstun, blockstun, set the attack to mid, overhead, or low, etc.

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

---

## Automated Indoor Mapping System

Automated Indoor Mapping System for the Misty II Robot. This was created while I was working at The Car Lab as a student research assistant. The goal of the project was to make a program that would allow the Misty II robot to create maps of rooms without the need for a human to manually drive her around. The best comparison is how roombas roam around and make maps as they go.

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

---

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
- Ubuntu
- ros1_bridge package
- ncurses

---

## Secure S3FS


Secure S3FS builds on top of s3fs-fuse to add encryption and decryption of files stores in Amazon S3. S3fs-fuse mounts a cloud-based storage system locally so that it can be accessed and used like a regular filesystem. Secure S3FS adds the feature that all files are encrypted when uploaded to Amazon S3 and decrypted with a unique key when mounted to your local filesystem. Unfortunately, I don't have any videos of this project, as it was a couple years ago.


**Link to the full repository with more details**

https://github.com/maclo4/Secure-S3fs

**Tech Stack**
- C++
- Amazon S3
- S3fs-fuse: https://github.com/s3fs-fuse/s3fs-fuse
- OpenSSL
- Ubuntu
---

## Humdrum

Humdrum is a social media music website that allows users to share music with their friends. Users are able to link their humdrum account to their spotify account to share playlists and search for music/artists. In addition, there is a rating and posting feature to provide feedback on different music. Although I know I could do better if I made this today, this was a fun project to work on because it was my originally idea and because it was the first time I had worked with databases, an API (Spotify's), and PHP. This was created for a group project in school where I was the team lead. Unfortunately, I don't think that the database for this website is still online, so it is probably not usable. 

**Link to the website**

https://humdrum-php.azurewebsites.net/

**Link to the full repository with more details**

https://github.com/WSU-4110/humdrum

**Tech Stack**
- PHP
- MySQL, PHPMyAdmin
- Spotify's API
- HTML
- CSS
