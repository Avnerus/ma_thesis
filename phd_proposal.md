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
With great determination and humility I am applying for the position of Doctoral Candidate in Digital Learning in the Learning Environments research group at the Aalto Media Lab. Following the completion of my Master's thesis at the media lab: _Soft Robotic Incarnation_ [@peledSoftRoboticIncarnation2019], I wish to carry on the same research path that brought me to my current state, but to expand on it, and induce bifurcations that would lead me to unexplored territories of soft robot mediation. I intend to persist with an active and exploratory approach that adjoins scientific research with philosophy, and philosophy with design and artistic practices; not forgetting the initial motivation that brought me to the media lab, the dire need for creative and technological solutions in the Israeli-Palestinian conflict. 

During my doctoral studies, I aim to design and produce the next generation of my soft robotic telepresence: HITODAMA, as well as deploy it in public spaces both in Israel and in Palestine. At the same time, I will perform local case in Finland to asses various UX strategies, targeting public spaces and educational systems. I hope to initiate international research collaborations, not only in Japan as I have already done in my Master's thesis, but also in Israel, where cutting edge research in the psychology of conflict and in expressive robotics is taking place, and in Palestine, where emerging artists and technologists are dealing with the conflict from personal and knowledgable perspectives. The work on HITODAMA in my Master's thesis has taught me a great deal of valuable lessons which will serve my greatly as I proceed toward the next steps. I have devised the following draft for a research plan based on the conclusions and evaluations of my Master's thesis, as well as my future aspirations for the field.

# Research overview
 
## From reification to incarnation through user experience
In my Master's thesis, I investigated and categorized various ways in which the experience of robotic telepresence, or remote re-embodiment, is experienced both by the local interlocutor who is interacting with the mediating robot, and the remote individual taking control of the robot. I am primarily interested in the depth, authenticity and presence of the controller's inner, irreducible qualities, as they are expressed through the robot, and the ability to express those qualities through a remote interface. I began to materialize these notions nominally through phenomenological terms such a flesh [@merleau-pontyVisibleInvisibleFollowed1968], logos [@ranciereDisagreementPoliticsPhilosophy1999;@edgarThingsSeenUnseen2012] and intercorporeality [@merleau-pontyVisibleInvisibleFollowed1968;@meyerIntercorporealityEmergingSocialities2017]. A spectrum could be thought-of (see @fig:incarnation), describing the range of of phenomena within individuals in both sides of the conversation in relation to the depth and corporeality of the interaction. As the local interlocutor incorporates the embodied figure of the stranger into their mind as it is represented by a robot, the experience ranges between two phenomenological endpoints: When it is a shallow, flat, virtual, experience, I hypothesize that the interlocutor is liable to generate a biased and fetishized figure of the stranger; a reification of predispositions that stick to the body of the stranger. When the interaction, however, has corporeal depth, the veritable logos of the stranger is assimilated into the body of the interlocutor. At the same time, a spectrum of experience exists for the controller, in which I hypothesize that the sense of agency and ownership [@dolezalRemoteBodyPhenomenology2009] rises in relation to the depth of the interaction. This affects the controller's ability to express themselves; when they experience an increased sense of ownership, they are more accountable to their actions, but are then more cautions in expressing deeper and more controversial opinions.

Within the scope of the Master's thesis, those hypotheses were mostly taken as axioms, validated by a reflective, or even prereflective, logic of experience. A web-based soft robotic telepresence solution was produced to ratify those intuitions, and the results and their qualitative analysis were in-line with the theory but nonetheless inconclusive. What was shown, is that design choices which may first appear as user interface nuances, carry a crucial role in determining the position of the experience on the aforementioned intercorporeal scale. The use and location of the digital display, the turn-taking dynamics, modalities of language, the fluidity and dynamic range of the controls and robotic motion, the field of view of the camera, feedback signals - these are elements that make up the whole user experience, and shift the perception of the interlocutors and their view of the medium and of each-other. Pursuing these questions under the scope of a doctoral dissertation would provide me with ample time not only to expand on the theoretical notions that derived them, but to delve into each and every UX element, placing them on the intercorporeal scale, designing variations and testing them in the field.

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
Half of my Master's thesis was dedicated to technological research and development in the field of soft robotics and remote telepresence. Novel methods for the production of soft-moving body parts were presented, and a modern web platform was developed for easy operation and extensibility. Additionally, HITODAMA, a post-humanoid robot, was presented, inspired by Japanese spirit folklore and the regenerative salamander Axolotl. While the design showed promise, it also fell short in utilizing the full range of possibilities enabled by the soft medium, as noted in my evaluation: "The robot’s movements, for instance, are restricted to switching between discrete states rather than utilizing the full spectrum of fluid continuous movements possible with soft robotics." Fluid web-base remote control, one that does not rely on passive sensing, but encourages active expression using lowest-denominator devices such as low-tier smartphones and desktops, is a challenge worth pursing. As a ground plan, the complexity of the soft body parts used for HITODAMA could be drastically reduced, opting for smaller, more abstract shapes that still convey organic characteristics and enable fluid control. 

