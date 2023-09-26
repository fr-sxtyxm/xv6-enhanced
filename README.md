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
intital interface : <br>
![1](https://github.com/fr-sxtyxm/xv6-enhanced/assets/142148094/330a796c-93ae-42f9-b9fa-ffd104720bb4) <br>

type command "ls" to list all the available commands : <br> 
![2](https://github.com/fr-sxtyxm/xv6-enhanced/assets/142148094/d18d997c-8539-4c2e-a83a-ecfb888d8bb3) <br>

type prsd : <br>
![3](https://github.com/fr-sxtyxm/xv6-enhanced/assets/142148094/51b97bd1-58f8-44db-8cdc-18e7a4c86e88)


 For WSL users :  
```
sudo apt update
sudo apt install qemu
sudo apt install qemu-system-x86
make
make clean
make qemu-nox 
```

