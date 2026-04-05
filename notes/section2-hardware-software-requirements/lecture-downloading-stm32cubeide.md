# Lecture 
# Downloading STM32CubeIDE

**Date:** 4 Apr 2026

---

## Key Concepts

STM32CubeIDE is an eclipse based IDE with STM32 related customization, it will be used throughout the remainder of the course. (Good to learn but personally will be using STM32 extension for PlatformIO, to continue using VSCode — keep everything clean and uniform). 

## Notes

- IDE = Integrated Development Environment
- Will need STM32CubeIDE extension for Visual Studio Code. 
- STM32CubeIDE is available on Mac — current version is 2.1.0/2.1.1. Staying below 2.0 recommended to stay consistent with course material.
- STM32CubeMX is a code generator and is separate from the STM32CubeIDE and will need to be installed separately
	- Support for GCC
	- Support for semihosting feature through debug via ST-LINK GDB server
	- Support for bundled CMake/Ninja binaries
- Won't be using STMCubeMX, will build everything from scratch focusing on **bare metal programming**, but still good to know how to access.

## Code Snippets

```c
// paste any important code here
```

## Questions / Things to Revisit

- [ ] Is the VSCode extension up to scratch compared to Mac desktop IDE

## Summary

STM32CubeIDE is the Eclipse-based IDE used throughout the course, but on Mac the workflow runs through the STM32 extension for VS Code instead. STM32CubeMX is a separate code generation tool that won't be used since the course focuses on building everything from scratch at the bare metal level.