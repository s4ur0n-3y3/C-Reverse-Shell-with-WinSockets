# C-Reverse-Shell-with-WinSockets
Simple C++ Reverse Shell with WinSockets

For Compiling the code on kali:

x86_64-w64-mingw32-g++ shellRev.cpp -o revshell.exe -lws2_32 -s -ffunction-sections -fdata-sections -Wno-write-strings -fno-exceptions -fmerge-all-constants -static-libstdc++ -static-libgcc -fpermissive >/dev/null 2>&1
