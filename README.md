# SimpleFS: A Simple FAT-Based Virtual File System

## Project Overview

**SimpleFS** is a minimal file system implemented on top of a virtual disk using a flat directory structure and a FAT (File Allocation Table)-style block management approach. It is designed as part of an operating systems course (CS351) to deepen understanding of how file systems manage files, metadata, and block allocation without relying on the host OS filesystem APIs.

## Features

- 8192 blocks (4KB each) virtual disk
-  Flat root directory (no subdirectories)
-  Supports up to 64 files
- Max file size: 16MB (4096 blocks)
- Max 32 open file descriptors
- FAT-based block allocation and chaining
- Persistent metadata and data on virtual disk
- Files cannot be deleted while open
