# Project Name
> Chore Door 2.0  

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
A basic game of chance using basic programming  

## Screenshots
![Example screenshot](https://github.com/TarrMarr/choreDoor2.0/blob/master/screenshot.JPG)

## Technologies
* HTML5
* CSS
* JavaScript  

## Code Examples
Show examples of usage:
`var randomChoreDoorGenerator = () => {
  const choreDoor = Math.floor(Math.random() * numClosedDoors);
  if(choreDoor === 0){
    openDoor1 = botDoorPath;
    openDoor2 = beachDoorPath;
    openDoor3 = spaceDoorPath;
  } else if (choreDoor === 1){
    openDoor1 = spaceDoorPath;
    openDoor2 = botDoorPath;
    openDoor3 = beachDoorPath;
  } else {
    openDoor1 = beachDoorPath;
    openDoor2 = spaceDoorPath;
    openDoor3 = botDoorPath;
  };
};`

## Status
Project is:  _finished_

## Inspiration
Codecademy Full Stack Web Developer pathway

## Contact
Created by TarrMarr(https://www.tarrynmarr.me) - feel free to contact me!
