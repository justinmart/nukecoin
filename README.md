NukeCoin (NKC) - a 'faster' version of Litecoin which also uses scrypt
as a proof of work scheme and is intended for educational purposes.
 - 60 second block targets
 - 28 000 000 total coins
 - difficulty retargets every 24 hours
 - currently peers are looked up over IRC only
 - currently no block checkpoints are in the code (but could be easily
   added)

Other than that, this coin is exactly like Litecoin and should by no
means be used as a real cryptocurrency. All of the coin parameters
are chosen arbitrarily and with educational purposes in mind.

So actually, this 'new' coin exists for the following reasons:
 - NKC proves that really anyone can start a Litecoin/Bitcoin based currency
    (just look at the changes I applied to the original Litecoin source,
     for genesis block generation look at main.cpp)
 - Allows me to experiment with coin parameters (in a private network)

Credits go to the original authors/communities that created Bitcoin and 
Litecoin.

Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
