# Hyperledger Fabric

Hyperledger Fabric is a blockchain framework that provides a modular architecture for developing enterprise-grade blockchain solutions. It is designed to be flexible and scalable, allowing organizations to deploy and manage their own blockchain networks. Fabric enables developers to create smart contracts in various programming languages and provides a range of tools to manage and interact with the blockchain network. This document provides an overview of the Fabric application stack and instructions for installing the necessary prerequisite software to get started with Fabric.

## Getting Started

The Fabric application stack has five layers:

- **Prerequisite Software**: the base layer needed to run the software.
- **Fabric**: the Fabric executables to run a Fabric network.
- **Contract APIs**: to develop smart contracts executed on a Fabric Network.
- **Application APIs**: to develop blockchain applications.
- **The Application**: the blockchain application will utilize the Application SDK to call smart contracts running on a Fabric network.

## Prerequisite Software:

### For Linux

#### Git
Install the latest version of git if it is not already installed
```sudo apt-get install git```

Check the version of the installed git.
```git --version```

#### cURL
Install the latest version of cURL if it is not already installed.
```sudo apt-get install curl```

Check the version of the installed cURL.
```curl --version```

#### Docker
Install the latest version of Docker if it is not already installed.
```sudo apt-get -y install docker-compose```

Check the version of the Docker installed.
```docker --version```

Check the version of the docker-compose installed.
```docker-compose --version```

#### Go
Install the latest version of Go if it is not already installed.
```sudo apt-get golang-go```

Check the version of Go installed.
```go version```

#### JQ
Install the latest version of Jq if it is not already installed.
```sudo apt-get install jq```

Check the version of Jq installed.
```jq --version```

#### Git For Windows (Optional)
Although not required, if you do decide to install Git on Windows and manage the Fabric repositories natively(as opposed to within WSL2 and its Git installation), then make sure you configure Git as follows:

Update the following 'git' configurations:
```git config --global core.autocrlf false```
```git config --global core.longpaths true```

You can check the setting of these parameters with the following commands:
```git config --get core.autocrlf```
```git config --get core.longpaths```

These output from these commands should be false and true respectively.

