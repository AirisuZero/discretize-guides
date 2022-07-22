---
hidden: false
archive: false
hasBeginner: true
specialization: Virtuoso
boons: []
code: "[&DQcBHQoZQjojDyMPjwGPAd0aawFpAWkB7RK8AQAAAAAAAAAAAAAAAAAAAAA=]"
classification:
  - 3
  - 4
  - 3
  - 3
  - 4
date: 2022-07-22T10:21:16.748Z
title: Power Virtuoso
rating: Good
role: Power Damage
profession: Mesmer
conditions:
  - name: Vulnerability
    uptime: 25 stacks
---

<Advanced>

The <Specialization text="Power Virtuoso" name="Virtuoso"/> is currently the strongest power build for <Specialization name="Mesmer"/> in fractals.

You'll provide boon removal through <Skill name="Phantasmal Disenchanter"/> and <Trait name="Vicious Expression"/> as well as Sword auto-attack chains when playing the Sword/Focus variant.

The <Specialization name="Mesmer"/> provides an optimal skipping toolset for T4 fractals which should be utilized. This build profits from sigils like <Item name="Impact" type="Sigil"/> as well as slaying potions such as <Item name="Powerful Potion of Slaying Scarlets Armies"/>.

</Advanced>

<Beginner>

The <Specialization text="Power Virtuoso" name="Virtuoso"/> is currently the strongest power build for <Specialization name="Mesmer"/> in fractals. It can bring a decent amount of CC while offering good burst damage and great sustained DPS, as well as being able to adapt to bring a ton of extra utility such as <Boon name="Stability"/> or a reflect from the <Specialization name="Mesmer"/> toolkit.

The beginner version of the guide will focus on the most important utility options and try to teach the Greatsword version of the build which has a good amount of extra burst while also having notes for the Sword/Focus variant which can be useful for slightly more sustained damage and nice utility through <Skill name="Temporal Curtain"/>.

The advanced page provides a more complete overview of all the utilities the <Specialization name="Mesmer"/> has to offer. Once you can execute the step-by-step rotation provided below without spending too much thought on it and are confident with the utility options provided here, head over and check out the advanced page for some extra information. Feel free to swap to the advanced page early if you feel like you are missing some information on additional (less common) utility skills or trait swaps.


</Beginner>

<Divider text="Equipment"/>

<CharacterWithAr>  
<Character title="DPS" gear={{
  "profession": "Mesmer",
  "weight": "Light",
  "gear": [
    "Berserker",
    "Assassin",
    "Berserker",
    "Assassin",
    "Assassin",
    "Assassin",
    "Berserker",
    "Berserker",
    "Berserker",
    "Assassin",
    "Berserker",
    "Assassin",
    "Berserker",
    "Berserker"
  ],
  "attributes": {
    "Health": 20702,
    "Armor": 2210,
    "Power": 3508,
    "Precision": 2156,
    "Toughness": 1243,
    "Vitality": 1478,
    "Ferocity": 1460,
    "Condition Damage": 750,
    "Expertise": 0,
    "Concentration": 243,
    "Healing Power": 0,
    "Agony Resistance": 162,
    "Condition Duration": 0,
    "Boon Duration": 0.162,
    "Critical Chance": 1,
    "Critical Damage": 2.473  ,
    "Power Coefficient": 3013,
    "Power2 Coefficient": 1172,
    "Burning Coefficient": 0,
    "Bleeding Coefficient": 8.325,
    "Poison Coefficient": 0,
    "Torment Coefficient": 0,
    "Confusion Coefficient": 0.21,
    "Flat DPS": 0,
    "Effective Power": 29738.943224923456,
    "Power DPS": 34502.67074959352,
    "Power2 DPS": 5459.581863855729,
    "Bleeding Damage": 1052.3645507812498,
    "Bleeding Stacks": 8.325,
    "Bleeding DPS": 126.41015625,
    "Burning Damage": 373.19296875,
    "Burning Stacks": 0,
    "Burning DPS": 0,
    "Confusion Damage": 124.59890625,
    "Confusion Stacks": 0.24,
    "Confusion DPS": 26.165770312499998,
    "Poison Damage": 118.48593749999999,
    "Poison Stacks": 0,
    "Poison DPS": 0,
    "Torment Damage": 149.8809375,
    "Torment Stacks": 0,
    "Torment DPS": 0,
    "Damage": 41187.520434543,
    "Effective Health": 70025114.4278607,
    "Survivability": 46287.545495704,
    "Effective Healing": 390,
    "Healing": 390,
    "Siphon Base Coefficient": 139.75,
    "Siphon DPS": 146.7375,
    "Phantasm Critical Chance": 0.95,
    "Phantasm Critical Damage": 2.4726666666666666,
    "Phantasm Effective Power": 12097.725341666664
    
  },
  "runeId": 24836,
  "runeName": "Scholar",
  "infusions": [
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131,
    37131
  ],
  "weapons": {
      "weapon1MainType": "Dagger",
      "weapon1MainSigil1": "Force",
      "weapon1OffType": "Sword",
      "weapon1OffSigil": "Impact",
      "weapon2MainType": "Greatsword",
      "weapon2MainSigil1": "Force",
      "weapon2MainSigil2": "Impact"
    },
  "consumables": {
      "foodId": 91709,
      "utilityId": 9443,
      "infusion": "Mighty +9 Agony Infusion"
    },
  "skills": {
    "healId": 21750,
    "utility1Id": 10267,
    "utility2Id": 45425,
    "utility3Id": 10211,
    "elite": "Signet of Humility"
  },
  "assumedBuffs": [{ "type": "Item", "gw2id": 79722 }, { "type": "Item", "gw2id": 96613 }, {"id": "Might", "type": "Boon"}, {"id": "Fury", "type": "Boon"}, {"id": "Protection", "type": "Boon"}, {"id": "Vulnerability", "type": "Condition"}]
}}>

