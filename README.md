# Creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

### DEVELOPED BY : M.CHANDRU
### REGISTER NO : 212222230026

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/b1be6e3e-8721-4e81-8815-6b9f52eb568c)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/75dc75ee-d92d-4348-9352-18866e9272e3)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/bd656f09-7131-4009-baf8-9496bc2cd264)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/c58b13b1-64b3-4a93-bcd1-8189ea91fa29)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/45a11075-c837-4442-bdfb-53d5ab171e6e)

It shows the following screen in which the option Google can be selected: 

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/c8637903-4ea3-480a-9f51-624dbe0885fd)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/e681b1c5-cd69-4a4f-9098-c96865b868ee)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/2d08796d-1274-40cd-98e4-b7b68d680c53)

SET logs the information regarding the Google credentials: 

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/2d67b215-1175-443e-8779-d8780c9e6cd7)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/chandrumathiyazhagan/creating-a-backdoor-with-SET/assets/119393023/ed57a8a8-a769-4f01-9f9b-22858135071d)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
