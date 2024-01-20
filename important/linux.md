### Introduction
- [cpu.land](https://cpu.land/the-basics)
### Full tutorial :
- [Bash Scripting Tutorial – Linux Shell Script and Command Line for Beginners](https://www.youtube.com/watch?v=sWbUDq4S6Y8) [Blog](https://www.freecodecamp.org/news/bash-scripting-tutorial-linux-shell-script-and-command-line-for-beginners/)
- [How to Configure and Operate Linux Servers - Full Course](https://www.youtube.com/watch?v=WMy3OzvBWc0)[Blog](https://www.freecodecamp.org/news/linux-server-course-system-configuration-and-operation/)
- [Linux Commands for Beginners](https://www.youtube.com/playlist?list=PLT98CRl2KxKHaKA9-4_I38sLzK134p4GJ)
- [Linux Crash Course](https://www.youtube.com/playlist?list=PLT98CRl2KxKHKd_tH3ssq0HPrThx2hESW)
- [Complete Linux Training Course to Get Your Dream IT Job 2023](https://udemy.com/course/complete-linux-training-course-to-get-your-dream-it-job/)
- [Mastering Linux: The Comprehensive Guide](https://udemy.com/course/mastering-linux/)

#### Linux mindset 
- [Why Linux Rules the Data Center](https://www.youtube.com/watch?v=xDLBpe5gbUg)
- [Why so many distros? The Weird History of Linux](https://www.youtube.com/watch?v=ShcR4Zfc6Dw)
- [The Secret OS That Really Runs The World](https://www.youtube.com/watch?v=5Ll0G5yKJK0)
- [The Making of GNU: The World's First Open-Source Software](https://www.youtube.com/watch?v=sQDvkd2wtxU)
- [The Making of Linux: The World's First Open-Source Operating System](https://www.youtube.com/watch?v=E0Q9KnYSVLc)
- [Linux: The Origin Story](https://www.youtube.com/watch?v=s7u7jBwIocU)
- [The mind behind Linux | Linus Torvalds | TED](https://www.youtube.com/watch?v=o8NPllzkFhE)
- [Why Linux Is Better For Programming](https://www.youtube.com/watch?v=otDOHt_Jges)
- [Why Linux is better for (most) developers!](https://www.youtube.com/watch?v=E_C3pgc1Iho)
- [Why I Code on Linux Instead of Windows](https://www.youtube.com/watch?v=HrYtwz0Xe2Q)
- [10 ways Linux is just better!](https://www.youtube.com/watch?v=mAFMJ1LnQu8)
- [10 Things I Wish I Knew When I First Started With Linux](https://www.youtube.com/watch?v=HIJ6LixbcAY)
- [I Forced Myself to Use Linux For 30 Days (Linux Challenge)](https://www.youtube.com/watch?v=moYwK0YMFjQ)

#### Linux filesystem
- [Linux Directories Explained in 100 Seconds](https://www.youtube.com/watch?v=42iQKuQodW4)
- [Linux File System/Structure Explained!](https://www.youtube.com/watch?v=HbgzrKJvDRw)


#### Youtube tutorials
- [How Does Linux Boot Process Work?](https://www.youtube.com/watch?v=XpFsMB6FoOs)
- [Kali Linux on Windows in 5min (WSL 2 GUI)](https://www.youtube.com/watch?v=AfVH54edAHU)
- [you need to learn Virtual Machines RIGHT NOW!! (Kali Linux VM, Ubuntu, Windows)](https://www.youtube.com/watch?v=wX75Z-4MEoM)
- [Virtual Machines Pt. 2 (Proxmox install w/ Kali Linux)](https://www.youtube.com/watch?v=_u8qTN3cCnQ)
- [The Linux Tier List](https://www.youtube.com/watch?v=KyADkmRVe0U)
- [Ranking Linux Distributions for 2023: not your average tier list!](https://www.youtube.com/watch?v=d7-EhGIeGUs)
- [Switching to Linux](https://www.youtube.com/watch?v=tB_oSFLQXVo)
- [Choosing the Right Linux Distro](https://www.youtube.com/watch?v=dL05DoJ0qsQ)

#### Linux for hacking
- [Linux for Hackers (and everyone) // FREE Course for Beginners](https://www.youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL)

### Command to start the wsl 2 from windows
```
wsl --set-default-version 2
sudo apt-get update && sudo apt-get upgrade -y
sudo apt install xrdp -y
sudo service xrdp start
ip add
```


### Setup ubuntu server in VM
- [Ubuntu Server for ARM](https://ubuntu.com/download/server/arm)
- **Setup VM**
```
sudo apt update && sudo apt upgrade -y
sudo apt install ubuntu-desktop
sudo reboot

# for directory sharing between host os and guest os (127.0.0.1:9843)
sudo apt install spice-vdagent spice-webdavd -y 
# https://docs.getutm.app/guest-support/linux/
sudo mkdir -p /media/shared
sudo mount -t 9p -o trans=virtio share /media/shared -oversion=9p2000.L
# You can also modify `/etc/fstab` and add the following line to automatically mount the share on startup
share	/media/shared	9p	trans=virtio,version=9p2000.L,rw,_netdev,nofail	0	0
sudo chown -R $USER /media/shared

```


#### File system internal
- [Explaining File Systems: NTFS, exFAT, FAT32, ext4 & More](https://www.youtube.com/watch?v=_h30HBYxtws)
- [The "New" File System in Windows: ReFS](https://www.youtube.com/watch?v=lxrF9FzxeTU)
- [FAT32 vs exFAT vs NTFS - Windows File Systems](https://www.youtube.com/watch?v=bYjQakUxeVY)