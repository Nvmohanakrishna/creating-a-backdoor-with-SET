# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

<img width="755" alt="image" src="https://github.com/user-attachments/assets/17e1686e-8774-4db4-8fb6-7a0575a01321">


 It displays the following menu and select 2 for Website Attack Vectors:

<img width="783" alt="image" src="https://github.com/user-attachments/assets/46bc3d93-7478-437b-bd43-68dd42480a5e">


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

<img width="854" alt="image" src="https://github.com/user-attachments/assets/ae678ddd-f360-43dc-aff2-e8339244dc47">


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

<img width="688" alt="image" src="https://github.com/user-attachments/assets/bbe6cea4-c634-4619-aebf-45e5c249c8e1">

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

<img width="488" alt="image" src="https://github.com/user-attachments/assets/d3d887e9-66ef-4195-8fb7-3858059edace">

It shows the following screen in which the option Google can be selected:

<img width="560" alt="image" src="https://github.com/user-attachments/assets/bf850c3b-e26b-4823-b695-9f1d371a1b00">

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

<img width="742" alt="image" src="https://github.com/user-attachments/assets/3d5a4b62-f5d4-433c-a914-5dd27f215ed3">

In windows IE, on giving the url http://192.168.43.135, the fake Google page is displayed. The victim can enter the username and password:

<img width="416" alt="image" src="https://github.com/user-attachments/assets/f74e550c-4ec8-4061-8152-5097aa8fd9b4">

SET logs the information regarding the Google credentials:

![Uploading image.png…]()




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
