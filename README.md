# optimalcognition

A scratchpad for some notes about how to discover one's ideal type of work

## Case Study 1: Loki Verloren (the author!)

1. Lego

In my play with my first toy, and my passion for the toy:

I first showed that I enjoy playing with permutations, taking a set of pieces and finding new ways to arrange them.

I never made big constructions, even when my collection got quite large. I tended towards small things, and playing with how to structure them most efficiently.

I wasn't really interested in representational things either, I enjoyed the geometry and visual elements, textures, repeating patterns, and so forth.

I did not fall in love with anything I made, it would usually be torn apart before I would even bother to show it to anyone, and showing it to people was not a major motivation.

2. Computer Programming

### My initial work with programming was on a TRS-80 Color Computer. 

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

