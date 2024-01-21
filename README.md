Smart_Falcon_Hackathon
# step 1: To setup Hyperledger Fabric Test Network
use the below commands:-
# ./network.sh down
# ./network.sh up

# step 2: Package and Deploy the chain code into fabric test network 
use the below commands:-
# ./network.sh deployCC -ccn basic -ccp ../asset-transfer-basic/chaincode-go -ccl go

# step 3: Test the chain code functionality using Fabric Peer CLI commands
