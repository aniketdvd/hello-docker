:whale: :whale2: :whale:

# Hello Docker
### A simple PHP Hello World

This is a Docker image that after being built and ran, greets hello world in browser through PHP

# Directory structure
.

├── Dockerfile :whale2:

└── src
    └── index.php

# Building the Docker image

Run the following command in the command line to build the image.

```docker build -t hello-docker .```

*NOTE*: This may take some time due to the fetching of the images that are required.

#Running the container

```docker run -p 80:80 hello-docker``` shall do.

# Accessing the page

Go to localhost and you will see the Greeting! 


