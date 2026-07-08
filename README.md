# Polished Platinum

This is a minimal ROM hack of Pokemon Platinum that allows completing the Regional Dex and most of the National Dex without external tools or trades, plus a handful of fixes. Based on the decompilation at [pret/pokeplatinum](https://github.com/pret/pokeplatinum).

## Regional Dex Changes

- [ ] All encounter tables have been merged so version exclusive Pokemon can be found anywhere they could be found in Diamond, Pearl, or Platinum
- [ ] Pokemon from all generations have been placed into trade buckets, and trades within these buckets have been added to the Global Trade System. In particular:
  - [ ] All starters have been bucketed with other starters from their own generation
  - [ ] All legendary Pokemon have been bucketed with other legendary pokemon of their same trio/pair
- [ ] GTS trades that the player makes will be satisfied in a random amount of real-world time after the player places them (an hour on average, and no longer than 24 hours). Trades that cannot be satisfied will be rejected
- [ ] The Secret Key will be delivered by the deliveryman after catching Rotom
- [ ] The Member Card will be delivered by the deliveryman after delivering the Lunar Feather

## Quality of Life Changes

- [ ] All TMs are now reusable
- [ ] The game will now prompt you if you'd like to use another Repel when one runs out
- [ ] HMs are considered "learned" after both the HM and the associated badge are considered obtained; Defog and Flash will automatically activate when entering a room where they could be used
- [ ] All honey trees now share a much more generous encounter table, and will keep shaking until the player activates their encounter. You can also save scum them too, if you really want
- [ ] The Odd Keystone will summon Spiritomb 24 hours after being slotted into the Hallowed Tower
- [ ] The Underground is accessible, and items from Diamond, Pearl, and Platinum will be findable in a single save
- [ ] Mindy's Haunter no longer holds an Everstone, and she will perform self-criticism for her original behavior
- [ ] The ghosts in the Old Chateau are now guaranteed to appear on the player's first visit
- [ ] Feebas now appears in ~~4~~ ==> 56 of the 528 tiles in the Mount Coronet lake
- [ ] The Wi-Fi plaza is accessible
- [ ] Saving is substantially faster
- [ ] All HP bars move at the fastest speed

### Bug Fixes
- [ ] Pokemon with the Poison Heal ability no longer take damage while poisoned in the overworld

## Post-Game Changes

- [ ] All encounters exclusive to having a cartridge in the GameBoy Advance slot of the Nintendo DS are available
- [ ] Regirock, Regice, and Registeel can all be encountered. Any trio of Regirock, Regice, and Registeel (regardless of each Pokemon's origin) will be sufficient to awaken Regigigas (who has been restored to level 70)
- [ ] Oak's Letter will be delivered by the deliveryman in the PokeMart after earning all eight gym badges
- [ ] The Azure Flute will be given by Professor Oak when 492 Pokemon have been caught in the National Dex
- [ ] Community Mystery Gift DNS support has been added; if not configured, a random distribution that has not already been received will be given out once every 24 hours after obtaining the National Dex

# Installation

To set up the repository, see [INSTALL.md](INSTALL.md).
