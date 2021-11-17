<div align="center">
  <br>
  <img alt="S◎LSniperNFT" src="https://raw.githubusercontent.com/kcotoi/SOLSniperNFT-Releases/master/images/SolSniperNFTLogo.png" width="300px">
  <h1> Easily snipe best ranked NFTs!</h1>

</div>
<br>
<p align="center">
  <img src="https://img.shields.io/github/commit-activity/w/kcotoi/SOLSniperNFT-Releases" alt="GitHub commit activity">
  <a href="https://github.com/kcotoi/SOLSniperNFT-Releases/issues">
    <img src="https://img.shields.io/github/issues/kcotoi/SOLSniperNFT-Releases" alt="GitHub issues">
  </a>
  <a href="https://github.com/kcotoi/SOLSniperNFT-Releases/releases">
    <img src="https://img.shields.io/github/v/release/kcotoi/SOLSniperNFT-Releases.svg?style=flat" alt="GitHub Release">
  </a>
  <a href="https://twitter.com/SOLSniperNFT">
    <img src="https://img.shields.io/twitter/follow/SOLSniperNFT?label=Follow&style=social" alt="Twitter">
  </a>
</p>

S◎LSniperNFT allows you to easily see the ranks of the NFTs directly on your favorite Marketplaces.

![solsnipernft png](images/solsnipernft.png)

## 🔥 Features

- Show ranks from howrare and moonrank on supported marketplaces.
  - Howrare has multiple ways of calculating ranking but we show only the following 3 types:
    - HR - this is howrare own ranking system more info <a href="https://howrare.is/faq/#rarity_calculation">here </a>
    - ST - Statistical ranking more info <a href="https://howrare.is/faq/#statistical_rarity">here</a>
    - NT - Normalized traits more info <a href="https://howrare.is/faq/#trait_normalization">here</a>
  - Moonrank supports one type of ranking and this is calculated using statistical ranking system.

## 📖 Extension Settings

- The extension pop-up allows you to :
  - Enable/Disable ranks to be shown.
    ![Settings png](images/Settings.png)
  - Enter your own thresholds and colors for colouring ranks.
  - Enter your own mappings. On mappings page you can enter your own mappings to make sure that we
    find the rankings. The names can be found at the end of the urls:
    - For example if we want to map Solana Monkey Business collection on Magic Eden with rankings from Howrare, you will have the following:
      - Magiceden link : https://www.magiceden.io/marketplace/solana_monkey_business
      - Moonrank link : https://howrare.is/smb
    - We will have to set in the popup the following:
      - Marketplace Collection ID : solana_monkey_businessr
      - Moonrank Collection ID : smb
        ![Mappings png](images/Mappings.png)

## 💻 How to install on Firefox

- Get it from <a href="https://addons.mozilla.org/en-US/firefox/addon/solsnipernft/"> here</a>

## 💻 How to install on Chrome

- Get it from <a href="https://chrome.google.com/webstore/detail/s%E2%97%8Elsnipernft-snipe-best-r/ogefhfdeljjlmhmbipoimkggolpeghan"> here</a>

## 💻 How to install unpacked extension on Chrome, Brave, Edge, Opera

- Download the Release 1.4 zip file , unzip it, and load the unziped folder into your browser.
- <a href="https://github.com/kcotoi/SOLSniperNFT-Releases/releases/download/release1.4/solsnipernft-v0.1.4-production.zip">Link here</a>

## 🏦 Supported Marketplaces

| Marketplace | Status |
| ----------- | ------ |
| MagicEden   | ✅     |
| Alpha.art   | ✅     |
| Solanart    | ✅     |

## 📊 Supported Ranking Sites

| Ranking Site | Status |
| ------------ | ------ |
| Howrare      | ✅     |
| Moonrank     | ✅     |
| Soltracker   | ⏳     |

## 💻 Supported Browsers

