## Evangelion-insipred tactical combat
Short: tactical strategy of defending the earth with the focus on characters.

### Design

#### Base management
XCOM style: you manage the underground of the city. Possible blocks: shield, research, hangar. You hire/grow/create pilots, train them to increase skills, synchronization with mechs, and to understand each other better. You research technologies and order manufacturing from the outside, including new mechs and items.

#### Finances
You are financed by the government(s) depending on the level of protection you provide for the city. I.e. destroying half of the city will give you money penalty.

#### Time
XCOM style: real outside, paused in the base.

#### Battle
MechCommander/XCOM style with close-up view since there is only a few units on the field. Zonal damage, limbs destruction, pilots disobeying orders if they will. There is a pre-mission phase, where you equip the team and may ask for fire assistance from the outside (tanks, artillery, air force).

#### Story
Evangelion movie-like. You need to stop the end of the world.

#### Characters
Base team members & pilots, all having opinions and loyalty changing by your decisions. Pilots interact with each other, getting used (synchronizing) with mechs.

### Implementation
- (low) Base: a sandbox with a fixed number of different blocks.
- (med) City: there is only one city, but it has to be large and detail. +living city. +destructible city.
- (low-med) Characters: need a lot of well-done characters drawn in anime-style. Can be substituted by pictures until they are done. Dialogs can also be grown independently of the game process.
- (low-med) Battle: turn-based mechanics is simple, we just need mechs, aliens, and their animations.
- (high) GUI: there is plenty of HUD stuff, especially during the battle.
