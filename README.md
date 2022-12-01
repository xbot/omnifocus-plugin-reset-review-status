# omnifocus-plugin-reset-review-status
Reset review status of projects under selected folders.

## Quick Start Guide

### Dependencies

This plugin depends on the [omnifocus-plugin-libdev](https://github.com/xbot/omnifocus-plugin-libdev) library.

### Installation

Clone the repo and link it in the Automation Configuration dialog in OmniFocus, or add it as a git submodule to the default plugin folder of OmniFocus. I recommend the latter for an easier synchronization with other devices.

```shell
cd ~/Library/Mobile Documents/iCloud~com~omnigroup~OmniFocus/Documents/Plug-Ins

git init

# Install the dependent library, ignore this if you have already installed it.
git submodule add https://github.com/xbot/omnifocus-plugin-libdev.git libdev

git submodule add https://github.com/xbot/omnifocus-plugin-reset-review-status.git reset-review-status

# For updating:
git submodule update --remote --recursive
```
