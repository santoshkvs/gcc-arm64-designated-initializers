# Designated Initializer Support for GCC on 64-bit ARM (AArch64)

This project focuses on enabling **C99-style designated initializer support in the GNU C++ compiler (G++) for 64-bit ARM (AArch64) architecture**.

The implementation extends C++ compiler capabilities to support more flexible aggregate initialization of structures and arrays, including features such as:

- **Out-of-order initialization:** Allows structure members to be initialized in an order different from their declaration order.
- **Selective member initialization:** Enables initialization of specific structure members without explicitly initializing every member.
- **Indexed array initialization:** Supports initializing individual array elements using designated indices.
- **Range-based array initialization:** Enables initialization of a specified range of array elements using designated ranges.
- **Improved initialization flexibility:** Provides a more expressive and convenient mechanism for initializing complex structures and arrays.

### Objective and Motivation

C99 introduced designated initializers in C, providing a convenient mechanism for initializing selected structure members and array elements. However, these capabilities were not equivalently supported in C++, resulting in a significant language compatibility gap between C and C++.

This work aims to bridge that gap by extending G++ to support nontrivial designated initialization features, bringing C++ initialization capabilities closer to those available in C99.

### Significance

The implementation improves compatibility when working with codebases that use advanced designated initialization techniques, particularly in embedded systems and low-level software development targeting 64-bit ARM platforms.

It also simplifies the initialization of complex data structures, improves code readability and maintainability, and reduces the need for verbose or repetitive initialization code.

**Key Technologies:** GNU GCC, G++, C++, C99, Designated Initializers, AArch64 (ARM64), Compiler Development, Embedded Systems.
