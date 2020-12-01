# BufferOverFlow

This repo consists of all my BufferOverFlow scripts written by me.

## TryHackMe

### Buffer Overflow Prep
#### https://tryhackme.com/room/bufferoverflowprep
```
Win32 Stack Based BufferOverflow Win32
Debugger : Immunity Debugger
Payload : windows/shell_reverse_tcp
```

## HackTheBox

### Buff (10.10.10.198)
#### https://www.hackthebox.eu/home/machines/profile/263
Exploit Link : https://www.exploit-db.com/exploits/48389 
This exploit is modified by me, not written by me.
```
Win32 Stack Based BufferOverflow Win32
IP : 10.10.10.198
Difficulty : Easy
Points : 30
Program : CloudMe 1.11.2
Payload : windows/shell_reverse_tcp
```
### Frolic (10.10.10.111)
#### https://www.hackthebox.eu/home/machines/profile/158
```
32-Bit Elf BufferOverFlow ret2libc Linux
IP : 10.10.10.198
Difficulty : Easy
Points : 30
Payload : Ret2Libc
Binary : rop
```

## VulnHub

### BrainPan
#### https://www.vulnhub.com/entry/brainpan-1,51/
```
Win32 Stack Based BufferOverflow Linux
payload : linux/shell_reverse_tcp
The brainpan.exe is a win32 executable running with wine on linux
```