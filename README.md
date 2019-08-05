# Debian Live with encrypted *persistence* partition

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
