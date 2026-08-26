# Aspects and Visors

Aspects are hardmode variants of gem staves. Visors are hardmode variants of gem robes.

## General Rules

- All aspects have their staves in their recipes.
- Aspects can be empowered by **only** their respective gem robes.
- Aspects should have a primitive trail and appear as two perpendicular sharp tears stacked on each other, similar to the recently reworked vanilla staves. Reference: `drawprettysparckles` used by projectiles like Terra Blade.
- Aspects have **10% crit** and **pink rarity**.

## Gem Aspects

### Aspect of Amethyst

- Fires from a random radius away from the cursor and then fires at the center.
- Has increased homing compared to the Amethyst Staff.
- One pierce.
- Cannot home onto the same target twice.
- Suggested values: `use time 14`, `velo 6`, `damage 55`

**Upgraded with:**

- Crystal Shards
- Souls of Light
- Gelatinous Crystal

**Gem robe bonus:**

- Adds a second ring that fires at 30% speed.

### Aspect of Topaz

- Has a primed explosion.
- Flies for 1 second before exploding for 100% damage.
- A pre-emptive hit deals 50% explosion damage and 50% radius.
- Suggested values: `use time 37`, `velo 9`, `damage 120`

**Upgraded with:**

- Light Shard x2
- Souls of Light
- Pixie Dust

**Gem robe bonus:**

- Increases explosion radius by 100%.

### Aspect of Sapphire

- Fires four consecutive gems.
- Each gem has its own helix with random progress.
- Different X offsets in the sine wave.
- Suggested values: `use time 4`, `animation 16`, `reuse delay 12`, `velo 8`, `damage 50`

**Upgraded with:**

- Souls of Night
- Sight
- Tier three hardmode bars

**Gem robe bonus:**

- Increases the size of the helix.
- Adds a mirrored projectile for each helix.
- Reduced 30% damage for each projectile.

### Aspect of Emerald

- Has fast projectile speed.
- Sticks to blocks.
- Has three pierce.
- Maximum of three crystals can be stuck to blocks.
- When pierce is depleted, stuck emeralds burst into a pillar of emeralds with infinite pierce and 100% damage for a short time.
- Pillar uses local immunity frames: `10`.
- Pillars point outwards from the attached block, similar to Blood Thorn behavior (reference projectile ID `756`).
- Suggested values: `use time 24`, `velo 12`, `damage 30`

**Upgraded with:**

- Bloodthorn
- Purification Powder

**Gem robe bonus:**

- Increases the maximum crystals stuck to blocks to 8.

### Aspect of Amber

- Repeatedly bounces toward enemies like nano bullets.
- Has two pierce.
- Suggested values: `use time 24`, `velo 10`, `damage 60`
- This is the only aspect with gravity enabled.
- Reference: chlorophyte arrows for AI behavior.

**Upgraded with:**

- Desert Spirit Lamp
- Amber Torch
- Desert Torch

**Gem robe bonus:**

- Adds one pierce.

### Aspect of Ruby

- Spawns a volley of 3 gems at a random Y position on the left or right side of the player’s screen.
- Spawns on the side opposite to where the player is aiming.
- No pierce.
- Ignores blocks.
- Suggested values: `use time 5`, `animation 16`, `reuse delay 16`, `extra updates 1`, `velo 20`, `damage 60`

**Upgraded with:**

- Souls of Might
- Souls of Night
- Starfury

**Gem robe bonus:**

- Adds another gem to the volley.
- `use time 5 -> 4`

### Aspect of Diamond

- Can be charged for a maximum of 2 seconds.
- Does 300% damage.
- Has 200% size.
- Loses 50% speed when at max charge.
- Has the largest base hitbox of all the gems.
- Releases a visual white flash on impact.
- Suggested values: `size x2`, `use time 25`, `velo 8`, `base damage 120`

**Upgraded with:**

- Hallowed Bars

**Gem robe bonus:**

- Maximum charge time becomes 4 seconds.
- Maximum damage increases to 800%.
- Size increases to 250%.
- Speed remains unchanged after 2 seconds.

## Visors

### Amethyst Visor

- Provides great homing capabilities for all common mage staves:
  - Frost
  - Crystal Serpent
  - Sky Fracture
  - Gem staves
  - Inferno Stave
  - Meteor Staff
  - Poison Staff

### Topaz Visor

- Adds an explosion to all gem stave projectiles for 33% damage.

### Sapphire Visor

- Doubles the projectiles of all common staves at reduced 40% damage.
- Second projectile has inaccuracy.

### Emerald Visor

- Makes all other gem staves erupt three gem pillars when hitting an enemy at the hit normal.
- All pillars have `-1` immunity frames.
- The main pillar does 20% damage, while the other pillars do 10% damage.

### Amber Visor

- Gives +1 pierce to all common staves.
- Makes them deal 30% less damage every enemy hit.

### Ruby Visor

- Increases time flow for all magic weapons.
- Grants +1 extra update.

### Diamond Visor

- Increases the size of all stave projectiles by 50%.
- Decreases use speed by 33%.
- Increases damage by 33%.

## Crafting and Set Bonus

- All visors are crafted via their respective giant gem and hallowed bars.
- They gain a set bonus with gem robes, which decreases mana usage by 50%.
