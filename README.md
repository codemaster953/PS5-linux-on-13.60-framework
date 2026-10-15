# PS5-linux-on-13.60-framework

PS5 Linux Installation on Firmware 13.60
Requirements
1. A PS5 running compatible jailbroken firmware 13.60.
2. A USB drive with at least 64 GB of storage.
3. Linux boot image file (.img).
4. Compatible 1360 linux.elf payload.
5. balenaEtcher software.
6. Payload Manager on the PS5.
Installation Instructions
Step 1: Prepare Your PS5
Make sure your PS5 is jailbroken and running firmware 13.60. Confirm that your jailbreak and payload tools are working correctly.
Step 2: Download the Required Files
Download the Linux boot image (.img) and the compatible 1360 linux.elf payload from the project's GitHub repository or its official download links.
Step 3: Install balenaEtcher
Download and install balenaEtcher from the official website:
https://etcher.balena.io/
Step 4: Flash the Linux Image to USB
1. Connect your 64 GB or larger USB drive to your Windows PC.
2. Open balenaEtcher.
3. Click Flash from file and select the Linux .img file.
4. Click Select target and choose your USB drive.
5. Verify that you selected the correct drive.
6. Click Flash and wait for the process to finish.
7. Safely eject the USB drive after flashing is complete.
Warning: Flashing erases the existing contents of the selected USB drive.
Step 5: Run the Linux ELF Payload
1. Turn on your PS5 and open Payload Manager.
2. Upload the compatible 1360 linux.elf file.
3. Run the payload according to the project's instructions.
4. Wait for the payload to initialize.
Step 6: Boot Linux
Connect the prepared USB drive to the PS5 using the connection method specified by the project. Follow the repository's instructions to boot Linux.
Step 7: Verify the Installation
If the payload, Linux image, and boot procedure are compatible, Linux should start on your PS5 display.
Important Notes
- Make sure the ELF payload and Linux image are compatible with PS5 firmware 13.60.
- A successfully flashed USB drive does not guarantee that Linux will boot.
- Do not interrupt the console while the payload is initializing.
- Back up important data before proceeding.
- Follow the project's official instructions for any additional boot settings or hardware requirements.
