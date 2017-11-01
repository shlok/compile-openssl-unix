# compile-openssl-unix

A Bash script for compiling OpenSSL as static libraries for Unix-based systems.

## OpenSSL version

1.1.0g.

## Building on macOS for 64-bit macOS development

Tested on macOS Sierra with Xcode 9’s command line tools.

1. On the Terminal, `cd` into `compile-openssl-unix`.
2. Run `./compile-openssl-unix macos`.
3. The directory `openssl-macos` should now contain (a) OpenSSL’s header files and (b) the `libcrypto.a` and `libssl.a` static library files built for x86_64.

## Building on macOS for 64-bit iOS development

Tested on macOS Sierra with Xcode 9’s command line tools.

1. On the Terminal, `cd` into `compile-openssl-unix`.
2. Run `./compile-openssl-unix ios`.
3. The directory `openssl-ios` should now contain (a) OpenSSL’s header files and (b) the `libcrypto.a` and `libssl.a` static library fat files built for both x86_64 (simulator) and arm64 (device).
