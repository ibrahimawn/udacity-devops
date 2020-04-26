App URL:
http://udagram-lb-240006247.us-west-2.elb.amazonaws.com/

Run in this order:
1. Network  -   ./create.sh udagram-network network.yaml network-params.json
2. Bastion  -   ./create.sh udagram-bastion bastion.yaml bastion-params.json
3. Server   -   ./create.sh udagram-server server.yaml server-params.json