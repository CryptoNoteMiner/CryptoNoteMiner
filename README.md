# CryptoNoteMiner - CryptoNight CPU mining tool based on XMR-STAK / CryptoGoblin
**For coins based on cryptonight-classic, cryptonight-light or cryptonight-heavy.**<br>
**Support for Monero, Electroneum, Aeon, Sumokoin, Edollar, Mynt, Kryptonium and more.**

CryptoNoteMiner is a greedy miner stak that will push the cpu to get as many hashes as possible.

## Overview
* [Download](https://github.com/CryptoNoteMiner/CryptoNoteMiner/releases)
* [Documentation](https://github.com/CryptoNoteMiner/CryptoNoteMiner/tree/master/doc)

CryptoNoteMiner was forked from xmr-stak in early 2017, it utilizes several GCC compiler-specific tweaks and
many other (medium, small, minor and micro) optimizations to get the most speed out of your cpu.
CryptoNoteMiner can also be compiled using, but several of the optimizations will not be activated.

## Installation and Configuration
If you are using Windows, download the pre-compiled windows binaries, or compile them yourself.
If you are using Linux, MacOS, BSD or similar, you need to compile them yourself.

After you have compiled or downloaded the executables, just run the miner without any configuration files,
and it will help you generate the config files. After that, you can optionally tune your configuration.
* [CPU Tuning](doc/tuning-cpu.md)
* [GPU Tuning](doc/tuning-gpu.md)

## Windows
Download the pre-compiled binaries [here](https://github.com/CryptoNoteMiner/CryptoNoteMiner/releases)

## Compilation
CryptoNoteMiner includes a script `build.sh` that can be edited to easily change important settings
and then run to start the compilation.

To compile, run:
`./build.sh`

For more information about compiling and dependencies, please have a look at the documentation
targeting your OS/distro [here](https://github.com/CryptoNoteMiner/CryptoNoteMiner/tree/master/doc).

## Donation
Dev fee mining is set to 1.5%, and part of it goes to xmr-stak authors.

If you want to make a little donation directly to research devs (Dead2), transfers or donation mining (at donate.coinmine.network:5555), dev donation XMR address is:
```
45obtQLBPgyZL8Xb4qFFdZQLZugJzkHUo7oHeKd2zZSmfjxRg6WKhAjD4o1eb6LjK1RY2V4sp1nmDAity9Ks9NvZHw8z1EL
```
Any donation is much appreciated. (not required)

