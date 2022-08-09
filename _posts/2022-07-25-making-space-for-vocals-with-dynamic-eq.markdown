---
layout: post
title: Making Space for Vocals with Dynamic EQ
date: 2022-07-25 17:48
---

I was working on a mix recently and amongst some very mid-heavy electric guitars had some trouble getting the lead vocals to cut through. A normal solution to this would be to just scoop the guitar tone significantly and let the vocals sit in that space -- but I was pretty happy with the guitar tone from my Marshall DSL20, and it felt a shame to ruin that in sections of the mix where the vocals were less prominent. As a solution, then: sidechaining! And dynamic EQ using Fabfilter Pro Q-3.

First, the final (in its current state) mix:

<audio controls=""><source src="/assets/audio/scattered fullmix.mp3" type="audio/mpeg">Your browser does not support the audio element.</audio>

Hopefully you can hear that the vocals are cutting through fairly well and aren't lost amongst the wide guitars. I'll show the trick using Fabfilter and then some audio examples of the isolated guitar/vocals before and after.

I'm sending the vocals to the guitar bus' side chain -- in Reaper's case that's channels 3 and 4 on the track. 

![Routing](/assets/img/upload/Screenshot 2022-05-04 174419.png)

From within Pro Q-3, I have a dynamic EQ band at around 300-400Hz, which is where a lot of the mid frequencies were competing as the vocal here isn't sung in a particularly high register. The analyser is set to show the sidechain, and then under the section where you can set a manual threshold for a dynamic EQ band there's a little blue button -- this tells the EQ band to react to the sidechained signal rather than the track's primary L & R channels.

![FabFilter Pro Q-3](/assets/img/upload/Screenshot 2022-05-04 175603.png)

What this means is that when the vocals are playing, that 300-400 region of the guitars is softened -- the guitars can keep the beef in sections like the intro where there aren't any vocals, but when the singer actually sings they can be heard properly. It's the best of both worlds, where you get your favourite guitar tone when it matters and vocals that actually sit in the mix when *that* matters.

Here is a before and after using the dynamic EQ on the guitars to give you an idea of the difference:

EQ Bypassed
<audio controls=""><source src="/assets/audio/vox and guitars, eq bypassed.mp3" type="audio/mpeg">Your browser does not support the audio element.</audio>

EQ Engaged
<audio controls=""><source src="/assets/audio/vox and guitars, eq'd.mp3" type="audio/mpeg">Your browser does not support the audio element.</audio>