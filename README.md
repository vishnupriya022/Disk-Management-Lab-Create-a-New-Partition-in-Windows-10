Project Title

# Disk-Management-Lab-Create-a-New-Partition-in-Windows-10
Hands-on IT Support Lab – Demonstrating how to manage disks in Windows 10. This project covers creating a new partition by shrinking an existing volume, assigning a drive letter, and formatting it with NTFS.

🎯 Purpose

This lab demonstrates how to manage disks in Windows 10 by:

Shrinking an existing partition

Creating a new partition

Assigning a drive letter

Formatting it with NTFS

👉 These are core IT Support skills used for storage management and troubleshooting.

🔹 Steps
1) Open Disk Management

Press Windows key (or Right-click Start) → choose Disk Management

Or press Windows + R, type diskmgmt.msc, press Enter
📸 Screenshot: DiskMgmt_Open.png

2) Shrink a Volume to Make Unallocated Space

In Disk Management, find the main partition (C:) → Right-click → Shrink Volume...

Enter shrink size (e.g., 20000 MB = 20 GB) → Click Shrink

You will see a black block labelled Unallocated
📸 Screenshot: Disk_Shrunk.png

3) Create a New Partition (New Simple Volume)

Right-click Unallocated area → New Simple Volume...

Wizard: Next → Next

Assign drive letter: choose D: (or next free letter) → Next

Format partition:

File system: NTFS

Allocation unit: Default

Volume label: e.g., Data

Check Quick Format → Finish
📸 Screenshot: Disk_NewVolumeWizard.png
📸 Screenshot: Disk_AssignedDrive.png


4) Verify in File Explorer

Open This PC → confirm the new D: drive is visible
📸 Screenshot: Disk_Verify_ThisPC.png

5) (Optional) Remove the Partition

Right-click new volume (D:) → Delete Volume... → OK

Space becomes Unallocated again
⚠️ Warning: Deleting removes all data from that partition


🔹 Why NTFS?

Default Windows file system

Supports large files (>4GB)

Provides security permissions (Read/Write/Full Control)

More reliable and secure

👉 Formatting with NTFS makes the new partition usable for storing files safely.


✅ Outcome

Successfully created a new partition (D:) from free space

Assigned a drive letter and formatted with NTFS

Verified new drive in File Explorer

📌 This skill is important for IT Support roles when setting up user storage, backups, and troubleshooting disk issues.
