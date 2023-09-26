# xv6-enhanced
Developed system calls for MIT's UNIX like Operating System Xv6.

Currently added system calls : 
1. command&emsp;&emsp;&nbsp;     :&nbsp; prsd <br>
   system call&emsp;&emsp; :&nbsp; getppid()<br>
   Function&emsp;&emsp;&emsp;    :&nbsp; displays process-id along with parent process-id.
   
3. command&emsp;&emsp;&nbsp;     :&nbsp; ps <br>
   system call&emsp;&emsp; :&nbsp; sps() <br>
   Function&emsp;&emsp;&emsp;    :&nbsp; displays - PID (Process ID), PPID (Parent Process ID), Process name, process state.

PS :<br> 
Will be adding more advanced system calls in future.
 
How to run ? 

1. Download the code of this repository
2. Unzip the downloaded file and open in Linux terminal
3. Run the following commands to setup Emulator :

 For Linux booted system :
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make
make clean
make qemu
```
 For WSL users :  
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make
make clean
make qemu-nox 
```

