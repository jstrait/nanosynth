# NanoSynth

A miniature tone generator written in Ruby.

# Installation

* Download `nanosynth.rb`
* Install the [WaveFile gem](http://wavefilegem.com): `gem install wavefile`

# Example Usage

NanoSynth expects 3 arguments: the waveform, frequency, and amplitude. It will then generate 1 second of sound and write it to a file called `mysound.wav` in the working directory.

For example:

    ruby nanosynth.rb square 440.0 0.5

The waveform can be one of `sine`, `square`, `saw`, `triangle`, or `noise`.
