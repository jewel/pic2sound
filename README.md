pic2sound
=========

This is an experimental project to create sound effects from image files.  The
images are meant to be a spectrogram, which is converted to a waveform.

Status
------

The project currently functions but there is a lot of unexpected noise.
I think this is because each frequency's sine wave will be out of phase from
the others, even when moving up or down a single pixel.
