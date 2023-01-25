# 1A2B Game with Client-server Architecture

It's a project that realize 1A2B game with client-server architecture on AWS 

## Basic Usage

* Run `bash build.sh` to generate server.o and build directory
* Run `./build/server` on Amazon EC2 to let server working
* Run `python3 demo.py` or `python3 demo_part3.py --server-ips <server1 IP> <server2 IP> <server3 IP>` to check the whether the result of the repsond from server corresponding to the request from the client is correct 
