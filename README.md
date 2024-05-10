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



![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/755d4e81-2e4a-4eda-8dd5-b281da49a946)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/7e3635ff-8478-46c8-9ee9-70b0d2c5331c)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/3deda3ce-f26d-440b-b58d-aa51fda8d191)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/0cbe45d3-c9ef-477b-ad20-db89e011f0b7)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/e7d5ecc8-92b9-4b93-b771-038d0dbddc97)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/eb6d07ee-c060-40ae-bb28-290481a4c414)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/69532c37-b9c5-4b13-bb4b-145a53dd31da)

In windows IE, on giving the url http://192.168.43.135, the fake Google page is displayed. The victim can enter the username and password:

![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/5784c318-efe0-4714-9825-9bc18aa24311)



SET logs the information regarding the Google credentials:
![image](https://github.com/kavisree86/creating-a-backdoor-with-SET/assets/145759687/1832855e-6819-4e03-881a-6495c4a6a1b5)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
