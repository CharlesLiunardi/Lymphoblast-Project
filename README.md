# Lymphoblast-Project

1. Open GCP in a Google tab.
2. Log in to GCP using gmail account.
3. Claim GCP Voucher to get free billing credit.
4. Make a new project.
5. Linked the project to billing account.
6. Go to IAM & Admin menu, add member and specify its specific role, then save.
7. Go to Compute Engine > VM Instances.
8. Create VM instance with configurations as needed, authors use Machine Family General-Purpose Series N1 and Boot Disk Ubuntu-1804.
9. Open Firebase in a new Google tab.
10. Add project, then click create a project.
11. For project name, connect your GCP Project by choose it on Firebase Project.
12. Choose your plan (Blaze), then continue.
13. In Firebase, deploy your Android model to Firebase.
14. Create bucket for upload lymphoblast images from users.
15. Users will upload images via Android interface, then they will be automatically uploaded to Firebase storage.
16. Move to GCP again.
17. Go to Cloud Storage > Browser.
18. As you can see, the images also can be seen and edited on GCP bucket cloud storage.
19. To make the images and bucket become public, choose the bucket and click the three dots, then choose edit bucket permissions.
20. Click add member.
21. On new member, type "allUsers".
22. On select a role, specify the roles to Cloud Storage > Storage Object Viewer.
23. Files in buckets are publicly accessible.
