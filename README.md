# optimalcognition

A scratchpad for some notes about how to discover one's ideal type of work

The basis of one's ideal kind of work is the exact set of talents one was given by birth. These cannot be changed. Experience and learning can only compensate for it, either by mitigation or accentuation. 

The facts are unimpeachable, and can always be confirmed by a third party and thus achieve a consensus.

A consensus is then mislabeled "Truth" by liars. It is a false assertion because only an outside observer to the universe with all the facts, who can exhaust every path of investigation (ie, infinite time) can determine the nature of "truth".

## Case Study 1: Loki Verloren (the author!)


## Lego

In my play with my first toy, and my passion for the toy:

I started by simply following the instructions to learn how to piece together the object the package showed completed. It was a lot more fun to me than a jigsaw puzzle because it was tactile and modular, but I wanted to see the physical thing, that the picture promised. This is a pattern I can point to in almost every other aspect of my life, I start by watching, then I poke, then I start to take it into pieces, and then I try to build a whole system.

I never made big constructions, even when my collection got quite large. I tended towards small things, and playing with how to structure them most efficiently.

I wasn't really interested in representational things either, I enjoyed the geometry and visual elements, textures, repeating patterns, and so forth.

I did not fall in love with anything I made, it would usually be torn apart before I would even bother to show it to anyone, and showing it to people was not a major motivation.

## Computer Programming

### My initial work with programming was on a TRS-80 Color Computer, circa 1984

Firstly, I got in lots of trouble modifying the code my father had spent many hours inputting from programming magazines. I was more interested in seeing how the system went from the details and to the result.

When I actually got to doing something by myself, it was after I first saw a Macintosh computer. My very first piece of code combined multi dimensional arrays and boolean logic, and polling to making a mouse pointer.

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

My father did the same thing to me with carpentry too. In fact, Carpentry was probably the first activity I got the passion to engage in as a child. I was never able to do anything, because he never made the effort to teach me, and when I seized the opportunity to play with them, I got in huge trouble. 

An experience in 2004 in New Zealand proved that despite this, I had a talent for building as well. I started from nothing, first mastering how to cut square ends, then how to join them side by side with the correct stud width (600mm), and I aimed to use as little wood as possible, reusing offcuts as corners and braces.

An idiot, interfering twit housemate forced upon the project the idea of putting a structural floor at the base of it. This basically destroyed the utility of the space by making it so low I could almost bump my head if I stretched up on my tippy toes. 

In spite of this, I still did the rest. The frames all were up, and next, I placed all the fibre cement cladding on the outside, figuring the less time the frame is exposed, the better. I carefully predrilled the fixing points to minimise the amount of shock while I put the nails in that held them in place. Then I placed the window and door frames.

What I wanted to do for the floor was minimalistic. It had a sloped concrete track under it for car tyres, I wanted to just form a level box around the structure and make it flat and raise the higher part minimally and to provide a flat floor that would have had another 6 inches of height, and made the whole thing practical as a living space rather than an awkward storeroom.

I knew I would do it well, and I knew I would do it better than my father. My father was always leaving things not properly finished, to the point, that one time it resulted in my sister ending up with a massive gash in her back as we played near some half-arsed shelving made with cinderblocks and wire reinforced glass panels ... right next to our beds... 

Of course, this experience left a big imprint on me, as I was playing some sort of game involving rocking back and forth like a see-saw ... and she fell back and... yeah, I felt so bad, but it wasn't really my fault. Whenever I see buildings unfinished but being lived in (very common in the balkans) I see something that disturbs me, and something that I would never allow in my own work. Safety first, before usage. Never let children in a space that adults would even injure themselves in. Sharp edges, nails sticking out, junk on the floor. All of these are traps that can literally kill.

### Art

In much the same vein, my efforts to produce art, both music and visual forms, painting, drawing, and so on, always were about the details, and then building a structure up from them in an ad-hoc manner, creating a style of art that was completely dense and formed of hundreds of repeating patterns elaborated into different ways and scales. Representations were very difficult, beyond mastering the human form.

