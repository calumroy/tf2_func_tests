# tf2_func_tests
Testing out some sweet tensor flow 2 stuff.

# To get the docker container already setup 
`docker pull docker.pkg.github.com/calumroy/tf2_func_tests/tf2_jupyter_ade:latest`  

# To run and enter the docker container
From this directory  
`ade start`  
`ade enter`  
You will then be inside the docker contianer where jupyter and tensorflow2 is already installed with firefox.
Run this to view and interact with the notebooks.  
`jupyter notebook`  

# Build the ade docker container
`cd ./minial_ade`
`docker build -t tf2_jupyter_ade .`  

# Push a new docker image to the repos container repository
`docker push docker.pkg.github.com/calumroy/tf2_func_tests/tf2_jupyter_ade:latest`  
