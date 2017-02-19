# Arduino-Guitar-Tuner
An Arduino based Guitar Tuner using Autocorrelation for accurate frequency indentification

A while ago I wrote an article on Reliable Frequency Detection Using DSP Techniques.

I mentioned at the time that this is an ideal basis for designing your own Arduino based guitar tuner. In real life, musical intruments can have strong harmonic contents, and you want to detect the fundamental frequency. Time based techniques that measure the time between periods don’t do that very well. The advantage of using an autocorrelation based frequency detection method is robustenss against noise and the overall harmonic content  of the signal.

So, having got a few questions about how you’d make a guitar tuner. I’ve published a tutorial on that here:

http://www.akellyirl.com/arduino-guitar-tuner/
