# Mesteam-Masternode-Install
Script for Mesteam Masternode Install

## VPS Side
Type in your vps this line

wget https://raw.githubusercontent.com/Simo190/Mesteam-Masternode-Install/master/masternode.sh && bash masternode.sh

./masternode.sh


During the installation prepare your private key and put into when the vps ask for it

## Wallet Side

First of all prepare your private key typing in you debug consolle:

masternode genkey

1) Generate a new receiving address and name it for example MN1

2) Send 2,000 coin exactly to your specific address MN1

3) Wait almost one confirmation and go on the debug consolle and type masternode outputs. Copy the answer

4) Open Masternode configuration file (Tools Menu) and type your masternode line as below specificated:

MN1 IpAddress:40104 PrivateKey Masternode outputs

5) Close your wallet and start it again

6) Wait 15 confirmation for your collateral transaction and type in your debug consolle masternode start-alias MN1

Check your masternode in vps typing mesteam-cli masternode status





