---
description: Find answers to common issues
---

# Troubleshooting

## I cannot connect to the platform

* Make sure to select the correct network (Ethereum Mainnet or Gnosis Chain). Normally on the wallet provider you can switch the network in the settings option.
* On a non-custodial wallet app (e.g. Rabby):
  * Make sure to unlock and select Ethereum app.
  * Make sure contract data is allowed on the Ethereum app settings.
* On custodial wallet app (e.g. Coinbase):
  * Use the scan QR option to connect.
  * If you want to access directly from the wallet browser, just go to app.spark.fi.
* Using Wallet Connect:
  * Use the scan QR code to connect

## Enable contract data on Ledger

If you are using a Ledger hardware wallet, make sure to select the Ethereum app and enable contract data.

To enable contract data:

* Connect and unlock your Ledger device.
* Open the Ethereum application.
* Press the right button to navigate to Settings.
* Then press both buttons to validate.
* In the Contract data settings, press both buttons to allow contract data in transactions.
* The device displays Allowed.

[Here is a visual guide.](https://teckers.co/uniswap-ledger/)

## I cannot send transactions

Make sure you have enough ETH in your wallet to pay the transaction fees. Depending on the network status, the cost of the transactions may vary. At least 0.05 ETH may be required to interact properly.

## The site does not load

The following steps may solve your problems:

* If you are using Brave browser, switch to another browser to see if the issues are related to Brave. If it is related to Brave browser some helpful actions are:
  * Clearing cache data and cookies for the site
  * Hard refresh with control + F5 (or cmd + r)
  * Disable brave wallet (or the wallet not being used as default, e.g. metamask) or other extensions that might be interfering with proper connection with the wallet
  * If the site still won't load after taking the steps above, you will have to use the platform in another browser.
* Make sure your internet connection is working and stable
* Restart the browser and try to connect again
* Try to hard refresh the site with control + F5
* Check if there are any updates for your browser or wallet provider. If so, update it to the latest version.

## My transaction is stuck pending confirmation

In this situation make sure to not keep sending transactions, as every new transaction will be stuck pending the oldest transaction to be confirmed. You can get rid of the stuck transaction by speeding it up or cancelling it. Depending on the wallet you are using, you may have that option natively.

For example, Metamask or Trust Wallet both have the options to cancel or speed up transactions.

Alternatively, if your wallet provider doesn't have this option, you can still drop the stuck transaction by sending a 0 ETH transaction, to your address (yourself) using the same nonce (number id) as the stuck transaction. You can inspect the nonce in your stuck transaction in [Etherscan](https://etherscan.io) and use interfaces such as [MEW](https://www.myetherwallet.com/) and [MyCrypto ](https://mycrypto.com/)to send a 0 ETH transaction with a higher gas cost to replace the one that is stuck.

Here are a couple of guides about the topic for [MEW ](https://kb.myetherwallet.com/en/transactions/checking-or-replacing-a-tx-after-sending/)and [MyCrypto](https://support.mycrypto.com/how-to/sending/checking-or-replacing-a-transaction-after-it-has-been-sent).

{% hint style="info" %}
If you still have any questions or issues, feel free to reach out to the Spark team on the official [Discord](https://discord.com/sparkdao).
{% endhint %}
