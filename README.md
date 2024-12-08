This repository contains scripts for building Ngspice releases
(https://ngspice.sourceforge.io/) for various hardware/OS combinations
and the packages they build.  The built packages can be found under the
"Actions" tab above.  (Look for "artifacts".)
A Github login is required for downloading.

Builds of current development code (pre-master-xx branch) are
available from the adjacent "ngspice" repository.

The binaries are packaged as ZIP files so the execute permission
is not preserved.  Use this command to restore it:

	chmod a+x bin/ngspice

and for a Macintosh also:

	xattr -d com.apple.quarantine bin/ngspice
	xattr -d com.apple.quarantine lib/ngspice/*

The packaged files are intended for installation in /usr/local or
C:\Spice64.  If expanded elsewhere, environment variables must be set
to indicate the location.
