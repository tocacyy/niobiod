### About
Niobio coin is a brazilian cryptocoin based on forknote project.

### Dependencies
* GCC 4.7.3 or later     (http://gcc.gnu.org/)
* CMake 2.8.6 or later   (http://www.cmake.org/)
* Boost 1.55 or later    (http://www.boost.org/)
* MSVC 2013 (Windows only)

Step by step Windows instructions:
https://github.com/forknote/cryptonote-generator/blob/master/docs/windows-requirements-install.md

Ubuntu (tested on Ubuntu 14.04) / Mac dependencies install script:
https://github.com/forknote/cryptonote-generator/blob/master/configure.sh


### Usage
1. Download or compile the binaries
2. Create configuration file.
3. Start the daemon:
```
./forknoted --config-file PATH_TO_YOUR_CONFIG
```

### Configuration file content
```
EMISSION_SPEED_FACTOR=18
DIFFICULTY_TARGET=120
CRYPTONOTE_DISPLAY_DECIMAL_POINT=8
MONEY_SUPPLY=33600000000000000
GENESIS_BLOCK_REWARD=0
DEFAULT_DUST_THRESHOLD=1000
MINIMUM_FEE=1000
CRYPTONOTE_MINED_MONEY_UNLOCK_WINDOW=10
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=100000
MAX_TRANSACTION_SIZE_LIMIT=100000
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=126
DIFFICULTY_CUT_V1=60
DIFFICULTY_CUT_V2=60
DIFFICULTY_CUT=0
DIFFICULTY_LAG_V1=15
DIFFICULTY_LAG_V2=15
DIFFICULTY_LAG=0
DIFFICULTY_WINDOW_V1=720
DIFFICULTY_WINDOW_V2=720
DIFFICULTY_WINDOW=17
ZAWY_DIFFICULTY_V3=1
ZAWY_DIFFICULTY_DIFFICULTY_BLOCK_VERSION=3
p2p-bind-port=8313
rpc-bind-port=8314
BYTECOIN_NETWORK=958b4459-c496-6b98-24ba-906d89efce2a
CRYPTONOTE_NAME=niobio
MAX_BLOCK_SIZE_INITIAL=100000
UPGRADE_HEIGHT_V2=1
UPGRADE_HEIGHT_V3=30
GENESIS_COINBASE_TX_HEX=010a01ff00019dd085bedd03029b2e4c0281c0b02e7c53291a94d1d0cbff8883f8024f5142ee494ffbbd0880712101ad57d730d6e2419095871c3b5882daa96e0d30af050f7c97bfbe2433593224ee
seed-node=35.200.110.7:8313
seed-node=45.55.141.227:8313
seed-node=138.197.222.188:8313
seed-node=45.55.172.1:8313
CHECKPOINT=24758:ef7b7c3803df58e06b21dde88c252569f118cda2fafeae9b56c6061e7c4c18eb
CHECKPOINT=24759:c244f99cbcdae7eadbe19e72d17746cdb36b3fb5a446e2cd464a1bf8e4264f3c
```

---
