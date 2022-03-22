# pyJAMa
_the low orbit floating island cannon_

## Content
1. Introduction
2. Installation
3. Config

## Introduction
pyJAMa is a script that makes LDJAM theme voting less painful. It supports bulk voting themes that fit a given keyphrase and can be used to vote on themes in general.

## Functions
- Command line based voting
- Bulk voting

## Installation
1. Go to [RELEASES](https://github.com/InitialPosition/LDJAMPlus/releases) and download the latest release version.
2. Make sure Python 3 is installed. You can check by typing `python3 --version` into your terminal. If a string containing a version number is displayed, continue. Otherwise, install Python 3 from the [OFFICIAL WEBSITE](https://www.python.org/downloads).
3. Create a virtual python environment by typing `python3 -m venv <target folder>` into your terminal and switch to it using `source <target folder>/bin/activate`. If creating the environment fails, you may need to install venv3 by typing `sudo apt install python3-venv` first.
4. Install the required packages by running `python3 -m pip install -r requirements.txt` while the virtual environment is active.
5. To launch the program, use the command `python3 main.py`.
6. Enter your cookie data when the program asks you to. **The cookie will be saved locally and is NEVER sent anywhere except to the official LDJAM website.**

### Cookie Data
The program needs your session cookie from ldjam.com to communicate with the website API and to vote on themes. Your cookie can be found like this:

- FIREFOX: go to ldjam.com. Make sure you are logged in. Press F12 to open the developer console and switch to the "Storage" tab. Select the "Cookie" entry from the list on the left. Your cookie should be displayed here.
- CHROME: go to ldjam.com, making sure you are logged in. Click on the padlock to the left of the URL, then click on "Cookies". You should now see your cookie under "ldjam.com".
- OPERA: go to ldjam.com. Make sure you are logged in. Go to Settings > Privacy & security and click the ldjam cookie to see the content.

## Roadmap
- [ ] Load tokens automatically

Entering tokens manually is not the most elegant solution. There might be a way to detect the browser used on the machine and to extract the cookies automatically.

- [X] GUI

A GUI would be nice to have to make the program more accessable to people who don't like using the command line or that don't want to deal with pip requirements.
