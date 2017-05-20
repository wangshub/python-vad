python vad
==========

Python code to voice activity detection.This python program can read stream data from your microphone (like USB microphone)

Requirements
------------

-	a buildin microphone or usb microphone on your device, you can use `arecord -L` to show your audio input devices.
-	webrtcvad - `pip install webrtcvad`
-	pyaudio - `pip install pyaudio`

How to Run
----------

Make sure your default audio input device is avaliable, and run  
`python vad.py`

Some details
------------

This program reads stream audio data from your default audio input device, and decide if a chunk of audio is blank space. It can estimate when you start your sentence and the time you finished.Once you end your conversation, the program write the voice into `*.wav`file.
