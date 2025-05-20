# Assignment-2

Hyperledger Fabric Test Network Setup

This project explains how to set up and run a basic Hyperledger Fabric test network using its official sample repository. It includes installing the required tools, downloading the Fabric samples, and using the network.sh script.

Prerequisites Installation

1. Install Go (Golang)

Go is needed to build Fabric binaries.

sudo apt install golang-go

2. Check Docker Installation

docker --version

3. Check Docker Compose Installation

docker-compose --version

4. Verify Directory Structure

Check the current directory structure:

ls

Cloning Fabric Samples

5. Clone the Fabric Samples Repository

git clone -b main https://github.com/hyperledger/fabric-samples.git

6. Go to the Fabric Samples Directory

cd fabric-samples

7. Download Binaries and Docker Images

curl -sSL https://bit.ly/2ysbOFE | bash -s

Running the Test Network

8. Navigate to the Test Network Folder

cd test-network

9. Start the Network

./network.sh up

10. Create a Channel

./network.sh createChannel

11. Shut Down the Network

./network.sh down

Conclusion

This setup shows how to install tools and run a basic Hyperledger Fabric test network. It includes starting the network, creating a channel, and stopping everything afterward.


