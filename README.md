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
```
ATCHAYA.K
212223220011
```
## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:


![image](https://github.com/user-attachments/assets/32f220ea-2c50-40a8-8301-dcaf213b7616)


It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/ebf3e71a-1827-4c3f-9460-eeaf668f3157)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/29fb22be-e09d-4019-8556-e7d41d763e10)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/17b46423-9805-46db-96c4-4d1206783f2b)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/5d88cb65-db14-452a-97a6-d3f26d8ad630)


It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/ac4e1eee-6fc8-47c6-9cba-94c10f5e2518)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/bedbfe95-08eb-493b-9eed-e2dceaa668ab)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password


![WhatsApp Image 2025-04-25 at 17 02 38_c3f2b042](https://github.com/user-attachments/assets/60ef6053-2134-487f-9452-7e494d14c1a3)




SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/170b7b2c-2890-4574-8912-27d8ba4258b2)


SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/8ffc0fc3-f76b-426c-b2c7-d2c728182674)











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
