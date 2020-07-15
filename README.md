# Data preprocessing for the GCBM implementation in Chile
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

## About

This repo contains the data preprocessing algorithms performed by Chile in order to preprocess the official data to fit with the Generic Carbon Budget Model (GCBM) format. This products consists in a proof of concept and a work of progress, that uses the Los Rios Region, in southern Chile, as pilot area.

The preprocessing steps were designed to mimic the data preparation conducted by Chile in the elaboration of its Forest Reference Emissions Level / Forest Reference Level, [FREL/FRL](https://redd.unfccc.int/files/chile_mod_sub_final_01032017_english.pdf), submitten in August 31th, 2016.

The methods and results of this work were compiled into the [technical document](https://moja.global/wp-content/uploads/2020/04/Chile_GCBM_Pilot_Technical_Document.pdf) "Modelling forest carbon dynamics for REDD+ using the Generic Carbon Budget Model (GCBM)", were more details can be found.

Disclaimer: The results derived from the use of this algorithms do not necessarily reflect the positions of the Government of Chile for REDD+ accounting or any other purpose.

## Environment

This repo was tested using R 3.6.3 (64-bit) on a Windows 10 OS

## Run instructions

1. Clone or download the repo
2. Go to "releases"" and download the Input data (the expected output is also available)
3. Unzip the input data folder into the project folder

To make sure the R codes will work as expected, make sure you have the following directory structure

``` bash
├── Preprocessing_Codes
├── Input_Files
│   ├── Growth                # Excel spreadsheet with growth data
│   ├── LUC                   # Trazabilidad (Land use) data
│   ├── SOC                   # Soil Organic carbon data
|   └── Temperature           # Temperature raw data (NetCDF)
├── Output_Files
│   ├── input_database
│   └── layers
│     └── raw 
        ├── disturbances
│       ├── environment                   
|       └── inventory
├── README.md
└── ...
```

4. Run the processing codes inside the Preprocessing_codes folder in order

(I strongly reccomend the use of the RStudio IDE to run the R codes)

## How to Get Involved?  

moja global welcomes a wide range of contributions as explained in [Contributing document](https://github.com/moja-global/About-moja-global/blob/master/CONTRIBUTING.md) and in the [About moja-global Wiki](https://github.com/moja-global/.github/wiki).  

  
## FAQ and Other Questions  

* You can find FAQs on the [Wiki](https://github.com/moja.global/.github/wiki).  
* If you have a question about the code, submit [user feedback](https://github.com/moja-global/About-moja-global/blob/master/Contributing/How-to-Provide-User-Feedback.md) in the relevant repository  
* If you have a general question about a project or repository or moja global, [join moja global](https://github.com/moja-global/About-moja-global/blob/master/Contributing/How-to-Join-moja-global.md) and 
    * [submit a discussion](https://help.github.com/en/articles/about-team-discussions) to the project, repository or moja global [team](https://github.com/orgs/moja-global/teams)
    * [submit a message](https://get.slack.help/hc/en-us/categories/200111606#send-messages) to the relevant channel on [moja global's Slack workspace](mojaglobal.slack.com). 
* If you have other questions, please write to info@moja.global   
  

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table><tr><td align="center"><a href="http://moja.global"><img src="https://avatars1.githubusercontent.com/u/19564969?v=4" width="100px;" alt="moja global"/><br /><sub><b>moja global</b></sub></a><br /><a href="#projectManagement-moja-global" title="Project Management">📆</a></td></tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!


## Maintainers Reviewers Ambassadors Coaches

The following people are Maintainers Reviewers Ambassadors or Coaches  

<table><tr><td align="center"><a href="http://moja.global"><img src="https://avatars1.githubusercontent.com/u/19564969?v=4" width="100px;" alt="moja global"/><br /><sub><b>moja global</b></sub></a><br /><a href="#projectManagement-moja-global" title="Project Management">📆</a></td></tr></table>  

**Maintainers** review and accept proposed changes  
**Reviewers** check proposed changes before they go to the Maintainers  
**Ambassadors** are available to provide training related to this repository  
**Coaches** are available to provide information to new contributors to this repository  
