## Rendering shooter

### Design

A classy top-down scrolling shooter. The player controls a ship with weapons.

#### Ships
Multiple kinds of ships, each is associated with different difficulty of the game:
  - GL
  - Metal
  - DX12
  - Vulkan

#### Shooting
Shooting is expressed via firing draw calls. Upgrading weapons is getting extensions, or abilities to use more sophisticated draw call mechanics:
  - vertex buffer objects / array objects
  - indexed draws
  - instancing (sequence firing)
  - multi-draw (spread firing)
  - geometry shading
  - tessellation (bullet splits)
  - indirect (smart bullets)
  - conservative rasterization (bombs)
  - compute?..

#### Levels
Levels can be scenes to render, with enemies represented either by unfilled pixels, or flying bugs, or both. User completes a level by rendering everything.

### Implementation
  1. single square moved left/right on the screen
  2. basic enemies and shooting
  3. enemy types and moving/shooting patterns
  4. player weapons
  5. better graphics, text
  6. actual playable levels
