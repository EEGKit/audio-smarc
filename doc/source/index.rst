.. Smarc documentation master file, created by
   sphinx-quickstart on Wed Nov  4 16:07:49 2009.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Smarc audio rate converter
==========================

.. toctree::
   :maxdepth: 2

*Smarc* is a **fast** and **high quality** audio rate converter. It allows conversion between any audio samplerate.
*Smarc* is a command-line program and a C library to be integrated in other applications.

Features
--------

* signal rate conversion between any sample rates.
* optimized for conversion between standard audio sample rates: 8, 16, 44.1, 48, 96, 192 kHz
* command-line tool to convert audio files
* C library to integrate *smarc* converter into other applications.
* Can convert audio, but also any signal like EEG, seismic signals, etc.
* Convert sample rate using polyphase decimation and interpolation filters. This method guarantees high-quality for upsampling and downsampling.
* Internal filters can be tuned to emphasize speed or quality.

Download
--------

.. highlights::
	Download current release: `smarc-0.22.tgz <https://sourceforge.net/projects/audio-smarc/files/smarc-0.22.tgz/download>`_

*Smarc* source code is release under the terms of the **GNU LGPLv3 License**. *Smarc* source code is known to compile on Linux, MacOsX, Windows/mingw platforms.


Credits
-------

.. image:: _static/logo_tecomptech_85949.gif 
	:align: left
	:alt: Telecom Paristech
	:target: http://www.tsi.telecom-paristech.fr/aao/en/

*Smarc* is developed at Télécom ParisTech, France.

.. raw:: html

	<br style="clear: left"/>

