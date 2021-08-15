To expose the service on k3d . Run:
k3d cluster create -p "8089:30001@agent[0]" -a 3

A cluster with 3 agents will be created 
Type localhost:8089 in broweser to access the cluster. 
