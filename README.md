# RISCVy-BSDness
The stepping stones on my journey to porting software to OpenBSD on RISC-V and security research in that environment.
I'm also interested in writing Linux kernel drivers for RISC-V, which as time goes on may actually end up happening 
before I'm ready to submit those kinds of contributions to OpenBSD. 

My end goal is to have the skills to build a RISC-V mobo that fits in either an old Thinkpad or one'a them fancy newfangled Frameworks, but that's too much cart before the ponies right now. 

//TODO: Markdown Makeover

## On the beaten path
### Knowledge (which is power)
RISC-V Instruction Set Manual Volume 1: Unprivileged ISA - https://github.com/riscv/riscv-isa-manual/releases/download/Ratified-IMAFDQC/riscv-spec-20191213.pdf
RISC-V Instruction Set Manual Volume 1: Privileged Architecture - https://github.com/riscv/riscv-isa-manual/releases/download/Priv-v1.12/riscv-privileged-20211203.pdf
Recently Ratified Extiensions - https://wiki.riscv.org/display/HOME/Recently+Ratified+Extensions
Processor Specific RISC-V ABI Specification - https://github.com/riscv-non-isa/riscv-elf-psabi-doc/releases/download/v1.0/riscv-abi.pdf
RV SBI Spec - https://github.com/riscv-non-isa/riscv-sbi-doc/releases/download/v1.0.0/riscv-sbi.pdf
RISC-V UEFI Protocol Spec - https://github.com/riscv-non-isa/riscv-uefi/releases/download/1.0.0/RISCV_UEFI_PROTOCOL-spec.pdf
RISC-V Reader by David Patterson and Andrew Waterman. This is to RISC-V what Kernighan & Ritchie is to C, or Nielsen & Chuang is to Quantum Computation & Information Theory - http://riscvbook.com/
RISC-V ASM Reference Card - http://riscvbook.com/greencard-20181213.pdf
Linux Foundation's RISC-V Fundamentals (LFD210) - https://training.linuxfoundation.org/training/riscv-fundamentals-lfd210/
Fun C Review course and light project. Would not reccomend as a starting point for learning C (C Above!(pun intended)) - https://lowlevel.academy/courses
Starting point for OpenBSD driver Development - https://www.youtube.com/watch?v=W5qhWw07qpU&t=384s
My starting point for low-level exploit development. It's a bit dated, for example they reference the x86 processors running on 
"newer Macs", and it does use CISC for the curriculum, but as the dodgeball legend Patches O'Hoolighan once said, "If you can dodge a wrench, you can dodge a ball." "Hacking: The Art of Exploitation" by Jon Erickson - https://nostarch.com/hacking2.htm

### Hardware (Toys!)
What will probably end up being my first bare metal desktop dev environment - https://www.starfivetech.com/en/site/boards
Intent is to swap the 1 GHz/1Gb RAM with the more powerful Milk-V Mars CM using a CM4 adaptor. Backup Plan is to port useful command line software to the R-01 for a neat cyberdeck network client, and maybe some light retro gaming. - https://www.clockworkpi.com/uconsole
Small portable soldiering iron running a SiFive E24 Core RV32IMAFC. Necessary? No, but it's sterile and I like the taste. - https://pine64.com/product/pinecil-smart-mini-portable-soldering-iron/



## Off the beaten path
### Community Engagement
RISC-V Technical Forums List - https://live-risc-v.pantheonsite.io/technical/technical-forums/
RISC-V Tech Specs Wiki - https://wiki.riscv.org/display/HOME/RISC-V+Technical+Specifications



### Blog Posts (and light propaganda)
Crash course on what RISC-V is and isn't - https://riscv.org/blog/2023/03/top-ten-fallacies-about-risc-v/
Intro to RISC-V from Linux Foundation - https://training.linuxfoundation.org/training/introduction-to-riscv-lfd110x/
https://semiengineering.com/is-risc-v-the-future/
https://www.designnews.com/embedded-systems/why-risc-v-architecture-is-the-future-of-embedded-design
https://www.computer.org/publications/tech-news/trends/reasons-to-adopt-risc-v
https://www.youtube.com/watch?v=RrVRMFjYti0



// TODO add a buymeacoffee link and other passive begging solutions to fund/subsidize hardware. 
