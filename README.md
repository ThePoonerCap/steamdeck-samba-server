<h1 align="center">SteamDeck Samba Server</h1>
<p align="center">
  <i>This is a simple script that sets up a Samba server on your SteamDeck, allowing you to easily transfer files to and from your device.</i>
  <i> Changed to open samba for all devices in var/run/media </i>
  <br/>
  <br/>
  <br/>
  <br/>
  <a name="download button" href="https://github.com/ThePoonerCap/steamdeck-samba-server/releases/download/latest/samba.download"><img src="./docs/download_button.svg"  alt="Download steam-deck-samba-server" width="350px" style="padding-top: 15px;"></a>
  <br/>
  <br/>
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-0aa8d2?logo=opensourceinitiative&logoColor=fff" alt="License MIT">
  </a>
</p>

## Installation

To run the script, simply insert the following command in your SteamDeck terminal:

 
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ThePoonerCap/steamdeck-samba-server/main/script.sh)"`


This will automatically download and run the script.sh file from the GitHub repository, which will install and configure the Samba server on your SteamDeck.

## Usage

Once the Samba server is installed, you can connect to it from any device on the same network. Simply open a file explorer window on your computer, and type the following in the address bar:

`\\steamdeck`

You should then be prompted to enter your SteamDeck username and password. Once you do so, you'll be able to access the files on your SteamDeck just like any other shared folder.

