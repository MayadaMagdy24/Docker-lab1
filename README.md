# Docker-lab1
1-
•Run the container hello-world
![Screenshot (775)](https://user-images.githubusercontent.com/93229250/228752560-36a1b365-da07-4904-9828-71d2cb1e7470.png)

•Check the container status
![Screenshot (776)](https://user-images.githubusercontent.com/93229250/228752602-cca8d399-1b49-4860-83e8-eeef5dc00483.png)

•Start the stopped container
![Screenshot (778)](https://user-images.githubusercontent.com/93229250/228752708-af899f5f-9595-4349-b727-7d9a5da6b0e0.png)

•Remove the container
![Screenshot (792)](https://user-images.githubusercontent.com/93229250/228754794-a6a4462f-5916-46d5-aae9-bba5ade1b98c.png)

•Remove the image
![Screenshot (780)](https://user-images.githubusercontent.com/93229250/228752879-0b8f53ff-6e7a-425b-b464-4657956bb03e.png)

2-
•Run container centos or ubuntu in an interactive mode
•Run the following command in the container “echo docker ”
•Open a bash shell in the container and touch a file named hello-docker
•Stop the container and remove it. Write your comment about the file hello-docker (file removed )
•Remove all stopped containers

![Screenshot (783)](https://user-images.githubusercontent.com/93229250/228753051-18f08e1d-5ac7-442b-8631-1e5a7b010785.png)

3-
•Run a container httpd with name apache and attach a volume to the container
•Volume for containing  static  html file
•Remove the container
![Screenshot (784)](https://user-images.githubusercontent.com/93229250/228753178-f04b3a57-23ef-4b70-b625-36f7829b71d0.png)

•Run a new container with the following:
•Attach  the volume  that  was attached  to the previous  container
•Map  port 80 to port  9898  on you host machine
![Screenshot (786)](https://user-images.githubusercontent.com/93229250/228753242-2ff83dd7-4ee4-493c-ac1c-e96bf9e27282.png)

•Access the html  files from your browser
![Screenshot (772)](https://user-images.githubusercontent.com/93229250/228753275-572c6df6-7f5e-491c-ba8f-11f33601f620.png)

4-
•Run the image httpd again without attaching any volumes
![Screenshot (788)](https://user-images.githubusercontent.com/93229250/228753401-d8547432-e5db-458c-b260-ca48222de5c7.png)

•Add html static files to the container and make sure they are accessible
![Screenshot (796)](https://user-images.githubusercontent.com/93229250/228860205-c30c3e59-251e-46f8-b11e-630bd12bc1c3.png)

•Commit the container with image name my apache
![Screenshot (790)](https://user-images.githubusercontent.com/93229250/228754132-51358f9a-2481-47a0-9992-3a0bc96fc870.png)

5-
•Create a volume calledmysql_data, then deploy a MySQL database calledapp-database. Use the mysqllatestimage, and use the-eflag to setMYSQL_ROOT_PASSWORDtoP4sSw0rd0!.Mount themysql_datavolume to/var/lib/mysql. The container should run in the background.
![Screenshot (774)](https://user-images.githubusercontent.com/93229250/228752478-b8a295c6-4d86-4ecb-bec5-bbfceb910f23.png)
