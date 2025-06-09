🚀 NashOS: A Simple Assembly Kernel
Welcome to NashOS!

NashOS is a small, 16-bit operating system kernel written entirely in Assembly language. Inspired by the simplicity and educational value of MikeOS, NashOS aims to provide a clear, hands-on understanding of low-level system operations and basic hardware interaction.
✨ Features

    Hardware Information Display: Detects and displays:

        Base, Extended, and Total Memory

        CPU Vendor and Brand String

        Number of Hard Drives

        Mouse Status

        Number of Serial Ports and Base I/O address for Serial Port 1

        Key CPU Features (FPU, MMX, SSE, SSE2)

    Basic Command-Line Interface (CLI):

        info: Shows detailed hardware information.

        help: Displays a list of available commands.

        clear: Clears the console screen.
        

🛠️ Built With

    Assembly Language (NASM Syntax): The entire kernel is crafted using NASM syntax for 16-bit real mode.

🎯 Project Inspiration & Thanks

This project is heavily inspired by MikeOS (by Mike McLaren and the MikeOS Developers). A huge thank you to the MikeOS project for its excellent educational resources and foundational ideas, which have been invaluable in developing NashOS.
💻 Getting Started

To build and run NashOS, you will typically need:

    NASM Assembler: To assemble the .asm source code into a flat binary.

    QEMU (or a similar emulator): To run the resulting bootable image.

Building and Running Instructions:

sudo ./build-linux.sh && sudo ./test-linux.sh

📸 Screenshots

Here's a glimpse of NashOS running in an emulator:

NashOS home
![NashOS home](https://github.com/user-attachments/assets/14797702-1f9f-42ac-be7e-9dc499d27c42)

NashOS help
![NashOS help](https://github.com/user-attachments/assets/94f76b5f-5b51-4b06-9ae7-bb27b36986de)

NashOS info
![NashOS info](https://github.com/user-attachments/assets/a4462847-233c-4f19-81a8-cae2571ba5b4)


Enjoy exploring the fundamentals of operating systems!
