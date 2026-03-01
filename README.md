# The-Game-Room
The Game room
CS 230 – Software Design Portfolio Draw It or Lose It

Name: Jarod Jecas 
Course: CS 230 – Software Design 
Project: The Gaming Room – Draw It or Lose It

Project Description 

This repository holds my Software Design Document that I turned in as a finished product for Draw It or Lose It. This software application was created for a client called The Gaming Room. The objective of this project was to architect a scalable web-based multiplayer game service inspired by the TV show Win, Lose or Draw.

Specifications provided by the client included the need for a centralized game service that can handle multiple games, teams, and players. This service also needs to keep track of all names and IDs being used to ensure that there are no duplicates. Draw It or Lose It will need to be able to run distributed, be web aware, and scale across multiple platforms.

Client Specifications 

Provided by The Gaming Room: 

Multiple teams per game 

Multiple players per team 

Unique game names 

Unique team names 

Unique identifiers for games, teams, players 

Single game service instance in memory 

Deployed on a distributed web based platform 

I designed Draw It or Lose It using Object Oriented principles, alongside the Singleton pattern to ensure there is always a centralized version of game state.

Design Summary 

Client-Server Architecture 
Server running a Linux distro 
Clients can be web browsers (desktop or mobile)
Communication will happen over HTTPS with REST considerations
Domain Model 
Entity (id, name) 
Game 
Team 
Player 
GameService (Singleton) 

This design should allow for a robust application that can scale, be easily maintained, and have a nice separation of concerns.

Platform Pros/Cons Analysis 

Linux macOS Windows Mobile 
Winner Platform for Hosting Server 

Allows for low cost, high volume hosting with great performance under load. Linux also has fantastic security practices and is highly cloud-native.

Can be used as hosting platform. Windows Server is a bit bulky due to licensing costs and higher overhead.

Can be used for development purposes. Not great for hosting lots of servers due to cost.

This platform will be supported on the Client side of the application through the use of a responsive front-end design. Not suitable for hosting at all. 

Reflection 

Completing this document before jumping into implementation helped me to see how crucial designing the architecture of your software is before even beginning development. Clearly defining requirements, constraints, and how your software will be laid out helps to design a product that will meet the needs of your business while allowing you to create something that can scale and be easily maintained.

If I could go back I would have liked to do more focused security modeling. I would also add more visual diagrams to break up content for readers who may not be as technical.

Overall I feel this project helped me gain a greater understanding of what it takes to design distributed systems while implementing Object Oriented architecture.
