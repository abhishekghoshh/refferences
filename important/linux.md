### udemy course :
- [Complete Linux Training Course to Get Your Dream IT Job 2023](https://udemy.com/course/complete-linux-training-course-to-get-your-dream-it-job/)

### Youtube tutorials :
- [Kali Linux on Windows in 5min (WSL 2 GUI)](https://www.youtube.com/watch?v=AfVH54edAHU)
- [you need to learn Virtual Machines RIGHT NOW!! (Kali Linux VM, Ubuntu, Windows)](https://www.youtube.com/watch?v=wX75Z-4MEoM)
- [Virtual Machines Pt. 2 (Proxmox install w/ Kali Linux)](https://www.youtube.com/watch?v=_u8qTN3cCnQ)
- [The Linux Tier List](https://www.youtube.com/watch?v=KyADkmRVe0U)
- [Ranking Linux Distributions for 2023: not your average tier list!](https://www.youtube.com/watch?v=d7-EhGIeGUs)
- [Switching to Linux](https://www.youtube.com/watch?v=tB_oSFLQXVo)
- [Choosing the Right Linux Distro](https://www.youtube.com/watch?v=dL05DoJ0qsQ)


### Command to start the wsl 2 from windows
```
wsl --set-default-version 2
sudo apt-get update && sudo apt-get upgrade -y
sudo apt install xrdp -y
sudo service xrdp start
ip add
```


#### Others
- [cpu.land](https://cpu.land/the-basics)

### Setup ubuntu server in VM
- [Ubuntu Server for ARM](https://ubuntu.com/download/server/arm)
- Setup VM
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