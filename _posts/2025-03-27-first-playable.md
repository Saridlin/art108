---
layout: post
title:  "Doodle and Twiddle: First Playable"
date:   2025-03-27
categories: blog
---

Doodle and Twiddle is a cute 2D platformer where the player controls a small bug called Doodle, and is trying to survive in a post-apocalyptic world to meet up with their lost friend, Twiddle. 

![Image]({{ site.baseurl }}/images/vg-alphatest.png)
> Play the most recent Alpha Build of *Doodle and Twiddle* [here](https://saridlin.github.io/doodle-n-twiddle/testBuild4/index.html)!

I am the producer and programmer for this video game. As the producer, I laid out the schedule of tasks to complete before the first Alpha Test session that occurred on March 26th. Working together with the artist/designer, I then implemented the designs and art assets into the game.
For the Alpha Test, we finished the character sprite and a basic level map. The character sprite included animations for an idle state, walking and jumping. For the level map, the main goal was to get the colliders coded so that the player could move and explore while also correctly activating the double jump mechanic in a way that prevents infinite wall-jumping. 

### Playtest Session Feedback

At the Alpha Test, players responded really positively to the overall design and initial feel of the game. They enjoyed the simple, pixel aesthetic and setting to the game. The fan favorite was the design of the player character as a chibi-bug inspired by the Ohmu creatures from Nausicaa of the Valley of the Wind. Since there was not much to do in the current game state, players jumped and moved the character around the screen to explore how the controls felt and the animations looked. 

The most common comment from this testing was that players felt that the map was lacking in things to do. It was short and minimal, so they quickly got bored and lost on what to do or left wondering if there was an end goal to achieve. I do want to finish working on an end goal where the main character’s friend, Twiddle, is placed on a larger level map design that then triggers a completion scene. This I think would communicate the end to the game more effectively.
Tied to this, both the designer and I want to create a short tutorial graphic or start scene that quickly explains to the player that their goal is to go find their friend on the map.

Another piece of feedback we received on the game was that the controls made sense, but not communicated. We used the commonly known controls of arrow keys, WASD and spacebar, however, there was no text or description to inform the players. We will also be adding this information to a possible tutorial graphic and the description on the WebGL publish link of the game.

We also received some feedback that the contrast of the design and colors of the level map did not make the ground platforms feel obvious for the players. This may or may not be changed based on time constraints and so it will be a lower priority change. If we end up creating a new and larger level map, we may take this feedback into account to make the platforms and starting area clearer for players.
