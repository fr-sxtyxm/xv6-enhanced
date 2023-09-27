# xv6-enhanced
Developed system calls for MIT's UNIX like Operating System Xv6.

Currently added system calls : 
1. command&emsp;&nbsp;     :&nbsp; prsd <br>
   system call&emsp; :&nbsp; getppid()<br>
   Function&emsp;&emsp;    :&nbsp; displays process-id along with parent process-id.
   
3. command&emsp;&nbsp;     :&nbsp; ps <br>
   system call&emsp; :&nbsp; sps() <br>
   Function&emsp;&emsp;    :&nbsp; displays - PID (Process ID), PPID (Parent Process ID), Process name, process state.<br>
 
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

Images : <br>
Default Interface of XV6 : <br>
![1](https://github.com/fr-sxtyxm/xv6-enhanced/assets/142148094/89a1cf7a-65d0-4157-9e7b-893447d6ab5c) <br>

type command "ls" to list all the available commands : <br> 
![2](https://github.com/fr-sxtyxm/xv6-enhanced/assets/142148094/4ece77a9-90bb-4fa3-a577-b2a33a0f0246) <br>

type prsd : <br>
![3](https://github.com/fr-sxtyxm/xv6-enhanced/assets/142148094/e65da65d-be7f-4b51-b3f2-3461e270791e)



 For WSL users :  
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make
make clean
make qemu-nox 
```

