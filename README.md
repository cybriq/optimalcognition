# optimalcognition

A scratchpad for some notes about how to discover one's ideal type of work

## Case Study 1: Loki Verloren (the author!)

## 1. Lego

In my play with my first toy, and my passion for the toy:

I started by simply following the instructions to learn how to piece together the object the package showed completed. It was a lot more fun to me than a jigsaw puzzle because it was tactile and modular, but I wanted to see the physical thing, that the picture promised. This is a pattern I can point to in almost every other aspect of my life, I start by watching, then I poke, then I start to take it into pieces, and then I try to build a whole system.

I never made big constructions, even when my collection got quite large. I tended towards small things, and playing with how to structure them most efficiently.

I wasn't really interested in representational things either, I enjoyed the geometry and visual elements, textures, repeating patterns, and so forth.

I did not fall in love with anything I made, it would usually be torn apart before I would even bother to show it to anyone, and showing it to people was not a major motivation.

## 2. Computer Programming

### My initial work with programming was on a TRS-80 Color Computer, circa 1984

Firstly, I got in lots of trouble modifying the code my father had spent many hours inputting from programming magazines. I was more interested in seeing how the system went from the details and to the result.

When I actually got to doing something by myself, it was after I first saw a Macintosh computer. My very first piece of code combined multi dimensional arrays and boolean logic, making a sprite.

I first figured out how to paint the pointer.

Then I somewhere read about bitmasking, and created the transparent boundary around it that makes it stand out on a black ground.

I devised an inertial motion system from the only input device I had available, a non-centering joystick with 8 bits of precision for horizontal and vertical. I don't remember if I got it working fantastically, but it was usable.

Then I started learning how to use the bitmask with the bitmap to create a difference that allowed my code to avoid ever painting any pixel twice.

I always like to point out that Bill Gates operating system developers never fixed this problem, and I did it with his programming language on 700 hertz 6809 processor. 

If the motion was more than the width of the bitmap, restoring the background behind the old position only involved painting the pixels inside the mask area. When it overlapped its previous position, there was a third masking pattern to redraw the background, to avoid repainting any part of the overlapped areas, and then the final area.

Of course, the Mac did this from day one, which was why I was so obsessed to make it flicker free. There was no vertical blank, and no blitter, so every pixel cost processing, and I wrote the most efficient.

Second thing I did was text shaping, I think, though it may have been window frames, I am not sure.

To be honest, I don't remember exactly, because windows were much bigger arrays of pixels to mask out, I think possibly I did text first. I can't remember so much details of what I did with this part, as I didn't finish it past some point of having a title bar and frame, and I didn't get to widgets.

In actual fact, this was the best programming I did until 2018. I believe this was because my father attacked me with psychological torment that associated confusion with the activity, in order to stop me 'getting in his way'.

### Carpentry

He did the same thing to me with carpentry too. In fact, Carpentry was probably the first activity I got the passion to engage in as a child. I was never able to do anything, because he never made the effort to teach me, and when I seized the opportunity to play with them, I got in huge trouble. 

An experience in 2004 in New Zealand proved that despite this, I had a talent for building as well. I started from nothing, first mastering how to cut square ends, then how to join them side by side with the correct stud width (600mm), and I aimed to use as little wood as possible, reusing offcuts as corners and braces.

An idiot, interfering twit housemate forced upon the project the idea of putting a structural floor at the base of it. This basically destroyed the utility of the space by making it so low I could almost bump my head if I stretched up on my tippy toes. 

In spite of this, I still did the rest. The frames all were up, and next, I placed all the fibre cement cladding on the outside, figuring the less time the frame is exposed, the better. I carefully predrilled the fixing points to minimise the amount of shock while I put the nails in that held them in place. Then I placed the window and door frames.

What I wanted to do for the floor was minimalistic. It had a sloped concrete track under it for car tyres, I wanted to just form a level box around the structure and make it flat and raise the higher part minimally and to provide a flat floor that would have had another 6 inches of height, and made the whole thing practical as a living space rather than an awkward storeroom.

I knew I would do it well, and I knew I would do it better than my father. My father was always leaving things not properly finished, to the point, that one time it resulted in my sister ending up with a massive gash in her back as we played near some half-arsed shelving made with cinderblocks and wire reinforced glass panels ... right next to our beds... 

Of course, this experience left a big imprint on me, as I was playing some sort of game involving rocking back and forth like a see-saw ... and she fell back and... yeah, I felt so bad, but it wasn't really my fault. Whenever I see buildings unfinished but being lived in (very common in the balkans) I see something that disturbs me, and something that I would never allow in my own work. Safety first, before usage. Never let children in a space that adults would even injure themselves in. Sharp edges, nails sticking out, junk on the floor. All of these are traps that can literally kill.

### Blockchain Programming

The first thing I did that I consider to have been important was replicating the different consensus. I had the C++ code to work from, and had to alter the parts of the mining protocol that generated the difficulty change, and adding the scrypt hash, and then set up the original node so it only connected to the legacy old node to take the blocks, and then correctly validate and accept the blocks.

I can't remember exactly how long it all took me, maybe 2 weeks, maybe a month. In parallel to this, I was studying every bit of the language syntax and grammar that I was modifying so I could understand how to rewrite it. I am not completely sure exactly what I had done before this. I was really quite still a beginner, I was not composing any new code, just altering existing code to match the Parallelcoin consensus.

In this step you can see the same process repeating, first I start with an existing system, then tweak it, and then start to add new parts.

Prior to this, I never got past the initial stage of a rough specification of the application, and I would just start trying to build it from the ground up.

This is of course impossible to succeed at without first being fluent in the language and the algorithms.

Next, I started to think about how to make a hard fork, I took the existing definitions of the various details that defined the legacy version, that I now had successfully replicated, and added a scheme to track multiple versions, even though I was only making one new one.

This is a repeat of this pattern of 'finish it before using it' and the modularity from Lego that was very important to me. If I didn't make it easy to extend, I was committing a crime against whoever followed me. This is called Tech Debt, and I am extremely obsessive about not leaving it for others.

The fact that this same thing in construction work led to a severe injury to my sister, that I was witness to the horror of, I consider it to be a fact that every bit of tech debt, and shortcut used in code, can some day literally kill someone, or at least lose them a huge amount of money, as is more likely with blockchain systems.

I see no functional difference between injury and death, or to steal life, whether all at once, or piece by piece, both are crimes, and I knew from observing my father that his incremental damage was more insidious for being hard to observe, and as I have high intelligence, sharp senses, and a strong sense of order, that many other political and philosophical positions are clearly death traps like a half built house with 3 year old children playing in it.

I was not in danger, because of my alertness. My sister, however, was more awkward, more like her father, and I was like my mother, extremely dextrous, even in spite of my "cackky hands" - which is in fact due to the fact that I am right handed and target with my left eye, so I cannot swing a bat right handed, and cannot play hockey, I lost a nail playing hockey due to that, I don't know what the hell the teachers taking the class were thinking.

Once I had the framework for hard fork in place, I divided things up that were relevant to it, putting the various functions that goverened the difficulty adjustment, and made a second file that had the new versions.

Next, I had to implement the transition process. 
