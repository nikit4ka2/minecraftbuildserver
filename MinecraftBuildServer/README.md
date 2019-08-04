# BuildServer

BuildServer is a tool to quickly get a Minecraft server running specifically made for building maps in a void world.

This tool isn't the perfect setup for every build situation. I made this because I want to quickly make arenas for minigames I am developing. Instead of manually downloading plugins and compiling Spigot, I use this. Other's needs may vary, but I hope this can be of use to some.

## Included Tools

This utility comes with a few essential plugins built in for the fastest time-to-build server setup around. The currently included tools are listed below:

**WorldEdit**: ([link]()) Used for easily manipulating the world around you.

**VoidGenerator**: ([link](http://dev.bukkit.org/bukkit-plugins/voidgenerator/)) Used to generate a void world.

## Installation

Convinced? Great! It is extremely simple to get BuildServer up and running.

Clone this repo onto your local machine:

```sh
git clone https://github.com/nikit4ka2/minecraftbuildserver
cd BuildServer
```

Install the included tools:

*You need to do this once, and then you're set to use the server.*

```sh
./scripts/init
```

Run the server:

```sh
./scripts/run
```

## Saving your map

To save your map into a zip file, just run:

```sh
./scripts/save
```

To get a fresh map to build on, run:

```sh
./scripts/clean
```

*Note: This will delete the current map on the server. Be sure to save that before using this command.*
