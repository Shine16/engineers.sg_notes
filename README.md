# Engineers.sg recording notes

This guide is written for using equipment Set 3 to do event presentation recordings as of August 2019.

## Setup
It will take about half an hour to setup the equipment. Look for the optimal place for equipment, considering the following:

1. Look for accessable power points.
2. Look for a small table or chair to setup the equipment.
3. Look for the HDMI cable to the projector.
4. Look for where the presenter slide/code laptop will be.
5. Optional backup: Look for clear line of sight for backup handycam camera.

There are three main things that need to be connected before turning the recording laptop on.

1. Webcam
2. Sound capture
3. Slide capture

The setup will mostly be similar to [this setup](https://github.com/engineersftw/gitwiki/tree/master/07_setup_2016), with condenser mike replaced with a audio reciever to mixer and audio transmitter on the presenter.

### Webcam
Webcam will plug directly to the laptop.
Webcam is placed on a tripod and can be pivoted left and right to track the presenter.

### Sound capture
Turn on the audio capture and connect the clip on mike.

#### Placing audio transmitter on presenter
Have the audio capture transmitter in the presenters pocket, and clip on mike to collar or shirt.
Side note: The mike is sensitive enough to record audience in Q&A too!

#### Audio reciever
Connect AC adapter to audio reciever. Ensure audio reciever and audio mixer is attached with a cable. 
Connect audio mixer to laptop by a USB cable, which powers and draws capture data from it.

On the audio mixer, we will see the green bar on the knob rise when sound is being captured. If it goes to red, there is distortion and knob needs to be turned down. Use this just a general indicator of whether the mixer is working. The audio levels in OBS software will be more important as it will be recorded. 
There are two sides for stereo audio capture, however in usual recordings, only one side is used.
On the right is a monitoring volume and headphone output port which is usually not used.

### Slide Capture
1. Connect AC adapter to HDMI splitter.
2. Connect a long HDMI cable from input to presenter HDMI out. If presenter laptop does not have hdmi, various hdmi adapters are available in the front pouch. HDMI adapters include USB C, Display port, Thunderbolt, VGA. Mini HDMI is not supported as of August 2019 however could be in the future.
3. Connect projector to HDMI splitter output. If it is an old projector that uses VGA, a HDMI to VGA adapter is available.
4. Connect Avermedia pro HDMI to HDMI splitter output, and AC adapter to Avermedia pro.

### Backup Handycam
Backup handycam will be mounted on a smaller tripod, and face the projector screen where there is clear line of sight. If main setup fails, backup footage can be used to sync footage with slides from presenter using Adobe premier pro.



## Using OBS software on laptop

### OBS Modes

There are several capture modes in OBS. 
If in doubt, just use modes PIP1 for the bulk of presentation and PIP3 for the Q&A.

PIP1 - usual 16:9 powerpoint slides
PIP2 - if slides have larger fonts, we can increase the size video capture for presenter
PIP3 - usually for Q&A

PIP 4x3 - Tf presenter uses 4:3 sized slides, there would be two black blocks in capture. This mode is to resize the presentation capture to remove the two black blocks!
PIP 4x3 large , for 4:3 slides, Q&A time
Screen w video - for code demos and more focus on screen, presenter capture will be smaller
Screen only - for full screen code demo
Video only - for Q&A

Follow me slide - to end the video
Black - another way to end the video

Side by side - special case if presenter is perfectly still

### Using OBS
These buttons can be found on the lower right of the screen
Start Recording - to start recording
Stop Recording - to stop recording
Studio mode - to preview capture modes before transitioning them to record. Do not use when starting out!



## Recording Procedure
It would be best to have two people do recordings, each handling one task. However both tasks can be done by one person if required!

Task 1: Video focus to track presenter
We will want the presenter to be mostly at the center of the presenter video capture. If presenter walks from position, pivot the camera left or right to track the presenter. This can be handled by one person.

Task 2: Recording the presenter
Adjust OBS recording formats to suit presentation, adjusting sound volume, start and stop capture, catch frozen screens, troubleshoot if any issues. This can be handled by one person.

### Adjusting Sound Volume
Try to have the sound levels fall within green and yellow range in the OBS volume indicator. If it falls within the Red range, there are distortions, and knob on the mixer should be turned towards the left and reduced.
It is more important to check the volume levels in OBS software, over the mixer LED volume indicator, as this is what will go into the capture.

Advice: try to start with selecting a lower volume capture. This is to avoid sudden unwanted distortions or overmodulation in recording.
During sound test, presenters are usually softer. When presenting, usually project their voice. So better to set a lower volume in mixer and play by ear.
Adjust mixer to increase if presenter is soft.



## Troubleshooting
### OBS Avermedia Screen freeze
This can happen between speakers or during the presentation, where screen or slide freezes. Click lock on Avermedia, Deactivate, and Activate. This would reset the frozen input.

## Uploading the Videos
Files are uploaded to Engineer.sg server, which does some processing and uploads the videos to Youtube hourly by a Cronjob.

If venue has good wifi, videos can be uploaded while packing up equipment. Alternatively saved to thumbdrive and uploaded later.

### Uploading to Server
Video files can be uploaded to Engineer.sg server with the following steps:
1. Save the video files from OBS
2. go to [upload.engineers](http://upload.engineers.sg/admins/sign_in)
3. Sign in with username and password from Michael
4. Find event which is synced by Meetups, or click the (+) to create it in.


If files are too large, we can upload the file to dropbox instead using this [link](https://www.dropbox.com/request/wDrwdUK4ioaBCzd2m1vR)
Some audio processing is done with scripts [here](
https://github.com/engineersftw/gitwiki/blob/master/scripts/README.md)

### Uploading Written Format
We can use the meetup details and edit from there.

Usual format as follows:
Title of talk: -Presentation title-
Speaker: -Speaker name-
Blurb about speaker, can be taken from event page
Produced by: Engineers.sg
Event page: -Event page link-
Recorded by: -Volunteer name-


## Packing up
Laptop goes into the suitcase first.
Sensitive equipment - Audio recorder, webcam, handycam and AC adapter goes into the black sponge cushioned file.
The rest other then long HDMI cables and HDMI adapters goes into the green file.
HDMI adapters go into a file in the outer pouch.
Remember to pack up the handycam before leaving!













