# Instructions
> [!WARNING]
> This is a bit complicated, and untested on the steam branch. A backup of your game files is HEAVILY RECOMMENDED, even if you are on the epic branch.

## Requirements
- [Node.js with NPM](https://nodejs.org/en/download)

## Getting Started
> [!NOTE]
> If you run this on your machine you will only get your own data, IE you will be the only person on the leaderboard

> [!WARNING]
> Before you start I HIGHLY RECOMMEND BACKING UP YOUR GAME!!! This will make sure that you have something to fall back to if it breaks - it probably will - and the game will clear all of your saved data, IE controllers settings, graphics settings, maps, ect.

You are going to also need to install some npm packages to run this. You can run this comand below
```
npm install express express-rate-limit sqlite3
```

You are also going to need the code which you can grab with git
```
git clone https://github.com/Mr-milky-way/Custom-DRL-Server.git
```
or download from github up at the top here.

## DLL setup
Go over to [this release](https://github.com/Mr-milky-way/Custom-DRL-Server/releases/tag/V1-DLLS) and follow the instructions there

## Running the server

Go into what ever folder you downloaded this repo into and run it with
```
node index.js
```
wait for it to say:
```
Server is running on [http://localhost:8080](http://localhost:8080)
```
then run the game.

**Now you are done and can play the game**

> [!NOTE]
> Some things are still broken and do not work right. If something fails make an issue on this repo. I should get to it at somepoint