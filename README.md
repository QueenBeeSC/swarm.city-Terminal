# Terminal - Swarm City's First Release


The Swarm City app is a decentralized web app running on the Ethereum blockchain and is not available in the app stores. Simply visit https://swarm.city to begin. 

The Swarm City Terminal is the starting point of the user journey in Swarm City. It serves as the main entry screen into the Swarm City ecosystem and will lead you to [Boardwalk](https://github.com/swarmcity/sc-terminal/blob/master/README.md), the browser for the hashtags offering services, starting with #ridesharing. 

The first step is to create a SWT wallet. It provides Swarm City users the ability to:
  * create and manage a basic profile
  * exchange Arcade City tokens (ARC) for Swarm City Tokens (SWT)
  * view SWT balances
  * send & receive SWT from any wallet

We are also working on integrating a fiat to crypto exchange into the DApp. SWT is exchanged directly between users over the Ethereum blockchain; no need for a middelman. The new wallet it is stored locally on your device; no central database. The password you choose will be used to encrypt your wallet on your device. Your wallet is as secure as you keep it, and there is no way to recover lost passwords. Welcome to the blockchain! Let's get started...


<br>


# [Enter the Terminal](https://swarm.city)  


<br>


<button onclick="myFunction()">Create new user</button>

<div id="myDIV">
  With the first visit to the Terminal everyone must create a new user, even if you previously created an AC wallet. You will be able to load your AC wallet and create a new vault for your tokens in the Terminal. If you have ARC tokens then you will have a few options to access your tokens and you will be prompted to exchange ARC to SWT as long as there is an ARC balance in your wallet. If you have no tokens to convert then you can simply create a new wallet by creating a password to secure your wallet.

Listed below are the step by step processes required to complete each action.

* ### Yes, convert my tokens
  * as a json file **from an AC wallet**
    * choose file
    * enter password of ARC wallet
    * creating new wallet
    
  * as a print PDF (private key) **from an AC wallet**
    * enter private key
    * create password
    * repeat password
    * creating new wallet
    
  * from an external wallet
    * enter private key
    * create password
    * repeat password
    * creating new wallet
  
* ### Nope, don't have any
  * create a password 
  * repeat password
</div>
<script>function myFunction() {
    var x = document.getElementById('myDIV');
    if (x.style.display === 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
</script>

## [Create new user](https://github.com/QueenBeeSC/swarm.city-Terminal/wiki/Account-Creation)
---

With the first visit to the Terminal everyone must create a new user, even if you previously created an AC wallet. You will be able to load your AC wallet and create a new vault for your tokens in the Terminal. If you have ARC tokens then you will have a few options to access your tokens and you will be prompted to exchange ARC to SWT as long as there is an ARC balance in your wallet. If you have no tokens to convert then you can simply create a new wallet by creating a password to secure your wallet.

Listed below are the step by step processes required to complete each action.

* ### Yes, convert my tokens
  * as a json file **from an AC wallet**
    * choose file
    * enter password of ARC wallet
    * creating new wallet
    
  * as a print PDF (private key) **from an AC wallet**
    * enter private key
    * create password
    * repeat password
    * creating new wallet
    
  * from an external wallet
    * enter private key
    * create password
    * repeat password
    * creating new wallet
  
* ### Nope, don't have any
  * create a password 
  * repeat password


<br>


## [Restore a backup file](https://github.com/QueenBeeSC/swarm.city-Terminal/wiki/Restore-a-backup-file)
---

** Note: Restore a backup file can only be used to retrieve a previously deleted SWT wallet that was created, backed up with IPFS, and deleted from the device through the Terminal.** 

* ### Restore an account
  * enter IPFS-hash
  * restore
  * enter password


<br>


## [Create a Profile](https://github.com/QueenBeeSC/swarm.city-Terminal/wiki/Create-a-profile)
---

Click on the profile avatar or username to access the profile view. On the profile view, you see a profile avatar, username, and public wallet address. You also see a button to make backup, delete this user, and log out.

Personalize your account by changing the profile picture and username. The user can upload a profile picture or take the picture with the camera in his device. The image can be cropped before saving.  

Once you have created a profile you can log in and out at will. Upon re-entry to the Swarm City Terminal, your wallet can be loaded by entering your password only, unless you delete the user. In which case, you can follow the steps to cretae a new user and load a new wallet. 


<br>


<iframe width="560" height="315" src="https://www.youtube.com/embed/kFD1t3MsdCs" frameborder="0" allowfullscreen></iframe>


<br>


## Exchange ARC for SWT
---

[Original whitepaper](https://drive.google.com/file/d/0B9RSMdR2vWssV2JJX0t6dmN6SUk/view) - [SWT whitepaper](https://github.com/swarmcity/sc-token/blob/master/token-exchange-miniwhitepaper.md) - [Swarm City Token (SWT) Contract](https://etherscan.io/token/0xb9e7f8568e08d5659f5d29c4997173d84cdf2607)

**If you have ARC tokens that you want to convert to SWT you will need a small amount of ether to cover gas fees, approximately 0.1 eth in the wallet holding the ARC tokens, before you can complete the swap. This will be more than enough to cover several transactions**


<br>


<iframe width="560" height="315" src="https://www.youtube.com/embed/ON5NLUQDFVM" frameborder="0" allowfullscreen></iframe>


<br>


## Send SWT & Receive SWT
---

Users can send to and recieve SWT from any other user by sharing their shortcode or public address.
**Never share your password, IPFS-hash or private key*


### Send SWT
  * click on SWT balance
  * send SWT
  * enter amount
  * enter shortcode or public address of receiver
  
### Receive SWT
  * click on SWT balance
  * shortcode
  * copy and paste to the sender before the code expires


<br>


## Create a backup
---

The Swarm City app is fully decentralized so there is no central party storing your account information. When a user is removed from a device it can only be recovered by a backup that you have created for yourself. The backup with your password will give you permanent and complete control of your tokens.

* ### Create a backup
  * click on the profile avatar or nickname
  * create a backup
  * download and/or ipfs
  
Next to the avatar and username there is a warning sign (!). It will be there as long as the user hasn’t made a backup. Clicking on it or on the avatar/username takes the user to the profile view with instructions to make a backup. 

The user can download the json file and can choose to store it on the device or on the [IPFS distributed web](https://ipfs.io).
**Be sure to store your public address, private key, password, and IPFS-hash in a safe place.**


<br>


## Delete this user
---

Select delete this user to switch between wallets. At this time, the Terminal can load contents from only one wallet at a time. When deleting a user the contents of the wallet will remain intact. Any IPFS-hash or backup download created will retain it's merit and can be used to reload the account after deletion.

* ### Delete this user
  * click on the profile avatar or nickname delete this user
  * continue
  

<br>


## Logout
---

Select logout to keep your profile stored locally on your device. Upon re-entry to the Terminal you will enter your only your password.

* ### Logout
  * click on the profile avatar or nickname
  * logout


<br>


### Meet the community, visit the swarm.city [welcome page](https://queenbeesc.github.io/swarm.city/)