With music, the same... I was more interested in elements, like the combinations of progressions made of overlapping waveforms, and always struggled with the development from thesis to conclusion, never knowing when to stop, and struggling with all elements of the music that had to do with the narrative of the music.

With fiction, I did not have the patience to develop characters, and generally ran out of steam after I write some stream of consciousness that quickly leads to a conclusion, and has no overarching narrative structure. 

Of course, in all of these, training in this structuring work would have helped, but it highlights the fact that this structuring cognition is a weakness that should not be depended upon. And that this was a critical area to devote a sufficient amount of time to ensure it did not interfere with the team's work process.

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

Next, I had to implement the transition process and the additional features.

I don't remember exactly what order I did this in, as all of this part of the work was interdependent. This part of the system changed a lot, and though it was working as a whole thing, including a basic GUI wallet written in Gio, the lack of any kind of competent project manager in the team (or operations or treasurer) the project dragged on a lot longer, as I was learning to be project manager, architect, mentor, lead developer and manager (managing myself and my motivation) all in parallel during the total 2.5 years this all dragged out for.

I created a hash function that depended on cutting and rearranging and reversing bytes of the block's data, then performing a multiplication then division pattern that was designed to result in a growth in the size of the number, until it generated a 5-20kb long sequence of bytes, which then is finished off with a Blake3 hash. 

I am sure that this was an effective bottleneck that has a much narrower possibility for optimization than standard simple hash functions which generally function mainly by shuffling operations and bitwise logical operations. Long division is fastest in 64 bit cpus, and half as fast in GPUs and embedded processors like ARM64, that have 32 bits, and the reason being, that the amount of a chip dedicated to this computation is the largest single function on any CPU, and thus, only as fast as it needs to be for the median application, which this is an extreme application.

I extended the dual chain pattern to a 9 way pattern, experimented with using different finalising hashes at first, and then just using the same hash for each one but each different parallel schedule had a different time target, and different version number.

I then experimented with how to create an interdependency between the blocks so they would average a specific block time, and almost reinvented the concept of using the integral as found in the PID controller, used to get precise dynamic adjustment control in physics and quality adaptive control systems like antilock brakes, ballistic missile evasion control systems, and the like.

In my next role, with Energi, my manager, who was awesome, btw, Ryan Lucchese, probably due to my way of talking about my prior experience working with developing a stable proof of work consensus, realised that PID controllers are exactly what the task required, and built the functions that were required. 

Yes, I just want to reiterate something, that is further reinforced later about my personality, and based on my experience of near fatal accidents caused by this, as well as my own miserable prior life to 10th December 2021: 

If you are given the responsibility of leader, and you make a mistake, and a follower points it out, and they are correct, then you are leading the team into disaster. The simple visual representation of Integral and Derivative make this very clear. Integral gives you the area under the curve, and from this value, you get the momentary gradient at this point. The Derivative is simply the perpendicular in a 1 dimensional (up and down) adjustment, which neutrtalises the derivative, and would be used in a system where there is two dimensions and thus two ways the error can be incorrect. 

I extensively tested various factors and dumped the charts into an archive of screenshots of the charts that the different P, I and D factors created, and it just added noise, almost the same as if the Proportional factor was raised or the Integral decreased... which of course it does in a 1 dimensional system (over, or under target). If there was over, and beside, then the first dimension integral would be denoised by the derivative of the second dimension.

What I did not like about how he did it, though, which was a big mistake on his part, was taking that job away from me. Probably, because he didn't realise that I don't have a bachelor of science in physics, but I can visualise physics formulae with my imagination and thus from there describe them into code. It would have taken no more than twice the time he took to do it, and he had years of studying the PID controller compared to my zero minutes. 

As in the previous paragraph of reflections after the fact, the uses of the derivative would have been very relevant in the vibration proof air cushion system he described in his discussion about it, as the air cushion has two dimensions to keep a level, vibration free surface, X, and Y, or forwards and lateral, as you look at the plane of the platform.

