# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
### Name: Samakash R S
### Reg NO: 212223230182

## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage

```
lsblk
```
````
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
````
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
![img1](https://github.com/user-attachments/assets/903710dc-b1c8-4abe-89f9-5c85ebe7cd1d)


![img2](https://github.com/user-attachments/assets/9c0e2729-0fe2-4ff6-9ce6-39a885c50b75)


![img3](https://github.com/user-attachments/assets/b853930c-a5db-4ce5-8826-a4c169b3c473)


![img4](https://github.com/user-attachments/assets/ed046efa-6dd3-4f74-9c2a-d99590bec231)


![img5](https://github.com/user-attachments/assets/b56d6426-f6f2-4f48-9865-40b6274f6e5e)




## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

