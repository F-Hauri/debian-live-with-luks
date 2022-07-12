# Debian Live with encrypted *persistence* partition

== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project.  For further version of this projects, have a look
[My web bazzar ](https://f-hauri.ch/vrac/?C=M;O=D) where most of my ideas are
still published until I made a choice for further shares...

We urge you to read about the [Give up GitHub](https://GiveUpGitHub.org)
campaign from [the Software Freedom Conservancy](https://sfconservancy.org) to
understand some of the reasons why GitHub is not a good place to host FOSS
projects.

If you are a contributor who personally has already quit using GitHub, please
[send mail to gitproj@f-hauri.ch](mailto:gitproj@f-hauri.ch) for any comment
or contributions without using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)

Copying:
--------

As bash, this stuff is licensed under GNU GPL v3.0 or later.

Introduction:
-------------

This is a bash script intended to be run under Debian GNU/Linux

Requirement: live-helper parted git cryptsetup
Recommand: pv

This require root privilege or access to /sbin/parted and permission
to write over block device.

Once done (more than one hour on my desk), you become a Debian-Live-USB
stick able to run with or without *persistance*, but persistance passphrase
have to be given at boot.
