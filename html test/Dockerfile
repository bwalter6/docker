# Use latest Nginx runtime as a parent image
FROM nginx:alpine

# Copy the current directory contents into the container 
COPY . /usr/share/nginx/html

WORKDIR /usr/share/nginx/html

# Make port 80 available to the world outside this container
EXPOSE 80


