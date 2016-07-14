# Linux #

## Order of the Startup Files ##

When you first login to Linux, /etc/profile is read and evaluated, after which
the following files are searched (if they exist) in the listed order:

* _~/.bashprofile_ _~/.bashlogin_ _~/.profile_ The Linux login shell evaluates
whatever startup file that it comes across fist and ignores the rest. This means
that if it finds _~/.bashprofile_, it ignores _~/.bashlogin_ and _~./profile_.
Different distributions may use different startup files.
