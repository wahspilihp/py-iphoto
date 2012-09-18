py-iphoto
=========

Python tools for working with iPhoto'09 libraries

iPhoto'09 uses some rather unfriendly features which make using an ordinary ORM module a pain in the neck: in particular, it seems to have rather a lot of magic in strange places. A conventional ORM also isn't likely to be much help handling the miscelaneous blobs in the datbases.

The intention is to produce an API which can be used for future versions of iPhoto (and Aperture, now that the databases have been synchronised), but the immediate goal is to work with iPhoto'09 because I'm still using that.