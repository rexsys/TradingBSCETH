# BSCtradingbot
BSCtradingbot monitors any trading sygnals telegram channels and hunts for the tokens that meen config. file. After purchase bot sells the bought token as per config settings at 2x, 5x, 10x...  
The bot is crossplatform and works on windows, linux, ios, android. 

Installation

1. Download the bot by Code button
2. Follow config.jpg file settings from archive of the bot
3. Add liquidity to your metamask wallet of BNB and WBNB. BNB used to pay the gass fees while WBNB used to buy the tokens. Make sure balance is enough to make purchases.

Windows

1. Open CMD window and run pip install -r requirements.txt from the bot folder
2. When completed run main.pyc
3. For any help please add in to our https://t.me/BSCtradingbot group

Linux

Debian / Ubuntu
1. sudo
2. sudo apt install git
3. sudo apt install python-pip
4. sudo pip install web3
5. sudo pip install telethon
6. sudo pip install websocket-client
7. sudo pip install pandas
8. sudo pip eth_accounts
9. Clone git clone https://github.com/rexsys/BSCtradingbot.git
10. cd BSCtradingbot
11. python main.pyc
12. For any help please add in to our https://t.me/BSCtradingbot group

Fedora Linux / Centos
1. dnf install git
2. dnf install python-pip 
3. pip install web3 
4. pip install telethon
6. pip install websocket-client
7. pip install pandas
8. Clone git clone https://github.com/rexsys/BSCtradingbot.git
9. For any help please add in to our https://t.me/BSCtradingbot group

Arch Linux
1. pacman -S git 
2. pacman -S install python-pip 
3. pip install web3 
4. pip install telethon
6. pip install websocket-client
7. pip install pandas
8. Clone git clone https://github.com/rexsys/BSCtradingbot.git
9. For any help please add in to our https://t.me/BSCtradingbot group

Mac/iOS

1. Make sure python 3 is installed 
2. open terminal window
3. type : python3 --version
4. if you get an error message and python3 isn't installed, you need to add it.
5. go to https://www.python.org/ and install latest version of python for mac
6. in terminal window one last check to see you have Python 3 installed
7. type : python3 --version
8. should see Python 3.9.7 or later showing
9. install web3
10. install python-pip
11. install telethon
12. install websocket-client
13. install pandas
14. open terminal window
15. type : pip3 install web3
16. wait while web3 installs
NOTE : part way through the install you may be prompted to install xcodeif this happens carry on and install xcode some errors may be now showing in terminal window go back to terminal and type : pip3 install web3
17. after this (xcode installation) web3 should be good to go Edit config.json recommended opening a fresh metamask wallet for sniper testing
18. Edit lines 1,2,5,17,18,30,31,32,33,34,35,38,40, of config.json and telegram channels 
19. To get private key from metamask click the 3 dots just under the favicon
20. Select 'Account Details
21. Select 'Export Private Key'
22. Add Speedy Node to line 13 "bscNode": "Enter node URL here",
https://admin.moralis.io/register to get your free speedy node
Go to 'Speedy Nodes' on the left
Choose yellow BSC Network icon on right
Click Endpoints
Take key from top line and paste in (address must start with wss://)
23. Run script
24. Get in terminal window
Make sure you are in the directory of the script before you run it.
type : python main.pyc
Open finder, then click Applications —> Python 3.7 folder to expand it. There should be a file called 'Install Certificated.command', double click the file to run it. It will open another popup terminal window and show below command execution output text. Once it is complete close it and run the bot.
25. For any help please add in to our https://t.me/BSCtradingbot group

Android
1. Install Termux https://play.google.com/store/apps/details?id=com.termux&hl=en&gl=US 
2. Update
3. pkg update 
4. pkg upgrade
5. Install dependency
6. pkg install git python3 python-pip
7. Install web3
8. pip install web3
9. install telethon
6. install websocket-client
7. install pandas
10. install -U web3
11. Clone the repo using git
12. Clone git clone https://github.com/rexsys/BSCtradingbot.git
13. For any help please add in to our https://t.me/BSCtradingbot group