I had no problem understanding how to do the mathematics, and it was me who insisted, that in order to make the consensus as robust as possible, the calculations should be done on fixed precision rather than floating point, which required writing them, which was what I did first, and I butted heads against everyone in the team about this subject, until Ryan finally acknowledged that I was right.

Back to the Parallelcoin, the next few parts that I did with it, once I had a working replacement consensus for the hard fork, and a tested transition, there was several matters to attend to:

### GUI

This was a very long drawn out process of argument and counterargument, and was made a lot less productive by this indecision. I knew what way I wanted to implement the GUI, and quickly found the nearest thing to what I wanted in a library called Nucular. 

Eventually we settled on something very similar, that in fact now uses Gio, the choice we settled on, and the "ruler from the shadows" of the project then proceeded to take his extensive experience building web interfaces using HTML and javascript tooling, which he started with first, as many projects have chosen, due to the universal availability of webviews in most operating systems, such as the one used in Safari, that was forked to become the one in Chrome, and now is everywhere, even microsoft gave up trying to continue the long legacy of Mosaic, and Netscrape won. Yes, a lot of people don't realise that. The browser wars ended only a couple of years ago when Microsoft gave up trying to make their own, "better" engine.

I had nothing to do with this particular part of the project until out of months of humming and harring and scratching things out, he settled on Gio. 

Of course, his Python-derived methods of structuring the code were completely non-idiomatic for Go, and were very hard to debug. 

His style of building it was wrong for Go, and wrong for an immediate mode process, and he eventually created some really insoluble bugs with his ad hoc way of piecing it together.

He was following the examples of the author of Gio, which were extremely hard to read, and thus grew unbearably complex very quickly, at which point I started what is now in various places and versions, a Domain Specific Language form, which I based on method chaining with objects returning themselves so they could be passed through, and then finding a way to embed them more easily within each other, while minimising the depth of indentation required so a whole interface didn't have to be cut into twenty pieces.

The thing that made me eventually push hard enough that we were able to reach consensus on the use of Gio, was the point that it could be easily made to run on all platforms, Windows, Mac, Linux, Android and iOS.

But unfortunately, the library lacked a proper DSL, and I got quite waylaid building that DSL, and frustrated with trying to communicate this severe deficiency in the library, that as far as I know, even now lacks a proper scrolling panel.

I made a rudimentary scrollbar, additional to the sectioned box shortcut version that avoided rendering invisible parts of a viewport, that could not yield a proper indicator and widget set to make your *normal* scrollbars as found on all viewport implementations.

I found that there was a way to separate the size calculation from the rendering, which (is still, I think) interleaved in the processing at the deepest level of the library. 

### Creating a miner 

I first just took the inbuilt "toy" testnet miner from btcd, and then isolated it inside a separate binary, and created a stdio based IPC pipe to connect it to the node, so it was separated.

Then, I split the miner into a controller, which handled the delivery of the work, and the worker, and then split the worker, because I suspected that the Go concurrency system was not maximising the parallelism the same way as the preemptive kernel scheduler would.

With this three piece pattern, controller, miner, and worker, a chain of processes spawning child processes, I then had something that just needed a network protocol to deliver the work across a network instead of forcing the user to have a full node for every miner, which was obviously a huge waste of computing resources.

I eventually settled on using multicast, because there is a huge amount of overhead involved in connection management, that I had seen in great detail in the peer to peer libraries that btcd, the big list of peers, and the connection monitoring, and everything like this, could be avoided by using multicast, effectively making the network into a hub. At first, delivery of solutions was point to point, but even that turned out to be simpler to use multicast, and gave an extra bonus that it became another way for miners to recognise that working was pointless, as a valid solution block is quick to check. I'm not sure if I kept it that way, there was some experimenting.

The biggest problems I had in all of this were the vast differences between Windows process model, and Linux, and then the divergence between Linux/Android, MacOS, and Windows. It all eventually was made to work, on all platforms, identically, and heteregenous platforms could be used to run a cluster, I had the idea, that since the proof of work reduced the advantage of any of the platforms (including the hypothetical GPU implementation), that mining farms could reuse old mobile phone devices. 