Another aspect of the soft medium that was not explored during the thesis was the tethered nature of pneumatic solutions, requiring the robot to be connected by air tubes to an array of pneumatic circuits. This in fact limits the mobility of the experience, forcing the interaction to occur within the limited range of the tubes, but also frames the experience to a specific site and context. Untethered solutions for soft robots do exist, however, whether they are using enclosed pneumatic micro-circuits, or completely different actuation methods such as dielectric elastomers [@ahmedStrangeEncountersEmbodied2000]. The viability, cost and complexity of those solutions should be measured against the advantages of a more mobile experience.

## Robotic mediation for conflict resolution
The primary goal as was stated for HITODAMA, was mediation in conflict resolution when a face-to-face meeting between the adversaries is not possible or highly unlikely. In my Master's thesis, however, the scope of the tests was limited to interactions between Finnish locales and foreign immigrants. Furthermore, I did not have time for a deep investigation of conflict resolution methodologies and their juxtaposition with telerobotic mediation. One vantage point comes from the research of Professor Ruth Feldman, who formulates connections between the haptic sociality, neuroscience, and approaches to conflict resolution in the Israeli-Palestinian conflict [@influsSocialNeuroscienceApproach2018A]. I have contacted Professor Feldman regarding my project and was invited to visit her lab. I asked her whether she collaborated with the MILab ^[http://milab.idc.ac.il/], a human-computer interaction lab under the same academic institution as Feldman that specializes in innovation in the field of robotic movement [@hoffmanDesigningRobotsMovement2014]. Feldman has responded that they were in fact planning a collaboration, but were so far not able to realize it yet due to time constraints. It is my hope that I would be able to act as a bridge between those two disciplines, perhaps with the help of IDC's 
Global Affairs and Conflict Resolution Cluster^[https://www.idc.ac.il/en/schools/rris/undergraduate/pages/global-conflict.aspx]. Naturally scholars specializing in conflict resolution are abundant in Israel and there are multiple pathways for collaboration. One point of interface could occur with Dr Yael Berda, who specializes in freedom of movement and the bureaucracy that manages it [@berdaBureaucracyOccupationPermit2012]. In an aspiring interview in _Haaretz_ newspaper ^[https://www.haaretz.co.il/magazine/.premium-MAGAZINE-1.5975041], Berda discussed the embodied cognitive effects of the occupation, and the bodily experience of crossing the separation barrier. In addition to Israeli connections, it is imperative to involve the Palestinian art and science scene in the process. Before starting my Master's thesis, I had a chance to meet an artist and maker from Ramallah with whom I shared my vision for this project. He was very excited to participate, but because HITODAMA never made it to the final goal, we never carried through with our plans for collaboration. This time, however, I will commit to realizing the project in Israel and Palestine and will pursue the involvement of Palestinian partners as early as possible.


# Time-line

```{#fig:timeline .pyplot caption="Research timeline draft"}
import numpy as np
from matplotlib import pyplot as plt

x_arr = np.zeros(48)
y_arr = np.arange(48)

x_arr[0] = -24
x_arr[47] = 24

plt.hlines(y_arr, 0, x_arr, color='red')  # Stems
plt.plot(x_arr, y_arr, 'D')  # Stem ends
plt.plot([0, 0], [y_arr.min(), y_arr.max()], '--')  # Middle bar
ax = plt.gca()
ax.invert_yaxis()
ax.annotate("hello", xy=(-24, 0))
fig = plt.gcf()
fig.set_size_inches(8, 12)
```


# Summary


# References
