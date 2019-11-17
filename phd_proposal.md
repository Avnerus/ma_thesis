---
title: Doctoral Candidate in Digital Learning
subtitle: Applicant statement
author: Avner Peled
date: 11/2019
documentclass: article
indent: true
csl: apa2.csl
header-includes: |
    \usepackage{xeCJK}
    \usepackage{xelatexemoji}
    \usepackage{float}
    \usepackage{fvextra}
    \DefineVerbatimEnvironment{Highlighting}{Verbatim}{breaklines,breaksymbolleft={\quad},commandchars=\\\{\}}
    \makeatletter
    \def\fps@figure{H}
    \makeatother
...
---

\maketitle
\newpage
\tableofcontents
\pagebreak

# Statement
With great determination and humility I am applying for the position of Doctoral Candidate in Digital Learning in the Learning Environments research group at the Aalto Media Lab. Following the completion of my Master's thesis at the media lab: _Soft Robotic Incarnation_ [@peledSoftRoboticIncarnation2019], I wish to carry on the same research path that brought me to my current state, but to expand on it, and induce bifurcations that would lead me to unexplored territories of soft robot mediation. I intend to persist with an active and exploratory approach that adjoins scientific research with philosophy, and philosophy with design and artistic practices, not forgetting the initial motivation that brought me to the media lab, the dire need for creative and technological solutions in the Israeli-Palestinian conflict. 

During my doctoral studies, I aim to design and produce the next generation of my soft robotic telepresence: HITODAMA, as well as deploy it in public spaces both in Israel and in Palestine. At the same time, I will perform local case studies in various fields in Finland, focusing on public spaces and educational systems. I hope to initiate international research collaborations, not only in Japan as I have already done in my Master's thesis, but also in Israel where cutting edge research in the psychology of conflict and in expressive robotics is taking place. The work on HITODAMA in my Master's thesis has taught me a great deal of valuable lessons which will serve my greatly as I proceed toward the next steps. I have devised the following draft for a research plan based on the conclusions and evaluations of my Master's thesis, as well as my future aspirations for the field.

# Research overview

## From reification to incarnation through user experience
In my Master's thesis, I investigated and categorized various ways in which a remote, re-embodied individual is experienced by the local interlocutor who is interacting with the mediating robot. I am primarily interested in the depth, authenticity and presence of the remote individual's inner, irreducible qualities, as they are expressed through the robot. I began to materialize these notions nominally through phenomenological terms such a flesh [@merleau-pontyVisibleInvisibleFollowed1968], logos [@ranciereDisagreementPoliticsPhilosophy1999;@edgarThingsSeenUnseen2012] and intercorporeality [@merleau-pontyVisibleInvisibleFollowed1968;@meyerIntercorporealityEmergingSocialities2017]. A spectrum could be thought-of (see @fig:incarnation), describing the range of of phenomena as the figure of the stranger is incorporated into the mind of the individual in relation to the depth of the interaction. On one end, when the experience is shallow, I hypothesize that the interlocutor is liable to generate a flat, biased, and fetishized figure of the stranger; a reification of predispositions onto the body of the stranger; when the interaction, however, has corporeal depth, the veritable logos of the stranger is assimilated into the body of the interlocutor. At the same time, a spectrum of experience exists for the controller, in which I hypothesize that the sense of agency and ownership [@dolezalRemoteBodyPhenomenology2009] rises in relation to the depth of the interaction. 

Within the scope of the Master's thesis, those hypotheses were taken as axioms, validated by a reflective, or even prereflective, logic of experience. A web-based soft robotic telepresence solution was produced to ratify those intuitions, and the results and their qualitative analysis were inconclusive. What was shown, however, is that design choices which may first appear as user interface nuances, carry a crucial role in determining the position of the experience on the aforementioned intercorporeal scale. The use and location of the digital display, the turn-taking dynamics, the fluidity and dynamic range of the controls and robotic motion, the field of view of the camera, feedback signals - these are only part of the elements that make up the whole user experience, and shift the perception of the interlocutors and their view of the medium and of each-other. Pursuing these questions under the scope of a doctoral dissertation would provide me with ample time to delve into each UX element, design solutions and test them.

```{#fig:incarnation .pyplot caption="Interaction through robot mediation"}
import matplotlib.pyplot as plt

plt.figure()
fig, axs = plt.subplots(2, 1, sharex=True)
axs[0].plot([0,1,2,3,4], [0,1,2,3,4], marker='o', color='red')
axs[1].plot([0,1,2,3,4], [0,1,2,3,4], marker='o')
plt.xlabel('Depth of intercorporeality')
axs[0].set(ylabel="Controller's experience")
axs[0].set_yticks([])
axs[1].set(ylabel="Interlocutor's experience")
axs[0].text(2.4, 3.8, "Agency & Ownership")
axs[0].text(-0.1, 0.7, "Alienation")
axs[1].text(3., 3.8, "Incarnation")
axs[1].text(-0.1, 0.7, "Reification")
frame1 = plt.gca()
frame1.axes.get_xaxis().set_ticks([])
frame1.axes.get_yaxis().set_ticks([])
```

## Post-humanoid, web-based soft robotics as an expressive medium
About half of my Master's thesis was dedicated to technological research and development in the field of soft robotics and remote telepresence. Novel methods for the production of soft-moving body parts were presented, and a modern web platform was developed for easy operation and extensibility. Additionally, HITODAMA, a post-humanoid robot, was presented, inspired by Japanese spirit folklore and the regenerative salamander Axolotl. While the design showed promise, it also fell short in utilizing the full range of possibilities enabled by the soft medium. As noted in my evaluation: "The robot’s movements, for instance, are restricted to switching between discrete states rather than utilizing the full spectrum of fluid continuous movements possible with soft robotics." Fluid web-base remote control, one that does not rely on passive sensing, but encourages active expression using lowest-denominator devices such as low-tier smartphones and desktops, is a challenge worth pursing. As a ground plan, the complexity of the soft body parts used for HITODAMA could be drastically reduced, opting for smaller, more abstract shapes that still convey organic characteristics. 

Another aspect of the soft medium that was not explored during the thesis is the tethered nature of pneumatic solutions, requiring the robot to be connected by air tubes to an array of pneumatic circuits. This in fact limits the mobility of the experience, forcing the interaction to occur within the limited range of the tubes. Untethered solutions for soft robots do exist, however, whether they are using enclosed pneumatic micro-circuits, or completely different actuation methods such as dielectric elastomers [@ahmedStrangeEncountersEmbodied2000]. The viability, cost and complexity of those solutions should be measured against the advantages of a more mobile experience.

## Robotic mediation for conflict resolution

# Time-line

# Summary


# References
