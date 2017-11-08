## Top-down tactical shooter/RPG

### Design

#### Perspective
Top-down, in-door, similar to Hotline Miami.

#### Dynamics
Little-to-no inertia. Near-instant shots. Movement is rough, running from one cover to another.

#### Battle
Based on awareness and cover mechanics. Have to look out of cover, getting at risk of being shot, in order to see the surroundings and enemies. Can feel in other ways, such as sound indicators (possibly developed as augmentation / character progression). Cover shooting similar to Gears of War and others.

Mouse-controlled view and shooting. Hits require aiming, timing, and luck.

#### Exploration
Indoor levels with many rooms and corridors.

### Implementation
  1. Basic top-down square moved with keys, camera centered
  2. Level composed of blocks, loaded from a file and rendered in squares. Collision prevention when moving.
  3. Character rotation, mouse cursor, followed by the camera.
  4. Enemies with basic AI for shooting on sight.
  5. Cover mechanics and refined shooting.
  6 ...
