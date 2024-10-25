# CS476---Voting-Project
Create a project folder for DApp.
$ mkdir <PROJECT_NAME>
$ cd <PROJECT_NAME>

Initialize project with the following commands:
$ npm init -y
$ npm install --save-dev hardhat
$ npx hardhat init

Follow instructions to create js project

Copy Token.sol into contracts folder

Run the command:
$ npx hardhat compile

Create scripts folder
Copy index.html, main.js, style.css and deploy.js into scripts folder.

In new terminal, from project folder, run:
$ npx hardhat node

(go back )cd ..
From original terminal, run:
$ npx hardhat run scripts/deploy.js --network localhost

In new terminal, run (ensure web3 and python are installed):
$ python3 -m http.server

Open index.html in your browser
