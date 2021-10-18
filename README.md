> A script to cleanup up non-MP4s and non_JPGs. Should be easy to expand to other file types.

## Purpose

This was a \~30 minute type of effort that I wrote to automate a friend's GoPro cleanup as his GoPro spit out a bulk of all types of files he didn't want. 

## Error Debugging

If you're getting an error it's almost guranteed to be an error with file permissions. To fix try running the usage commands with sudo. If it still doesn't work your then the files are probably mounted as read-only.

## Installation

In a Linux terminal:

```sh
cd /~/Desktop/
git clone https://github.com/shford/Nix-File-Cleanup-Scripts.git
chmod 744 Delete_NonMP4s.sh
```

## Usage:
Open a Linux Terminal

```sh
cd /~/Desktop/
./script.sh click_and_hold_to_drag_and_drop_folder_into_terminal
```
Follow the prompts - I recommend utilizing the backup feature until you're familiar with the tool although it's hard to mess up.

## Release History and Support
Tested and regurlarly used on Ubuntu 18.04 and 20.04. Runs off bash shell. Fairly basic script - should work across on modern version of bash. Might work on other shells but currently untested.

## License
None. Do what you want with this, but I'm in no way liable for losses, damage, security flaws, or anything else this might do to your system(s). Use at your own risk.