==================================================
Micropython IoT Hackathon (featuring the ESP8266)
==================================================
This repository contains the content needed to run a Micropython-based IoT
Hackathon using ESP8266 development boards. Atendees will work through a
pre-defined project involving a light sensor and then explore more complex
applications. Both hardware and software will be covered.

This content was originally developed for a project night hosted by the
San Francisco Python meetup group. The content was designed to make this
hackathon easily reproducable

Abstract
========
Due in large part to the availability of cheap, low-power, internet-connected
microcontrollers, the Internet of Things is taking off. Python developers can
get in on the excitement with Micropython, an implementation of Python 3 that
runs on very small devices with no operating system. Micropython provides
the standard Python REPL (read-eval-print-loop) interface, so you can
interactively develop and debug applications on these small devices.

In this session, you will learn some basic electronics, wire up some sensors to
a low-power wireless controller board (based on the ESP8266 microcontroller),
load the Micropython firmware, and interactively write simple applications to
read from the sensors. We will also discuss how to connect to other systems via
the MQTT messaging protocol and exchange ideas on larger projects that can be
built at home for low cost with beginner-level knowledge.

The only prerequisite is to bring a laptop with a USB port. Here is a picture
of the completed project: https://data-ken.org/images/lighting-app-esp8266.png

Files in this Repository
========================
The instruction book is built using the Sphinx documentation tool [#]_.
Here's an overview of the key files and directories:

* ``book/Makefile`` - used by Spinx to build HTML and other representations
  of the instruction book.
* ``book/_build`` - Sphinx creates and puts its output in this subdirectory. A
  ``make clean`` in ``book/`` will delete this directory and its contents.
* ``book/conf.py`` - configuration file for Sphinx
* ``lecture.pptx`` - overview presentation to give at the start of the class.
* ``lecture.pdf`` - pdf version of the overview presentation


Copyright
=========
Copyright 2016 by Jeffrey Fischer. All rights reserved.