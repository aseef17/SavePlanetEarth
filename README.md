# [Save Planet Earth](https://saveplanetearth.io/)

This repository contains a rudimentary API for SavePlanetEarth. Which will be consumed by the Website as well as the Mobile Application

<img src="assets/icon.png" align="left" height="95" width="95">  

<br/>
<br/>
<br/>
<br/>

## APIs

#### [Token Info API](https://raw.githubusercontent.com/aseef17/SavePlanetEarth/main/spe_token_info.json)
- Details about HODLs, Trees Planted and Tokens Burnt
- Details about Tokenomics
- Social Links
- Donation Wallet/s along with description

#### [Team Info API](https://raw.githubusercontent.com/aseef17/SavePlanetEarth/main/spe_team_info.json)
- Details about team members of SPE along with their socials (if present)

#### [Configuration API](https://raw.githubusercontent.com/aseef17/SavePlanetEarth/main/spe_configuration.json)
- Maintenance toggle
- White Paper URL
- List of Announcements

#### [Markets API](https://raw.githubusercontent.com/aseef17/SavePlanetEarth/main/spe_markets_info.json)
- List of Exchanges $SPE is listed on along with basic information
- Featured Exchange

#### [Swap Backgrounds API](https://raw.githubusercontent.com/aseef17/SavePlanetEarth/main/spe_swap_background.json)
- Different swap backgrounds with various configurations

#### [Road Map API](https://raw.githubusercontent.com/aseef17/SavePlanetEarth/main/spe_roadmap.json)
- Road Map for Save Planet Earth LTD

## Changelog

- Updated Configuration API to add the WhitePaper URL
- Updated Road Map API with LottieAsset
- Added Road Map API to track live Road Map of Save Planet Earth LTD
- Updated Swap Background API to support `speTextColor` attribute
- Added Configurations for Swap Background
- Added Configuration API for announcement and scheduled maintenance
- Added Markets API for a list of Exchanges $SPE is listed on
- Added donation wallets to the Token Info API