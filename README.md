# Outer Wilds planet creation template
 A template project for adding planets to Outer Wilds with New Horizons.

## Prerequisites
- Outer Wilds Mod Manager (get it from the [Outer Wilds Mods](https://outerwildsmods.com/) website)
- OWML installed in the Mod Manager
- A GitHub account (required for forking the repo and for releasing your mod to the public)

## How to use this template
1. Follow the instructions in [Outer Wilds New Horizons](https://github.com/xen-42/outer-wilds-new-horizons) on how to create planet config files. You can test them by putting them in the `planets` folder wherever New Horizons is installed.
2. Generate your repository from this template.
3. Clone your repository to your machine.
4. Add your config files into the `planets` folder. You can delete the `example_config` file in there while you're at it.
5. Edit `NewHorizonsTemplate/manifest.json`. It will look like this:

```
{
  "filename": "NewHorizonsConfig.dll", 
  "author": "[your name]",
  "name": "[your readable mod name]",
  "uniqueName": "[your name].[your unique mod ID]",
  "version": "0.1.0",
  "owmlVersion": "2.1.0",
  "dependencies": [ "xen.NewHorizons" ]
}
```

- Replace `[your name]` with how you want your name to appear in the mod database.
- Replace `[your readable mod name]` with how you want your mod to appear in the database.
- Replace `[your unique mod ID]` with whatever you want, as long as it isn't already in use by another mod. Adding `[your name]` as a prefix helps to prevent overlaps but isn't required.

6. Edit the `README.md` file (you can do this on GitHub in your browser) and be sure to add some nice pictures of your planets.
7. Releasing the mod. See the "Relasing the mod" section on the  [Outer Wilds Mod Template](https://github.com/Raicuparta/ow-mod-template) repo for info on how to do this. Be sure to try out the mod by adding it to your OWML mods folder and make sure it works in game before releasing.

