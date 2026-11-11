
## **Speech Perception During Sentence and Story Listening — Experiment 1-3**


**Browser-Based Behavioral Experiment | JavaScript, HTML, jsPsych**
 

**Research Overview:**

This repository contains the implementations of three browser-based auditory perception experiments developed as part of a research project investigating age-related differences in speech perception under challenging listening conditions. The experiments contributed to the following peer-reviewed journal article:

**Age-related deficits in dip-listening evident for isolated sentences but not for spoken stories — Irsik et al.**

The research investigated how speech perception differs across listening contexts, including isolated sentences and continuous spoken narratives, and examined age-related differences in the ability to understand speech presented with background noise.


**General Experimental Design:**

Participants listened to a spoken sentence or story presented under different auditory conditions, including background amplitude-modulated multi-talker babble noise.

The experiment incorporated:

*  Random assignment to predefined experimental conditions
*  Audio stimulus presentation and condition-specific stimulus selection
*  Visual cues presented during narrative listening
*  Intermittent speech-recall tasks requiring participants to report recently heard words
*  Story comprehension questions
*  Hearing-related and demographic questionnaires
*  Volume adjustment, headphone verification, and practice procedures

**Technical Implementation and Dependencies:**

The experiments were implemented using JavaScript, HTML, CSS, and jsPsych 6.1.0, with Pavlovia used for online experiment hosting.

*  JavaScript and HTML — Custom experimental logic, stimulus presentation, and behavioral response collection
*  jsPsych 6.1.0 — JavaScript framework for behavioral experiments
*  CSS — Experimental interface styling
*  Pavlovia — Online experiment hosting

The experiments were originally developed using jsPsych 6.1.0. The jsPsych library files are not included in this repository. More information about the framework is available via https://www.jspsych.org/latest/.

**Repository Contents:**

Each experiment is organized into a separate folder containing its experimental implementation and supporting files. The primary experimental logic is contained in the respective index.html files, including custom JavaScript responsible for experimental condition assignment, stimulus selection, presentation sequences, and behavioral response collection.

**Data and Stimulus Availability:**
Participant data and original audio stimuli are not included in this repository due to research confidentiality and ownership considerations. The experimental code is provided to demonstrate the study design and technical implementation. Access to the original audio stimuli may be requested.

Note: The experiments cannot be run in their entirety without the restricted audio stimuli and required software dependencies.

**Associated Publication:**

Irsik et al., Age-related deficits in dip-listening evident for isolated sentences but not for spoken stories. The experiments documented here contributed to this publication.
