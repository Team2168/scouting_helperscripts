# Scouting Helper Scripts

These are a collection of python scripts to pull data from The Blue Alliance. These are also designed to be self-contained, so they can be used outside of this project.

This project is powered by [The Blue Alliance](https://www.thebluealliance.com/), but is not associated with them in any way.

# Usage
- [Required Software](#setup)
- [Navigating The Blue Alliance](#how-to-use-tba)


# Setup

## Download python3
Go to <https://www.python.org/downloads/> and download the latest python for your operating system.

### Note for Windows

Make sure you select "Add python.exe to PATH" at the start of installation.

![Emphasis on path checkbox](./assets/use_path.png)

At the end of installation, it will ask if you want to disable the
path length limit. Click the option to do this.

![Emphasis on path limit](./assets/path_limit.png)

## Downloading the scripts
The scripts have no external dependencies, so they can simply be downloaded and used.

To download the scripts repository on windows, open a new Git Bash window, and run `cd ~/Documents/`, then `git clone https://github.com/Team2168/scouting_helperscripts.git`. The scripts will now be located at `Documents\scouting_helperscripts`. Type `cd scouting_helperscripts` to open this folder.

# How to use TBA
*The Blue Alliance* is an external website used to collect and query FIRST match data. To query this data, we need to create an [API](https://en.wikipedia.org/wiki/API) token to authenticate requests we make to TBA.

## How to get an API key

To get an API key, you must first create an account with TBA. To do this, go to <https://www.thebluealliance.com/>, and select More > Account in the menu.

![TBA account menu](./assets/account_tab.png)

Then, create an account by linking a Google or Apple account and providing a username.

![Creating TBA Read API Keys](./assets/creating_key.png)

Scroll down in the account settings until you reach **Read API Keys**. Enter a description here for your own purposes, and click "Add New Key".
Copy the value under `X-TBA-Auth-Key`, and keep it safe. This value is used to identify your account to the Blue Alliance!

![TBA Read API Key Generated](./assets/created_key.png)

## How to find the event key

# Getting Data
## Event Roster
## Event Schedule
# Adding data to Google Sheets
