# Stay Awake | StayAwake.js

Prevents mobile browsers from shutting down and the screen turning off after a set period.

Plays a silent, hidden webm/mp4 video on repeat to keep the browser window open and active. 

Original code: https://github.com/richtr/NoSleep.js and: https://github.com/madeInLagny/mil-no-sleep/

* Adapted and simplified for Vue.js and other modern frameworks with module import functionality

# Usage

The module must first be imported in to the framework before being initiated. Once this is complete the video can be started and stopped enabling and disabling the no sleep functionality.

## Import

    import StayAwake from './stayawake.js';

Import the module into framework

## Initiate

    StayAwake.init();
 
 Initiate the module which creates a hidden video element on the page.

## Enable

    StayAwake.enable();

Plays and loops the video preventing screen from shutting down.

## Disable

    StayAwake.disable();
 
 Stops the video returning browser back to default state.



# Tested

Currently working on Android and iOS default browsers. It is a hacky solution so might be "fixed" in the future.

Tested Dec 2019 on:
- Android Chrome Browser Pixel 2 XL
- iPhone 8
- Cordova Android app build
