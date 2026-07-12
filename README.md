# CyberLoop – Game Design Document

**Event:** Hackathon 2025
**Type:** Team project (concept/design only — not implemented)

## Overview

*CyberLoop* is a Serious Game concept for VR, narrative and decision-based, designed during a hackathon to raise awareness about cyberbullying and social responsibility. This repository contains the Game Design Document (GDD) only: the idea, narrative, mechanics, and technical specification were fully designed as a team, but no software or prototype was implemented.

## Concept

The player lives through the same school day on a time loop, playing a popular teenager who mocks and bullies classmates online. After ignoring an anonymous warning message, he becomes trapped in the loop, forced to relive the day while experiencing distorted sensory effects (blurred vision, distant laughter, oppressive sound design) that mirror what a bullying victim feels.

The loop can only be broken by making at least 90% positive choices across the day, teaching the player, through direct experience rather than punishment, that every online action has a real consequence.

## Educational Objectives

- Build **digital empathy** by making players feel a victim's emotions (anxiety, isolation, fear of judgment)
- Show how **small online actions have large consequences**, visualized through escalating sensory feedback
- Encourage **personal and collective responsibility** (bystander, bully, defender roles)
- Contrast **popularity vs. integrity**, promoting authenticity over online validation
- Support **post-game reflection**, guided by a teacher or educator

**Target audience:** students aged 10–18, in school or educational settings (classrooms, youth centers, awareness workshops).

## Gameplay & Mechanics

- **Structure:** a repeating school day (wake-up → bus → school entrance → gym → locker room → home) with branching choices at each scene
- **Empathy Points:** rise with positive/defending choices, fall with bullying or inaction; low empathy triggers disturbing visual/audio distortions
- **Followers:** rise with cruel/denigrating choices, offering only superficial in-game rewards while the world grows colder and more alienating
- **AI role:** classifies player-written messages (positive/neutral/negative) in real time to update Empathy/Follower scores, and drives adaptive dialogue and environmental reactions to sustain narrative immersion
- **Endings:** loop continues (increasingly distorted) if <90% positive choices after 3 cycles → Bad Ending; loop breaks with a Good Ending once the 90% threshold is reached

## Technical Specification (as designed)

- **Platform:** VR (Meta Quest 2+), targeting 72–90 FPS; future cross-platform (PC/Mobile) support considered
- **Visual style:** semi-realistic/stylized, adaptive color palette (warm tones for high empathy, cold/desaturated/distorted for low empathy)
- **Interaction:** pointer/hand-gesture selection, teleport or fade movement to avoid VR motion sickness
- **Audio:** 3D spatial sound design with psychoacoustic effects, haptic feedback on critical choices, dynamic music
- **Accessibility:** subtitles, adjustable sensory intensity, short sessions, supervised use with facilitator
- **Scalability:** modular scene architecture, anonymized aggregate choice data for educational/research use

## Repository Contents

- `Game_Design_Document__GDD_.pdf` – full design document# CyberLoop – Game Design Document

**Event:** Hackathon 2025
**Type:** Team project (concept/design only — not implemented)

## Overview

**CyberLoop** is a **Serious Game concept for VR**, narrative and decision-based, designed during a hackathon to raise awareness about **cyberbullying and social responsibility**. This repository contains the **Game Design Document (GDD)** only: the idea, narrative, mechanics, and technical specification were fully designed as a team, but **no software or prototype was implemented** — this was a design/concept submission.

## Concept

The player lives through the same school day on a **time loop**, playing a popular teenager who mocks and bullies classmates online. After ignoring an anonymous warning message, he becomes trapped in the loop, forced to relive the day while experiencing distorted sensory effects (blurred vision, distant laughter, oppressive sound design) that mirror what a bullying victim feels.

The loop can only be broken by making **at least 90% positive choices** across the day — teaching the player, through direct experience rather than punishment, that every online action has a real consequence.

## Educational Objectives

- Build **digital empathy** by making players feel a victim's emotions (anxiety, isolation, fear of judgment)
- Show how **small online actions have large consequences**, visualized through escalating sensory feedback
- Encourage **personal and collective responsibility** (bystander, bully, defender roles)
- Contrast **popularity vs. integrity**, promoting authenticity over online validation
- Support **post-game reflection**, guided by a teacher or educator

**Target audience:** students aged 10–18, in school or educational settings (classrooms, youth centers, awareness workshops).

## Gameplay & Mechanics

- **Structure:** a repeating school day (wake-up → bus → school entrance → gym → locker room → home) with branching choices at each scene
- **Empathy Points:** rise with positive/defending choices, fall with bullying or inaction; low empathy triggers disturbing visual/audio distortions
- **Followers:** rise with cruel/denigrating choices, offering only superficial in-game rewards while the world grows colder and more alienating
- **AI role:** classifies player-written messages (positive/neutral/negative) in real time to update Empathy/Follower scores, and drives adaptive dialogue and environmental reactions to sustain narrative immersion
- **Endings:** loop continues (increasingly distorted) if <90% positive choices after 3 cycles → Bad Ending; loop breaks with a Good Ending once the 90% threshold is reached

## Technical Specification (as designed)

- **Platform:** VR (Meta Quest 2+), targeting 72–90 FPS; future cross-platform (PC/Mobile) support considered
- **Visual style:** semi-realistic/stylized, adaptive color palette (warm tones for high empathy, cold/desaturated/distorted for low empathy)
- **Interaction:** pointer/hand-gesture selection, teleport or fade movement to avoid VR motion sickness
- **Audio:** 3D spatial sound design with psychoacoustic effects, haptic feedback on critical choices, dynamic music
- **Accessibility:** subtitles, adjustable sensory intensity, short sessions, supervised use with facilitator
- **Scalability:** modular scene architecture, anonymized aggregate choice data for educational/research use

## Repository Contents

- `Game_Design_Document__GDD_.pdf` – full design document
- `README.md` – this file

## Authors

Alessio Abate, Federica Cirillo, Sabrina Lorenza Cozzolino, Fulvio Petrelli, Anna Sgambati
