# Kontakt scripts update for Drummica sample library

Changelog:

- code reduction by moving repeated blocks into function calls
- fix: show correct reverb channel labels when changing mixer presets
- change: make GM mapping compatible with NI Studio Drummer mapping
- change: save some RAM by unloading unused wire/non-wire samples based on Bleed volume position
- fix: properly restore wires bleed status on instroment load
- change: Mic Sel menu shows Overheads page if Master channel is selected (previously Drums overview was shown in Mic Sel)
