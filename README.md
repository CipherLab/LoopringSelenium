# LoopringSelenium
Just a selenium script to help send an nft to multiple addresses with far fewer clicks

You'll need the selenium ide
https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd
https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/

Open the side file from the IDE. When you run it, it opens a new browser window and you'll have to connect your wallet. From there on, the script will execute through that authenticated window, until you close it. 

Edit the script after opening it, set the name of the nft you are sending, and the list of addresses as a json list. IE the execute script step should say: return ["address1","address2"] 

If you have security concerns, just take a look at the side file. Seleium is just an automated scripting tool. It does nothing but click elements and enter the quantity and address for you. 

You will still have to authorize the transaction from your mobile for the script to continue to the next. 

You may want to note where it left off if an error occurs. 
