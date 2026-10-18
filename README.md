# Silver-Pines VR
VR Mod for Silver Pines

expect issues I played full game then made mod didnt play full game with VR mod

SILVER PINES VR  -  VR mod for "Silver Pines" (for controller)
===========================================================================

Version 0.1.12 (test build on Quest VDXR).

FIRST PERSON?
-------------
Not possible in this game: the characters are flat 2D drawings (sprite animation) standing in a
layered 3D world. From a first-person view they would be seen edge-on (thin lines). So the mod
gives you the next best thing:

WHAT IT DOES
------------
* Stereo VR through OpenXR (SteamVR, Meta/Oculus, Virtual Desktop, WMR...).
* "Stage" view: you stand where the game's camera is. The side-on world is a real 3D stage in
  front of you (the background layers really are far away, the foreground close), with your
  character in the middle. The view follows your character smoothly; the game's screen shakes
  and camera bumps are not passed on. Lean in and look around.
* Play with your Xbox controller as usual (or set [Input] UseVRControllers = true to use the VR
  controllers as the gamepad).
* Menus and HUD are on a screen floating in front of you (the black around the HUD is
  see-through). Menus: you can also point with the right controller and pull the trigger.

INSTALL
-------
1. unzip into the game folder (merge / overwrite).
3. Start SteamVR (or your OpenXR runtime) first, then the game.

CONTROLS (gamepad buttons)
--------------------------
controller: hold both stick clicks = VR settings menu, tap both = re-centre.)
All of it can be changed in BepInEx\config\silverpines.vr.cfg, [Controls].

VIEW SETTINGS (VR settings menu, or [View] in the config - changes apply live)
------------------------------------------------------------------------------
Zoom .............. 1 = the game's camera distance (14 m); 0.45 = about 6 m (default), 0.3 = about 4 m.
HeightOffset ...... view up / down (metres).    ForwardOffset ... towards the scene / back.
CameraSteadiness .. how calmly the view follows the camera (0 = exactly like the game).
WorldScale ........ >1 = the world feels bigger around you (you smaller), <1 = smaller.
