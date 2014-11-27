# Isotools GIT helper : busGitTools

## Install
- Step 1: install git command line interface. You can download it from http://git-scm.com
- Step 2: clone this repository into your "builder" directory. For example, the following command:

    C:\myIsotoolsFolder\builder> git clone https://github.com/isotools-busLab/busGitTools.git busGitTools

will clone busGitTools repository into "busGitTools" folder (it will create the folder if it doesn't exist).

## Features

Batches are here to help you map and pull all the components and themes. They all need the git cli system.

- migrationFromTFSTOGit_components : Suppress old components folders and clone all.
- migrationFromTFSTOGit_themes : Suppress old themes folders and clone all.
- NOSUPPRESSmigrationFromTFSTOGit_components : Just clone (for new workspace) 
- PULLGit_components : Pull all the components

## Road map

- Do a for loop instead of line by line
- Add a push bash
