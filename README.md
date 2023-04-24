# Autoscaling-an-Application-on-AWS
Autoscaling an Application on AWS https://www.youtube.com/watch?v=JubPv_UkBDg

Just follow the steps given in the video. Do let me know in comments if you face any problem
============================
Subscribe my channel -   

 / @devopstutorial  
==========================
Below Topics I will cover in this Video 

- Creation of VPC in AWS Cloud
- Creation of Launch Template 
- Creation of Autoscaling group 
- Creation of RDS Database 
- Creation of EC2 Instance 

![image](https://user-images.githubusercontent.com/99332618/233861905-9a27cbc6-eb8e-498c-b8fc-104e69128c60.png)
![image](https://user-images.githubusercontent.com/99332618/233861950-64949d12-d021-41f4-b800-aa0a108fd384.png)
![image](https://user-images.githubusercontent.com/99332618/233862834-1cb37b88-169d-4b24-8eb0-6d885dd0479b.png)
![image](https://user-images.githubusercontent.com/99332618/233862883-17d1f4f9-60f1-4078-a35b-bd18236c7f48.png)
![image](https://user-images.githubusercontent.com/99332618/233862998-b715d632-bbe6-4e30-b650-674868b60fb6.png)
![image](https://user-images.githubusercontent.com/99332618/233864290-2a02199a-e806-4ba6-9709-ae0b83a2e6f9.png)
![image](https://user-images.githubusercontent.com/99332618/233864332-42823069-aa28-4bb5-a75c-e686d4595a22.png)
![image](https://user-images.githubusercontent.com/99332618/233864388-bc2bd659-8ed8-43f3-aaf7-5d10b067bd8b.png)
![image](https://user-images.githubusercontent.com/99332618/233864441-dc653b0a-cb6f-43ca-9d2e-3eadda9a055a.png)
![image](https://user-images.githubusercontent.com/99332618/233864658-6896d51c-b139-406d-9b2a-d6c7e66b297a.png)
![image](https://user-images.githubusercontent.com/99332618/233864701-ed7be1ed-8d6a-4ef8-b013-26dbadd3f959.png)
![image](https://user-images.githubusercontent.com/99332618/233864745-682f8650-ee56-42a2-9000-09a2528da22c.png)
![image](https://user-images.githubusercontent.com/99332618/233865061-fb160513-8ba0-464f-b89c-a47ff2976a7f.png)
![image](https://user-images.githubusercontent.com/99332618/233865244-82af0a8c-a763-4f7a-bcf0-9f774900e1e7.png)
![image](https://user-images.githubusercontent.com/99332618/233865379-d52bc770-9521-4fd1-9312-62f6a81405de.png)
![image](https://user-images.githubusercontent.com/99332618/233865799-ecbee919-cc6c-42d2-92e4-83c0ad87fde8.png)
![image](https://user-images.githubusercontent.com/99332618/233865876-b835538c-bfe9-4178-8efb-204da08c5b16.png)
![image](https://user-images.githubusercontent.com/99332618/233865912-0974fa6c-bdb0-411a-95d2-da093eeac7d4.png)
![image](https://user-images.githubusercontent.com/99332618/233865946-27d2ed11-3f0f-4519-b3d2-4ce944700f42.png)
![image](https://user-images.githubusercontent.com/99332618/233866025-62beda01-4d06-4837-a027-0556b605ace0.png)
![image](https://user-images.githubusercontent.com/99332618/233866114-90d11298-1007-4c96-a7ee-9a156b5efbbd.png)
![image](https://user-images.githubusercontent.com/99332618/233866176-59277bbf-4379-4acf-9133-beeb7f787f21.png)
![image](https://user-images.githubusercontent.com/99332618/233866273-47ba6d46-2f65-49e6-93f9-2008db2ffdc4.png)
![image](https://user-images.githubusercontent.com/99332618/233866299-dd134182-7685-4cde-97c3-d3d12d46d49a.png)
![image](https://user-images.githubusercontent.com/99332618/233866342-fb3de414-8be8-42e2-be70-c33ef5623270.png)
![image](https://user-images.githubusercontent.com/99332618/233866541-5bbc2c7b-aee0-4858-b98c-ecc23a4d58b8.png)
![image](https://user-images.githubusercontent.com/99332618/233866630-ad2643ed-8658-4c87-9c3c-8a4b86bfea28.png)
![image](https://user-images.githubusercontent.com/99332618/233948076-9b988b3e-029c-44bc-b2ef-70f0db0be2a1.png)
![image](https://user-images.githubusercontent.com/99332618/233948232-5eca3c6b-3c95-4bbf-8f35-282e2ccb603e.png)

Note: Enable "Auto-assign IP settings" for public subnets only
![image](https://user-images.githubusercontent.com/99332618/233948342-8ca43100-82b8-4337-996e-5c6e070fb034.png)

CONT'D
![image](https://user-images.githubusercontent.com/99332618/233948925-74c1ef11-49ce-4372-b641-0c7c3de2fac3.png)
![image](https://user-images.githubusercontent.com/99332618/233950544-89ec8c38-e920-45bf-bca1-4d10e01e35b4.png)
![image](https://user-images.githubusercontent.com/99332618/233950610-7dc28520-f306-4d12-9104-689770628a3d.png)
![image](https://user-images.githubusercontent.com/99332618/233950695-b8914f54-e994-4207-b175-7aa2c0019bc2.png)
![image](https://user-images.githubusercontent.com/99332618/233950787-af0a9beb-3b1b-4f25-b2ce-4b025c9b9f5f.png)
![image](https://user-images.githubusercontent.com/99332618/233950860-283f80ca-a0fc-4393-9c52-93d544ab6e79.png)
![image](https://user-images.githubusercontent.com/99332618/233950999-c87b8d7f-7faf-4fe0-a99a-7132c5b3b49a.png)

#!/bin/bash
yum update -y
yum install -y httpd
systemctl start httpd
systemctl enable https
echo "<html><body><h1>Vicky Website - Demo for 3Tier Application</h1></body></html>" >/var/www/html/index.html

![image](https://user-images.githubusercontent.com/99332618/233951289-ed1215e4-7536-46e1-9308-3f1e7f7e10db.png)
![image](https://user-images.githubusercontent.com/99332618/233951779-ac4bff2d-e8f4-4bf4-9451-d1438d30878b.png)
![image](https://user-images.githubusercontent.com/99332618/233951836-10c9bff7-c792-45da-bd7b-8eade0d3c34c.png)
![image](https://user-images.githubusercontent.com/99332618/233952269-1c33d895-82f7-4ef0-aa32-0b3f9c9cb43c.png)
![image](https://user-images.githubusercontent.com/99332618/233952424-15ecea6a-b8af-441a-96b3-527ef021b3b5.png)

Do not make any changes on the load blancer page and Click "Next"

Configure group size and scaling policies - optional (Make no changes too) and clck "Next"

![image](https://user-images.githubusercontent.com/99332618/233953537-27f5446b-1b06-4304-98ca-8a56575ff7f2.png)
![image](https://user-images.githubusercontent.com/99332618/233953627-f25a7fdb-76f0-4060-92fe-6096f48473ce.png)
![image](https://user-images.githubusercontent.com/99332618/233954010-9c1a720b-1861-4714-9cdb-b5095d103c36.png)

![image](https://user-images.githubusercontent.com/99332618/233954475-1389b771-99c3-40b4-ab2c-1387ab0241dc.png)

Create a Lunch template for application tier too.
![image](https://user-images.githubusercontent.com/99332618/233966885-e85c7e81-fa0c-4a5e-bc76-92be8bcb840f.png)
For the second Security group, make sure to expose mysql, ssh and http. ssh eill be connected to webSG security group created earlier.

![image](https://user-images.githubusercontent.com/99332618/233967509-9ae4aef8-ec32-4e19-9998-8248eba2c33c.png)
![image](https://user-images.githubusercontent.com/99332618/233968083-0728c074-7fdb-49de-ba46-025aaabf783f.png)
![image](https://user-images.githubusercontent.com/99332618/233971305-2bff8d70-db8e-4ff0-942f-2d1bb2b6325c.png)![image](https://user-images.githubusercontent.com/99332618/233972331-d056f461-40c4-46f2-9a70-b42c055615bf.png)
![image](https://user-images.githubusercontent.com/99332618/233972421-89aedd9c-aff5-42bb-96ed-fc46303f9496.png)
![image](https://user-images.githubusercontent.com/99332618/233971791-184fbb89-dfe0-4e59-986a-fa759316bea6.png)
![image](https://user-images.githubusercontent.com/99332618/233972587-714c5859-0842-4d36-bf91-cbb236efd337.png)
![image](https://user-images.githubusercontent.com/99332618/233973941-5363a478-62d2-47a3-8edb-7a8ab104bb83.png)
![image](https://user-images.githubusercontent.com/99332618/233973996-28c2e9a6-0019-4700-aedb-7f53974019d6.png)
![image](https://user-images.githubusercontent.com/99332618/233974063-ed0f15b2-2535-43d1-b58f-8fb9f57f8a2c.png)
![image](https://user-images.githubusercontent.com/99332618/233974127-f7f6e699-123f-465e-82e0-e25f6d6ed276.png)
![image](https://user-images.githubusercontent.com/99332618/233974228-e99ea7b6-a68f-4b1e-9426-57d8b4699fc7.png)
![image](https://user-images.githubusercontent.com/99332618/233974311-b88d7cb7-3f83-42f5-825d-46f8a390ce8b.png)
![image](https://user-images.githubusercontent.com/99332618/233974421-bcfbc2ee-de41-4ff6-b261-c0f7ad2ba2ff.png)
![image](https://user-images.githubusercontent.com/99332618/233974480-02e1ab8f-c623-4bf0-9abc-83277dca6355.png)
![image](https://user-images.githubusercontent.com/99332618/233974555-b6093cc4-56b3-4b51-94bb-678fc9e797af.png)
![image](https://user-images.githubusercontent.com/99332618/233975572-2b602067-d0f6-4fad-8c31-0e66eb50d7f0.png)
![image](https://user-images.githubusercontent.com/99332618/233975994-b18d176f-9109-4291-853f-36685250c2b2.png)
![image](https://user-images.githubusercontent.com/99332618/233976574-a9d23008-4229-418f-842c-4260e251a3cd.png)

We have to wait for database to be created abd get an endpoint because it takes time to be created.
![image](https://user-images.githubusercontent.com/99332618/233976975-29ca8318-e42c-452c-8010-f36a827a5be7.png)




