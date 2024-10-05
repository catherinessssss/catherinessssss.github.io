---
layout: fish
title: "Paper notes"
permalink: paper_notes/music/
---

## 1. Gonzalez, Manuel F., and John R. Aiello. **"More than meets the ear: Investigating how music affects cognitive task performance."** Journal of Experimental Psychology: Applied 25.3 (2019): 431.


This paper explores how music affects task performance based on three factors: the type of music (simple or complex), the task complexity (simple or complex), and the listener's preference for external stimulation (introvert or extravert). Results show that music generally impairs complex task performance but complex music aids simple tasks. Preferences for external stimulation influence these effects: introverts benefit from music during complex tasks, while extraverts experience impaired performance, particularly with complex tasks. Volume also plays a role, with introverts performing better with soft music and extraverts with loud music on simple tasks.

---

- This paper investigate how music affects task performance in three different ways:
  - a) What one is listening to (simple music or complex music, determined by the number of instruments; more instruments make it more complex).
  - b) what task is being performed (simple task or complex task)
  - c) who is listening to the music (low [introvert] or high [extravert] preference for external stimulation). Participants completed personality measures, including the Boredom Proneness Scale, to determine their preference for external stimulation.

---


- The results suggest that:
  - In general:
    - **Music impaired complex task performacne**.
    - **Complex music facilitated simple task performance**.
  - However, perference for external stimulation moderated these effects,
    - **For low preference for external stimulation**:
      - Simple task:
        - complex music facilitated simple task performance, with no score difference between no music and simple music.
        - Soft volume of music (50-56dB) facilitated simple task performacne the most, followed by loud volume (62-78dB), and the least was no music.
      - Complex task:
        - Muisc facilitated complex task performance compare to no music.
    - **For high preference for external stimulation**:
      - Simple task:
        - Simple music slightly facilitated simple task performance compared to no music, while complex music impaired performance.
        - Loud volume of music (62-78dB) facilitated task performance more than no music; soft music (50-56dB) impaired task performance.
      - Complex task:
        - Music harmed task performance significantly.

----

## 2. Benetos, Emmanouil, et al. "Automatic music transcription: An overview." IEEE Signal Processing Magazine 36.1 (2018): 20-30.

This paper focuses on the transcription of polyphonic music—a complex mixture of multiple simultaneous sound sources from pitched instruments and voices. Automatic Music Transcription (AMT) is recognized as a transformative technology with significant potential for both economic and societal benefits, including:
  * **Music Education**: Facilitating automatic instrument tutoring.
  * **Music Creation**: Capturing improvisations and providing automatic accompaniments.
  * **Music Production**: Enhancing content visualization and editing capabilities.
  * **Music Search and Musicology**: Enabling indexing based on specific musical elements like melody or rhythm and detailed analysis of nonnotated music, such as jazz improvisations.
  


---
**Challenges and Open Problems in AMT**:
* Inffering musical attributes (e.g., pitch) from the mixture signal is an extremely underdetermined problem.
* For NN-based approaches:
  * Only a few, small annotated data sets available, and these are often subject to severe biases.
  * Adaptability to new acoustic conditions.
* Creation of context-specific AMT systems for multiple instruments.(such as given prior knowledge music style, instrument, ...)
* The discrepancies in musical assumptions between Western and non-Western traditions, such as variations in octave frequency ranges and the limited availability of non-Western music data.
* Creation of a robust music transcription system that supports both pitched and unpited sound.
* The existing metrics for evaluating music transcription do not always align with human musical perception. For example, the presence of an extra note can be a more critical error than a missing note, and out-of-tone errors may be penalized more severely than in-tone ones.
  * ❗ **Lack of perceptually relevant evaluation metrics** ❗ for AMT and the creation of evaluation metrics for notation-level transcription.

---

**Basic Knowledge**:
  
Musical note is usually characterized by three elements: pitch, onset time, and offset time.
THe beginning of a note(or attack phase) might have entirely different spectral properties than the central part(decay phase). How to model uch relationship?