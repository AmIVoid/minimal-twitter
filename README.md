<p align="center">
  <img alt="Minimal Twitter Icon" src="./minimal-twitter-icon.svg"/>
</p>

<h1 align="center">
  Minimal Twitter
</h1>

Minimal Theme for the new Twitter UI – [install now](#installation)!

This theme aims to drastically simplify and declutter the new Twitter UI. By default:

- Edited for effective use of space
- No border on main feed
- Hidden navigation labels (shown on hover)
- Navigation pushed to left side of window
- No trends or “Who to Follow” on Home Page
- Search on top right
- Tweet button on bottom right.

![screenshot](./screenshot.png)

## Installation

- [Chrome Extension](#chrome)
- [Firefox Add-on](#firefox)
- [Safari Extension - unofficial](#safari-extension-unofficial)

### Chrome

[Get from original developer on Chrome Web Store](https://chrome.google.com/webstore/detail/pobhoodpcipjmedfenaigbeloiidbflp)


### Firefox

[Get from original developer on Firefox Browser Add-ons](https://addons.mozilla.org/en-US/firefox/addon/min-twitter/)

[How to set Firefox preferences](#firefox-preferences)

Manual installation: 

1. Go to "about:debugging"
2. Click "This Firefox"
3. Download firefox.zip from [Releases](https://github.com/AmIVoid/minimal-twitter/releases)
4. Click "Load Temporary Add-on..." and select firefox.zip

(Will have to repeat everytime firefox is restarted unless on the Dev Edition, Nightly, or ESR of Firefox.)

Manual installation for Dev Edition, Nightly, or ESR:
1. Go to "about:config"
2. Set `xpinstall.signatures.required` to **false**
3. Go to "about:addons"
4. Download firefox.zip from [Releases](https://github.com/AmIVoid/minimal-twitter/releases)
5. Drag firefox.zip into about:addons

### Safari Extension (unofficial)

Who the fuck cares lmao

## Chrome and Firefox Preferences

Customization currently available in Chrome and Firefox! ⚙️

- Select preferred width of Twitter feed sections
- Anchor navigation to top
- Minimize borders between tweets, in explore, and in notifications
- Hide the bottom right Tweet button
- Hide retweet and/or like numbers

### Firefox Preferences

1. Right click or secondary click on the Minimal Twitter Extension and select "Manage Extension"
2. Go to "Preferences" tab
3. Select preferences
4. Click "Save" button

![Firefox Preferences](preferences-firefox.png)

## Developing

- [Firefox Add-ons Documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons)
  - [How to load add-ons into Firefox locally](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Temporary_Installation_in_Firefox)
