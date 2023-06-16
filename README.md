These are the source files for building the MMDVMHost, the program that
interfaces to the MMDVM or DVMega on the one side, and a suitable network on
the other. It supports D-Star, DMR, P25 Phase 1, NXDN, System Fusion, M17,
POCSAG, FM, and AX.25 on the MMDVM, and D-Star, DMR, and System Fusion on the DVMega.

On the D-Star side the MMDVMHost interfaces with the ircDDB Gateway, on DMR it
connects to the DMR Gateway to allow for connection to multiple DMR networks,
or a single network directly. on System Fusion it connects to the YSF Gateway to allow
access to the FCS and YSF networks. On P25 it connects to the P25 Gateway. On
NXDN it connects to the NXDN Gateway which provides access to the NXDN and
NXCore talk groups. On M17 it uses the M17 Gateway to access the M17 reflector system.
It uses the DAPNET Gateway to access DAPNET to receive
paging messages. Finally it uses the FM Gateway to interface to existing FM
networks.

It builds on 32-bit and 64-bit Linux as well as on Windows using Visual Studio
2019 on x86 and x64.

This software is licenced under the GPL v2 and is primarily intended for amateur and
educational use.
