# <img align="left" width="42" height="42" src="/src/qt/res/icons/pyrite-48.png"> Pyrite 1.0.0
### Pyrite is a fairly launched, 100% decentralized cryptocurrency. Community involvement is encouraged. Pyrite, like most other altcoins, starts as an experiment - a fool's gold.

##### Ticker: PYE
##### Reward Scheme: PoW/PoS Hybrid
##### PoW Mining Algorithm: Sha256q
##### PoW Block Reward: 88 Coins
##### PoS Block Reward: 0 Coins + Fees
##### Block Time: 10 Minutes (*effectively 5 minutes, since PoW and PoS blocks are targeted at 10 minutes*)
##### Block Maturity: 200 Blocks
##### Block Halving: Every 105120 Blocks
##### Max supply: 21 Million*
##### P2P Port: 6996
##### RPC Port: 6997
:heavy_exclamation_mark:*Max supply approximation is based on the assumption that ratio of PoW to PoS blocks remains 50:50. This is an unlikely scenario, because PoS blocks are generated only if transactions are sent to the mempool. 
##### Building instructions for Ubuntu 16.04

##### Install dependencies for QT wallet:

1. `sudo apt-get install git qt5-default qt5-qmake qtbase5-dev-tools qttools5-dev-tools \
    build-essential libboost-dev libboost-system-dev \
    libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev \
    libssl-dev libdb++-dev libminiupnpc-dev libqrencode-dev`
    
2. `git clone https://github.com/pyritepirate/pyrite.git`

3. `cd pyrite`

4. `qmake`

5. `make`

##### Install dependencies for headless client:

1. `sudo apt-get install git build-essential libssl-dev libdb++-dev libboost-all-dev libqrencode-dev libminiupnpc-dev`

2. `cd pyrite/src`

3. `make -f makefile.unix`

###  :mega: https://bitcointalk.org/index.php?topic=5055485