Well, until I found out that such applications were prohibited to be on either Android or Mac walled gardens. They still could be installed, but this release avenue was shut.

Because it used multicast, essentially one could then create redundancy with multiple nodes in a network, transparently, and miners would pick and stick to the first one they heard, until it went offline, and then automatically pick up the other controller's jobs within seconds, avoiding downtime.

It was a core goal of the mining protocol to be as fast as possible, as the key to proof of work mining is purely about racking up attempt counts. The more times a new option was tried, the greater the chance of finding a solution, so the less time a cluster spent not working, and conversely, from the times when the network knew there was no solution, to delivering the new job in parallel to propagating the solution, to give the solver an edge at the time of the solution, to grab the next one.

### The Monitor

This did not end up going very far, but made use of the child process code used in the miner to create a testing environment for monitoring logs and filtering them by subsystem to improve the experience compared to the less flexible use of TTY consoles as logging, where colors and patterns became difficult to make different enough to notice errors appearing in the form of incorrect outputs.

This part of the project downloads and installs a Go development environment, closes the repository, and allows the developer to edit the code, and rapidly restart it.

## Conclusions from Case Study of Loki

Firstly, it is best to use Loki's creativity in a more research oriented role, where there is not a deadline, but where safety and efficiency are the most important feautures of the end product. Loki believes that safety and efficiency cannot be compromised on, period, and will endlessly berate anyone who takes shortcuts, to the point of disrupting the team by his stubborness.

Secondly, Loki learns best by doing, and for this reason, the simplicity of Go was a key ingredient in making progress. The more complicated the language, the more likely he is to make choices on how to do something from the first thing that presents, and miss the better solution. So a language that aims to make only one way to do something is better than an "expressive" language like C++ or Rust. 

Thirdly, Loki always thinks of who is going to inherit the code, and thus always aims to make the code adequately annotated, but also quite self evident and readable at the same time. Thus, he can start documentation, but it will end up excessively exhaustive if he is left to the whole task. It is probably even better for documentation writing to be done by consultation and a more top down thinker who can easily start from rubrics and elaborate optimally takes the task of adjunct documentation beyond the bullet point level.

Fourthly, derived from the two preceding, this focus on simplicity and responsibility means he can and is enthusiastic towards sharing the refined designs makes him good for both working with tooling and designing work protocols, as well as teaching them, as the teaching process often exposes further flaws and ambiguities that ensure the goals of safety and maintainability are achieved.

Fifth, the deep understanding and ability to model complex, interacting individual parts as found in distributed and concurrent systems, also means that he can in fact manage the work process of groups of other programmers, once he becomes familiar with each individual's style of cognition, and assign them to the elements that fit them best. For sure, in the beginning, his management and delegation processes should be monitored until he is familiar with both the organisational demands and the time to acquire the necessary information about who is best at doing what.

Lastly, Loki can be relied upon to be completely ruthless in critiquing anything. This is a feature that means that he should not be asked his opinion if the querant is emotionally invested in their work, and causes him to come into fatal conflict with colleagues who engage in any kind of narcissistic or manipulative behaviour. Thus, he can be utilised as an early warning system for new team members who are attempting to usurp power from the project's founders and management. 

Thus, also, it is advisable that he has a routine meeting with a mentor/manager to stop these concerns interrupting his productivity, and devise a way to fix this problem before it becomes a reason to abandon the team. In this way, this sensitivity can be turned to the advantage of the whole team, who will benefit from the early detection of organisational issues. Loki does not want to be stuck seeing a problem he can't do anything about it. Unsolved problems that the team seems unconcerned with lead to attempts to act to fix them directly, or, a sense of exclusion from the group that leads to alienation and eventual abandonment.

The last point is directly the result of the first point. Such mischief in a team is always a slow road to a very bad result for the entire team, if it is ignored, and this talent for recognising errors in systems is a key value that Loki can bring to a team, and thus to disrespect it is to exclude Loki from the team.
