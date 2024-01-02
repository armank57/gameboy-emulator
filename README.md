# Gameboy Emulator

This project was inspired by __CS250: Computer Architecture__, a course I completed in my third semester at Purdue University. This is my first attempt at building an emulator, and it seemed doable using what I've learned as a basis and researching from there.

## Development

To start off with this project, I found a handful of resources to use as reference to learn about the specific Gameboy architecture, which has many features similar to a Z80 architecture. This was different for me as I was mainly familiar with x86 architecture from CS250.

The bulk of what I've been doing so far is making the CPU work and finetuning it. In the _/roms_ folder, there are a few roms that are helping me test the functionality of my CPU and its instructions. Mostly, the CPU is finished but I'm working on bug fixes - specifically with interrupts.

## Dependencies

This project requires the following packages, which I installed using Homebrew:
- SDL2
- SDL2_ttf
- Cmake
- Check

## References

https://gbdev.io/pandocs/ - The most comprehensive technical reference to Game Boy available to the public

https://www.pastraiser.com/cpu/gameboy/gameboy_opcodes.html - Table of all opcodes used by the CPU
