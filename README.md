# GFX6502

The point of this pet project is to:

1. Learn 6502 assembly
2. Learn 3D graphics programming
3. Implement a 3D engine in 6502 assembly

Below are a sea of notes and ideas to do so. 

If you're looking for order, come back in a few months (:

## 6502 Basics

- Best tutorial ever, learn 6502 assembly in one sitting: Assembly In One Step. 
  - Link: https://dwheeler.com/6502/oneelkruns/asm1step.html
- Easy6502. Good explanations! 
  - Link: http://skilldrick.github.io/easy6502/
- Extensively commented opcode list.
  - Link: https://www.atariarchives.org/alp/appendix_1.php

## Exercises

Start with the Easy6502 emulator. Then move on to 8bitworkshop. Lastly, build a local dev environment.

- [ ] See the Snake game from Easy6502 above. Re-implement it from memory, fixing the bugs discussed in this gist: https://gist.github.com/wkjagt/9043907
  - Run it locally: https://github.com/skilldrick/6502js
  - Fun fact: I helped! 🎉 https://github.com/skilldrick/6502js/pull/9
- [ ] Learn Bresenham's line drawing algorithm. 
  - [ ] Implement it from memory in Go.
  - [ ] Implement it for 6502, either NES or 6502js.
  - [ ] Implement it from memory on the NES.
- [ ] Implement Snake on the NES.
- [ ] Implement 3D tutorial from Coding Train in Go.
- [ ] Implement 3D tutorial from Coding Train on the NES.
- [ ] Implement 3D engine from javidx9 in Go.
- [ ] Implement 3D engine from javidx9 on the NES.
- Look into ray casting.

Extras:
  
- [ ] Solve Project Euler puzzles in 6502
- [ ] Re-implement all of these: https://www.youtube.com/playlist?list=PLB_ibvUSN7mzUffhiay5g5GUHyJRO4DYr

## Assembly Practice

Ordered by complexity. Go through them all.

- Implementing Factorial in 6502
  - Link: http://c64os.com/post/factorialin6502
- Coding Algorithms
  - Link: http://www.obelisk.me.uk/6502/algorithms.html
- 6502 Coding Algorithms Macro Library
  - Link: https://atariwiki.org/wiki/Wiki.jsp?page=6502%20Coding%20Algorithms%20Macro%20Library
- Macros.
  - Article: http://wilsonminesco.com/StructureMacros/
  - CA65: https://www.cc65.org/doc/ca65-11.html
  - CA65: https://www.cc65.org/doc/ca65-12.html
- Project Euler.
  - Link: https://projecteuler.net/
- Learn Multiplatform 6502 Assembly (ChibiAkumas)
  - Link: https://www.youtube.com/watch?v=lsvSZamCCBM&list=PLp_QNRIYljFofA93OyUFnxDamjemzidFv
  
## NES Practice

Go through them all.

Tutorials:

- NES Development Day 1
  - Link: https://www.moria.us/blog/2018/03/nes-development
- Nerdy Nights.
  - Link: https://nerdy-nights.nes.science/
- CA65 port for Nerdy Nights. (Broken?)
  - Link: https://bitbucket.org/ddribin/nerdy-nights/src/default/
- GBA Guy.
  - Link: https://patater.com/gbaguy/nesasm.htm
- Famicon Party.
  - Link: https://book.famicom.party/

Watch and learn:

- ChibiAkumas channel.
  - Link: https://www.youtube.com/playlist?list=PLp_QNRIYljFoSkq8absJGxocIvofS06RN
- Tyler Barnes channel.
  - Link: https://www.youtube.com/user/TylerBarnesMusic/videos
    
Sample projects:

- A minimal NES example using ca65 
  - Link: https://github.com/bbbradsmith/NES-ca65-example
- Nova The Squirrel: an open source NES platformer game
  - Link: https://github.com/NovaSquirrel/NovaTheSquirrel
  - Interesting: https://github.com/NovaSquirrel/PrincessEngine
- NESASM Hello World.
  - Link: https://gist.github.com/camsaul/0bd13b94574d936ce9a7
- Reference.
  - Link: https://www.chibiakumas.com/6502/nesfamicom.php
- Raycaster demo.
  - Link: https://www.youtube.com/watch?v=po69zgqyFWM
  
## NES Emulators

- Mesen.
  - Link: https://www.mesen.ca/
- Fceux. It has no debugger on Linux! Emulate with Wine.
  - Link: http://www.fceux.com/web/home.html
- JSNES. 
  - Link: https://github.com/bfirsh/jsnes-web
- Nesicide.
  - Link: https://knob.phreneticappsllc.com/nesicide/
  
## NES Game References

- The Games That Pushed The Limits Of The NES
  - Link: https://www.racketboy.com/retro/best-nes-graphics-sound
