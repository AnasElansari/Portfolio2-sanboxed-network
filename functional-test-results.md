### 1.	 Desktop VM Ping to Gateway VM on Subnet 1 (192.168.5.1):
   
•	The Desktop VM pings the Gateway VM’s IP on Subnet 1.

•	This verifies that the Desktop VM can communicate with the Gateway on its own subnet, confirming internal connectivity within Subnet 1.

Screenshot:

![image](https://github.com/user-attachments/assets/2d04c8f1-fec6-42e9-9adf-0cfda34173c3)

### 2.	Desktop VM Ping to Application Server VM

•	The Desktop VM pings the Application Server VM’s IP on Subnet 2.

•	This confirms connectivity between the Desktop VM and Application Server across subnets via the Gateway.

Screenshot:

![image](https://github.com/user-attachments/assets/2c49b906-c7ea-4ab5-bd44-2aa06259a4d2)

### 3.	Application Server VM Ping to Gateway VM on Subnet 2
   
•	The Application Server VM pings the Gateway VM’s IP on Subnet 2.

•	This shows that the Application Server can communicate with the Gateway on its own subnet, confirming internal network connectivity.

Screenshot:

![image](https://github.com/user-attachments/assets/abffe224-4ce7-4337-98dd-a547fd34bf46)

### 4.	Application Server VM Ping to Desktop VM

•	The Application Server VM successfully pings the Desktop VM’s IP on Subnet 1 (192.168.5.10).

•	This verifies that cross-subnet communication through the Gateway is functional.

Screenshot:

![image](https://github.com/user-attachments/assets/d2c4f878-593a-4ccb-88ce-d9197a656a37)


### 5.	Application Server VM Ping to the internet
   
•	This shows the Application Server VM successfully pinging 8.8.8.8, indicating it also has internet access through the Gateway VM.


Screenshot:

![image](https://github.com/user-attachments/assets/cc4851fb-aa42-49fb-824c-a5e5ad020a6b)

### 6.	Desktop VM Ping to the internet
   
•	This screenshot shows the Desktop VM successfully pinging the external IP address 8.8.8.8 (Google DNS).

•	It confirms that the Desktop VM has internet access via the Gateway VM.

Screenshot:
 
![image](https://github.com/user-attachments/assets/e96d69f8-5d85-43b8-bc78-6bc67c262329)

### 7.	Additionally Desktop VM Accessing Application Server Web Application
   
•	The Desktop VM accesses a web application hosted on the Application Server (IP 192.168.105.10).

•	This confirms that the Desktop VM can reach and interact with services hosted on the Application Server over Subnet 2.

Screenshot:
 
![image](https://github.com/user-attachments/assets/4ec453ae-8915-48db-84bd-a4f8abd0f6e0)
