# FabledSkyblock WorldEdit (FSWE)

This is a Skript that can give your players access to a limited version of WorldEdit to place blocks from their inventory to a selected region on their island.

### Dependancies

What things you need to have on your server in order to use FSWE

* [FabledSkyblock](https://songoda.com/marketplace/product/fabledskyblock-the-ultimate-skyblock-plugin.17)
* [Sky](https://github.com/TheLimeGlass/Sky/releases)
* [Skript](https://github.com/SkriptLang/Skript/releases)
* [Skript-Mirror](https://github.com/btk5h/skript-mirror/releases)

### Installing

* Drag and drop 'Sky', 'Skript-Mirror' and 'Skript' into your /plugins/ folder
* Restart your server
* Drop FSWE.sk into your /plugins/Skript/scripts/ folder
* Restart your server

### Info

Commands + Permissions
```
/set [<material>] - fswe.set
```

In the Skript, under the settings tab, you can change many options.

By changing wooden axe to the item of your choice, that will be used to select regions.
```
wand-item: wooden axe 
```

To reduce lag or balance the feature out for your sever, try playing around with the block-place-speed.
```
#you can also use seconds "example, block-place-speed: 2 seconds"
block-place-speed: 2 ticks
```


## Credit

* [ANDREI923](https://www.spigotmc.org/resources/authors/andrei923.153123/) - Made the plugin but only supports ASkyBlock which was recently discontinued.