| Browser         | Status |
| --------------- | ------ |
| Chrome          | ✅     |
| Mozilla Firefox | ✅     |
| Brave           | ✅     |
| Microsoft Edge  | ✅     |
| Opera           | ✅     |

## 🛎️ Issues

- Please let me know if you find any.

## 📈 Future developments

- Inform user that the ranking has not be found and should check if mapping is needed.

- Add more mappings to the application (This is something that will be done weekly)

- Add other marketplaces and ranking sites

- Please let me know any of your wishes

## 🎯 Release History

- 1.0 Initial Version

- 1.2 Release info:

  - Fixed bugs:
    - Issue with extension icon.

- 1.3 Release info:
  - New changes/ added features:
    - Thresholds - now you can set your own thresholds for colouring and choose your own colors.
    - When you enable/disable ranks the changes are reflected immediatly in the UI.
    - Added mappings for collections that can be seen on howrare and don't follow a predictable pattern
    - Removed column for Moonrank in Mappings page as this is not needed from now on.
  - Fixed bugs:
    - Issue with magiceden when you switch to Activity tab and come back the ranks were not shown.
    - Issue with magiceden when you go into detail page and come back the ranks were not shown.

- 1.4 Release info:
  - Fixed bugs:
     - Issue with getting collection name when we have no mappings for a marketplace.
     - Issue with alphart when getting collection name while filtering.
  - Improved the performance of extension.
    	- Now we save the ranks for the NFTs you see in the local storage so when you visit it next time it will be shown faster. Also we don't make a lot of requests to ranking sites anymore.
  - Improved the layout of rankings. (Still some improvements to be done)
    - Made the ranks to be links that will redirect you to the ranking page.
      - NOTE: On Alpha.art you have to right click on the rank and click on open in new tab.

- 1.5 Release info:
    - Fixed bugs:
      - Issue with adding new ranks when collection is not initialized.
    	- Issue with setting multiple mappings.
          - Now you are able to open the popup in a new tab and you will be able to insert multiple mappings.
    	- Fixed issues with Naked meerkat and Meerkat Millionaire collection when I get rank from howrare. 
          - Now also the NFTs with leading zero  in  the numbeer will be fetched.
   -  New changes/ added features:
      - Added new marketplaces:
    		  - Digitaleyes.market
    		  - Exchange.art
    	- Removed statistical rating and normalized traits from howrare (ST, NT) based on user feedback.
   - Added button in the popup to open it in a new page
   - Clear Cached Ranks Page:
     - Added option to clear the rankings. 
      - Now in the popup you can go to the Ranks page and delete the collection you don't see that often or you added a new mapping for it and you want to refresh the ranks on the next page load.

   - Implemented a rate limiter for the requests sent to ranking providers and a sleep and retry process to fetch the  ranks after the temporary block ends.
   - Added code (NF) to inform user to check for mappings.
      - If you see "NF" instead of ranking it means that the rankings are not found.
        - There can be 3 reasons for this : 
            1) The rankings are not provided but this ranking provider. 
            2) You need to add mappings for this new collection.
                NOTE: After you add a new mapping please refresh the page, to request new rankings. 
                    (See Clear Cached Ranks) 
            3) There is a bug with the extension, if you checked that the collection is supported by the ranking provider you have added mappings for it and you still have the issue.Then please contact me (via discord or twitter) and I will try to help you.
        - If you see the loading icon, please wait until the requests are finished. 
          It should take a few seconds. Currently when you try to look at too many NFTs (60 or more in 2-3 seconds by scrolling quickly).it will send all the request to ranking providers. 
          
          Some of them may have limits in place for the amount of requests someone can do, for this reason they may temporarily restrict yuur access to their website for a few seconds.

          But no worries the extension will try to get the rankings again after the temporary ban is lifted, so don't worry and just wait a few and the rankings will show up.

NOTE: To ensure the best experience I advise you to scroll slowly to avoid sending too many requests in a short amount of time.
