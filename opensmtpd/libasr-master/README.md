Description
===========

libasr is a free, simple and portable asynchronous resolver library.

It allows to run dns queries and perform hostname resolutions in a fully
asynchronous fashion.  The implementation is thread-less, fork-less, and
does not make use of signals or other "tricks" that might get in the
developer's way.  The API was initially developed for the OpenBSD
operating system, where it is natively supported.

This library is intended to bring this interface to other systems. It is
originally provided as a support library for the portable version of the
OpenSMTPD daemon, but it can be used in any other contexts.  It is known
to work on the following systems:

* Linux
* FreeBSD
* NetBSD
* DragonFly
* MacOSX

The primary source of information about libasr is the [github repository][1].

[1]: http://github.com/OpenSMTPD/libasr