- The 10 Best NES Games
  - Link: https://uk.pcmag.com/gallery/124205/the-10-best-nes-games
- Double Dragon
- Elite
  - Source: https://github.com/kieranhj/elite-beebasm
- Solstice
- Metal Gear
- Rad Racer
- Cosmic Epsilon
- WorldRunner
- Marble Madness
- Snake Rattle 'n' Roll
- Super Glove Ball
- Faceball (GB)
- Zen - Intergalactic Ninja
- Destination Earthstar

## Graphics

I'm Too Young to Die:

- Bresenham line drawing:
  - Go: https://raw.githubusercontent.com/StephaneBunel/bresenham/master/drawline.go
  - Go: https://rosettacode.org/wiki/Bitmap/Bresenham%27s_line_algorithm#Go
  - 6502: https://gist.github.com/petrihakkinen/cc07aa5d15baf157c668f3dcc582ecc2
- 2D Graphics Algorithms:
  - Part 1: https://www.youtube.com/watch?v=bfvmPa9eWew
  - Part 2: https://www.youtube.com/watch?v=IDFB5CDpLDE

Hurt Me Plenty:

- Matrix Multiplication for 3D Rendering (The Coding Train)
  - Link: https://www.youtube.com/watch?v=tzsgS19RRc8
- 3D Rendering with Rotation and Projection (The Coding Train)
  - Link: https://www.youtube.com/watch?v=p4Iz0XJY-Qk

Ultra-Violence:

- Code-It-Yourself! 3D Graphics Engine Series (javidx9)
  - Link: https://www.youtube.com/watch?v=ih20l3pJoeU

Books:

- Fundamentals of Computer Graphics (Marschner & Shirley)

## Graphics on 6502

- Line drawing routines programming: a different approach. 6502/6510 assembly implementation on the Commodore 64
  - Link: http://retro64.altervista.org/blog/line-drawing-routines-programming-different-approach-6502-assembly-implementation/?doing_wp_cron=1588435063.2778320312500000000000
- Developing a 3D-Demo for the Apple ][
  - Link: https://www.golombeck.eu/index.php?id=34&L=1
  
## Debuggers

All of them suck.

Interesting:

- BBC Micro emulator. 
  - Link: https://github.com/mattgodbolt/jsbeeb/wiki/Debugger
- 8bitworkshop. 
  - Link: https://8bitworkshop.com/v3.5.1/?repo=sehugg%2FNES-ca65-example&platform=nes&file=example.s
- Ghidra loader for NES. 
  - Link: https://smb3.bf0.org/ghidra-loader/ghidra-plugin/2019-08-20-ghidra-loader/
- Article: "Debugging 6502 Assembly Doesn't Have to be Awful"
  - Link: https://vintageisthenewold.com/debugging-6502-assembly-doesnt-have-to-be-awful-retrochallenge-2018-04-update-9/
- clever-disasm
  - Link: https://github.com/bisqwit/nescom
    
To take matters in your own hands:

- Something that looks good. 
  - Link: https://github.com/cyrus-and/gdb-dashboard
- Writing a debugger. 
  - Link: https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/

## Tools

- Tiled map editor. 
  - Link: https://www.mapeditor.org/
- PrincessEdit.
  - Link: https://github.com/NovaSquirrel/PrincessEdit

## Random Fun

- InfoSec NES. 
  - Link: https://news.ycombinator.com/item?id=12951503
  
History:

- Fabien Sanglard's books about the Doom and Wolfenstein 3D engines.
  - Doom: http://fabiensanglard.net/gebbdoom/
  - Wolfenstein: http://fabiensanglard.net/gebbwolf3d/
- The Making of Prince of Persia

6502 trickery:

- Dirty tricks 6502 programmers use
  - Link: https://nurpax.github.io/posts/2019-08-18-dirty-tricks-6502-programmers-use.html
- List of 6502 bugs. Are they present in emulators?? 
  - Link: http://www.textfiles.com/apple/6502.bugs.txt
- Dirty Assembly Tricks in NES Assembly
  - Link: https://news.ycombinator.com/item?id=8405214
- 6502 assembly optimisations
  - Link: https://wiki.nesdev.com/w/index.php/6502_assembly_optimisations
- 6502 arithmetic and why it is terrible
  - Link: https://news.ycombinator.com/item?id=17275797
    
Next steps:

- SNES
  - A Comprehensive Super Mario Bros. Disassembly
    - Link: https://news.ycombinator.com/item?id=15484907
    - Link: https://gist.github.com/1wErt3r/4048722
- x86
  - x86 assembly book:
    - Link: http://download-mirror.savannah.gnu.org/releases/pgubook/ProgrammingGroundUp-1-0-booksize.pdf
  - x86 assembly programs:
    - Link: https://softwareengineering.stackexchange.com/a/155740
    
