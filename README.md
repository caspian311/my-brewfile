# My Brewfile file

Use [Homebrew](https://brew.sh/) to install packages on your MacOS. Then your _Brewfile_ to maintain the packages so you can quickly get a new environment up and running.

### Prerequisites

You'll need brew bundle to make this work. To get that, use the following command...

    $ brew tap Homebrew/bundle

### Create

To create or update a _Brewfile_, run the following command...

    $ brew bundle dump

This generates a _Brewfile_ in the directory you are in.

### Restore

To restore your brew packages, run the following while in the directory where you _Brewfile_ is located...

    brew bundle

### More info

This was all stolen from [here](https://tomlankhorst.nl/brew-bundle-restore-backup/).