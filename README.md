### About
UnicornCoin is innovative way to create Cryptonote (https://cryptonote.org) based cryptotokens. It gives the users the ability to create cryptotokens just by creating a simple configuration file.

### Dependencies
* GCC 4.7.3 or later     (http://gcc.gnu.org/)
* CMake 2.8.6 or later   (http://www.cmake.org/)
* Boost 1.55 or later    (http://www.boost.org/)
* MSVC 2013 (Windows only)


### Usage
1. Download or compile the binaries
3. Start the daemon:
```
./forknoted --config-file PATH_TO_YOUR_CONFIG
```

### Configuration parameters
All fields supported:
```
GENESIS_COINBASE_TX_HEX=     // REQUIRED. Use " ./forknoted --config-file PATH_TO_CONFIG --print-genesis-tx " to generate 
CRYPTONOTE_NAME=unicorncoin
p2p-bind-port=12239
rpc-bind-port=12240
seed-node=127.0.0.1:33669    // format:  IP:PORT
seed-node=127.0.0.2:33669    
UPGRADE_HEIGHT_V2=1             // REQUIRED. Use 1 for new cryptotokens
UPGRADE_HEIGHT_V3=2             // REQUIRED. Use 2 for new cryptotokens
MONEY_SUPPLY=2100000000000000000
EMISSION_SPEED_FACTOR=18
GENESIS_BLOCK_REWARD=0           // premined coins. Default: 0
DIFFICULTY_TARGET=120
CRYPTONOTE_DISPLAY_DECIMAL_POINT=11
DEFAULT_DUST_THRESHOLD=1000000
MINIMUM_FEE=1000000
CRYPTONOTE_MINED_MONEY_UNLOCK_WINDOW=10
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=100000
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=120
BYTECOIN_NETWORK=be1a10de-9ad4-6796-3bae-6ecd7941f67b

```# unicorncoin
