# Custom Floating Point System (CFPS)

## Overview
This document defines a set of custom names for floating-point types with different bit sizes. Each type represents a floating-point number with a specific number of bits.

For example, if only a minimal amount of data is required (such as a boolean-like value), a 1-bit type like ZeroFloat could theoretically be used.

## Types
- ZeroFloat (1 bit)
- FemoFloat (4 bits)
- PicoFloat (8 bits)
- NanoFloat (16 bits)
- Float (32 bits)
- Double (64 bits)
- KiloFloat (128 bits)
- MegaFloat (256 bits)
- TantoFloat (512 bits)
- ZeptoFloat (1024 bits)
- TeraFloat (2048 bits)
- MontoFloat (4096 bits)

## Use Cases
These types can be used in different scenarios, particularly in programming and numerical computations.

- Lower-bit types (e.g., PicoFloat, NanoFloat) could be used for memory-efficient data storage.
- Standard types (Float, Double) match commonly used precision levels.
- Higher-bit types (KiloFloat and above) could be used for extremely high-precision calculations.

## Technical Details
These types are not officially implemented or standardized. They are conceptual names for floating-point formats that could potentially be defined or implemented in the future.

This system is intended as a conceptual or experimental framework rather than a real-world standard.
