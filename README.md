
# swap

A script to create swap in linux. 

Usage:
=====

Download and run the script using wget:

`wget -qO swap bit.ly/zac-swap && sudo bash swap <size>`

---------------------------------------
Available options:
size - Size of swap ( Example - 1G,2G)
path - Path to create a swapfile

Usage with Docker:
================
Build the docker image first

`docker build -t swap .`

Now run the docker image

`docker run -it swap 2G`

