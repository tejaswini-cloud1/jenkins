What is Jenkins?

Jenkins is an  open-source automation server  used to facilitate  Continuous Integration (CI)  and  Continuous Delivery (CD)  in software development. It helps automate various stages of software delivery, enabling teams to build, test, and deploy their applications efficiently. Jenkins is written in Java and provides hundreds of plugins to support building, deploying, and automating projects.

Key Features of Jenkins
1. Open-Source: Free to use with an active and supportive community.
2. Extensibility: Supports a wide range of plugins for different tools and technologies.
3. Cross-Platform: Runs on multiple platforms, including Windows, macOS, and Linux.
4. Easy Installation: Simple to set up and configure.
5. Scalability: Can be scaled using master-slave architecture to distribute workloads.
6. Customization: Supports scripting for custom workflows using Groovy or other languages.

Step by step process of installing jenkins on AWSInstance
. AWS EC2 Instance

 ->Go to AWS Console

 ->Instances(running)
 
 ->Launch instances

![Screenshot (29)](https://github.com/user-attachments/assets/e71a3dfb-79cc-44c3-9cd7-8e5da0e4315f)

![Screenshot (30)](https://github.com/user-attachments/assets/b1917589-2192-4ad9-91d6-14d9d6f45c14)

![Screenshot (31)](https://github.com/user-attachments/assets/08ae1a4e-e392-4c27-b4f8-c0e1ea693dc5)

![image](https://github.com/user-attachments/assets/ff6e7039-3f9c-405b-b879-c584955c6496)

Go to security groups and Edit inbound rules

![image](https://github.com/user-attachments/assets/7e0e49e7-55e2-4286-b847-fadf6edfb843)

![image](https://github.com/user-attachments/assets/f0f0fda3-8c77-40e1-ae2b-f0e2eb438c4c)

![image](https://github.com/user-attachments/assets/ac6e1d5b-32f8-4025-99a9-e09771ceaeb5)

Click on save changes

![image](https://github.com/user-attachments/assets/ff6e7039-3f9c-405b-b879-c584955c6496)

Select the instance and  click on connect

![image](https://github.com/user-attachments/assets/0a90a4ab-9d1e-4574-a402-ffe8a09a0ec9)

 To install  Jenikins and java
 
 https://www.jenkins.io/doc/book/installing/linux/#debianubuntu  
![image](https://github.com/user-attachments/assets/0c99ec7f-4392-4c63-ab73-be51a3e1a898)
![image](https://github.com/user-attachments/assets/d1eee25e-f2a4-45f4-a560-b7375233f0f1)
![image](https://github.com/user-attachments/assets/b962fe0f-1295-445e-a5de-de82c7120b40)
![image](https://github.com/user-attachments/assets/bb5d881f-9521-4a8a-abfd-fde089336c99)
Here copy the publicIPs and paste in the new tab  the PublicIps no:8008 (for  Example:34.238.118.90:8080)

here 8080  port no for jenkins

![image](https://github.com/user-attachments/assets/23abfd1f-5c93-4293-b4b0-c6df5fb5ef97)

copy the permission(/var/lib/jenkins/secrets/initialAdminPassword) and paste it in teminal with (sudo cat /var/lib/jenkins/secrets/initialAdminPassword) and we will get a password copy and paste it  .

![image](https://github.com/user-attachments/assets/68e2b6dc-275e-4853-912f-b3a40e027243)

![image](https://github.com/user-attachments/assets/4f5dce2f-7574-4ba8-ad9a-8eafdf1c645b)

![image](https://github.com/user-attachments/assets/9a86f028-a4e2-4b13-a354-010d0d755cea)

![image](https://github.com/user-attachments/assets/8799626c-2f52-41e0-8920-206d2ee32a85)

![image](https://github.com/user-attachments/assets/b6638165-be10-4c57-9289-204b852ecf47)

![image](https://github.com/user-attachments/assets/4e83103a-ed92-4cac-850c-e07d42e2d6f0)

![image](https://github.com/user-attachments/assets/b3710ee5-9a63-4807-bd5d-55ed70cc2a3c)



















