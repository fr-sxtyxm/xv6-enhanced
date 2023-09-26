# xv6-enhanced
Developed system calls for MIT's Unix like operating System Xv6.

Currently added system calls : 
1. system call named getppid() and a command named "prsd" which can display process-id along with parent process-id using the help of getpid()
2. system call named sps(system processes), command named ps that can display the : PID {Process ID}, PPID, Process name {Parent Process ID}, process state.

PS : Will be adding more advanced system call in future.
 
How to run ? 

1. Download the Code of this repository
2. Unzip the downloaded file and open in Linux terminal
3. Run the following commands to setup Emulator :
For Linux booted system :
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make clean
make qemu
```
For WSL users :  
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make clean
make qemu-nox 
```

