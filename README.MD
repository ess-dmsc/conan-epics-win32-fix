The file win32.bat is used to configure EPICS for building EPICS on Windows.
In EPICS it is found in base-3.1X.X.X\startup

This version is intended to be a drop-in replacement to allow EPICS to be built
on the DMSC's Jenkins system.


Requires the following to be installed:
* GNU Make for Windows (http://gnuwin32.sourceforge.net/packages/make.htm)
* Strawberry Perl (64-bit) (http://strawberryperl.com/)
* VS2014 or VS2015

It expects Make to be installed at C:\gnuwin32 and Strawberry Perl to be
installed at C:\Strawberry.
If it is installed elsewhere then modify win32.bat to match.
