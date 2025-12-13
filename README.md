# This is a fork of hekate that provides a single change:

| Config option          | Description                                                        |
| ---------------------- | ------------------------------------------------------------------ |
| Rename                 | Renames the given file path to "/startup.te" for payload lauches   |

## Why is this notable?
[TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer/) allows you to execute [TegraScripts](https://github.com/suchmememanyskill/Tegrascript). On boot it will execute "/startup.te". What this key allows you to do is run any script from a hekate launch config. With this, you can take full control over the sd configuration before boot, ***automatically***. You can run completely different setups for sysmmc or emummc, or between multiple emummcs. See the [examples](https://github.com/auggeythecat/hekate_-Test-/tree/master/examples/) folder.

## If you use this
Tegrascripts can be hard to make for most poeple. If you make a config even just for personal use, please make a pull request or upload the scripts in an issue for them to be added to the [examples](https://github.com/auggeythecat/hekate_-Test-/tree/master/examples/) folder. These examples will make it much easier for people to make functional configs.


## About
I did nothing here. This repo is built on the shoulders of geniuses like [CTCaer](https://github.com/CTCaer), [suchmememanyskill](https://github.com/suchmememanyskill/), [SciresM](https://github.com/SciresM), and everyone else who has contributed to hekate, TegraExporer/TegraScripts, Atmosphere, and all other homebrew tools that make this scene amazing. 

```
hekate  (c) 2018,      naehrwert, st4rk.
        (c) 2018-2025, CTCaer.

Nyx GUI (c) 2019-2025, CTCaer.

Thanks to: derrek, nedwill, plutoo, shuffle2, smea, thexyz, yellows8.
Greetings to: fincs, hexkyz, SciresM, Shiny Quagsire, WinterMute.

Open source and free packages used:
 - Littlev Graphics Library,
   Copyright (c) 2016-2018 Gabor Kiss-Vamosi
 - FatFs R0.13c,
   Copyright (c) 2006-2018, ChaN
   Copyright (c) 2018-2022, CTCaer
 - bcl-1.2.0,
   Copyright (c) 2003-2006, Marcus Geelnard
 - blz,
   Copyright (c) 2018, SciresM
 - elfload,
   Copyright (c) 2014 Owen Shepherd,
   Copyright (c) 2018 M4xw

                         ___
                      .-'   `'.
                     /         \
                     |         ;
                     |         |           ___.--,
            _.._     |0) = (0) |    _.---'`__.-( (_.
     __.--'`_.. '.__.\    '--. \_.-' ,.--'`     `""`
    ( ,.--'`   ',__ /./;   ;, '.__.'`    __
    _`) )  .---.__.' / |   |\   \__..--""  """--.,_
   `---' .'.''-._.-'`_./  /\ '.  \ _.--''````'''--._`-.__.'
         | |  .' _.-' |  |  \  \  '.               `----`
          \ \/ .'     \  \   '. '-._)
           \/ /        \  \    `=.__`'-.
           / /\         `) )    / / `"".`\
     , _.-'.'\ \        / /    ( (     / /
      `--'`   ) )    .-'.'      '.'.  | (
             (/`    ( (`          ) )  '-;   [switchbrew]
```
