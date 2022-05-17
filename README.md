Simulate P2P Nano network with Docker

USAGE:

To create a new network with 1 origin and 10 work nodes:

docker-compose up --scale node=10 

or with custom node image tag:

NODE_IMAGE=custom-node docker-compose up --scale node=10