# PocketMine-Soft

PocketMine-MP Project with less overhead, tuned for small servers

## How To

Init the PocketMine-MP module: `git submodule update --init --recursive`

Apply patches: `./applyPatches.sh`

### Create patch ###

`cd PocketMine-Soft-Core`

Do changes

Add your file for commit: `git add <file>`

Commit: `git commit -m <msg>`

`cd ..`

Create patch: `./rebuildPatches.sh`

### Install PocketMine-Soft ###

On Linux: `wget -q -O - http://get.pocketmine.net/ | bash -s - -v soft`

On MacOS: `curl -sL http://get.pocketmine.net/ | bash -s - -v soft`



`applyPatches.sh`, `rebuildPatches.sh` and `upstreamMerge.sh` come from the [Spigot project](https://github.com/SpigotMC/Spigot)
