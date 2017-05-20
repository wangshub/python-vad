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

Make sure your default audio input device is avaliable, and run`python vad.py`
