# Counterstrike 2

*This files can be seen as the doc for my .cfg files used is CS2*

## [buybinds_CS2.cfg](https://github.com/julis99/CS_Config/blob/main/CS2/buybinds_CS2.cfg)

This config file binds all avaible slots of your loadout to specific keys. I myself use the numpad and its surroundings here. To change keybinds simply change the [key] in each line to your desired one.

### Usage

```css
bind [KEY] "buy [item]";
```

For multiple items on one key simply do:

```css
bind [KEY] "buy [item1]; buy [item2]; ...";
```

Yet note that upon changing the keybinds my *echo* loses its correctness.

## [config_CS2.cfg](https://github.com/julis99/CS_Config/blob/main/CS2/config_CS2.cfg)

This file is the heart of my config setup. Not only does it change the default stuff. It furthermore executes the *buybinds* the *crosshair* and the *volume* config. The following list shows what this config does change:

- Basic stuff (sensitivity, instructor, fps_max, ...)
- Video (only fullscreen_gamma) *more is not possible (yet)*
- Viewmodel
- HUD & Radar
- Aliases
  - **practice**

        ```css
            exec prac_CS2;
        ```

- Keybinds
- Lobby Background

## [prac_CS2.cfg](https://github.com/julis99/CS_Config/blob/main/CS2/prac_CS2.cfg)

This config will drastically change server wide settings, so one can see where stuff is penetrable, can carry more grenades, ...

This also will introduce some aliases and change the keys which are rebound by config_CS2. The introduced aliases are
- **buyequipment**

    ```css
    buy vesthelm;
    buy molotov;
    buy flashbang;
    buy hegrenade;
    buy smokegrenade;
    buy decoy;
    give weapon_healthshot;
    ```

Executing this config will prepare ones current game server (given the right permission) for a practice session and will adapt keybinds to make the practice better.
