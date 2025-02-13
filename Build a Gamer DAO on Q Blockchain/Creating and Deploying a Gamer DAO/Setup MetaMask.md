# Setup MetaMask

Welcome back!  So, you've dived deep into learning about Q blockchain! Great job! Well, roll up your sleeves, because in this section we will be building stuff! A DAO! Are you excited? But before that let’s set up the necessary environment required to run your code. Let's get started!

## What is a development environment?

You now need a super cool environment to run our code in and you need to set it up!

For this tutorial, you will use Metamask wallet, Q faucet, and Remix for compiling and deploying your code. Don’t worry, setting them is super easy and you will do it in no time!

### Quick setup

Just go to the link [https://metaschool.so/rpc/qTestnet](https://metaschool.so/rpc/qTestnet) and click on “Add to Metamask” **** to quickly add Q Testnet to your MetaMask. Here’s how it looks like.

![Frame 3560339 (2).png](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560339_(2).png?raw=true)

### Manual steps

1. If you have not yet installed Metamask, you can download it from [here](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn) for Chrome. If you are using any other browser, kindly try searching MetaMask extension for your browser.
2. Open your MetaMask browser extension, scroll through networks and click on “Add Network” button.
    
    ![Frame 3560364 (1).gif](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560364_(1).gif?raw=true)
    
    The following screen will appear after clicking the “Add Network” button. 
    
    ![Frame 3560339 (1).png](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560339_(1).png?raw=true)
    
3. Now click on the “Add a network manually” to add a new network to your MetaMask. 

![Frame 3560339 (1).gif](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560339_(1).gif?raw=true)

1. Now fill in the following details:
    1. **Network name**: Q Testnet
    2. **New RPC URL**: [https://q-testnet.rpc.thirdweb.com](https://q-testnet.rpc.thirdweb.com/)
    3. **Chain ID**: `35443`
    4. **Currency symbol**: Q
    5. **Block explorer URL**: [https://explorer.qtestnet.org/](https://explorer.qtestnet.org/)
2. Click on the “Save” button. Finally, click on “Q Testnet” button and switch to your newly added network.

## Fill your account with Q tokens

Next, we will fill your newly created Q Testnet account with tokens using the Q faucet. Here’s how you can do that:

### Steps

1. Copy your Q account address. you can find it in your MetaMask account.
2. Next, head over to [https://faucet.qtestnet.org/](https://faucet.qtestnet.org/), connect your MetaMask or paste your copied address to the Wallet address field. Select “I am human," and then click on “Claim tokens” button.
    
    ![Frame 3560364 (4).gif](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560364_(4).gif?raw=true)
    
3. In the next couple of seconds, your wallet will be filled with 5 Q tokens.
    
    ![Frame 3560364 (8).jpg](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560364_(8).jpg?raw=true)
    

Now you have Q tokens in your Metamask wallet. The next step is becoming familiar with the Remix IDE.

## What is Remix?

Remix is like an all-in-one toolbox for developers, and it is an Integrated Development Environment (IDE).

Here's the deal: Remix is all about making your life easier when you're working on creating smart contracts. It's open-source, which means it's free for everyone to use and improve. It's like having a special workspace just for writing and running programs in Solidity programming language.

Head over to [https://remix.ethereum.org/](https://remix.ethereum.org/) and click on “New File” button. Set the name of your file as `MyFirstDAO.sol`.

![Frame 3560364 (5).gif](https://github.com/0xmetaschool/Learning-Projects/blob/main/Build%20a%20Gamer%20DAO%20on%20Q%20Blockchain/Creating%20and%20Deploying%20a%20Gamer%20DAO/Setup%20MetaMask/Frame_3560364_(5).gif?raw=true)

## That’s a wrap

Well, that’s it. We are all set to build our DAO.

In the next lesson, you will write code for DAO in the Solidity programming language which you will deploy on your Q network using Remix IDE later on.
