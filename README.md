# bitwarden
A repo for self hosting a password manager

# Set up raspberry pi
1. Install the OS
From [here](https://www.tomshardware.com/reviews/raspberry-pi-headless-setup-how-to,6028.html)
2. How to secure the raspberry pi
From [here](https://pimylifeup.com/raspberry-pi-security/)
3. For better performance and speed 
From [here](https://www.makeuseof.com/tag/raspberry-pi-performance-tips/)
4. Install UFW
From [here](https://pimylifeup.com/raspberry-pi-ufw/)
5. Install fail2ban
From [here](https://pimylifeup.com/raspberry-pi-fail2ban/)

4. Official doc at [here](https://www.raspberrypi.com/documentation/computers/os.html)

# Log into raspberry pi
```
bitwarden (main) ✗ ssh pi@raspberrypi.local
pi@raspberrypi.local's password: 
Linux raspberrypi 5.10.63-v7+ #1459 SMP Wed Oct 6 16:41:10 BST 2021 armv7l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Sat Oct 30 12:37:18 2021

SSH is enabled and the default password for the 'pi' user has not been changed.
This is a security risk - please login as the 'pi' user and type 'passwd' to set a new password.

pi@raspberrypi:~ $ ls
Bookshelf  Documents  Music     Public     Videos
Desktop    Downloads  Pictures  Templates
pi@raspberrypi:~ $ 
```

# Install docker
From [here](https://pimylifeup.com/raspberry-pi-docker/)
```
pi@raspberrypi:~ $ docker --version
Docker version 20.10.12, build e91ed57
```
# Install bitwarden
From [here](https://pimylifeup.com/raspberry-pi-bitwarden/)

# Using Ansible