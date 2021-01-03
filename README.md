Assignment #18 - blockchain  <br /> 

In this project, I will create a testnet blockchain network for an imaginary company. <br />
Below are the steps of this assignment:
- Set up a custom testnet blockchain
- Send a transaction
- Create a repo
- Write instructions on how to use the chain for the rest of the team

In order to set up a testnet, I will need to use the following tools we covered in FinTech bootcamp;
- Puppeth, to generate the genesis block
- Geth, a command-line tool, to create keys, initialize nodes, and connect nodes together
- The clique proof of authority algorithm

#1. Blockchain Installation Guide#
***Installing MyCrypto Desktop App***

​ MyCrypto is a free, open-source, client-side interface that allows I to interact directly with the blockchain. ​ For this example, we will use MyCrypto Desktop App to manage ethereum wallets and make transactions in the blockchain. ​ To install MyCrypto Desktop App, please follow the next steps: ​

Open my browser and navigate to the downloads page at https://download.mycrypto.com/. ​

Depending on my operating system, you will be redirected to the corresponding application installer. If you are not correctly redirected, choose the appropriate installer for my operating system. ​

Once you download the installer, open the file, and follow the installation wizard. ​

***My Crypto Installation Notes***

​ General Notes: ​

The first time you execute MyCrypto, you will see the following starting tutorial, we suggest to read trough as I click "Next" to continue. ​ ​ Running in OS X: ​
The first time I execute MyCrypto, I will see the following warning message, I can safely click on the "Open" button to start the application. ​ ​

***Installing Go Ethereum Tools***

​ Go Ethereum is one of the three original implementations of the Ethereum protocol. It is written in Go, fully open-source and licensed under the GNU LGPL v3. ​

In this example, we will use Go Ethereum Tools to create our very own blockchain, from the genesis block to mining tokens and making transactions. ​

Despite there are installers for OS X and Windows, we will use the application executable binary files to have a seamless experience between both operating systems and avoid some technical issues that currently exist in Windows. ​ To install the Go Ethereum Tools, please follow the next steps: ​

Open my browser and navigate to the Go Ethereum Tools download page at https://geth.ethereum.org/downloads/ ​
Scroll down to the "Stable Releases" section and proceed depending on my operating system. ​ 2.1. Installing in OS X. Click on the "***Geth & Tools 1.9.7***" to download the applications bundle archive. ​ 2.2. Installing in Windows.
You need to know if I are running a 32 bit or 64 bit version of Microsoft Windows, if I are not sure about that, I can check my version following these steps.

Depending on my Windows version, I should download the 32 bit or 64 bit version of the Go Ethereum Tools. ​

After downloading the tools archive, open my "Downloads" folder, and I will find a file named geth-alltools-darwin-amd64-1.9.7-a718daa6.tar.gz in OS X, and a file called geth-alltools-windows-amd64-1.9.7-a718daa6.zip in Windows. Note that the last numbers in the filename could vary depending on the last built available.​

Decompress the archive in the location of my preference in my computer's hard drive, and rename the containing folder as Blockchain-Tools. We recommend using a location that can be easily accessed from the terminal window like the user's home directory.

You have finished the installation process; I will use these tools to create my very own blockchain! ​
