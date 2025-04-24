## Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## Reg no:212223100061
## Name: V.Sai Sruthi
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
## Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

## Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

## Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/75d39dc8-5472-461d-aa82-3e1104a9e0a2)
![image](https://github.com/user-attachments/assets/a44fc512-97c6-4f3c-b6e2-3134b88df097)
![image](https://github.com/user-attachments/assets/50064674-2dd3-4d7b-8632-3d8dc252f907)
![image](https://github.com/user-attachments/assets/9f27f049-bc0a-45ce-819c-7a07b7dc3fcf)
![Uploading image.png…]()

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
