git clone git@github.com:leon-do/mainnet-neutrino-lnd.git

cd mainnet-neutrino-lnd

./lnd-debug --lnddir=./lnd

./lncli-debug --lnddir ./lnd create

./lncli-debug --lnddir ./lnd unlock

npm install

node app.js


![](https://i.imgur.com/1GoAuoY.png)
