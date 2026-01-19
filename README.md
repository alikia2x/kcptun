# kcptun

This is a fork of [xtaci/kcptun](https://github.com/xtaci/kcptun), a quantum-safe, secure tunnel built on QPP, KCP, FEC, and multiplexing.

This version was specifically modified for [KctM](https://github.com/alikia2x/kctm), a macOS utility for managing kcptun.  
This fork adds a simple feature: it uses [Kqueue](https://developer.apple.com/library/archive/documentation/System/Conceptual/ManPages_iPhoneOS/man2/kqueue.2.html) to monitor the parent process and terminates the program when the parent process exits, preventing it from becoming an orphan process.


Please see the [original repository](https://github.com/xtaci/kcptun) for core documentation and usage instructions.
