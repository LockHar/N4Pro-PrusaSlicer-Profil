# Elegoo Neptune 4 Pro - PrusaSlicer Profils
**Its just my personal profils for PrusaSlicer if you need it**
([last release](https://github.com/LockHar/N4Pro-PrusaSlicer-Profil/releases/tag/2024.01v0))

How to import the printer and print config :
>File / Import / Config and select the .ini file
---

I also use :
Bed’s model from user [@georgmierau](https://www.printables.com/@georgmierau) on printables.com ; file : [elegoo_neptune_3_pro.stl](https://www.printables.com/model/409310-custom-build-plates-for-neptune-3-proplusmax-and-4/files)

#### How to use it
In PrusaSlicer (2.7.1)
>Printer Settings > General > Bet shape > [Set …] > In model part [Load…] and select the .stl file and [OK]

Thumbnails post-processing script from : [TheJMaster28](https://github.com/TheJMaster28)

[last release](https://github.com/TheJMaster28/ElegooNeptuneThumbnailPrusa/releases) (I'm using the [v2.1.1](https://github.com/TheJMaster28/ElegooNeptuneThumbnailPrusa/releases/tag/v2.1.1))

#### How to use it
1. Unzip archive on your computer
+ check : Printer Settings > General > in -Firmware section and G-code thumbnails set *`200x200/PNG`*
+ Print Settings > Output options > in Post-processing scripts section add the full directory path of the thumbnail.exe file location between *`" ";`* and copy/paste it for each Print Settings profils you would use.

>(I had trouble when I put the script in a directory like *"C:\Program Files\Prusa3D\PrusaSlicer\thumbmail.exe";*
>maybe the space between 'Program' and 'Files' in the directory path… so I put in a directory without any space in dir. like *"C:\ElegooNeptuneThumbnailPrusa\thumbmail.exe";* )
