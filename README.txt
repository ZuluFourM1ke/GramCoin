
Working update for Gram Coin [GRAM]

Name: GRAMCOIN
Symbol: GRAM
Algorithm: SHA256,POW
Block Reward: 220 Block
Reward Halving Rate: 144000
Block time: 120 sec
Difficulty retarget: Dark Gravity Wave
Total supply: 65,360,000 

RPC port: 7566
Net port: 7567


Trading: https://yobit.net/en/trade/GRAM/BTC

To compile: 

sudo apt-get update

sudo apt-get install -y git make g++ build-essential libminiupnpc-dev

sudo apt-get install -y libdb++-dev libssl-dev libboost1.48-all libboost-chrono1.48-dev

git clone https://github.com/ZuluFourM1ke/GramCoin.git 

cd GramCoin/src/leveldb

chmod +x build_detect_platform 

cd ../..

To compile daemon only:
cd src/
make -f makefile.unix

To compile qt wallet
sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler

qmake gramcoin-qt.pro

Update 18 Jan 2018
make
