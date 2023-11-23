# install-mail-server
install-mail-server



    
    root@master:/home/sangbinlee9# adduser sammy
    Adding user `sammy' ...
    Adding new group `sammy' (1001) ...
    Adding new user `sammy' (1001) with group `sammy' ...
    Creating home directory `/home/sammy' ...
    Copying files from `/etc/skel' ...
    New password:
    Retype new password:
    Sorry, passwords do not match.
    passwd: Authentication token manipulation error
    passwd: password unchanged
    Try again? [y/N] y
    New password:
    Retype new password:
    passwd: password updated successfully
    Changing the user information for sammy
    Enter the new value, or press ENTER for the default
            Full Name []: sangbinlee
            Room Number []: 1
            Work Phone []: 01033307962
            Home Phone []:
            Other []:
    Is the information correct? [Y/n] Y
    root@master:/home/sangbinlee9#



    
    root@master:/home/sangbinlee9# usermod -aG sudo sammy
    root@master:/home/sangbinlee9# cd /home/
    root@master:/home# ll
    total 16
    drwxr-xr-x  4 root        root        4096 Nov 24 02:26 ./
    drwxr-xr-x 23 root        root        4096 Oct  2 01:28 ../
    drwxr-x---  2 sammy       sammy       4096 Nov 24 02:26 sammy/
    drwxr-x--- 15 sangbinlee9 sangbinlee9 4096 Nov 24 02:22 sangbinlee9/
    root@master:/home#

        
        
        PS C:\Users\sangbinlee9\Desktop> ssh sammy@192.168.0.65
        The authenticity of host '192.168.0.65 (192.168.0.65)' can't be established.
        ED25519 key fingerprint is SHA256:a7aUlnQpil/sAXiJcL7BLU7Gv8Daq1G63zKv4x9n1J8.
        This key is not known by any other names
        Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
        Warning: Permanently added '192.168.0.65' (ED25519) to the list of known hosts.
        sammy@192.168.0.65's password:
        Permission denied, please try again.
        sammy@192.168.0.65's password:
        Welcome to Ubuntu 22.04.2 LTS (GNU/Linux 5.15.0-88-generic x86_64)
        
         * Documentation:  https://help.ubuntu.com
         * Management:     https://landscape.canonical.com
         * Support:        https://ubuntu.com/advantage
        
          System information as of Fri Nov 24 02:32:10 AM KST 2023
        
          System load:                      0.00537109375
          Usage of /:                       34.5% of 115.78GB
          Memory usage:                     23%
          Swap usage:                       0%
          Temperature:                      48.0 C
          Processes:                        228
          Users logged in:                  1
          IPv4 address for br-0bc2a079b319: 172.20.0.1
          IPv4 address for br-14daac2d7157: 172.18.0.1
          IPv4 address for br-3ba71cb58f83: 172.23.0.1
          IPv4 address for br-488de9945d90: 172.25.0.1
          IPv4 address for br-54a515f28da8: 172.24.0.1
          IPv4 address for br-57f4a7c588d6: 172.21.0.1
          IPv4 address for br-6e4d6813981a: 172.28.0.1
          IPv4 address for br-838d4ec11800: 172.26.0.1
          IPv4 address for br-cdf132a1a6d2: 172.19.0.1
          IPv4 address for br-d7c58f5a5c3c: 172.22.0.1
          IPv4 address for docker0:         172.17.0.1
          IPv4 address for enp0s25:         192.168.0.65
        
         * Strictly confined Kubernetes makes edge and IoT secure. Learn how MicroK8s
           just raised the bar for easy, resilient and secure K8s cluster deployment.
        
           https://ubuntu.com/engage/secure-kubernetes-at-the-edge
        
         * Introducing Expanded Security Maintenance for Applications.
           Receive updates to over 25,000 software packages with your
           Ubuntu Pro subscription. Free for personal use.
        
             https://ubuntu.com/pro
        
        Expanded Security Maintenance for Applications is not enabled.
        
        91 updates can be applied immediately.
        To see these additional updates run: apt list --upgradable
        
        Enable ESM Apps to receive additional future security updates.
        See https://ubuntu.com/esm or run: sudo pro status
        
        
        
        The programs included with the Ubuntu system are free software;
        the exact distribution terms for each program are described in the
        individual files in /usr/share/doc/*/copyright.
        
        Ubuntu comes with ABSOLUTELY NO WARRANTY, to the extent permitted by
        applicable law.
        
        To run a command as administrator (user "root"), use "sudo <command>".
        See "man sudo_root" for details.
        
        sammy@master:~$





![image](https://github.com/sangbinlee/install-mail-server/assets/4024414/f6a521ac-0b74-4855-a925-e3d6be1e6b3f)
