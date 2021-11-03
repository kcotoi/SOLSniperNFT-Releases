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
  <a href="https://twitter.com/KC0T0I">
    <img src="https://img.shields.io/twitter/follow/KC0T0I?label=Follow&style=social" alt="Twitter">
  </a>
</p>

S◎LSniperNFT allows you to easily see the ranks of the NFTs directly on you favorite Marketplaces.

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
    - For example if we want to map The Tower collection on Magic Eden with rankings from Moonrank.
      - Magiceden link : https://magiceden.io/marketplace/the_tower
      - Moonrank link : https://moonrank.app/collection/towerdao
    - We will have to set in the popup the following:
      - Marketplace Collection ID : the_tower
      - Moonrank Collection ID : towerdao
        ![Mappings png](images/Mappings.png)

## 💻 How to install on Firefox

- Get it from <a href="https://addons.mozilla.org/en-US/firefox/addon/solsnipernft/"> here</a>

## 💻 How to install on Chrome, Brave, Edge, Opera

- Download the Release 1.3 zip file , unzip it, and load the unziped folder into your browser.
- <a href="https://github.com/kcotoi/SOLSniperNFT-Releases/releases/download/Release1.3/solsnipernft-v0.1.3-production.zip">Link here</a>

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

- Improve the UI. Currently the ranks are not shown very nice so this will be improved.

- Inform user that the ranking has not be found and should check if mapping is needed.

- Add more mappings to the application (This is something that will be done weekly)

- Refactor code

- Improve performance of the extension

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

