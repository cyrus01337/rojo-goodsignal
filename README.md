# Rojo-compliant GoodSignal
Stravant's signal implementation, A.K.A. GoodSignal, converted to a Rojo-compliant file structure to allow for inclusion as a Git sub-module. Full credits go to [Stravant](https://github.com/stravant), more info available at [the original repo.](https://github.com/stravant/goodsignal)

The reasoning behind me doing this is mostly for my own purposes and workflow, while anyone who also follows a similar workflow can also indulge in the repo at their leisure, I am in no way trying to steal work that is not mine. To double down, this repo is made **purely for my own convenience** when using Rojo.


## License
Inherited from the original repo as of 8th May 2022, [see here.](https://github.com/cyrus01337/rojo-goodsignal/blob/rojo/LICENSE)


## Prerequisites
There is an approach that uses Git if your project is Git-oriented for simplicity, however, approaches still exist for non-Git and strictly Roblox Studio users as well. If your project is or going to be on Github, your only requirement will be [Git](https://git-scm.com/).


## Setup
- [For Git users](https://github.com/cyrus01337/rojo-goodsignal#Git)
- [For strictly Rojo users](https://github.com/cyrus01337/rojo-goodsignal#Rojo)
- [For strictly Roblox Studio users](https://github.com/cyrus01337/rojo-goodsignal#ROBLOX-Studio)


## Git
After you've cloned the repo, all you need to do is change directory to the location you want GoodSignal to be installed and run:
```sh
git submodule add -b rojo https://github.com/cyrus01337/rojo-goodsignal.git GoodSignal
```

For those new to sub-modules, this clones the repo from the rojo branch only (`-b rojo ...`) and creates the folder under the name GoodSignal (`git submodule add ... <url> GoodSignal`) then adds the sub-module as a dependency to your project. If you didn't already have a sub-module added before, a new `.gitsubmodules` file will appear at the root of your project that stores metadata for Git to use as CLI settings when manipulating (i.e. pulling, fetching) the repo. More info on Git sub-modules [here.](https://git-scm.com/book/en/v2/Git-Tools-Submodules)


## Rojo
Download the repo as shown in the diagram below then extract it where you would like to have it installed.
![Click "Code" then click Download ZIP](https://i.imgur.com/CoMPFJb.png)


## ROBLOX Studio
For Studio users, [go here](https://github.com/cyrus01337/rojo-goodsignal/blob/rojo/init.lua) or click the `init.lua` in the repo. Right-click the "Raw" button and save the link as a file, then go into Studio, right-click the instance you want to insert the script into, select "Insert from file..." and open the file you saved.


## Note
All contributions to the original GoodSignal should either be made on your own fork of the original repo or sent as PRs there, [link here.](https://github.com/stravant/goodsignal)
