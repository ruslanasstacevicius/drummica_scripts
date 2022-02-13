# Kontakt scripts update for Drummica sample library

Changelog:

- code reduction by moving repeated blocks into function calls
- fix: show correct reverb channel labels when changing mixer presets
- change: make GM mapping preset compatible with NI Studio Drummer mapping
- change: save some RAM by unloading unused wire/non-wire samples based on Bleed volume position
- fix: properly restore wires bleed setting on instrument load
- change: shows Overheads page in Mic Sel menu if Master channel is selected (previously Drums overview was shown in Mic Sel)
- change: attach two channel meters to all mixer channels, single channel meters could not show levels when panned right
- fix: Transient Master Soft button status not updated properly
- fix: Transient Master labels for attack and sustain are "%", not "dB"
