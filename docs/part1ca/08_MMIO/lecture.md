Lecture 8
---

# Memory-mapped I/O (MMIO)

## Lecture

Slides ([PDF](CA_Lecture_08.pdf), [PPTX](CA_Lecture_08.pptx)).

#### Outline

* I/O devices
* Direct memory access (DMA)
* Memory-mapped I/O (MMIO)
* Drivers
* RARS MMIO device emulators

#### Examples:

* [digit_lab1.s](https://github.com/andrewt0301/hse-acos-course/blob/master/docs/part1ca/08_MMIO/digit_lab1.s)
* [digit_lab2.s](https://github.com/andrewt0301/hse-acos-course/blob/master/docs/part1ca/08_MMIO/digit_lab2.s)
* [bitmap_display.s](https://github.com/andrewt0301/hse-acos-course/blob/master/docs/part1ca/08_MMIO/bitmap_display.s)

## Workshop

1. Input a floating-point number, round it to one digit to the left of decimal point (e.g. `3.5`)
   and display it in the Digital Sim Lab display.
   User [digit_lab1.s](
   https://github.com/andrewt0301/hse-acos-course/blob/master/docs/part1ca/08_MMIO/digit_lab2.s)
   as a starting program.

# Homework

Solve the following tasks:

1. [EightSectors](../Tasks/homeworks.md#eightsectors)

2. Modify the [digit_lab2.s](
   https://github.com/andrewt0301/hse-acos-course/blob/master/docs/part1ca/08_MMIO/digit_lab2.s) program
   to display keys pressed in the hexadecimal keyword in the diginal display (as decimal values).

Commit the programs to your private GitHub account. Place them into the folder `ca/lab08`.

## References

* [Memory-mapped I/O](https://en.wikipedia.org/wiki/Memory-mapped_I/O) (Wikipedia).
* [Direct memory access](https://en.wikipedia.org/wiki/Direct_memory_access) (Wikipedia).
