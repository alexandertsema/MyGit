# MyGit

## Overview

This is small script to set up a local Git server.

## Usage

### On your server:
* Adjust WORKING_COPY_PATH and GIT_BARE_PATH as needed inside the script.
* Make %GIT_BARE_PATH% shared folder and share it among desired Windows users.
* To create a new repository run the script with double click and put the repository name.

### Clients:
* Each team member should map the network drive with %GIT_BARE_PATH% to their local machine.
* The mapped drive can be used as a remote repositories catalog (like you use GitHub).