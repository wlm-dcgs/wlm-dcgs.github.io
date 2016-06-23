---
title: BBC Microbit:1
layout: post
author: ske
permalink: /bbc-microbit:1/
source-id: 1TIsQRkwMOl_HHmE3Ho2DWYovCvB-LOfW2qKOoQ9jkWE
published: true
---
/* When the BBC micro:bit runs  */

function onStart(  ) {

 microbit.say("press A for a response");

 

}

function onPressA(  ) {

 globals.answer = Random.number(0, 1);

 if (globals.answer == 0) {

  

  microbit.say("No");

  

 }

 

 if (globals.answer == 1) {

  

  microbit.say("Yes");

  

 }

 

 

}

