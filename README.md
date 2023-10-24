# MaldevAcademyLdr.1

## Actual (Bypassed Defender 20231024)

## How to use 20231024
- Create a binary shellcode, could be your favorite C2.

```
PS Z:\Def-Evasion\MaldevAcademyLdr.1\x64\Debug> .\PayloadEncrypter.exe .\payload_x64.bin
[i] Reading .\payload_x64.bin From The Disk ... [+] DONE
[i] Generating AES Key and IV:
        <i> AES KEY : [ C0 B0 F4 B6 26 59 8B DB 1C E2 DC FE BE CE A6 E1 22 A1 D8 01 25 7A 91 B4 E8 49 E7 5D 0A 15 49 E1 ]
        <i> AES IV  : [ 98 C1 B8 2D F4 E5 D5 2B C4 51 71 0D 94 35 1E 64 ]
[i] Final Payload Size: 976
[i] Writing "Payload.ctaes" To The Disk ... [+] DONE
[*] The Payload Is Ready To Go!
```

- Copy the Payload.ctaes to the loader directory.
- Rebuild the Loader tool, and execute.

## Quick Links

* Maldev Academy Home - https://maldevacademy.com
  
* Maldev Academy Syllabus - https://maldevacademy.com/syllabus

* Maldev Academy Pricing - https://maldevacademy.com/pricing

## EXE Loader

Maldev Academy's October update saw several interesting modules being released to our users. One of them was our DLL loader that was successfully tested against several EDRs including MDE and Crowdstrike.

We promised to release an EXE version of the loader on GitHub.

| ![tweet](https://github.com/Maldev-Academy/MaldevAcademyLdr.1/blob/main/tweet.png) |
|:--:| 
| *https://twitter.com/MalDevAcademy/status/1701981413938012462* |

## Features

* Indirect-Syscalls using an improved HellsHall implementation.

* Dll Unhooking via the \KnownDlls\ directory

* Payload injection by chunking

* Using custom AES encryption library.

* Executing payload via Thread Pool APIs.

* Obfuscating IAT using API hashing and API camouflage.

* CRT library independent.

## Demo

[![Demo](https://github.com/Maldev-Academy/MaldevAcademyLdr.1/blob/main/demo-cover.png)](https://github.com/Maldev-Academy/MaldevAcademyLdr.1/blob/main/demo.mp4)

