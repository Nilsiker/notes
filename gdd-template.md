# GDD Template

#gamedev #piratesoftware #gdd

## Introduction

### Game Summary

Mass Flux is a tile based puzzle game about reducing or generally manipulating the shape of a mass of cell-blocks to navigate to a goal.

### Inspiration

#### Snakebird

![](https://lh7-us.googleusercontent.com/a93EooStuHt_yfJ7Fl3gYjtkeYAKBTkAykS3_0vk_JtGk-OldoWN7ap15vvTE1vLiS5woQa4UBJj_t-pz28kShPjjrBb2Ie-Y5nPlqh7hw_bXsyz8kv2thU5G2esIGZWDOCS3n7gPrEfH25Z9kqi7vX4FDxCWTjvqxeyIn8Kf8EfDirRQzK4zI-qHPuaOQ)

Snakebird provides the ingenuity for the player to control a body that isn't always helpful and will certainly get in the way more often than aid one’s plan. A long body in that game may be susceptible to support the player from falling but often can restrict and block certain movement making puzzle areas much harder  to navigate.  
  

#### Baba Is You

![](https://lh7-us.googleusercontent.com/9SIYpswSmpP3D4AG1JLlt3SC_IiFIlRf8X0CtPiaZk0M7pjud9S5nzB4CntlFcK3UWkv_MY8VZEn_d-kfmPRlbiBiAj2b-D9elVd9i1RWXq3tEGAiqyx_e1NkupSfxgh7Ayt9o3EEiBBXmgHxGjZo4I_I8Uu2f5C1U1BwC88nhyJgskKRUQC0F7RT_GsVA)

Baba is You is the main inspiration towards the style and mood of the game. Especially graphics-wise to fit the 2-bit graphical prompt, the minimalist art style will hold useful to act as a base. Otherwise, the gameplay also further provides inspiration towards level design as an abstract puzzle game.

### Player Experience

In a single screen dungeon for each of the 15 levels, the player will solve a short but perhaps complex puzzle requiring planning and management. The player must learn and use their knowledge of the interactions between the player cells and various environmental items to understand how to pass through each level.

### Platform

The game is developed to be released on windows PC

### Development Software

- Gamemaker Studio version 2.3 for programming
- Aseprite for graphics and UI
- FL Studio 12 for all music and SFX

### Genre

Singleplayer, puzzle, casual

### Target Audience

Without heavy or complicated ideas, and intuitive-to-grasp mechanics, this game is marketed to at least casual game players who are up for puzzling challenges as well as more veteran players up for solving complicated problems

## Concept

### Gameplay Overview

The player controls a mass of player cells, each with individual status, but moves as a collective. Individual cells may die or be created which influences the total shape of the mass. By navigating through each level, the player must strategically manipulate the shape of the mass to be able to pass around or through obstacles to reach the goal.

### Theme Interpretation (Descriptor)

> *‘Sacrifice’ interpretation - The player voluntarily offers something they would otherwise use to their benefit to then gain something else of use in its stead.*

Within the context of a puzzle game, rather than a sacrifice strictly being an optional upgrade of sorts, the timing, placement, and orientation a ‘sacrifice’ within this game instead occurs to allow the solution or progression of the puzzle. Only through careful planning of movement to remove parts of the player’s mass can the player make their way to the exit. One must often sacrifice a part of the player mass to pass through specific areas as they may be too large or encompass the wrong shape.

### Primary Mechanics

|Mechanic|Description|Animated Mockup|
|---|---|---|
|Walls|A stopping force to prevent a player too large to access a certain area. Otherwise to simply restrict movement.|![](https://lh7-us.googleusercontent.com/wHG6kwCV6lp_2GngPJgxF7p5Dj43IutJAJQQhFAyY9fI6tT4oCQ4aPGmJDixbMPzOonSl4sq7bujrlmTS3vJod6_ZnD0WB-Bj0TIa9XUnzH_lSt1JzOohJeltJl9-liex6n5z6FfkAwE8qgaOCs4mhgfM9d6qsHpQv1bQZKhIkalQ9p7Vn9iBeU0t3PoKw)|
|Spikes|When a player cell walks on top of a spike, that cell will die and further simplify the player mass.|![](https://lh7-us.googleusercontent.com/pH-VtJ-dGKXkXXCXW0KYJLEBnArMPr78l9-L22r5Q313zmj9W-uS-kMf033Ewo3FjmPAKm-gvroMNDmtHofTIycpeisYet0V5AgwaCkekyfDWoIO22xQZkUgA4BZ4sdsHqERqVleOOoTjAU9_ycTfJRlY4fnvpMwD2dhncwwuwFNQJOI5wvjKBDXcJPvMw)|
|Holes|The player mass can walk freely over a hole as long as at least one cell is on a floor tile. If the entire mass is over the hole, the entire player mass dies.|![](https://lh7-us.googleusercontent.com/iwt-vGWLcV3PciBwkyyXXLVHd9IN7hez829UmSBAh2mHlHZkRsqUO0erUdCvttc8vIGBs4G13WF-U8sabBuQCn66MwwAePxIedR7IUD3FnXz_-683glV9gxKKJXcRaQ01fkEwtzDUQC5JSoN3rwbKZhGHFh9BZ5Rh2R4cGfssdL2Xhs82dG8BZDgvCqZ1g)|
|Fruit|If a player cell moves over a fruit, it will eat the fruit and generate a new cell on the opposite side of the mass it is a part of.|![](https://lh7-us.googleusercontent.com/jyO5dLgMT0osafwUdH7SZswEmSF31TMK2D-PKsrbswMzf2zGaT-i1d9q3Qvi7WReVjbNAfHCb-9XnKFR2t7VLELGtyg09LZGKHr3SNArJZeOm6GMkSa3qfMDVyV7RpCDXbFE1j4F61Dg95pSw2tBO1WRhwbhRG3PqPM_vM1tNwcSvDNn7I7qmRgVj3Dk3w)|

### Secondary Mechanics

|Mechanic|Description|Animated Mockup|
|---|---|---|
|Independence|If two player masses happen to separate, they will still move synchronously but interact with the environment independently. If then connected again, the two masses will join to act as one.|![](https://lh7-us.googleusercontent.com/2uiQCmcjvKdsVZC3bYJOjh3yBfF8EVo9RMvMetlq9fcFv630yibddy7xGiWqs31cv_bPZn60Zt1L8c8fhz7V-qgipf1kD-IsQcietlok3STsiWkZRsBoBoeJvJheV-nPQLf3pyaulD_bnKi-avVHyX5QPlJCMxxKyixVM6M5X03d_5y1ZtT2XIkRUo_0RA)|
|Set Spikes|When a player cell walks on top of a set spike, after moving off of it, it will then become a regular spike trap|![](https://lh7-us.googleusercontent.com/4F5SFIsOFQxyG0JjKNBFIW0tLB3d8EcPc0IhRc7eFu3AdVOrwWNS_7_Jpg9JmdAy8xdjbkavL36TOUVwr-zmLYWhtJgh-5i7ax129mJM5e3rK7UCD5CemdWWjBwsN7RkexTQDk5-ByP1eom59YafMpbvS7eaAegQ9pWEx56FE1pqMRrk9ZBlZyq6q6EfTw)|

## Art              

### Theme Interpretation

While maintaining the very limited color palette theme, the sole use of black in white seems way too common, and a bit harsh as a color scheme for a relaxing puzzle game. To circumvent this, a soft, dark blue color will act as the unique accent color as opposed to black with white being the primary, carrying color to base the sprites off of.

![](https://lh7-us.googleusercontent.com/XEPszYckT6TeurtqIM6kQmF9f9HyJLdQoy5v9yLUL38dERcewtMXYvvoPH3Auul2TRG_QYqYEZNRSw-UmCWYylwXNis_aoLnGxvXZ8n8FkyDqW_8zydvkgPUT5hNHCVRdG3HbV4RRBb2JXoRSnIjf31lsnCB31mBVzuYvdqDYFMcbLI9QmRphELpx_RuwA)

### Design

A very minimalistic approach will go into the design of the game, heavily relying on the severe contrast of the limited colors to provide detail. Though, the design still is clean and smooth in the sense that, the use of many shades of a color will not be as present to confront the retro style and pixel art.

![](https://lh7-us.googleusercontent.com/XvUoXaDigjd690VRjuZuGJmZk7d_eI8XYHi2fa4x5bY-39ElYsK4hgNo4KqosTFQnSPHSPz9IbwnjEove7TyEpiIGolV1VcvrRJe462BiLsP-cME9N5zmH_icpnhL23gZa0enuvvTawGf3R2Ill6ig-q8NTNR9FIVBZEvEjQNTx2WY6L-XupriR6E2EgZw)

*Not an actual puzzle/level, merely a full example of the tileset and art style*

## Audio
### Music

To add to the overall theme and vibe of the game, there will be minimalism incorporated into the music. Heavy use of reverb and effects to fill space within the few instruments. Bass and drums will generally constitute the majority of tracks with accompanying softer sounds. Mainly through synthesized sounds rather than acoustic will further suggest the retro style.

### Sound Effects

To add more flare and polish to the experience, a multitude of environmental sound effects will give weight and feedback to the player’s actions. Rather than foley, or otherwise realistic sounds, synthesized blips, bloops, and whooshes are used.

## Game Experience

### UI

On top of the rigid pixel art constituting the rest of the art, a more smooth, higher definition style will be incorporated in the UI. Utilizing many shades of white and black allowed in the art restriction, anti-aliasing is used to further emphasize the UI.

### Controls

**Keyboard**
Arrow keys / WASD  

**Gamepad**
Dpad

## Development Timeline

|#|Assignment|Type|Status|Finish By|Notes|
|---|---|---|---|---|---|
|1|Design Document|Other|Finished|Jun 22, 2022||
|2|Create player and wall assets|Art|Finished|Jun 23, 2022|Prototype for GDD is done|
|3|Main menu theme|Audio|Finished|Jun 23, 2022|Can be really short, player won’t be on main menu for long|
|4|UI / Main menu|Coding|Finished|Jun 23, 2022|Button UI, screen transition, title screen|
|5|Level theme|Audio|Finished|Jun 24, 2022|Should be more substantial and not annoying|
|6|Simple player movement|Coding|Finished|Jun 23, 2022|Move single cells around and collide with walls|
|7|Complex player movement|Coding|Finished|Jun 24, 2022|Multi cell masses act together to collide with walls|
|8|Spikes and holes with player interactions|Coding|Finished|Jun 24, 2022|Implement spike and holes mechanics|
|9|Fruit interaction|Coding|Finished|Jun 25, 2022||
|10|Special effects|Art|Finished|Jun 25, 2022|Dust particles during movement|
|11|Player animation|Art|Finished|Jun 25, 2022|Idle blinks, movement polish|
|12|Sound effects|Audio|Finished|Jun 25, 2022|Player movement, UI interaction|
|13|Pause menu|Coding|Finished|Jun 26, 2022|Access to the main menu or resetting the level|
|14|Level select menu|Coding|Finished|Jun 26, 2022||
|15|Level design (1-7)|Other|Finished|Jun 27, 2022|Create levels 1 through 7|
|16|Level design (8-15)|Other|Finished|Jun 28, 2022|Create levels 7 through 15|
|17|Any extra polish|Other|Finished|Jun 29, 2022||
|18|SUBMIT|Other|Finished|Jun 29, 2022|Create Itch Page and upload|