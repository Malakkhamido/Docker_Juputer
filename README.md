# Docker_Juputer
attached below is a code of my juputer notebook an analysis of the world wide books especially Harry Potter series also i took an image of jupyter datascience notebook so that i can pull it in a container i did a dockerfile 
# Instructions on how to build and run the Docker container.
first pull the image you want to work with
>docker pull jupyter/datascience-notebook
second: make a Dockerfile
check it
Third in the command line write:
cd "the path of the dockerfile in your laptop"
example: cd "C:\Users\malak\OneDrive\Dokumente\Docker"
Fourth
docker build -t my-jupyter-notebook .
my-jupyter-notebook  is the name of the new image
Fifth:
docker run -p 8888:8888 my-jupyter-notebook
this code opens the path and tokens for the juputernotebook you created
Now you Jupypter container is created succefully and connected to the 
