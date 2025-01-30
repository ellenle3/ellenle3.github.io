---
title: "First light of IRTF's adaptive secondary mirror"
date: 2024-04-28T00:52:41-10:00
---

We successfully completed our first engineering run with IRTF-ASM-1 on Friday.
This marks a number of milestones:

- IRTF achieved stable diffraction-limited image quality for the first time.
- IRTF-ASM-1 is the first adaptive secondary mirror on Maunakea.
- This is the first on-sky demonstration of the hybrid-variable reluctance actuator
technology developed by TNO.

Overall, the
run went exceptionally well despite [the highly compressed timeline](/blog/20240428/Mikroniek-2024.pdf)
of this project. We obtained closed-loop, diffraction-limited images (Strehl ~ 40%
in H-band over 5 minutes of integration) and successfully ran the system under a
variety of seeing conditions (0.4" to 0.9"). The first light image was acquired
on [Hokule'a](https://blog.bishopmuseum.org/history/hokulea/), which is a tradition
at IRTF.[^1]

<p align="center">
  <img src="/blog/20240428/hokulea_irtf-1.jpg" alt="snapshot closed loop on Hokule'a"/>
</p>

We had a great team of people all around, including our collaborators at TNO, UCSC, 
and IRTF staff. Special thanks in no particular order:

- IRTF day crew: Paul, Keith, Dwight, Jun, and Darryl supported major work at the
telescope for several months and on short notice.
- Our director: John has been very generous with observing time and funding for
the ASM and has been working to balance that with IRTF science.
- Telescope operators and assistants: Brian, Bernie, and Frankie supported our
observations the three nights.
- TNO: Fred and Saunder took a long flight from the Netherlands to document this
process for National Geographic. Max also joined remotely to help debug the controllers.
- Olivier flew in from France to support the first two runs and has helped us
with lab testing as well.
- IfA Hilo: Suzanne, Mike, and Mark have kept me sane in the lab.

![group photo in front of IRTF after first light of IRTF-ASM-1; credit: Fred Kamphues](/blog/20240428/FKamphues_group.jpg)

The run started on the morning of April 23. The day crew performed a top end
exchange to put the ASM on the telescope. We closed the loop around 2 AM on the
first night after dealing with alignment issues, and the RTC fighting the facility
guider. The run ended on April 26 after three full, productive nights at the
telescope.

We have a ton of data to analyze over the coming weeks, both for presenting basic
on-sky functionality at SPIE and FELIX-like (fast low-order + slow high-order)
correction for my dissertation. Not bad considering that we recieved the ASM from 
TNO in mid-February! It's hard to believe that that things went so smoothly given
all of the problems that even mature adaptive optics systems tend to have, let
alone a new technology.[^2] Because we were worried about flexure, we also got away
with disassembling and reconfiguring the entire wavefront sensor breadboard ~2
weeks before the run began... The past few weeks have felt like months to me.

Last but certainly not least, the weather was cooperative. The sky was clear
throughout the run. As we were leaving the summit after our last night at IRTF,
we could see cirrus clouds starting to come over the horizon. Talk about good
luck!


[^1]: Definitely not a coincidence and totally planned on my part. Hokule'a (known
to most in the West as [Arcturus](https://en.wikipedia.org/wiki/Arcturus) or
[&alpha; Boo](http://simbad.cds.unistra.fr/simbad/sim-id?Ident=alf+boo)) is a
prime first light target because it's *very* bright and goes through zenith at
Hawai'i's latitude. The same reasons make it important for Polynesian navigation.

[^2]: Lots of firsts this run. The response of the ASM is somewhat slow due to the
thickness of the facesheet. The seeing makes it difficult create interaction matrices
on-sky by poking individual actuators and we don't have an intermediate focal plane
to work with at IRTF. Olivier came up with a new method to generate interaction
matrices by sinusoidally modulating the actuators. This method (CACOFONI) will be
described in an upcoming paper.