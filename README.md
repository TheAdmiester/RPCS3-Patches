# RPCS3-Patches
Tweaks for PS3 games with RPCS3 (mostly Gran Turismo)

# Patch List
## Gran Turismo 5 (BCUS98114)
- Chase Camera - CAR5 FOV and Pitch - allows the user to fix a common complaint with GT5 - weird camera positions and low FOV. Does not adjust anything directly but rather forces the game to respect what a car has defined in its cameras. Cameras can be edited using [Edo's mass editor](https://github.com/emissary935/Gran-Turismo-CAR5-Editor-Tool) or manually using [Nenkai's CAR5 template](https://github.com/Nenkai/GT-File-Specifications-Documentation/blob/master/Formats/PS3/Cars/CAR5.bt) for 010 Editor.
- Read Car Camera Data from USRDIR - mostly for development purposes, complements the patch above as it makes tweaking way quicker
- Enable Motion Blur in Gameplay - enables replay motion blur in gameplay modes with a couple of fixes to stop it breaking mirrors. Also upgrades motion blur to 24 samples vs 8.

# Chase Cam Example
Before:
![Before](https://github.com/TheAdmiester/RPCS3-Patches/blob/main/GT5-Before.png "Before")
After: (Y: -1.35, Z: -3.8, Pitch: 5 deg, FOV: 53 deg (2.00569 in raw CAR5))
![After](https://github.com/TheAdmiester/RPCS3-Patches/blob/main/GT5-After.png "After")

