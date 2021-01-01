# reward-capture
The html file will run through 10 training VDAC trials, 5 normal trials, then 10 training RSVP trials, 5 normal trials, and then download a csv file with the data. 
the following settings can be edited to change the experiment for ease of troubleshootingand will be marked in the code
VDACtask: trial_duration => changes how long stimuli are presented to make it easier or harder
var trialSize => changes number of test trials for VDAC task, RSVP trials are seperate
speedRSVP => changes how long each stimuli in the RSVP task are presented
jsPsych.init timeline: => can include or remove elements to test individual parts of the experiment e.i. if you wanted to skip straight to the RSVP task only
jsPsych.init on_finish: can be changed to stop downloading data file
