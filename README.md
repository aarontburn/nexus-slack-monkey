# [Nexus](https://github.com/aarontburn/nexus-core): Slack Monkey

  <img src="./src/assets/icon.png" alt="Slack Monkey Icon" width="200"/>

A module for [Nexus](https://github.com/aarontburn/nexus-core) to "embed" Slack as a Nexus module...

And by "embed", this just takes your Slack window and monkeys it around.



<p align="center">
  <img src="./assets/image.png" alt="Slack Monkey Sample" width="1000"/>
</p>

## Required Dependencies
### Module Dependencies
You will need the following modules installed into Nexus.
- [**Monkey Core**](https://github.com/aarontburn/nexus-monkey-core)

### Application Dependencies
The following applications need to be installed to your computer.
- [**Slack**](https://slack.com/downloads)
  - Windows: Download using the `.EXE` installer; Slack from the Microsoft Store (or from the `.MSIX` installer) will prevent you from accessing its executable path which removes some features.

## Installation
1. Download and install all dependencies.
2. Download the latest release `.zip`. 
3. In Nexus, navigate to **Settings** > **Import Module**
4. Select the downloaded `.zip` file to install.


## Usage
- On startup (or when the `Locate window` button is pressed), Slack Monkey will look for your open Slack window, and, if found within 10 seconds, will start monkeying the window into Slack.
- By providing a path to your Slack executable in the Settings, you unlock the following features:
  -  Opening the Slack app while it's already embedded into Slack will swap to the Slack Monkey module.
  -  The `Locate window` button will start a new instance of Slack if one isn't found.
