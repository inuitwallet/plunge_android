#Plunge for Android

##Android UI for the Nu trust-less liquidity pool.

###Build
Install Buildozer (https://github.com/kivy/buildozer) along with Kivy (http://kivy.org)

in the root directory of plunge_android execute

    buildozer android debug

This will build a debug apk which can be installed on your android device

###Notice
This is a work in progress. The client interaction works but may break without warning.  
I am adding statistics to the UI when I can, I aim to add everything that is available from the server.  
  
Use with caution. the idea is that this client is trust-less so you remain in charge of your API keys.  
The server, client, ui and pool operator cannot see your secret keys so cannot interact with your money.  
However, money is at play so use wisely.  



