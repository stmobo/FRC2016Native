# lib5002: Team 5002 Native C++ Code
Team 5002 (Dragon Robotics)'s code. Intended to be run on both X86-64 and hard-float ARM.
Compile on a Linux system with G++ >= 4.9.
Supports the x86-64 and gnueabihf toolchains.

# Make Targets for Static Libraries:
 * lib5002-vis.a: static library containing vision processing code.
 * lib5002-net.a: static library containing networking code.

# Make Targets for Testing Programs:
 * ballproc: Ball processing test.
 * goalproc: Goal processing test.
 * goalproc-basic: Basic goal processing test (no realtime visual output, just console)
 * nettest: Networking test (echo server). Builds for ARM only.

Define ARCH=ARM to enable builds for ARMHF.
Binaries and library files will be output in the ./bin/ subfolder.
