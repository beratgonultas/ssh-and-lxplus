Here is simple guide for those who are having a hard time with installing ROOT. This is basically the refined version of Enes Gönültaş' guideline for me when I was trying to install ROOT for the first time for Phys442.

1)Choose the release you want to install here. If you don't have any special preference, then you are advised to choose the latest.
2)Choose your Ubuntu version and download.
3)Extract the file.
4)There must be a file called .bashrc in /home/<yourusername>
5)Check it with typing ``la`` in terminal. 
6)Use ``gedit .bashrc`` to open it.
7)At the end of this file, create a new line and write ``. <pathname>/root/bin/thisroot.sh`` 
8)Save the file.
9)Close terminal. Reopen it. Type ``root``