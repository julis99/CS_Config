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

Adter CS Update 02/14/2025

- added new aliases
  - *dc*   - to shorten *disconnect*
  - *exit* - aliases *quit*
- added *cl_invites_only_mainmenu* and set to true to prevent invites when ingame
- added *cl_radar_square_with_scoreboard* and set to true
PULXRLRYH

## ##Version 2.6.0

- **new dependency**: *viewmodel_cod.cfg*
  - will change the viewmodel to feature a centered weapon
- added new aliases
  - *cod*   - centres the gun (like in COD)
  - *reset* - executes config_CS2
- changed lobby commands to be working again
  - *Lobby* Background is set to *de_train*
  - *Inspect* Background is set to *warehouse*
- Update prac_CS2 to version 1.6.1
  - new alias:
    - *noshowimpacts* - revert the *sv_showimpact* changes
  - added *sv_showimpacts_penetration* and set to 1,
  to get more detailed penetration feedback
  - reduced *sv_showimpacts_time* to 3 sec

## ##Version 2.6.1
- change lobby backgrounds
  - *Lobby* -> cs_italy
  - *Inspect* -> de_train
- update *volume_CS2*
  - added *snd_headphone_eq* and *snd_headphone_eq_active*
    - both set to 1
- update *crosshair_CS2*
  - added *cl_show_observer_crosshair* and set to 2 (show crosshair of everyone)
  - added *cl_observed_bot_crosshair* and set to 1 (show own crosshair on bot spec, WHEN takeover is possible)
  - upadate own crosshair code

## ##Version 2.6.2
- add *cl_weapon_selection_rarity_color* and set to 1
  - will make the weapon icon glow in the rarity color of the skin

## ##Version 2.7.1
- change Lobby backgrounds
  - *Lobby* -> de_ancient
  - *Inspect* -> de_train
- update *crosshair_CS2* to version *2.1.1*
  - added *cl_sniper_delay_unscope* and set to False (undelayed unscope)
  - added *cl_crosshair_sniper_width* and set to 1 (minimum width)
  - added *cl_sniper_show_inaccuracy* and set to True
  - added *cl_sniper_auto_rezoom* and set to True
- add **Player Settings** section
  - added *cl_teamcounter_playercount_instead_of_avatars* and set to 0
  - added *cl_teamid_overhead_colors_show* and set to 1
  - added *cl_teamid_overhead_mode* and set to 3 (PIPS, Names, Health and Equipment)
  - added *cl_teammate_colors_show* and set to 2 (colors and letters)

## ##Version 2.7.3
- change *mm_dedicated_search_maxping* to 30 *(from 50)*