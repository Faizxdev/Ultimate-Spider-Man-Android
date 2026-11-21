# Ultimate Spider-Man (2005) — Native Android Port

An unofficial, native ARM64 Android fan port of *Ultimate Spider-Man* (2005, PC) by Treyarch.

## Project Architecture
- **Target:** Native ARM64 Android (API 29+, Vulkan 1.1+)
- **Graphics Pipeline:** Direct3D 9 -> dxvk-native -> Vulkan 1.1
- **Audio:** DirectSound 8 -> SDL2 Audio
- **Video:** RAD Bink 1.7d (`binkw32.dll`) statically recompiled
- **Static Recompilation:** x86-32 to C lifted runtime, compiled with Android NDK (Clang)
- **Engine Source Enhancements:** Incorporating verified physics, input, and actor logic from decompiled Treyarch engine research (`USM_src_code`)
- **Controller & Input:** Fully customizable mobile on-screen touchscreen controller with analog stick, smooth swipe camera, context-sensitive combat/swing/dodge buttons, and Bluetooth gamepad support.

## Notice & Disclaimers
This repository contains no game assets, copyrighted data, or extracted original game code. 
Users must provide their own legally purchased copy of *Ultimate Spider-Man (PC, 2005)*.
