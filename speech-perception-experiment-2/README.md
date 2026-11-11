## **Speech Perception During Narrative Listening — Experiment 2**


**Browser-Based Behavioral Experiment | JavaScript, HTML, jsPsych**
 

**Research Overview:**

 This repository contains the implementation of a browser-based auditory perception experiment developed as part of a larger research project investigating age-related differences in speech perception during narrative listening. The experiment was one of three conducted for the published journal article:

 Age-related deficits in dip-listening evident for isolated sentences but not for spoken stories — Irsik et al.
The broader research investigated how speech perception differs across listening contexts, including isolated sentences and continuous spoken narratives.


**Experimental Design:**

Participants listened to a spoken narrative presented under different auditory conditions, including background amplitude-modulated multi-talker babble noise.

The experiment incorporated:

*  Random assignment to predefined experimental conditions
*  Audio stimulus presentation and condition-specific stimulus selection
*  Visual cues presented during narrative listening
*  Intermittent speech-recall tasks requiring participants to report recently heard words
*  Story comprehension questions
*  Hearing-related and demographic questionnaires
*  Volume adjustment, headphone verification, and practice procedures

**Technical Implementation and Dependencies:**

The experiment was implemented using JavaScript, HTML, CSS, and jsPsych 6.1.0, with Pavlovia used for online experiment hosting.

*  JavaScript and HTML — Custom experimental logic, stimulus presentation, and behavioral response collection
*  jsPsych 6.1.0 — JavaScript framework for behavioral experiments
*  CSS — Experimental interface styling
*  Pavlovia — Online experiment hosting

The experiment was originally developed using jsPsych 6.1.0. The jsPsych library files are not included in this repository. For more information about the framework, see the jsPsych GitHub repository (https://www.jspsych.org/latest/).

 Note: The experiment requires the original jsPsych version and restricted audio stimuli to run as originally implemented.

**Repository Contents:**

 The primary experimental implementation is contained in index.html, including the custom JavaScript responsible for experimental logic, stimulus selection, and response handling.

**Data and Stimulus Availability:**

Participant data and original audio stimuli are not included in this repository due to research confidentiality and ownership considerations. The experimental code is provided to demonstrate the study design and technical implementation. Access to the original audio stimuli may be requested.

 **Note**: The experiment cannot be run in its entirety without the restricted audio stimuli.

 Associated Publication
 Irsik et al., Age-related deficits in dip-listening evident for isolated sentences but not for spoken stories. This repository represents one of three experiments contributing to the publication (Experiment 2).

