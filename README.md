# prebuilt cling binary for android

Currently supported:
- debian in UserLAnd on Android arm64
- termux(arm64), experimental

It takes my Android tablet approximately 3.5 hours to download and build it.

Hope this prebuilt binary is useful for someone else.

## Download
- UserLAnd: https://github.com/kxxt/prebuilt-cling-for-android/releases/tag/initial
- termux: https://github.com/kxxt/prebuilt-cling-for-android/releases/tag/termux

You may need to install some system dependencies manually.

For termux, you need to install `ndk-sysroot`.

## Usage
- Decompress it and you will get an `inst` folder.
- (for UserLAnd) Execute `./inst/bin/cling`.
- (for termux) Execute `./inst/bin/cling -isystem /data/data/com.termux/files/usr/include -isystem /data/data/com.termux/files/usr/include/arm-linux-androideabi/`.


If this repo helps you, don't forget to give it a star.
