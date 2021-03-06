Visicut settings
================

Settings for [VisiCut](https://github.com/t-oster/VisiCut) (A userfriendly tool to prepare, save and send Jobs to Lasercutters) used by [ZAM](https://zam.haus).

Instructions
------------

 * Delete all settings before you clone this repo:
    
    ```bash
    rm -rf ~/.visicut/
    ```

 * Clone the repo to .visicut:
    
    ```bash
    git clone git@github.com:zam-haus/visicut-settings.git ~/.visicut
    ```


 * To update the settings run:

    ```bash
    cd ~/.visicut
    git pull
    ```

 * Before you commit changes, please check the settings by running
    `git diff`
   and
    `git status`
  inside the repository. Check also, that the settings are working properly.

*  Then add and commit everything:
    
    ```bash
    git add -A
    git commit -A
    ```