For fractals you need 150 agony ressistance. Gear going to stay the same for any amount of agony ressistance!

Check the [gear optimizer](https://optimizer.discretize.eu/) for more gear variants!


</Character>

</CharacterWithAr>

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Card title="Extra Weapons">

- You can run Sword/Focus instead of Greatsword. This will result in lower burst damage but slightly higher sustained damage. Therefore, it can make sense to run this version when bosses have long phases. Above 10 seconds into the phase, they will be roughly equal, at 25 seconds, the Sword/Focus variant will pull ahead slightly.
- If you want to run one variant on all fights, Greatsword is highly recommended.
- Focus specifically is very useful to use in T4 fractals to pull groups of enemies together with <Skill name="Temporal Curtain"/> to cleave them down more easily.

<Advanced>

- You can run Pistol instead of Focus on fights with multiple enemies when deciding to run this variant as <Skill name="Phantasmal Warden"/> does not always attack your target.
- Greatswords, Swords, Pistols and Foci with <Item name="Night" type="Sigil" disableText/>, <Item name="Serpent Slaying" type="Sigil" disableText/> and other slaying sigils.
- Torch for stealth, blasting, and precasting
- Staff for precasting at certain bosses.
- Shield for blocks if you are skipping with <Specialization name="Chronomancer"/>

</Advanced>

</Card>
<Traits traits1="Dueling" traits1Selected="Phantasmal Fury,Fencers Finesse,Superiority Complex" traits2="Domination" traits2Selected="Bountiful Blades,Egotism,Vicious Expression" traits3="Virtuoso" traits3Selected="Mental Focus,Phantasmal Blades,Bloodsong"/>

<Card title="Situational Traits">

|                                                            |                                                                           |
| ---------------------------------------------------------- | ------------------------------------------------------------------------- |
| <Trait name="Empowered Illusions" size="big" disableText/> | Take this trait if you're playing with Sword/Focus instead of Greatsword. |

<Traits traits1="Illusions" traits1Selected="Shatter Storm,Phantasmal Haste,Phantasmal Force" unembossed/>

You can go this Illusions variant over the Domination traitline when you're facing <Boon name="Quickness"/> uptime issues to be more self-sufficient in bad groups, if you're also lacking <Boon name="Might"/> and <Boon name="Fury"/> consider going <Trait name="Persistence of Memory" size="small"/> as well.

<Advanced>
<Traits traits1="Mirage" traits1Selected="Elusive Mind" unembossed/>

Utilize Mirage for skips!

<p>
<Trait name="Elusive Mind"/>, <Skill name="Jaunt"/> and <Skill name="Mirage Thrust"/> along with the typical Mesmer toolset makes it really good for mobility and skips.
</p>

<Traits traits1="Chronomancer" traits1Selected="Improved Alacrity,Seize the Moment" unembossed/>

Situationally used for <Skill name="Continuum Split"/>, which can be useful when stealthing your group with <Skill name="Mass Invisibility"/> or any utility you want to use twice. Additionally allows for shield to be equipped giving you a very strong block with <Skill id="30769"/> and <Skill id="29649"/>. In niche cases can be used for some self <Boon name="alacrity"/> through <Trait name="Flow of Time"/> and <Trait name="Improved Alacrity"/>.

</Advanced>
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Situational Skills">

Swap out <Skill name="Mantra of Pain"/> before any other skill.

<Beginner>

|                                                                |                                                                               |
| -------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| <Skill name="Mantra of Concentration" size="big" disableText/> | A nice source of party-wide <Boon name="Stability"/>.                         |
| <Skill name="Blade Renewal" size="big" disableText/>           | For prestacking blades before the fight                                       |
| <Skill name="Feedback" size="big" disableText/>                | Mainly for Artsariiv to reflect Taw Shot.                                     |
| <Skill name="Thousand Cuts" size="big" disableText/>           | Can be used instead of <Skill name="Signet of Humility"/> if no CC is needed. |

<Divider text="CC Skills"/>

|                                      |                       |
| ------------------------------------ | --------------------- |
| <Skill name="Bladesong Dissonance"/> | 50 damage (per Blade) |
| <Skill name="Counter Blade"/>        | 200 damage            |
| <Skill name="Into the Void"/>        | 150 damage            |
| <Skill name="Signet of Humility"/>   | 600 damage            |
| <Skill name="Illusionary Wave"/>     | 150 damage            |
| <Condition name="Slow"/>             | 50 damage per second  |

</Beginner>

<Advanced>

|                                                                |                                                                                                                                                                                            |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <Skill name="Mantra of Concentration" size="big" disableText/> | A nice source of party-wide <Boon name="Stability"/>.                                                                                                                                      |
| <Skill name="Blade Renewal" size="big" disableText/>           | For prestacking blades before the fight                                                                                                                                                    |
| <Skill name="Mimic" size="big" disableText/>                   | For precasting <Skill name="Rain of Swords"/> at bosses, and for double casting <Skill name="Blink" size="small"/> for skips.                                                              |
| <Skill name="Null Field" size="big" disableText/>              | When you have issues with boons on the boss (should only be used in extreme cases).                                                                                                        |                                                                                                                                                        |
| <Skill name="Feedback" size="big" disableText/>                | Mainly for Artsariiv to reflect Taw Shot.                                                                                                                                                  |
| <Skill name="Thousand Cuts" size="big" disableText/>           | Can be used instead of <Skill name="Signet of Humility"/> if no CC is needed.                                                                                                              |
| **Skips**                                                      |                                                                                                                                                                                            |
| <Skill name="Blade Leap" size="big" disableText/>              | A 600 leap (only availible as <Specialization name="Virtuoso"/>)                                                                                                                           |
| <Skill name="Returning Edge" size="big" disableText/>          | Useable after <Skill name="Blade Leap"/> to return to your original location                                                                                                               |
| <Skill name="Portal Entre" size="big" disableText/>            | For skipping sections of the fractal for your party.                                                                                                                                       |
| <Skill name="Blink" size="big" disableText/>                   | 1200 range blink, use it for skips!                                                                                                                                                        |
| <Skill name="Mass Invisibility" size="big" disableText/>       | For stealthing your party for skips, can be combined with <Skill name="Continuum Split" size="small"/> and <Trait name="Prismatic Understanding" size="small"/> for 18 seconds of stealth. |
| <Skill name="Well of Precognition" size="big" disableText/>    | Situational uses such as the Underground Facility door.                                                                                                                                    |
| <Skill name="Mirage Thrust" size="big" disableText/>           | 600 range leap, can be cancelled mid-air for slightly more range.                                                                                                                          |
| <Skill name="Jaunt" size="big" disableText/>                   | 450 range blink, 3 charges.                                                                                                                                                                |
| <Skill name="Illusionary Ambush" size="big" disableText/>      | 1200-2400(1500 activation) range targeted teleport. This skill is tricky because of its random nature but allows for some skips.                                                           |

</Advanced>

</Card>
</GridItem>
</Grid>

<Advanced>
<Divider text="Details"/>

<Grid>

<GridItem sm="8">
<Card title="Skill priority">

To play <Specialization text="Power Virtuoso" name="Virtuoso"/> in fractals you need to adapt on the go as phantasms are slower than skills from other classes.

If you lose yourself in the rotation follow this priority list.

1.  Cast your phantasms whenever ready.
    - <Skill id="10174"/>
    - <Skill id="10267"/>
    - <Skill id="10221"/>
2.  Use <Skill id="21750"/> to recharge them all.
3.  Use <Skill name="Bladesong Harmony"/> with 5 Blades as much as possible. Only delay it for <Effect name="Exposed"/> but remember that it also grants you a 5% damage buff through <Trait name="Deadly Blades"/>.
4.  Use <Skill name="Bladesong Sorrow"/> for damage and to keep up the buff from <Trait name="Deadly Blades"/>. Make sure to prioritize having 5 Blades for <Skill name="Bladesong Harmony"/> though. Situationally you can use this with 5 Blades such as in your burst rotation or when a phase is about to end and <Skill name="Bladesong Harmony"/> is on cooldown.
5.  <Skill id="62553"/> deals damage over time so make sure to cast it at the start of phases. If a boss is close to phasing, save it for the start of the next phase.
6.  Use <Skill id="62560"/>, <Skill id="62607"/>, <Skill id="10333"/> and <Skill id="10218"/> off recharge.

- <Skill name="Illusionary Riposte"/> is a DPS increase if you time it well, and don't interrupt other casts.

Remember that your personal damage skills are faster than phantasms, but that they deal more damage over time, this means that direct damaging skills such as <Skill id="62560"/> and auto-attacks get higher priority if the boss is close to phasing.

Utilize <Skill name="Bladesong Dissonance"/> for CC, but also remember to not use too much CC on the break bar and space out your big CC cooldowns like <Skill name="Signet of Humility"/> so they don't overlap with other powerful CC skills.

Apart from doing DPS, you'll also have access to a wide range of utilities which can all be used for skips, blocks, and damage mitigation. Make sure to read what they do and don't be afraid to swap to them situationally, especially in T4s.
</Card>
</GridItem>

<GridItem sm="4">
<Card title="CC skills">

|                                      |                       |
| ------------------------------------ | --------------------- |
| <Skill name="Bladesong Dissonance"/> | 50 damage (per Blade) |
| <Skill name="Counter Blade"/>        | 200 damage            |
| <Skill name="Into the Void"/>        | 150 damage            |
| <Skill name="Signet of Humility"/>   | 600 damage            |
| <Skill name="Illusionary Wave"/>     | 150 damage            |
| <Skill name="Magic Bullet"/>         | 250 damage            |
| <Skill name="Phantasmal Mage"/>      | 100 damage            |
| <Condition name="Slow"/>             | 50 damage per second  |

</Card>
</GridItem>
</Grid>

</Advanced>

<Divider text="Rotation / Skill usage"/>

<Grid>
<GridItem xs="12" sm="7">

<Beginner>

<Card title="Step by Step Rotation">

**Step 1: Phantasms**

We'll start with the basic rotation for summoning Phantasms. This is the backbone of the rotation and practicing this part for a bit will get you set up well for the rest of the rotation.

1. Start on Greatsword and use <Skill name="Phantasmal Berserker"/>, then swap to Dagger/Sword.
2. Use <Skill name="Phantasmal Swordsman"/> and <Skill name="Phantasmal Disenchanter"/>.
3. Reset your cooldowns with <Skill name="Signet of the Ether"/> and cast both Phantasms again.
4. Wait on Dagger/Sword until you can cast one more <Skill name="Phantasmal Swordsman"/>, then swap back to Greatsword.
5. Use <Skill name="Phantasmal Berserker"/> right away.
6. Use <Skill name="Phantasmal Disenchanter"/> when it comes back.
7. Wait for one more <Skill name="Phantasmal Berserker"/> and then swap back to Dagger/Sword.
8. Repeat from Step 2. (skipping the <Skill name="Phantasmal Disenchanter"/> in that step.)

**Step 2: F1 Shatter**

Next, we will incorporate our F1 Shatter <Skill name="Bladesong Harmony"/>.

- Use it only when you have 5 Blades stocked.
- Use it for the first time after your initial <Skill name="Phantasmal Berserker"/>.
- Use it off-cooldown but only with 5 Blades afterward.

**Step 3: Weapon Skills**

In Step 3, we will incorporate other Weapon Skills. We will add multiple skills at once so take your time if you feel like you struggle with this.

1. Cast <Skill name="Bladecall"/> right after swapping to Dagger/Sword.
2. Cast <Skill name="Unstable Bladestorm"/> right before your Heal Signet.
3. Use both skills off-cooldown afterward until you swap to Greatsword.
4. Cast <Skill name="Mirror Blade"/> and <Skill name="Mind Stab"/> right after <Skill name="PHantasmal Berserker"/> and use them off-cooldown until you swap back to Dagger/Sword.
5. Repeat from Step 1.

**Step 4: Utility Skills**

Lastly, we will add the remaining Utility Skills to the rotation.

- Cast <Skill name="Rain of Swords"/> at the start of the fight and then use it off-cooldown.
- Cast <Skill name="Mantra of Pain"/> off-cooldown as well. This skill is an instant cast and can therefore be used while casting other skills.

</Card>

<Card title="Improving Further">

Once you are comfortable with the above steps, you are already doing most of the full rotation and will be able to deal great damage.

There will be a few additional things on the advanced page to improve further but if you got here, you already know the most important things and these will have a smaller impact than what you learned so far.

The additional steps are:

- Use other Shatter skills (F2/F3) for extra damage and to keep up the buff from <Trait name="Deadly Blades"/>. Make sure to always have 5 Blades back for when your <Skill name="Bladesong Harmony"/> comes back.
- Precast additional skills before the encounter starts to get a bigger spike of damage at the start of the fight.

</Card>

</Beginner>

<Advanced>
<Card title="Information">

Golem rotations out of the raid builds are generally suboptimal in fractals due to <Effect name="Exposed"/> and phases being much shorter compared to raids. The raid rotations are optimized for sustained DPS while in fractals a player needs the ability to adapt a rotation to the amount of time a group needs to finish a phase.

It's important to note that phantasms do not benefit from most modifiers unless it is stated to be the case.

They do however benefit from <Effect name="Exposed"/>.
</Card>

<Card title="Precasting">

At the Mistlock Singularity

- Make sure to start with 5 Blades. If you need use <Skill name="Blade Renewal"/> to replenish them.

1. Blast fire fields with <Skill name="The Prestige"/>.
2. Extend boons with <Skill name="Signet of Inspiration"/> if you have time.
3. Precast <Skill name="Mimic"/> and take the singularity when your group is done pre-buffing.
4. Additionally you can precast a <Skill name="Time Warp"/> on the boss and take the singularity as well on bosses like Skorvald, or any boss if you use portals.

At the boss (spawnable bosses)

1. Cast <Skill name="Rain of Swords"/>. Skip this step if you did not use <Skill name="Mimic"/> at the singularity.
2. You can precast <Skill name="The Prestige"/> and <Skill name="Chaos Storm"/> to squeeze out a little more burst, if your group coordinates.
3. Cast <Skill name="Rain of Swords"/> (again).
4. Start casting <Skill name="Signet of Humility"/> if the boss starts with a break bar.

At the boss (pre spawned bosses)

- You can also precast <Skill name="Phantasmal Warlock"/>.

</Card>
</Advanced>
</GridItem>

<GridItem xs="12" sm="5">

<Beginner>
<Card title="Step-by-Step Video">

This video shows the step-by-step approach to the rotation listed on the left.
<Video caption="by Ascers" youtube="10c1XNlXeVk"/>
</Card>
</Beginner>

<Card title="Golem Rotation">

This video shows the full rotation for the Greatsword variant on the golem. It will slightly vary from the step-by-step version.

<Video caption="by Tipcat [CnD]" youtube="92FJUY1IKh4"/>
</Card>

<Beginner>
<Card title="Sword/Focus Variant">

If you are using Sword/Focus instead of Greatsword, follow the same step-by-step guide but make the following changes:

- Replace <Skill name="Phantasmal Berserker"/> with <Skill name="Phantasmal Warden"/>. You will only be able to cast it once each time you are on the Sword/Focus weapon set (while <Skill name="Phantasmal Berserker"/> can be cast twice per Greatsword Loop.)
- Instead of spamming <Skill name="Mirror Blade"/> and <Skill name="Mind Stab"/> off-cooldown, use <Skill name="Blurred Frenzy"/> off-cooldown on Sword/Focus.
- Try to finish your auto-attack chains on Sword if possible.

</Card>
</Beginner>

<Advanced>
<Card title="Opener">

There is a basic opener, you will need to adapt this depending on the boss and cooldowns.

- Start on Greatsword

1. <Skill id="62553"/>
2. <Skill name="Phantasmal Berserker"/>
3. <Skill name="Bladesong Harmony"/>
4. _Weapon Swap_
5. <Skill name="Bladecall"/>
6. <Skill name="Phantasmal Swordsman"/>
7. <Skill name="Mantra of Pain"/>
8. <Skill name="Phantasmal Disenchanter"/>
9. <Skill name="Mantra of Pain"/>
10. <Skill name="Unstable Bladestorm"/>
11. <Skill name="Signet of the Ether"/>
12. <Skill name="Phantasmal Swordsman"/>
13. <Skill name="Bladesong Sorrow"/>
14. <Skill name="Bladecall"/>
15. <Skill name="Phantasmal Disenchanter"/>

</Card>
</Advanced>

</GridItem>
</Grid>
