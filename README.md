# GW-TestLab  
*Instruments for measuring sound systems*

GW-TestLab is the scientific side of GhostWire Audio: a collection of Python and C++ tools for testing, visualizing, and benchmarking DSP systems.

This repo exists to answer questions like:
- What does this filter actually do across the spectrum?
- Did this refactor change the sound?
- How much CPU does this block cost at 64 samples vs 512?

---

## What This Is

- Signal generators (sine, sweeps, noise, impulses)
- FFT and spectral analysis tools
- Frequency and phase response visualization
- Regression tests for DSP blocks
- Performance benchmarks

---

## Philosophy

Sound software shouldn’t be a black box.

If a system works, you should be able to measure it, plot it, and explain it. This lab treats DSP like a physics experiment: generate a signal, run it through the system, observe the result.

---

## Typical Workflow

1. Generate a test signal
2. Run it through a DSP block or engine
3. Visualize the output
4. Compare against expected behavior
5. Repeat until the math and the sound agree

---

## Status

This repo is intentionally experimental. Scripts and tools may change as the engine evolves.

---

## Part of GhostWire Audio

GW-TestLab is part of the **GhostWire Audio** open-source lab for understanding how real-time audio systems behave, not just how they sound.
