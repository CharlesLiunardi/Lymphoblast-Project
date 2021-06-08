# Lymphoblast-Project

1. Open GCP in a Google tab.
![image](https://user-images.githubusercontent.com/78900200/121197633-a9d92b00-c89b-11eb-9f64-e3cddc100d64.png)
2. Log in to GCP using gmail account.
![image](https://user-images.githubusercontent.com/78900200/121187710-8d84c080-c892-11eb-9200-009bbb115d52.png)
3. Claim GCP Voucher to get free billing credit.
![image](https://user-images.githubusercontent.com/78900200/121198355-44d20500-c89c-11eb-93bc-d311294e1c4c.png)
4. Make a new project.
![image](https://user-images.githubusercontent.com/78900200/121197837-da20c980-c89b-11eb-80d6-ee54f17d530f.png)
5. Linked the project to billing account.
![image](https://user-images.githubusercontent.com/78900200/121187909-c1f87c80-c892-11eb-8968-033c3c4d01bf.png)
6. Go to IAM & Admin menu, add member and specify its specific role, then save.
![image](https://user-images.githubusercontent.com/78900200/121188118-ff5d0a00-c892-11eb-8767-6d2e31646366.png)
7. Go to Compute Engine > VM Instances.
![image](https://user-images.githubusercontent.com/78900200/121188298-2d424e80-c893-11eb-84fc-14c98649b90d.png)
8. Create VM instance with configurations as needed, authors use Machine Family General-Purpose Series N1 and Boot Disk Ubuntu-1804.
![image](https://user-images.githubusercontent.com/78900200/121198668-82cf2900-c89c-11eb-8b7f-2945ae9ed35c.png)
9. Open Firebase in a new Google tab.
![image](https://user-images.githubusercontent.com/78900200/121188564-72ff1700-c893-11eb-9e1a-d6cd6986a17a.png)
10. Add project, then click create a project.
![image](https://user-images.githubusercontent.com/78900200/121199238-f96c2680-c89c-11eb-9713-a7eb6f083e82.png)
11. For project name, connect your GCP Project by choose it on Firebase Project.
![image](https://user-images.githubusercontent.com/78900200/121188564-72ff1700-c893-11eb-9e1a-d6cd6986a17a.png)
12. Choose your plan (Blaze), then continue.
![image](https://user-images.githubusercontent.com/78900200/121188682-8ad69b00-c893-11eb-8844-26d942b00fc4.png)
13. In Firebase, deploy your Android model to Firebase.
14. Create bucket for upload lymphoblast images from users.
15. Users will upload images via Android interface, then they will be automatically uploaded to Firebase storage.
![image](https://user-images.githubusercontent.com/78900200/121188870-b8bbdf80-c893-11eb-8b65-a73d74a1db04.png)
16. Move to GCP again.
17. Go to Cloud Storage > Browser.
18. As you can see, the images also can be seen and edited on GCP bucket cloud storage.
![image](https://user-images.githubusercontent.com/78900200/121189043-eacd4180-c893-11eb-85a3-e07a9e890d54.png)
19. To make the images and bucket become public, choose the bucket and click the three dots, then choose edit bucket permissions.
20. Click add member.
21. On new member, type "allUsers".
![image](https://user-images.githubusercontent.com/78900200/121189341-34b62780-c894-11eb-978a-bfbc78a08314.png)
22. On select a role, specify the roles to Cloud Storage > Storage Object Viewer.
![image](https://user-images.githubusercontent.com/78900200/121189213-14866880-c894-11eb-8593-1df486f7356b.png)
23. Files in buckets are publicly accessible.
