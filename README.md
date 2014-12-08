Keylogging iOS 8 Custom Keyboard
================================

This repository is a proof of concept for an iOS 8 custom keyboard that will log any key stroke entered by the user: it sends the data on a local server everytime the return key is pressed.

This code was implemented by CMU students as part of a research project with Data Theorem performed throughout Fall 2014. The original repository is available at https://github.com/priyank-sanghavi/Mobile-Security---Data-Theorem.


Instructions
------------

Build the code and enable the custom keyboard in the Simulator.

For the data to be sent on the local server, you need to run the api.rb file in the command line.
Go to the folder that contains the file in terminal.

Type ./api.rb and it should start the local server. After this it will record all the keystrokes you make.

