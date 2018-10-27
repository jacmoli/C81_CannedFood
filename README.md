# [C81] Canned Food
## A Rimworld v1.0 mod

### Mod description

This mod has the aim to help save fridge space in late game when food supplies may be huge.

The mod is XML only and adds the following items and relevant recipes (single and bulk versions):

- Steel can (standard)

  *1x steel -> 5x  cans*
  *4x steel -> 20x cans*
  
  Each can can store and extend life of 5x meat items or 5x vegetable items. 
    
- Steel can (advanced)

  *1x steel + 1x psychoid leaves -> 5x  advanced cans*
  *4x steel + 4x psychoid leaves -> 20x advanced cans*
  
  Each advanced can can store and preserve (fully prevents rotting) 5x meat items or 5x vegetable items. 

- [Canned / Preserved] [Meat / Vegetables]

  *1x [normal / advanced] can + 6x  food ingredients = 1x [Canned / Preserved] food ingredients*
  *4x [normal / advanced] can + 24x food ingredients = 4x [Canned / Preserved] food ingredients*
  
  Each can of food ingredients is equivalent to 5 vegs/meat items (i.e. half the dose required for a simple meal, or enough for a fine meal taking one of each type).
  Canning food requires the appropriate can and **6 (six)** ingredients, as the space saving is achieved by tasking only the useful parts from food. Shelf life is 30 days for canned meat and 60 days for canned vegetables. Preserved ingredients never rot.

NOTE: cans (any type, empty or full) stack up to 150. Meaning that in the end space efficiency is 10x base game's (5x nutrition content per item, 2x stack size per tile). 
  
### Skill requirements

Crafting items requires some skill:

**Machining table recipes**
    Standard cans (1x)  : crafting  6
    Standard cans (4x)  : crafting  8
    Advanced cans (1x)  : crafting  8
    Advanced cans (4x)  : crafting 10

**Stove recipes**
    Canned food (1x)    : cooking   6
    Canned food (4x)    : cooking   8
    Preserved food (1x) : cooking   8
    Preserved food (1x) : cooking  10

### Warnings, compatibility etc.

- Mod should be compatible with other mods, even those with similar functions.
- Mod probably can **not** be removed from a savegame. Maybe it can if all cans, canned food and canning bills are removed, but it will require testing. I'll let you know ASAP.
- Human and inscet meats are disabled from the meat canning recipes, as a mixed meat can would either lose the cannibalistic debuff or it would apply the debuff to all meat int he can (increasing food availability for cannibals).
- If any mod introduces food which is **more** nutrient than vanilla meat or vegetables, it is advisable to disallow these foods form ingredients, or their extra nutrition will be lost (5 items will always be required).
- If any mod introduces food which is **less** nutrient than vanilla meat or vegetables, it is advisable to disallow these foods form ingredients, as the canning process would create nutrition from scratch (see "cheating").

### Future developments (fellow modders help is welcome)

(V)HP = (very) high priority
(V)LP = (very) low priority

- LP: Better artworks for cans
- HP: Modify C# code to have a *IngredientValueGetter* returning nutrition (if defined for ingredient) or else item count (as for non-meal recipes)
- VLP: Evaluate behaviour of using part normal meat, part human meat.
