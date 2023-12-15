# cpp-os 
## Description
A basic but extensible UNIX-based operating system written in C++.

Extensible?
Should be modular/kept open to extension for future additions from either myself or others.

UNIX-based, you say?
Should adhere to standards set by UNIX, including a similar kernel design, command-line interface and hierarchal file system structure.

## Project Status
Currently in the research phase. Exploring design possibilities and doing my reading. A few questions to consider:
- Use [GRUB](https://git.savannah.gnu.org/git/grub.git) or write my own bootloader?
- Instruction set architecture? (e.g. x86)
- Scheduling algorithm? (e.g. round-robin)
- Virtual address space layout? (e.g. [Linux address space](https://i.stack.imgur.com/dvK8G.png))
- Memory allocation strategy? Slab/Buddy system?
- Testing Strategies (e.g. model checking for core algorithms, user space testing)