# Valgrind for macOS ![Linux Build](https://github.com/berkonat/valgrind-macos/workflows/Build_Linux/badge.svg) ![macOS Build](https://github.com/berkonat/valgrind-macos/workflows/Build_macOS/badge.svg)

This is a modified version of [Louis Brunner's valgrind-macos](https://github.com/LouisBrunner/valgrind-macos) repository.
Please check any update on the original repository before continue on installing this version.

## Status of this version

- Modified to be compiled on macos 10.14.6 with XCode 10.15 SDK
- Modified to be compiled with MPI version >= 3.0

## To check original `valgrind-macos` repository

The original `https://github.com/LouisBrunner/valgrind-macos` repository contains a version of Valgrind including a few patches to improve support for the macOS platform. It is maintained by [Louis Brunner](https://github.com/LouisBrunner).

## Main Repo Status

Valgrind now builds and works on every macOS version

Note that some features are still in progress:

 - crash when using wqthread (used in certain UI frameworks)
 - using threads and signals is undefined

It is currently tested on 10.14.6 and 10.15.4.

Checkout the [`patches`](https://github.com/LouisBrunner/valgrind-macos/commits/patches) branch for a list of patches that can be directly applied to the upstream Valgrind.
