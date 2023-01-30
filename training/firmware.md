Assuming knowledge ofGDB, Ghidra, and basic Exploitation:

## Firmware RE
1. Buildchains
  * BuildRoot Tutorial
    * Cross Compile Buildchain
    * QEMU
   * Other SDKs and Buildchains
2. Static Triage
   * Identifying an unknown firmware architecture
   * Identifying interesting functions and parsers 
3. Get to Rootfs
   * https://www.makemehack.com/2020/04/how-to-get-the-root-file-system.html 
   * Binwalk + Custom Toolchains
   * Encryption
4. Boot Process
   * https://www.makemehack.com/2020/04/startup-scripts-and-the-quest-for-root.html 
   * Inittab/init.d
   * Identify interesting services
5. Kernel
   * VMLinux to Elf 
6. Ghidra	
   * Eclipse IDE - Ghidra Scripts, Ghidra-Dev Plugin
7. Dynamic Triage
   * Architectures
       * Bug Types in Each
    * GDB Multi-Arch
    * Get things to work/TroubleShoot
8. RTOS
   * Anatomy of a  RTOS
   * Common code patterns present in RTOS and bare-metal firmware

## Emulation
1. Emulation with Qemu
   * https://www.makemehack.com/2020/05/how-to-emulate-firmware-with-qemu.html 
   * https://www.zerodayinitiative.com/blog/2020/5/27/mindshare-how-to-just-emulate-it-with-qemu
2. User space QEMU emulation
   * https://azeria-labs.com/arm-on-x86-qemu-user/ 
3. Full System Qemu Tutorial
   * https://www.tarlogic.com/blog/owasp-fstm-step-6-firmware-emulation/ 
   * https://www.reddit.com/r/ReverseEngineering/comments/grmxs4/how_to_just_emulate_it_with_qemu_a_guide_to/ 
   * https://azeria-labs.com/emulating-arm-firmware/ 
4. Usermode + System Build Libraries 
   * How to Guess Functionality of Things You Dont Have
5. LD Preload and Kernel Objects
6. Manual Patching
7. Editing Shared Library Header of Elf
   * Weak References


## Firmware Pulling
1. Identify Components
   * https://www.makemehack.com/2020/03/hardware-hacking-identifying-components.html 
2. UART
   * https://www.makemehack.com/2020/03/how-to-find-the-uart-interface.html 
3. JTAG
   * https://www.makemehack.com/2020/03/how-to-find-the-jtag-interface.html 
4. Get the Firmware
   * https://www.makemehack.com/2020/04/how-to-get-the-firmware.html 
