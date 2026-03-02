# 6502-Retro

The 6502-Retro is a homebrew project that is inspired by the Z80-Retro! project
by John Winans.  See: [https://github.com/z80-retro](https://github.com/z80-retro)

There are various source code repositories in this org that can be divided into
3 main categories:

## NOTE: The v4.3 hardware has 4 significant bugs

See the [6502-retro-v4](https://github.com/6502-retro/6502-retro-v4) repo for details.

## Hardware

- [6502-retro-v3](https://github.com/6502-retro/6502-retro-v3) This was the
  first version that supported a filesystem.  It's been my development board
  for the last couple of years.
- [6502-retro-v4](https://github.com/6502-retro/6502-retro-v4) This is the
  next iteration of the board.  It includes 2 expansion slots, a SPI bus and
  GPIO allowing for more experimentation with new hardware.
- Expect to see some add-on cards for this board in future.

## OS

- [bootloader](https://github.com/6502-retro/6502-retro-boot) A small rom
  resident program that will load the OS from the SDCard into memory and
  execute it.
- [rom monitor](https://github.com/6502-retro/6502-retro-monitor) A monitor
    program that runs from ROM and can be started by the bootloader
- [6502-retro-os](https://github.com/6502-retro/6502-retro-os) The main
  operating system for the 6502-Retro!

## Software

- [6502-retro-jumpingjack](https://github.com/6502-retro/6502-retro-jumpingjack) A platform jumping game.
- [6502-retro-chip8](https://github.com/6502-retro/6502-retro-chip8) Classic
Chip8 Emulator
- [6502-retro-snake](https://github.com/6502-retro/6502-retro-snake) Classic
  snake game

<!-- vim: set ts=2 sw=2 et set tw=80 cc=80: -->
