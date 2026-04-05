# Lecture
# PROCESSOR CORE VS PROCESSOR 

**Date:** 4 Apr 2026

---

# Key Concepts

Understand the difference between the processor core, processor, and microcontroller. What actually consists inside the core processor, and what do the supporting peripherals actually do.

---

# Notes

![[stm32f407-system-architecture.jpeg]]

- ARM released the Technical Reference Manual or the TRM to the market (Open to all users)
- Check functional description diagram to review the processor structure of the Cortex-M4 (Or any other ARM processor)
- The processor itself is simply a processor core surrounded by supporting peripherals. 
- Peripherals include: Nested Vectored Interrupt Controller (NVIC), Flash Patch Breakpoint (FPB), Memory Protection Unit (MPU), Data Watchpoint and Trace (DWT), AHB Access Port (AHB-AP), Bus Matrix, Instrumentation Trace Macrocell (ITM), Wake-Up Interrupt Controller (WIC), and a few others.
- Inside the core processor consists of the ALU — where data computation occurs, logic to decode and execute instructions, its own registers for data manipulations, pipe line engine, hardware multiplication and division engine.
- The Processor core is also known as the CPU (Central Processor Unit)
- A processor is the core + peripherals.
- The processor talks to the outside world using various BUS interfaces — ICode BUS interface, DCode BUS interface, and System BUS interface to name a few.

![[stm32f407-functional-overview.jpeg]]

---

## Questions / Things to Revisit

- [ ] Discuss NVIC (Nested Vectored Interrupt Controller) peripheral in detail
- [ ] Later BUS interfaces will be introduced
- [ ] Look up the different kinds of ARM processors and their specs
- [ ] Compare to a pc chip such as the Apple Silicon M series

---

# Summary

The ARM Cortex-M4 processor is made up of a core (CPU) plus supporting peripherals like the NVIC, MPU, and ITM, all communicating through dedicated BUS interfaces. Understanding this distinction is foundational because firmware development requires knowing which part of the processor you're actually talking to when you write code.