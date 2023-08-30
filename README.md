# Sword2
STL and SKP files for the light-up sword.

This is a heavy, solid light-up LED sword suitable for play, theatrics, or LED spinning. It features several color palettes that can be swapped with the push of a button. 

Most of the components for these swords are 3d-printed. I used Ninjaflex brand semiflex filament for its impact resistance.
You can smack these swords around pretty hard and they won't break or deform. Additional components include:

### Electronics (mostly from Adafruit):

- Trinket Pro 5v
- Adafruit Pro Trinket LiIon/LiPoly Backpack Add-On
- Dotstar SK9822 LED strips (60/meter)
- Lithium Ion Cylindrical Battery - 3.7v 2200mAh
- Colorful Square Tactile Button Switch
- On-Off-On-Off Alternating Power Button / Pushbutton 3-Way Toggle
- White LEDs (in the hilt to indicate powered-on state)

### Structural components:

- 3/4" PVC for the hilt (length depending on whether you want one-handed or two).
- Steel angle for the hilt (for grip and weight)
- Rebar tie to wrap the angle to the PVC (for grip and weight)
- Fabric tape to wrap the rebar tie
- 1" clear polycarbonate tube for the blade
- Two nails to pin the PVC and polycarbonate tube together inside the cross-guard and to pin the pommel on the PVC. (TODO: A single tube would likely be an improvement)

Assembly suggestions:
- Use relatively dense LEDs and get enough to fill the entire lenth of the blade. You can get 2x the length for a brighter sword - if you do, I recommend cutting and re-splicing at the end to avoid bending the LED strip, which can lead to issues.
  - The pommel (sword_end and sword_end_gem) houses the battery. There is space in the "gem" to house white LEDs which can be wired to light up when the sword has power. 
  - TODO: Make the gem and pommel fit more securely. TODO: Add an easy externally accessible charging port so that you don't have to open the trinket compartment to charge.
- The cross-guard houses most other components - it has two voids for the two caddies: one for buttons and one for the trinket.
- The blade segments and blade end should friction-fit tightly on the polycarb. 

I hereby declare a non-commercial attribution license!

TODO: Assembly instructions.
