# Rufus 4.16 BETA 2

Fast bootable USB media writer (`rufus.ie`) supporting GRUB 2.16, USB 3.2/4.1 speed detection, AMI NTFS UEFI validation workaround, and classic right-click menu restoration.

<img width="600" height="600" alt="images1" src="https://github.com/user-attachments/assets/39c9629a-bd1e-4b93-93b7-fbd18b5d5b40" />
<img width="1060" height="790" alt="images2" src="https://github.com/user-attachments/assets/565a4daa-0533-4bee-b928-3aae522a4b42" />
<img width="1060" height="790" alt="images3" src="https://github.com/user-attachments/assets/7fe61403-2a10-4897-88b5-527216b0f887" />

## Supported Partition & Boot Targets
- **GPT + UEFI (non-CSM)**: Standard modern firmware layout with UEFI:NTFS >4GB ISO support.
- **MBR + BIOS/UEFI-CSM**: Legacy hardware compatibility for older motherboards.
- **Unattended Flags**: Optional TPM, Secure Boot, and local account setup toggles.

<img width="1081" height="764" alt="images5" src="https://github.com/user-attachments/assets/7143c2a2-f69e-466e-ad3f-11a65c7cf02e" />
<img width="529" height="600" alt="images4" src="https://github.com/user-attachments/assets/d1eae7c5-71e4-4762-a718-d65de628cff2" />
<img width="1018" height="1234" alt="images6" src="https://github.com/user-attachments/assets/ac353cd9-9862-4a84-b21f-6554357217a8" />

## Verify ISO Checksum Before Flashing
```powershell
Get-FileHash -Algorithm SHA256 .\installer.iso
```

Plug in your target USB stick, confirm the drive letter so no secondary disk is wiped, select the ISO image, and start the write pass.
<img width="504" height="731" alt="images7" src="https://github.com/user-attachments/assets/4813d752-5764-4cfb-81a7-f4ee4e793a01" />
<img width="404" height="525" alt="images8" src="https://github.com/user-attachments/assets/badf75bd-3e2d-4850-8d49-2bfdc55aee9a" />
<img width="602" height="509" alt="images9" src="https://github.com/user-attachments/assets/abc80ae7-0c53-4c6a-b83c-c05c1c87691e" />
<img width="739" height="415" alt="images10" src="https://github.com/user-attachments/assets/b3b27d57-b397-4825-a29c-94d86141e621" />
