<p align="center">
  <img width="100" src="https://pnggrid.com/wp-content/uploads/2021/05/Discord-Logo-Circle-768x768.png">  
  <img width="100" src="https://o.remove.bg/downloads/8c5cefbb-85d7-432f-b40a-bd602ecd0fd4/12-126102_music-wave-png-audio-wave-icon-png-transparent-removebg-preview.png">
</p>

<h1 align="center">Audio Discord Bot</h1>

<p align="center">
  <img src="https://img.shields.io/badge/discord--net--labs-v3.1.7-blue" alt="discord-net" style="max-width:100%;">
  <img src="https://img.shields.io/badge/C%23-8.0-blue" alt="csharp" style="max-width:100%;"> 
  <img src="https://img.shields.io/badge/.NET Core-3.1-blue" alt="csharp" style="max-width:100%;"> 
  <img src="https://img.shields.io/badge/IDE-VS2019-purple" alt="ide" style="max-width:100%;">
</p>

Dockerized Discord audio bot with flexible file search using memory cache.

## Commands

Use `play` or the alias `p`

`!play <sound_name_substring>`
- Plays a sound given either the exact sound name or a substring of the name. If only a substring is provided, the bot tries to find the best match for the requested sound by looking for sounds that either starts with or contains the substring (in that order).

`!help play` 
- Shows a list of all available commands.

Additionally, the commands inherited from the [discord-bot-template](https://github.com/roedebaron/microservice-discord-bot-template) project.

### Remarks


> TODO: 
> - Explain cache






### Running the bot

Create a root folder and clone this project and the [discord-bot-template](https://github.com/roedebaron/microservice-discord-bot-template) dependency: 

1. `mkdir my-discord-bot && cd my-discord-bot`
2. `git clone https://github.com/roedebaron/audio-discord-bot`
3. `git clone https://github.com/roedebaron/microservice-discord-bot-template`

#### Running with Docker Compose 🐳

Cd into the folder of this project and run Docker Compose command to build and run the service:

4. `cd audio-discord-bot`
5. DEVELOPMENT: `docker-compose up`
6. PRODUCTION: `docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d`




