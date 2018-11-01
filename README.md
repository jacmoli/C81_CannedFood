# [C81] Canned Food
## A Rimworld v1.0 mod by Cocco81

Current mod version: v1.0.1

### Mod description

This mod has the aim to help save fridge space in late game when food supplies may be huge.

The mod is currently XML only and adds the following items and relevant recipes (single and bulk versions) after researching the **Food Canning** tech (requires Packaged Survival Meal):

- Steel can (standard)

  *1x steel -> 5x  cans*  
  *4x steel -> 20x cans*  
  
  Each can can store and extend life of 5x meat items or 5x vegetable items. 
    
- Steel can (advanced)

  *1x steel + 1x psychoid leaves -> 5x  advanced cans*  
  *4x steel + 4x psychoid leaves -> 20x advanced cans*  
  
  Each advanced can can store and preserve (fully prevents rotting) 5x meat items or 5x vegetable items. 

- [Canned / Preserved] [Meat / Vegetables]

  *1x [normal / advanced] can + 6x  [meat / vegs] = 1x [Canned / Preserved] [meat / vegs]*  
  *4x [normal / advanced] can + 24x [meat / vegs] = 4x [Canned / Preserved] [meat / vegs]*  
  
  Each can of food ingredients is equivalent to 5 vegs/meat items (i.e. half the dose required for a simple meal, or enough for a fine meal taking one of each type).  
  Different types of meat or vegetables *can* be mixed.  
  Canning food requires the appropriate can and **6 (six)** ingredients, as the space saving is achieved by taking only the best parts from food. Shelf life is 30 days for canned meat and 60 days for canned vegetables. Preserved ingredients never rot.

NOTE: cans (any type, empty or full) stack up to 150. Meaning that in the end space efficiency is 10x base game's (5x nutrition content per item, 2x stack size per tile). 
  
### Skill requirements

Crafting items requires some skill:

**Machining table recipes**
```
Standard cans (1x)  : crafting  6
Standard cans (4x)  : crafting  8
Advanced cans (1x)  : crafting  8
Advanced cans (4x)  : crafting 10
```

**Stove recipes**
```
Canned food (1x)    : cooking   6
Canned food (4x)    : cooking   8
Preserved food (1x) : cooking   8
Preserved food (1x) : cooking  10
```

### Warnings, compatibility etc.

- Mod should be compatible with other mods, even those with similar functions.
- Mod can be safely added mid-game.
- Mod probably can **not** be removed from a savegame. Maybe it can if all empty cans, canned food and canning bills (production and cooking) are removed, but it will require testing. I'll let you know ASAP.
- Human and insect meats are disabled from the meat canning recipes, as a mixed meat can would either lose the cannibalistic debuff or it would apply the debuff to all meat in the can (increasing food availability for cannibals).
- If any mod introduces food which is **more** nutritious than vanilla meat or vegetables, it is advisable to disallow these foods from ingredients, or their extra nutrition will be lost (5 items will always be required).
- If any mod introduces food which is **less** nutritious than vanilla meat or vegetables, it is advisable to disallow these foods from ingredients, as the canning process would create nutrition from scratch (see "cheating").

### Future developments (fellow modders help is welcome)

(V)HP = (very) high priority  
(V)LP = (very) low priority

- LP: Better artworks for cans
- HP: Modify C# code to have a *IngredientValueGetter* returning nutrition (if defined for ingredient) or else item count (as for non-meal recipes)
- VLP: Evaluate behaviour of using part normal meat, part human meat.

### License and misc

See license on https://github.com/jacmoli/C81_CannedFood  
(in short, it's MIT License).

Feel free to use this mod and do whatever you want with it, I only ask you to be kind enough to do the following:  
- tell me if you are borrowing code or incorporating it;
- give credit;
- please do not publish patches, improvements, balances etc. without even trying to reach me with a message or a pull request.

If you want to support me feel free to do so here:
https://ko-fi.com/jacmoli

### Main versions history

Note: older versions can be found in the *Releases* section on GitHub

**v1.0.0** : first release version.
**v1.0.1** : fixed missing research prerequisite on stoves bills.

