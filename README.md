# Assimil8or Helpers

Scripts I'm using while working with the Rossum-Electro Assimil8or.  The idea is to evolve the scripts based on my own workflow with the goal of focusing on music rather than anything else while I'm working on the modular.  If I can reduce some of the more tedious and repetitive tasks, then I can hopefully spend creative focus on music rather than configuration.

# Preset Template

The prst002.yml file is meant to be an ongoing evolution of a preset template that allows me to quickly dial in the values I like to use when working with the module.  This can save some time based on perferred cv mappings etc.  The other benefit I realized was the ability to preview samples on a computer, and place them in the template so they are loaded at the module, rather than previewing samples, copying them onto the microsd and turning the knob to select them.

# Slicer

The idea is a simple script that spits out preformatted text that divides a sample into 8 equal lengths (some precision lost from rounding).  I created this so that I could more easily divide zones and then fine tune the start and stop settings at the module.  It currently outputs the voltage table associated with the XOR NerdSeq that maps C-4 thru G-4 to each Zone 8 thru 1 (in that order).  It would be neat if the community would add more voltage tables for their specific sequencers and workflows.

# Thanks

Thanks to Gimber for allowing me to ping ideas off him and formula corrections.

Thanks to Rossum Electro for making kewl modules, and special thanks to Marco at Rossum for putting up with my constant support requests :D

The code was adapated from this stack answer https://stackoverflow.com/a/40652047
