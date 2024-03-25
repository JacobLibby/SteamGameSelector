# SteamGameSelector
A full-stack web-app that enables two users to determine a game in common on Steam that they wish to play



# Functionalities
* Lobby system
  * Hosting
  * Joining
  * \# of members, solo?  
  * save lobbies, able to re-run?
  * how to synchronize swiping? asynchronous and wait for results if first to finish?
* Swiping System
  * BEFORE, Select game preferences: genre, \# of players, required system compatibility
  * Range of preference: Dislike, meh, like, love
  * Sort matches from most universally preffered to least
  * Allow to re-run the lobby with new games
* UI

# Stack
| System | Technologies |
| --- | --- |
| Front-end | React, Redux, Bootstrap, Javascript, HTML, CSS |
| Back-end | Node.JS, Express.JS, Google Firebase, API? |
| Log-in | Google Auth or OpenID |
| Functionalities | Steam API |
| Planning | Figma, Notion, Gitmind |

# Stages of implementation
* Create lobby system - Hosting, Joining, Leaving, Saving?, Max # of members?, Solo?
* Create Front-end
* Get comfortable with SteamAPI calls
* Figure out recommendation system - Steam built-in?, ML Model?
* Decide on swiping system - one match -> done or continue?, finish and show users a list of matches?
* Log in, log out, account creation, session checking system


<br><br><br>



# Current Status
This project is currently in the ideation and brainstorm stage <br>
- [x] Scope - plan stack and functionalities 
- [ ] Database Modeling
     - [x] Design Schema - Gitmind
     ![alt text](https://github.com/JacobLibby/SteamGameSelector/blob/main/SteamGameSelector_Backend.jpg?raw=true)
     - [x] Create Firebase project
     - [ ] Create Firebase Database
- [ ] Design API
- [ ] Backend Build
- [ ] Backend Test
- [ ] Sketch and design frontend with Figma
- [ ] Plan React components for frontend
- [ ] Frontend Build
- [ ] Frontend Test
- [ ] Overall QA
