# FSUtils - FAT16 and EXT2 File System Reader

Academic project developed as part of the Advanced Operating Systems subject at La Salle Campus Barcelona.

FSUtils is a tool written in C to analyze FAT16 and EXT2 file system images without mounting them in the operating system.

## Project objective

The main objective of this project was to understand how file systems store information internally and how their structures can be read directly from a disk image.

The tool works at a low level, reading raw data from the image and interpreting file system structures such as metadata, directories, blocks, clusters and inodes.

## Features

- Detection of FAT16 and EXT2 file system images
- Reading file system metadata
- Directory structure exploration
- File content access from disk images
- Low-level reading using system calls
- Analysis of internal file system structures

## FAT16 concepts

- Boot sector
- FAT table
- Root directory
- Clusters
- Cluster chain reading
- Directory entries

## EXT2 concepts

- Superblock
- Group descriptors
- Inodes
- Blocks
- Root inode
- Directory traversal

## System calls used

- open
- read
- lseek
- close

## Technologies

- C
- Linux
- FAT16
- EXT2
- File systems
- Disk images
- Systems programming
- Terminal

## What I learned

This project helped me understand how file systems work internally and how information is stored and accessed in FAT16 and EXT2.

It also allowed me to improve my C programming skills, work with binary structures and practice low-level reading of disk images in Linux environments.
