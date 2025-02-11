# Patchnotes for [config_CS2.cfg](https://github.com/julis99/CS_Config/blob/main/CS2/config_CS2.cfg)

## ##Version 2.2.2

- added *cl_usenewbob 1* to use the new bobbling arround

## ##Version 2.2.1

- Removed hint for *exec lobbycmd* as these commands have stopped working

## ##Version 2.2.0

After CS2 Update 2/15/2024

- Added *cl_hud_telemetry* to display **FPS**, **Ping** and **Packet Loss** in HUD (top right corner)
- changed *cl_mainmenu_bkgnd_movie* to correct command
  - changed background to **warehouse**

## ##Version 2.3.0

After CS2 Update 4/25/2024

- Added *cl_prefer_lefthand* to keep righthand prefered
- Added *switchhand* keybinding
  - Bound to *q* as it was in CS:GO
  - But watch out it does not work like in CS:GO
    - it redraws the weapon with the other hand, you cannot shoot for a moment

## ##Version 2.4.0

After CS2 Update 01/30/2025

- Added *buy zeus* to buybinds_CS2
  - bound to *kp_multiply*
- removed aliases *+fader*, *-fader* from prac_CS2, as they dont work anymore
- added *disable prediction* section to config_CS2
  - *cl_predict_\** will make prediction on the clients and won't show the correct server side
- Updated crosshair_CS2 to feature the grenade crosshair commands

## ##Version 2.4.1

After CS Update 02/07/2025

- Added *cl_hud_radar_map_additive true* to Config_CS2
- Update crosshair_CS2 to Version 2.0.2
  - reduced *cl_grenadecrosshairdelay_smoke* to 1.5 sec

## ##Version 2.4.2

- changed *cl_hud_radar_map_additive* to false
- added *cl_hud_radar_background_alpha*, set to 0 to keep background visible but blurred

## ##Version 2.5.0

- added new aliases
  - *dc*   - to shorten *disconnect*
  - *exit* - aliases *quit*
- added *cl_invites_only_mainmenu* and set to true to prevent invites when ingame
- added *cl_radar_square_with_scoreboard* and set to true