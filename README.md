# What is this?

A fork of nibirud that doesn't care about this error and seems to validate future blocks just fine

```
10:56AM INF ABCI Replay Blocks appHeight=608 module=consensus stateHeight=608 storeHeight=609
10:56AM INF Replay last block using real app module=consensus
Error: error during handshake: error on replay: wrong Block.Header.LastResultsHash.  Expected 558806BD2AC3DB9D59515F277C846805499A95A7948A19478B2B26A0ADE1A7DD, got 585A87354B7BDEC219AB07E8B42D5474DAC7F08871B5D707772161FA77B3A5BF
```

# How to install

Don't do unsafe-reset-all

Backup your nibirud binary

Put my nibirud in it's place

Restart
