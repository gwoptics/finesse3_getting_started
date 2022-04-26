# Finesse 3: Getting started

## About
[Finesse 3](https://Finesse.docs.ligo.org/Finesse3) (Frequency domain INterfErometer Simulation SoftwarE) is a fast and easy to use Python-based interferometer simulation program. It uses frequency-domain optical modelling to build accurate quasi-static simulations of arbitrary interferometer configurations.

Note that Finesse 3 is in an alpha stage of development. You can find the documentation, executables and code for the stable [Finesse 2](http://www.gwoptics.org/finesse/) at http://www.gwoptics.org/finesse.

Double-click on these Jupyter notebooks in the sidebar to run the examples:
* 1_Finesse3_introduction.ipynb
* 2_Finesse3_GWdetector_sensitivity.ipynb

This [Binder](https://mybinder.org/) provides a [Jupyter](https://jupyter.org/) environment with Finesse 3 pre-installed, so that new users can 'try before they buy'.  The initial loading time may be slow depending usage and server load, but then you can play around with the live code in the example notebook, create your own notebook, or upload another notebook you wish to test-run. Note that work *cannot* be saved long-term in this environment, and the Binder will shut down after 10mins of inactivity (e.g. closing the browser tab), so it is not suitable as a substitute for installation. But you can download your work to save them locally.

## Get Finesse
If you decide to continue using Finesse, there are currently two options: 
* if you are mostly interested in obtaining results for your own interferometry     work, we recommend to use Finesse 2 via the `conda` package manager from Anaconda.  Please follow the instructions provided in the [Finesse 2 installation guide](http://www.gwoptics.org/finesse/download/Install.html).
* if you are interested in hacking the code, or implement new features you are welcome to play with the source code of version of Finesse 3. See for example the   [Finesse 3 installation instructions](https://finesse.docs.ligo.org/finesse3/getting_started/install/) or the [Finesse 3 developer guide](https://finesse.docs.ligo.org/finesse3/developer/) for an installation guide.

In either case, feel free to get in touch!

## Useful Resources
The [gwoptics.org](http://www.gwoptics.org) website is the primary resource for Finesse users.

Finesse 3 resources:
* [Finesse 3 documentation](https://finesse.docs.ligo.org/finesse3/)
* [Finesse 3 source code](https://git.ligo.org/finesse/finesse3)


Finesse 2 resources:
* [Finesse 2 syntax reference](http://www.gwoptics.org/finesse/reference/)
* [Finesse 2 cheatsheet / FAQ](http://www.gwoptics.org/finesse/reference/cheatsheet.php)
* [Finesse 2 manual (pdf)](http://www.gwoptics.org/finesse/download/manual.pdf)

Those wishing to learn more about how to use Finesse and modelling interferometers should follow the training materials provided through the [Learn Laser Interferometry](http://www.gwoptics.org/learn/) course.

The review article [Interferometer Techniques for Gravitational-Wave Detection](https://link.springer.com/article/10.1007/s41114-016-0002-8) is written by some of the team behind Finesse and includes Finesse examples for many of the key topics covered. It is therefore a good resource for those wanting to understand more about interferometry as applied to gravitational-wave detection, and as implemented in Finesse.

## Contact

GW community members ([LIGO](https://www.ligo.org/), [Virgo](http://www.virgo-gw.eu/), [KAGRA](https://gwcenter.icrr.u-tokyo.ac.jp/en/)) can access the Finesse chat channel on [chat.ligo.org](https://chat.ligo.org/ligo/channels/finesse) using their albert.einstein login. 

The [Ifosim logbooks](https://logbooks.ifosim.org/) provide a forum for users to share more examples and references of interferometry simulations, mostly generated in the course of gravitational-wave research. Posts are public; write-access is available for all GW community members via albert.einstein, and to others on request. <!-- link 'on request' somewhere? -->

General support is available by emailing us at finesse-support(at)nikhef.nl. If you have trouble with installation or think you have encountered a bug, please include the following information in your message:

 * Operating System and installation method used
 * versions of Finesse (and/or PYKAT) you are using 
 * [Minimum Working Example](https://en.wikipedia.org/wiki/Minimal_working_example) to reproduce the bug you encountered







