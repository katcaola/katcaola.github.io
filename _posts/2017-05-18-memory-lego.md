---
layout: post
title: "Memory Lego"
description: "A fix for those who are not the best at remembering"
tags: [idea, lego, mnemonic device, helpful, computer science, programming] 
image:
  feature: https://s-media-cache-ak0.pinimg.com/originals/6f/86/84/6f868405b5d1d6b533a84d9ffececf4e.png
---

I love my partner. 

They are not very good at remembering things. On several occasions they would have to check and re-check if they:
* locked the door
* turned of their car headlights
* shut off the oven

And it would become inconvenient if they had just gotten into bed to go to sleep; they would have to get up, put on proper attire, and go check whatever needed to be checked (anxiety strikes again!).

To help them remember things so that they would not worry about what they might have forgotten, I came up with the memory lego brick.

## How does it work?
<figure>
	<img src="https://s-media-cache-ak0.pinimg.com/originals/3b/36/ea/3b36eac458cfb52de974bd9663e2e9b7.png" alt="">
	<figcaption>A Memory Lego Brick</figcaption>
</figure>

Here we have a memory lego. 

The top row represents tasks, objects or goals that have been completed, remembered, or accomplished. 

The bottom row represents tasks, objects or goals _that have NOT been completed, remembered, or accomplished_. 

Each column represents the desired _"something"_ to be remembered. For example, on my partner's memory brick, they had 
* Column 1 - Bring lunch to work
* Column 2 - Turn off car headlights
* Column 3 - Lock the front door

Whenever a task is unfinished (or it's a new day), one (or all pieces) should be moved to the bottom accordingly. Then when a task is completed/remembered, the piece is moved to the top. This way, the _remeberee_ has a physical reminder that they "did" or "remembered" a specific thing. 

## Make your own
As you can tell this is a very easy idea to implement. You just need a small single piece for everything you want to remember, and a `2 by x` lego brick, where `x` is greater than or equal to the number of things you want to remember.

#### Tips
* Make sure you don't use the single flat square pieces, [like these](https://s-media-cache-ak0.pinimg.com/originals/89/d3/b5/89d3b5185ef8f0e0e1519c849d0577da.jpg){:target="_blank"} those can be really hard to remove from a `2 by x` lego piece.
* You can use different colors for each item in your remember list. 
    * This can help you color code each task.
    * Optionally, you can also use color to denote order of what tasks should be done in.
* You can draw pictures on the `2 by x` brick to be a reminder of what the task, goal, or thing to remember is. For the less artistic, you can also write shapes or use color to do this as well.
    * If you're feeling really creative, find a way to etch using a knife or laser.
    * Alternatively, you can also print really small pictures on address labels and stick that to your brick instead.
* Remembering to bring your lego everywhere can be difficult, so it might be wise to [invest in a lego brick keychain](https://shop.lego.com/en-US/LEGO-Red-Brick-Key-Chain-850154) or [make your own](https://www.etsy.com/listing/246969279/lego-brick-keychain-kit-ready-to){:target="_blank"}.

## Computer Science Background
This borrows the idea of the boolean from computer science. To those who aren't programmers, a boolean is, in it's most simplest terms, _a binary variable, having two possible values called “true” and “false”_. A great overview of booleans can be found on [Khan Academy.](https://www.khanacademy.org/computing/computer-programming/programming/logic-if-statements/p/booleans){:target="_blank"} Booleans have many uses, such as checking if a comparison or an equation is true or correct, used as flags, and also denote the "truthy-ness" of a statement/code. Thus the "things remembered" is equivalent to true while "things not remembered" is equivalent false.