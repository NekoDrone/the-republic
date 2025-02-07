# The Republic

The Republic is a private Minecraft modpack for a group of friends. Feel free to download the modpack and play with it, but the server IP is hidden as it is meant to be a private server, sorry!

The modpack is hosted as a `packwiz` modpack on GitHub for ease of distribution.

# Installation

There are two ways to install, from Pages, or from repository. I would recommend you install from Pages.

## From Pages

This method installs from the linked GitHub Pages page.

### Requirements

Prism, MultiMC, ATLauncher, or any other multi-instance minecraft launcher that can support prelaunch tasks.

### Steps

1. Download the pack [here]() (NYI)
2. Import it into your launcher of choice `Import from zip`.

On the first launch, the installer utility will handle downloading the mods and configs for you automatically.

On subsequent launches, the installer utility checks the GitHub Page for any updates to the modpack's metadata and automatically keeps you updated with the other players on the server.

## From repository

This method involves you cloning the repo and using `packwiz` to install and export the modpack to your launcher of choice.

Use this version if you'd like greater control over the modpack, or you'd like to use mod platforms like Modrinth or CurseForge.

> [!NOTE]
> This method prevents you from receiving automatic updates, and should be used if you know what you're doing, or you want to learn.

### Requirements

1. Git
2. Golang (1.19 or later)
3. A CLI of your choice. (I use Alacritty).

### Steps

1. Install [`packwiz`](https://github.com/packwiz/packwiz).
2. Clone this repository `git clone https://github.com/NekoDrone/the-republic.git/`
3. Enter the folder `cd the-republic`
4. Export the modpack `packwiz {curseforge|modrinth} export`
5. Import the modpack into CurseForge or Modrinth.