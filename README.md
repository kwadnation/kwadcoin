
KwadCoin development tree

What is KwadCoin?

KwadCoin is a POW/PoS-based cryptocurrency.

Algorithm 	Scrypt
Type 	PoW/PoS
Block reward 	186 coins
Total coin supply 	156240000 coins
Premine percent 	50%
Premine amount 	78120000 coins
PoS percentage 	8% per year
Last PoW block 	block 230000
Coinbase maturity 	11 blocks
Target spacing 	64 seconds
Target timespan 	1 block
Transaction confirmations 	6 blocks
RPC port 	19956
P2P port 	19955

Seednodes:
        node1.kwadnation.com
        node2.kwadnation.com

		For more information, as well as an immediately usable, binary version of
the KwadCoin client sofware, see http://www.kwadnation.com

You need to install the following dependencies to start your wallet in Linux.

apt-get install build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev git libssl1.0.0-dbg
apt-get install libdb-dev libdb++-dev libboost-all-dev libminiupnpc-dev libminiupnpc-dev libevent-dev libcrypto++-dev libgmp3-dev libqtgui4 


Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of KwadCoin.

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
