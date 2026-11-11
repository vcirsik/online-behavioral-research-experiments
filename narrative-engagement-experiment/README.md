
## Narrative Engagement Under Acoustic Masking — Online Behavioral Experiment

**Browser-Based Behavioral Research | JavaScript, HTML, jsPsych**

**Research Overview:**

This repository contains the implementation of an online behavioral experiment conducted as a complementary study to an EEG experiment. Both studies were published in the peer-reviewed journal article, Neural Activity during Story Listening Is Synchronized across Individuals Despite Acoustic Masking (Irsik et al., 2022).

The studies investigated related aspects of narrative engagement under challenging auditory conditions but employed distinct experimental tasks and methodologies. The broader research examined how listeners process and engage with continuous spoken narratives in the presence of background noise. This repository focuses exclusively on the online behavioral experiment and does not include the EEG experimental procedures, neural recordings, or associated analyses.

**Experimental Design:**

Participants listened to a spoken narrative presented with background noise and completed behavioral tasks designed to assess speech perception, comprehension, and engagement.

The experiment incorporated:

- Randomized presentation of speech-recall prompts during narrative listening
- Timed audio presentation and interruptions for behavioral responses
- Typed responses requiring participants to report recently heard words
- Story comprehension and engagement questions
- Hearing-related and demographic questionnaires
- Volume adjustment, headphone verification, and practice procedures

**Technical Implementation and Dependencies:**

The experiment was implemented using **JavaScript, HTML, CSS, and jsPsych 6.1.0**, with Pavlovia used for online experiment hosting.

- **JavaScript and HTML:** Custom experimental logic, stimulus sequencing, timed events, and behavioral response collection
- **jsPsych 6.1.0:** JavaScript framework for implementing experimental procedures and managing participant responses
- **CSS:** Experimental interface styling
- **Pavlovia:** Online experiment hosting and data collection

The experiment was originally developed using jsPsych 6.1.0. The jsPsych library files are not included in this repository. More information about the framework is available via https://www.jspsych.org/.

**Repository Contents:**

The primary experimental implementation is contained in `index.html`, including the custom JavaScript responsible for experimental procedures, stimulus presentation, response collection, and participant workflow. Additional files provide supporting interface styling and participant-facing materials.

**Data and Stimulus Availability:**

Participant data and original audio stimuli are not included in this repository due to research confidentiality and ownership considerations. The experimental code is provided to demonstrate the study design and technical implementation. Access to the original audio stimuli may be requested.

**Note:** The experiment cannot be run in its entirety without the original audio stimuli and required software dependencies.

**Associated Publication**
Irsik et al. (2022). *Neural Activity during Story Listening Is Synchronized across Individuals Despite Acoustic Masking.*
