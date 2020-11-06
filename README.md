# fabric-test-benchmark


1)First clone the repositry 

2) BasicNetwork_1.4.4/artifacts/channel

3) chmod 777 *.sh

4) ./create-artifacts.sh

5) cd ..

6) make sure the followings are installed: docker, docker-compose, curl, nodejs, npm, caliper example: sudo apt install nodejs

7) sudo docker-compose up -d 

8) cd ..

9) ./createChannel.sh

now we have created our simple Hyperledegr Fabric network.

# Sample scenario for hyperledger fabric smart contract to store different models of the car in the fabric network:

1) cd BasicNetwork_1.4.4/artifacts/src/github.com/fabcar/go

2) sudo nano fabcar.go 


reference: https://github.com/rddill-IBM/ZeroToBlockchain

Tutorial: https://www.youtube.com/watch?v=my7kZXvgbBY&t=578s





*Original repository: https://github.com/adhavpavan/BasicNetwork_1.4.4
