---
layout: post
title:  "technical work3"
date:   2021-03-02 15:41:00 -0500
categories: jekyll update
author: "Targy"
image1: "img/week5/ChinaTown.png"
image2: "img/week5/Park.png"
image3: "img/week5/WholeTown.png"
image4: "img/week5/GovernmentBuilding.png"
---

# Technical Work

This week, I've finished the work of building the map. The whole town now are free to implement more events to it. 

![]({{ page.image3 | relative_url}})  
Whole town overview

Specifically, the new added scenes are Chinatown, government building and city park. The overview of them are listed below.


![]({{ page.image1 | relative_url}})  
ChinaTown

![]({{ page.image2 | relative_url}})  
City Park

![]({{ page.image4 | relative_url}})  
Government Building

After the design of the map, I started the first scene and eventsystem building at player's home. In this first scene, the player would wake up at home and he can interact with most things in home. Every time the player mentions Jack, which is his roommate, he would ask himself "where is him ?". Until the player finds out the note on the table, the conversation would not appear finding his roommate. There is also teas for player to drink. The animation would fade out the game and fade in again pretending to drink the tea. There can also be some sound effects on the game later. After player come out from the home, he will be teleport to the town scene and meet a neighbor outside. This neibor NPC would walking around the house repeatedly until the player come to talk to him. The text appears would simulate they are having the conversation. Then player can go to Chinatown or anywhere in the town.

{% raw %}
<iframe width="480" height="360" src="http://www.youtube.com/embed/B7L7BbYYiGk"></iframe>
{% endraw %}

Next week, I will keep design and implement other events to finish the storyline. I will go with timeline when pandemic start at town to people are quarantined and wearing masks to the main character have covid. One specific value in this game would be the happiness value and player have to do things for character to stay happy(which would be hard in covid-19 time). 