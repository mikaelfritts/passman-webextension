# Passman Webextension
![Build Status](https://passman.cc/webextension-version.php)
[![Build Status](https://travis-ci.org/nextcloud/passman-webextension.svg?branch=master)](https://travis-ci.org/nextcloud/passman-webextension)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a3dd62087e5e4d2488314dbad02336df)](https://www.codacy.com/app/brantje/passman-webextension?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nextcloud/passman-webextension&amp;utm_campaign=Badge_Grade)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/nextcloud/passman-webextension/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/nextcloud/passman-webextension/?branch=master)


[![Chrome webstore](https://img.passman.cc/assets/chromewebstore.png)](https://chrome.google.com/webstore/detail/passman/hlpjhlifkgmoibhollggngbbhbejecph) | [![AMO](https://img.passman.cc/assets/AMO-button_1.png)](https://addons.mozilla.org/en-US/firefox/addon/passman/)    
-----------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
<img align="left" src="https://img.shields.io/chrome-web-store/users/hlpjhlifkgmoibhollggngbbhbejecph.svg"> <img align="right" src="https://img.shields.io/chrome-web-store/rating/hlpjhlifkgmoibhollggngbbhbejecph.svg">| <img align="left" src="https://img.shields.io/amo/users/passman.svg"> <img align="right" src="https://img.shields.io/amo/rating/passman.svg">



Passman @359f8491b7faeaa48d50abf712233dd81953597d with pr #270 applied.

Fixes issue with Vault  not loading on Google Chrome 68.0.3440.106 Mac.

Getting it to run (until an official release has fixed this):

 - `git clone git@github.com:mcguffin/passman-webextension.git`
 - `cd passman-webextension`
 - `npm install`
 - `grunt build`
 - (chrome://extensions/)[chrome://extensions/]
 - Turn off the original passman
 - Switch on developer mode
 - Upload unpacked extension: choose the `dist` folder in the `passman-webextension` directory
 - Switch developer mode off again.

My personal advice: Don't take any code from strangers.



Tested on:   
- Chrome
- Firefox
- Safari

This extension aims to provide you with your passwords in your browser.   
The passwords will be provided by [passman](https://github.com/nextcloud/passman).   


## Features
- Add multiple accounts
- List accounts for the current site
- Detect new logins and save them to passman
- Update existing logins in passman
- Build-in OTP generator
- Search for credentials

Make sure the credential has an url set, otherwise the extension won't be able to find accounts.


## Support Passman
Passman is open source, but we would gladly accept a beer (or pizza!)   
Please consider donating via
- [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6YS8F97PETVU2)
- [Patreon](https://www.patreon.com/user?u=4833592)
- Bitcoin: 1H2c5tkGX54n48yEtM4Wm4UrAGTW85jQpe



If you want to use this extension as a base for your own extension, please do so =).   
