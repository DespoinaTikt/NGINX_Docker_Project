# NGINX_Docker_Project

In this mini basic project, I create a simple static website and serve it with Nginx in a Docker container. Here are the steps I followed.

## Create directory, files and image

First I create the directory for my project. The structure is "my-docker-project/ > Dockerfile > html/ > index.html". After my files are ready, I navigate to my project directory in the terminal and run the command to build the Docker image.

![Screenshot (352)](https://github.com/user-attachments/assets/57801acc-d335-4c9d-bbe2-dbe17fa66e5a)

## Run the container and verify

After building the image, I run the Docker container. I use the option -d in order to detach the container and to be able to use the terminal.

![Screenshot (354)](https://github.com/user-attachments/assets/0074022a-3718-4eca-a7b0-6cbf9decd9ac)

I verify that my container is running.

![Screenshot (355)](https://github.com/user-attachments/assets/75461d12-2b35-41d5-bad3-2d768bdd297e)

Then, I open the web browser and enter "http://localhost:8080" to access my website.

![Screenshot (356)](https://github.com/user-attachments/assets/39200099-445b-45a2-a15a-6f3eda71039c)

## Push the image to Docker Hub

Additionally, I want to push my Docker image to Docker Hub. I return to the terminal and login to my Docker Hub account.

![Screenshot (357)](https://github.com/user-attachments/assets/bd8a5884-c209-4627-919e-1861d4280d67)

I tag my image and then push it.

![Screenshot (358)](https://github.com/user-attachments/assets/41d8b5dc-ef0d-4ac2-952d-b19ec83d06e6)

## Clean up resources

Finally, I stop my container from running.

![Screenshot (360)](https://github.com/user-attachments/assets/e9302280-3f94-4cd9-9c1c-4d47eaead33c)

And I also remove it.

![Screenshot (361)](https://github.com/user-attachments/assets/d990139b-9a4b-4f7e-b6a6-2398a5304e58)
