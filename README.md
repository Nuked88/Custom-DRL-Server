# Instructions (very wip)
> [!WARNING]
> This is a bit complicated, and untested on the steam branch. A backup of your game files is HEAVILY RECOMMENDED, even if you are on yhe epic branch.

## Requirements
- [Node.js with NPM](https://nodejs.org/en/download)
- [dnSpy](https://github.com/dnSpy/dnSpy)

## Getting Started
> [!NOTE]
> If you run this on your machine you will only get your own data, IE you will be the only person on the leaderboard

> [!WARNING]
> Before you start I HIGHLY RECOMMEND BACKING UP YOUR GAME!!! This will make sure that you have something to fall back to if it breaks - it probably will - and the game will clear all of your saved data, IE controllers settings, graphics settings, maps, ect.

You are going to also need to install some npm packages to run this. You can run this comand below
```
npm install express express-rate-limit sqlite3
```

You are also going to need the code which you can grab with git or download from here.

## DLL setup
At somepoint I will provide DLLs but in the meantime you will have to make your own with dnSpy.