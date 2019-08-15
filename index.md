---
layout: splash
header:
  image: /assets/images/ESA_LimeSDR_Mini_1.jpg
feature_row:
  - image_path: assets/images/LimeMicro.png
    alt: "Lime Microsystems"
    url: https://limemicro.com
    btn_label: " "
  - image_path: assets/images/ESA.png
    alt: "The European Space Agency"
    url: https://www.esa.int
    btn_label: " "
  - image_path: assets/images/MyriadRF.png
    alt: "MyriadRF - Democratising Wireless Innovation"
    url: https://myriadrf.org
    btn_label: " "
---

# Introduction

SDR Satcom is a project led by the [European Space Agency][1] (ESA) in
partnership with [Lime Microsystems][2], that aims to accelerate satellite
communication development and lower the barriers to innovation. It is hosted as
a project under the [MyriadRF][3] open source initiative and uses the low cost
LimeSDR software-defined radio, together with an app store for distributing
applications.

# App Store

The [SDR Satcom app store][4] is used to distribute Linux applications that are
packaged using the [snap][5] package format. Support for this is pre-installed
on Ubuntu and most derivative distributions, with installation instructions
available for many other distributions. Benefits include that dependencies are
packaged together with the application code and this runs in a confined
environment, with clearly defined system and application interfaces, plus
fine control over updates and release management.

In short, snaps take the hassle out of distributing complex application
stacks. In addition it is the native package format for [Ubuntu Core][6],
the secure, lightweight and robust operating systems for the Internet of Things.
Which means snaps can equally be run on classic Ubuntu desktops during
development and prototyping, or on Ubuntu Core as part of a managed deployment.

## Example snaps

![SDRangel](/assets/images/LimeSDR-Mini_SDRangel_Demo_768w.jpg){: .align-center}

The app store presently includes a number of snaps from early contributors:

* **Gpredict**, a real-time satellite tracking and orbit prediction program for
the Linux desktop. It uses the SGP4/SDP4 propagation algorithms together with
NORAD two-line element sets (TLE).
* **SatHelperApp**, an LRIT/HRIT Demodulator / Decoder program based on
libSatHelper and xritdemod.
* **SDRangel**, an Qt5 / OpenGL 3.0+ SDR and signal analyzer frontend. It has
support for various modes, including DVB, and transmit operation.
* **WeatherDump**, a multi-platform software for record, demodulate, decode and
processing of data from weather satellites.

For further details, please see the [wiki][7].

## Installing snaps

It takes just a few simple steps to configure your Linux distribution to use the SDR
Satcom app store and for details see the [wiki][8].

## Submitting a snap

Proposals for including a snap in the SDR Satcom store are invited!

While the main focus is software-defined radio applications for use with LimeSDR
hardware, we also welcome proposals to include other open source software that
may be used in support of satellite communications, such as offline decoders and
tracking applications etc.

Snap packaging is pretty straightforward and since it includes all your
application dependencies, it means that you don't have to worry about packaging
for different Linux distributions and distribution releases. 

To propose a snap for inclusion in the SDR Satcom app store or to simply find
out more, either post to the [MyriadRF forum][9] or send an e-mail to
[sdrsatcom@myriadrf.org](mailto:sdrsatcom@myriadrf.org).

# Developer Hardware

The European Space Agency were backers of the [LimeSDR Mini crowdfunding campaign][10]
and in addition to using the hardware in their labs, they're making it available
to qualifying individual developers, open source projects and academic
institutions. An initial batch of kits has been distributed to projects
including [SatNOGS][11], [Phase IV Ground][12], [Open Satellite Project][13],
and [Portsdown][14].

An additional 50x LimeSDR Mini kits are now being made available and to make a
request, please complete the form.

[Request Hardware](/hwrequest){: .btn .btn--primary .btn--large}

# Contact

General enquiries should be sent to [Andrew Back](mailto:a.back@limemicro.com).

# Supported by

{% include feature_row %}

[1]:https://www.esa.int
[2]:https://limemicro.com
[3]:https://myriadrf.org/
[4]:https://sdrsatcom.snapcraft.io/
[5]:https://snapcraft.io/
[6]:https://ubuntu.com/core
[7]:https://wiki.myriadrf.org/SDR_Satcom_Applications
[8]:https://wiki.myriadrf.org/SDR_Satcom_App_Store
[9]:https://discourse.myriadrf.org/c/projects/sdr-satcom
[10]:https://www.crowdsupply.com/lime-micro/limesdr-mini/
[11]:https://satnogs.org/
[12]:https://phase4space.github.io/
[13]:https://github.com/opensatelliteproject
[14]:https://wiki.batc.org.uk/Portsdown_2019
