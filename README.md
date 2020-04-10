# ELNS

Copright (C) 2015-2020 Svein Seldal <sveinse@seldal.com>

**Homepage:** https://github.com/sveinse/elns-release

ELNS is a tool for processing multi-channel audio, supporting interactive
adjustments of audio parameters. It processes live audio to and from a file
or sound card in real-time.

The tool comes with a set of audio processing functions, each written to test
or demonstrate specific features. The DSP engine support all samplerates,
including high-res rates, and supports processing up to 32-bit resolution.

The tool provides a tkinter based used interface to set up the audio and
file input/output and to adjust audio parameters interactively during processing.

This repository contains the binary releases.

![ELNS Screenshot](/notes/elns_screenshot.png)

The tool is currently angled towards running on a Windows platform, but it
is possible to run on other platforms.


## Features

- Selectable processing audio functions, each built for a specific purpose or
  demonstration.
- Reads and writes a wide range of file formats, including lossless format such
  as <em>flac</em>
- Full-duplex sound card input and output
- Interactive real-time adjustment of parameters
- Supports multi-channel audio, up to 8 channels
- Supports high sample rates
- Process audio in high bit resolutions, up to 32-bits per sample


## Technology

- ELNS is written in Python 3
- [SciPy and NumPy](http://scipy.org) for numerical processing
- [Portaudio](http://portaudio.com) and
  [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/) for audio interface
- [libsndfile](http://www.mega-nerd.com/libsndfile/) and
  [pysndfile](https://forge-2.ircam.fr/roebel/pysndfile) for audio file IO


## Download

Binary releases for Windows is available for download from:

> https://github.com/sveinse/elns-release/releases
