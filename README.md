# COVID-19 Open Data Philippines

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://raw.githubusercontent.com/altcoder/ncov-open-data-ph/master/LICENSE)
[![Chat with us at https://gitter.im/ncov-open-data-ph](https://badges.gitter.im/ncov-open-data-ph.svg)](https://gitter.im/ncov-open-data-ph?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

** THIS PROJECT IS NO LONGER UPDATED. PLEASE USE DOH's CSV FILES AVAILABLE AT [PUBLIC GDRIVE](https://drive.google.com/drive/u/0/folders/10VkiUA8x7TS2jkibhSZK1gmWxFM-EoZP) **

Generate machine readable data for tracking COVID-19 in the Philippines. 

Data source from Google Sheets maintained by [r/Coronavirus_PH subreddit
community](https://docs.google.com/spreadsheets/d/1wdxIwD0b58znX4UrH6JJh_0IhnZP0YWn23Uqs7lHB6Q/edit#gid=0)

## Quickstart

You need Python 3.x and Google API credentials to generate the dataset.

1. Clone this repo.

```
$ git clone https://github.com/[GITHUB_USERNAME]/[REPO_NAME].git
$ cd [REPO_NAME]
```

2. Follow **Step 1** and **Step 2** of the insturctions below to generate
   an access tokey using your Google API credentials.

[Link to Grant Access to Google Sheets](https://developers.google.com/sheets/api/quickstart/python)


3. Run quickstart.py included in this repo. The script will generate the dataset
   in csv format inside `ouput` directory.

```
$ python quickstart.py
```

### Official DOH NCOV Case Tracker Dataset
- You can access source dataset of the [DOH NCOV Case Tracker dashboard](https://ncovtracker.doh.gov.ph/). 

# CONTRIBUTING

Contributions are always welcome, no matter how large or small. Before contributing,
please read the [code of conduct](.github/CODE_OF_CONDUCT.md).
