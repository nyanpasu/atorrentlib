#atorrentlib
##About
atorrentlib is an (aptly named) library that implements the bittorrent
protocol. This work was necessitated and motivated by the need of the gTorrent
project for a bittorrent library that was simple and lightweight.

This document was written first in the hopes that code would eventually be
written.

##Design
atorrentlib was started by a very shit programmer who was then quite crap at
his trade. Hence, the objective of this library is to be simple and the library
is not expected to be a very serious reputation, at all. It will attempt to
implement the bittorent protocol in the most direct and unobstrusive way
possible. There will be little concern for "standards" or "convention". There
is no "style" the developer has chosen to adopt, although consistency will be
maintained. In other words, the developer will just shit out code until
something works.

The author will attempt to avoid anything deemed remotely "harmful", although
such definitions have been made purely on the author's sadly uninformed
opinion. Thus, this means that there will be little use of external libraries
and the author will attempt to use his own incredbibly hopeless implementation
that will no doubt cause great harm to the machine running the software.

The progress of the libraries creation will be documented intensively. There
will be an issue written with a problem, and a brief explanation if at all
necessary, followed by a resolving commit. Work is planned out before it is
implemented.  TODOs and bug fixes are scheduled in advance. There are no
"tests" because the dev is a chucklefuck who can't into test-driven
development. Hence the only way bugs are discovered is through disaster and
catastrophe. The author disclaims all warranties with regard to this software
including all implied warranties of merchantability and fitness.  However, the
library will be written to the best of the author's abilities.

The following places have been used as sources of information and reference for
the author: 
 - The bittorent specification: http://www.bittorrent.org/beps/bep_0003.html 
 - Details on operation: http://en.wikipedia.org/wiki/BitTorrent

The author does not plan on following any sort of healthy development cycle.
Code production is an awkward dance where functions fall into a file and hopes
to fit in with the rest of the crew. Followed by minor edits and various forms
of expressive head-scratching until the pieces fall into place.

##Objectives
This section is subject to continuous change as the main focus of each
particular time period of the project's timeline is decided and scheduled
in advance. There is no strict significance to the attached to the version
numbers. It used internally as an arbitrary means of signifying progress.

### 0.0.0
Create the data structures that hold the data required to contain:
 - BitTorrent metainfo data
 - BitTorrent tracker data
 - Peer data
