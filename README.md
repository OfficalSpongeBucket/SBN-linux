## Sponge Bucket Node Linux Emulator
This project is a minimal Linux terminal emulator implemented in C#. It simulates core Linux command-line functionality within a .NET console application. The emulator is designed for educational use, prototyping, and CLI-based system simulation.

## SBN plan

This is the free-tier plan so this is not hosted in the cloud

## Features
- Command-line interface with Linux-style prompt: SpongeBucketNode@linux:~$
- Core command support:
- ls, cd, pwd, mkdir, rm, touch, cat, whoami, help
- Single-file implementation in Program.cs
- Modular command routing using a dictionary
- Easily extensible with additional commands

## Requirements
- Visual Studio 2022 or later
- .NET 6.0 SDK or newer

## Setup Instructions
- Clone or download the repository.
- Open the solution in Visual Studio.
- Build and run the project.
The emulator will launch in the console window.

## Usage
Once running, the emulator accepts Linux-style commands. Examples:
SpongeBucketNode@linux:~$ mkdir test
SpongeBucketNode@linux:~$ cd test
SpongeBucketNode@linux:~$ touch file.txt
SpongeBucketNode@linux:~$ ls
SpongeBucketNode@linux:~$ cat file.txt
SpongeBucketNode@linux:~$ whoami
SpongeBucketNode@linux:~$ help


## To exit the emulator:
SpongeBucketNode@linux:~$ exit

## License
This project is provided for educational and non-commercial use. No license terms are currently specified.


