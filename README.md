# tf2_func_tests
Testing outsome sweet tensorflow2 stuff.

# To get the docker container already setup 
`docker pull docker.pkg.github.com/calumroy/tf2_func_tests/tf2_jupyter_ade:latest`  

# To run and enter the docker container
From this directory  
`ade start`  
`ade enter`  
You will then be inside the docker contianer where jupyter and tensorflow2 is already installed with firfox.
Run this to veiw and interact with the notebooks.
`jupyter notebook`  



# Build the ade docker container
`cd ./minial_ade`
`docker build -t tf2_jupyter_ade .`


