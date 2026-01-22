### Project Title

### Disk-Management-Lab-Create-a-New-Partition-in-Windows-10

Hands-on IT Support Lab – Demonstrating how to manage disks in Windows 10. This project covers creating a new partition by shrinking an existing volume, assigning a drive letter ** H **, and formatting it with NTFS.

### 🎯 Purpose

This demonstrates how to manage disks in Windows 10 by:

Shrinking an existing partition

Creating a new partition

Assigning a drive letter

Formatting it with NTFS

### 🔹 Steps

1) Open Disk Management

Press Windows key (or Right-click Start) → choose Disk Management

Or press Windows + R, type diskmgmt.msc, press Enter

📸 Screenshot: DiskMgmt_Open.png

2) Shrink a Volume to Make Unallocated Space

In Disk Management, find the main partition (E:) → Right-click → Shrink Volume...

Enter shrink size (e.g., 20000 MB = 20 GB) → Click Shrink

You will see a black block labelled Unallocated

📸 Screenshot: Disk_Shrunk.png

3) Create a New Partition (New Simple Volume)

Right-click Unallocated area → New Simple Volume...

Wizard: Next → Next

Assign drive letter: choose H : (or next free letter) → Next

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

Warning: Deleting removes all data from that partition


### ✅ Outcome

Successfully created a new partition (H:) from free space

Assigned a drive letter and formatted with NTFS

Verified new drive in File Explorer

📌 This skill is important for IT Support roles when setting up user storage, backups, and troubleshooting disk issues.
