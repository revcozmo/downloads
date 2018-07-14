Compiled wallets / daemon for download

Wallets available for Mac OSX 10.10+, Windows 8+, Ubuntu 16.04
Compiled daemon also available for Ubuntu 16.04

See the wiki for setup guides

## For a faster wallet sync - Add Nodes

1.  Click in the wallet menu "Tools -> Open Wallet Configuration File"
2.  Copy and paste the following data into the notepad -

* addnode=178.128.14.55
* addnode=178.128.3.233
* addnode=159.203.99.229

3.  Save the file, and restart wallet

# For Mac OS X High Sierra -

### In Terminal, run the following command:

`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

### Once the package manager has been installed, run this command: 

`brew install boost`
