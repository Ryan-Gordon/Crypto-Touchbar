# Crypto-Touchbar

* This is an add-on (via Better Touch Tool) to get Cryptocurrency prices on your MacBook Touchbar

Example : ![screenshot](https://github.com/FlashGordon95/Crypto-Touchbar/blob/master/example.JPG)
# Installation

- Download and install [Better Touch Tool](https://www.boastr.net/downloads/). 
- Install `jq` using [Homebrew](https://brew.sh/) with command `brew install jq`. It needs to be installed into `/usr/local/bin/jq` (this is the default location).
- Select any of the json docs for your currency.
- In your Mac's menu bar, click the Better Touch Tool `icon > Preferences`
- In the bottom left corner of the Better Touch Tool popup window, go to "Manage Presets".
- Click the "Import" button and select the appropiate script you want to use. 
- ???
- Profit

# Currencies
This repo contains scripts to get both the BTC/<Coin> pair and also the EUR/<coin> price. 
The JSON files are split such that you only have to add in either the EURO or BTC pair, or both if you like and you can add only the ones you want to see on the touch bar.

# Pull requests
One thing that could be added to this repo is USD price scripts, I have seen many of these but think it would be better to have one repo with both EUR, USD and other currencies. 

# Donations
Instead of sending me donations consider supporting MyEtherWallet or some other cause.

# Acknowledgments
The original idea came from [here](https://steemit.com/neo/@awesomemo/get-the-latest-price-of-neo-on-your-macbook-touchbar).
I decided to change the idea so it will do EUR prices and to break up the scripts into individual scripts so you only add what you want. 


