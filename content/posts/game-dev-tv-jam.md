+++
title = "Post Jam Reflections :)"
description = "How my game dev.tv jam went"
date = "2026-05-30"
#aliases = ["about-us", "about-hugo", "contact"]
author = "Miracle"
+++

## About the Game Dev.tv jam

The game dev.tv 2026 game jam just ended some days ago, and you know all the rush is gone, I am cool again, (I've always been). Its now me and my thoughts again and deadlines breathing down my neck.
See lets call it post jam energy, I just got relief after some days of crunch, no more bugs to worry about, features to implement, art to make or tweak(I make all my games alone, solo). So its me now me and my thoughts again :)

## So what made I?
You probably asking now what did you make? Well initially the goal was to make a a narrative driven game where you play as a network engineer(I know nothin about network engineering, nor what they actually do. They hack too I guess lol). Okay so yeah, your IT department is tasked with disabling a devious terminal, original description of the terminal was **"a funny, devious, prankster teminal".** So this rogue terminal is infecting all other terminals in the HELL network.


As a narrative game I wanted the game to have a branching dialogue, hence the game should have multiple ending scenarios based on your choices. Crazy thing was I had never written of line dialogue before lol.

Gameplay wise you mainly interact with the terminal, 
* to check logs 
* and messages 
* and connect and disconnect to the network and all those stuffs

Then as part of the game there will be mini hacking sequences where you'll have to play a mini game, a mini game about capturing signal packets, while avoiding some other type of stuffs . Writing this now I think im a going to look upon the mini game with favor and remake it into its own actual game for mobile. Pretty Cool.

![screenshot 1](/images/scr1.png)

## So How Did It Go?
Well really not bad in any way for me, I learnt a new game engine, and had a lot of fun learning the engine and making a game at the same time. You know that rush when youre runnin outta time and you know you cant make it and also have other grey(boring) tasks to attend to like work and assignments(I'm an intern hence for most parts I did most of the game in the weekend). 
Did I finish the game? Well maybe you might have guessed by now No. infact the game is a broken cute mess, frozen animations, weird UI placement, and bugs disguised as features(crazy).  Submitted it any ways

## What made things so:
Well for a couple of outlined reasons, like the fact that I have'nt written a story before, then there I was sweating on a 80+ dialogue worth stuff. Like 3 days before the jam concluded I was struggling to get any meaningful worth of dialogue text down. A quick prompt to chatgpt and I got myself some mostly generic sht, though got some cool facts from there though. After I spent about an hour trying to write some lines it did not come out well. Writers are cool I guess

Secondly internship, I currently just picked up and flutter and boy that stuffs needs some dedication than I expected. 
And finally I guess is the fact that I changed engines, thought it was a good time to learn a new engine, so I grinned at defold. 

Before now I was a Lover, oops I meant I have been making games prior using the love2d framework. Now just so you know Love2d is a great framework, and I felt so sad and heartless using defold, I'm sorry Love I'll be back😘. One cool reason was the HTML5 export that Defold provides, Love2d natively does not support the web, but the community has produced a coupla tools that help export your love game for web, like love.js for example. But sadly for me I have never had any success with those tools. And I am not beating love2d for not supporting the web either.

As for you Defold I gotta give ya one compliment *"you are weird bro, really weird and stay like dat its perfect"*.  And while it felt weird at first, once I or you understood the concepts or just simply gave up and accepted it's way, it's really a nice way to make games. It got stuffs like Gamobjects, Collections, Messages( I really love dis one) etc, which are used to build games. 

Another thing that caught me a bit off guard is the fact that I thought it was a one button click adds cool feature type engine, its actually a bit low  level that that. Such a way that I like to refer to it as someting in between a game engine and a framework. 

For example how do you implement **a full screen post fx in godot**, I can really remember the full steps but something like filling the screen area you want with a canvas node, attaching the shader to that and boom you got your cool effect.
But in defold should you decide to alter the default rendering pipeline, then defold be like *"oh cool, there you go"* and folds its hands like a resigned Dad watching His I want to do it myself son struggle to make a Lego car.

For example, in love2d say I wanna implement a full bloom effect. Assuming I have my shader already;

* I create a canvas(love2d's term for a frame buffer)
* Then in my draw function. I simply set the canvas, or bind it as the current Frame buffer object
* Clear the buffer and  draw my whole game,
* Reset the canvas back to the screen,
* Set my bloom shader,
* draw the canvas,
* reset the shader. Boom cool effects.

But in defold, its technically the same process but you now have to explicitly hadle some stuffs on ya own like the coordinate system or projection, depth buffers etc(cant think of any other thing annoyin lol) stuffs that are delicate and dont appreciate even a minute mistake. But yeah thats what you get when you yearn for control or simply graphics out of the usual.

## Conclusion
So? Will I still be using Defold yes, for my future projects yes at least if I don’t get lured to another game engine, hence I'll look at making a proper game out of the would be mini game, yeah bye.
