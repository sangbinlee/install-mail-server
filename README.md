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


![image](https://github.com/sangbinlee/install-mail-server/assets/4024414/fde44442-9e02-42dd-8cdd-bc0079cc2df8)











![image](https://github.com/sangbinlee/install-mail-server/assets/4024414/f6a521ac-0b74-4855-a925-e3d6be1e6b3f)
