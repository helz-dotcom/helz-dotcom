# helz

reverse engineer / kernel developer working on windows internals and anti-cheat systems

currently researching low-level system architecture and building tools for binary analysis. most of my work involves kernel drivers, obfuscation techniques, and windows security mechanisms.

![followers](https://img.shields.io/github/followers/helz-dotcom?style=flat&logo=github&color=58a6ff) ![views](https://komarev.com/ghpvc/?username=helz-dotcom&color=58a6ff&style=flat)

## projects

### [Cloakwork](https://github.com/helz-dotcom/Cloakwork) ![stars](https://img.shields.io/github/stars/helz-dotcom/Cloakwork?style=flat&color=58a6ff)
header-only c++20 obfuscation library with compile-time encryption and polymorphic transformations. designed for maximum portability without external dependencies.

### [ETOC](https://github.com/helz-dotcom/ETOC) ![stars](https://img.shields.io/github/stars/helz-dotcom/ETOC?style=flat&color=58a6ff)
comprehensive examples of kernel-to-usermode communication methods for windows drivers. covers ioctl, shared memory, callbacks, and alternative approaches.

### [wraith-rs](https://github.com/helz-dotcom/wraith-rs) ![stars](https://img.shields.io/github/stars/helz-dotcom/wraith-rs?style=flat&color=58a6ff)
rust library for windows process manipulation and memory operations. focused on clean abstractions over win32 api.

### [Sentinel](https://github.com/helz-dotcom/Sentinel) ![stars](https://img.shields.io/github/stars/helz-dotcom/Sentinel?style=flat&color=58a6ff)
static analysis tool for kernel drivers. scans for common detection vectors used by anti-cheat systems - string signatures, certificate validation, suspicious patterns.

### [DXComm](https://github.com/helz-dotcom/DXComm) ![stars](https://img.shields.io/github/stars/helz-dotcom/DXComm?style=flat&color=58a6ff)
proof of concept for kernel-user communication through directx shared surfaces. alternative approach to traditional driver communication channels.

### [CircBufferInjection](https://github.com/helz-dotcom/CircBufferInjection) ![stars](https://img.shields.io/github/stars/helz-dotcom/CircBufferInjection?style=flat&color=58a6ff)
demonstrates mouse input injection by directly manipulating the circular buffer in mouclass.sys. bypasses standard input APIs entirely.

## what i work with

**languages:** c++, c, rust, assembly (x86/x64), python  
**focus areas:** kernel driver development, binary reverse engineering, windows internals, anti-cheat research, compiler optimization, memory manipulation

most of my work involves digging through ida pro, building kernel drivers, or figuring out how anti-cheat systems detect modifications. if it runs in kernel mode or involves low-level windows apis, i've probably messed with it.

## writing

occasionally write about reverse engineering and kernel development at [helz.dev/blog](https://helz.dev/blog)

some articles:
- windows code integrity research
- claude code jailbreak analysis

---

[website](https://helz.dev) • [github (you're on it right now)](https://github.com/helz-dotcom) • discord - ck0i
