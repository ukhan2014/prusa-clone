# prusa-clone
Making a clone of the prusa mk2 3D printer

Frame is made from birch plywood 1inch thick

Cut using laser cutter at Noisebridge.

Threaded rods:
M5 - ??
M8   - cut to 4pcs of 205mm
M10  - cut to 2pcs of 360mm

Need 3d Parts printed:



Custom G-code for start routine (codes before the print starts):```
M83 ; extruder relative mode
M109 S[first_layer_temperature] ; set extruder temp
M190 S[first_layer_bed_temperature] ; set bed temp
```
