# bettertouchtool-crypto
Crypto market prices for your Macbook Pro touch bar! Values updated every minute.

Modified to support Denarius (DNR) https://denarius.io

Currently supported coins:
- **Bitcoin** - Pulled from Coinbase.com API.
- **Ethereum** - Pulled from Coinbase.com API.
- **Litecoin** - Pulled from Coinbase.com API.
- **Neo** - Pulled from bittrex.com API.
- **Civic** - Pulled from bittrex.com API.
- **Denarius** - Pulled from coinmarketcap.com API. (This is an addon under dnr.json)

# Notes:
- All values are in USD.
- For values taken from bittrex.com, the very last price this coin was sold for is used. Bonus feature: If you click the button it translates the current USD value to ETH.
- Once installed, you can delete any coins you are not interested in tracking.

# To Install

1. Download and install [Better Touch Tool](https://www.boastr.net/downloads/). It allows you to modify your touch bar and other cool things. It's a 45-day trial but "pay what you like" to register.
2. Right-click and download this repo and unzip it: [master.zip]
3. In your Mac's menu bar, click the Better Touch Tool `icon > Preferences`.
4. In the bottom left corner of the popup go to `Manage Presets`.
5. Click the "Import" button and select the [crypto-krunkosaurus.json](https://raw.githubusercontent.com/krunkosaurus/bettertouchtool-crypto/master/crypto-krunkosaurus.json) file you downloaded from the zip file in step 2. Voilà you're done!
6. If you want support for other coins, repeat step 5 with dnr.json or any of the other *.json files that came with the zip file you downloaded. By importing dnr.json for example, it will add support for Denarius.
7. Note that you can toggle these separate presets on and off in the BetterTouchTool settings. More to come!

# Customization

- In the Better Touch Tool preferences panel, you can add, delete, and rearrange the currencies.
- Timing: Currently each currency is refreshed every 60 seconds. Change this by going to Better Touch Tool preferences panel, clicking on a currency, going to "advanced configuration", and adjusting the "run script every x seconds" amount. It's not recommended to go under 30 seconds or the server could ban you.
- Changing the logo of any coin: Download or make a .PNG version of the file. It's best if it has a clear background. In BetterTouchTool preferences go to the coin you want to change and drag your PNG file on to the old logo.
- Changing the background color of a logo: Same step as the previous line except you go to "Advanced Configuration" and edit "Touchbar button color".

# Donations

_I am not the original author of this script. The original idea came from [here](https://steemit.com/neo/@awesomemo/get-the-latest-price-of-neo-on-your-macbook-touchbar).

# History
- Add-on support for Denarius (DNR)

# Acknowledgments

Thanks to the original source [here](https://steemit.com/neo/@awesomemo/get-the-latest-price-of-neo-on-your-macbook-touchbar) that my modified/optimized version is based on.
