# xv6-enhanced
Developed system calls for MIT's Unix like operating System Xv6.

Currently added system calls : 
1. system call : getppid()
   command     : prsd
   Function    : displays process-id along with parent process-id.
   
2. system call : sps
   command     : ps 
   Function    : displays - PID {Process ID}, PPID{Parent Process ID}, Process name, process state.

PS : Will be adding more advanced system calls in future.
 
How to run ? 

1. Download the code of this repository
2. Unzip the downloaded file and open in Linux terminal
3. Run the following commands to setup Emulator :

a. For Linux booted system :
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make clean
make qemu
```
b. For WSL users :  
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make clean
make qemu-nox 
```

