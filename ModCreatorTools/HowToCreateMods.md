How to create mods
ATC: Cleared for Takeoff

Mods are stored in the ProgramData folder (Windows default: C:\ProgramData\AtcSimAndMagic\ATC\Mod).
Each aircraft type need a separate folder (under ProgramData\AtcSimAndMagic\ATC\Mod\PlaneTypes), in which there has to be repaint files (png or jpg), and a planetype.cfg file describing which file is what. Description is done by keywords.

Example planetype.cfg:
[Example start]
airlinecode=LH
aircraft=B733
fuselage=LH733fuselage.png
kil=LH733kil.png
engine=eng.png
[Example end]

(means: this is a repaint for LH airline B737-300, and there are 3 pngs provided. Rest of the textures remain default)

Note that only those plane types can be repainted, which are already added to the sim.
