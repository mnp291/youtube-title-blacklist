# youtube-title-blacklist

This is a chrome extension to block youtube videos with certain words in their titles.

# Install

Eventually this extension will be posted on the Google Chrome Extension Marketplace. For now, you can download the directory using github desktop.

Once you have downloaded, navigate to the directory and run two commands. `npm install` then `npm run dist` which should build the extension. Please note the **Enviroment requirements** down below.

# After Install

Once installed you're going to open the [popup window](https://i.imgur.com/WdxKyc6.png).

In this window you can add any keys you want to block _(non-case-sensitive, length > 3)_, temporarily disable certain keys or remove them entirely.

_Note: This plugin was made in one day for mostly personal use, currently if you add a lot keys it may start to lag if you load a lot of videos. That's just a suscipicion I have, but be warned._

# Support

Donations for those who like the extension are appreciated, but not required.

BTC 37ag3836y5mDnqNjFZurwAziwUfCAAJybZ
ETH 0x44bA9Fc4931f4eCaBE45c161b7cF8eaEe54dE283
XRP rw2ciyaNshpHe7bCHo4bRWq6pqqynnWKQg Tag 2632592722

Or if you wish to [leave a message](https://streamlabs.com/creativebuilds/tip)

## This starter consists of the following parts

- Background script (vanilla TS)
- Content script (vanilla TS)
- Popup page (React.js, Styled Components)

_And, of course, the `./manifest.json` file describing its configuration._

## Environment

- Node.js >=12.0.0
- NPM >= 6.0.0
