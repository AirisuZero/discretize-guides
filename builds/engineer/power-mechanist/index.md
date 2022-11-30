---
hidden: false
archive: false
specialization: Mechanist
boons:
  - name: Alacrity
    uptime: 100%
    variant: Alac
  - name: Might
    uptime: 25 Stacks
    variant: Alac
  - name: Fury
    uptime: 100%
    variant: Alac
  - name: Protection
    variant: Alac
    uptime: 40%
  - name: Might
    uptime: 5-10 Stacks
    variant: DPS
code: '[&DQMGNyYvRh8NGwAAhgCNARobAAAQGwAACRsAAAAAAAAAAAAAAAAAAAAAAAA=]'
classification:
  - 2
  - 3
  - 4
  - 1
  - 2
date: 2022-08-10T22:25:39.750Z
title: Power (Alac) Mechanist
rating: Good
role: Power Damage
profession: Engineer
conditions:
  - name: Vulnerability
    uptime: 5 Stacks
cmGuide: ''
---

The <Specialization name="Mechanist" text="Power Mechanist"/> build is great for new players. It is very easy to play and deals a reasonable amount of damage, partly even at a range. It has a simple rotation, with a good amount of CC, which alongside its high self boon generation or <Boon name="Fury"/> and <Boon name="Quickness"/>, makes it very easy to play while dealing with mechanics. It also can help generate some <Boon name="Might"/> for your party through <Skill name="Blunderbuss"/> and if required, <Trait name="Pinpoint Distribution"/>.

The <Specialization name="Mechanist" text="Power Alacrity Mechanist"/> build is the boon support counterpart. It generates 100% <Boon name="Alacrity"/>, a large amount of offensive boons (25 <Boon name="Might"/> and 100% <Boon name="Fury"/>) and the same benefits of an easy, ranged rotation as seen with <Specialization name="Mechanist" text="Power Mechanist"/>. Alongside the offensive boons it also provides some <Boon name="Protection"/> and <Effect name="Barrier"/>, with 1 stack of <Boon name="Stability"/> and <Boon name="Aegis"/> on a fairly long cooldown. While the build has fantastic offensive support, it is lacking in defensive support and CC compared to <BuildLink build="Power Alac Renegade" specialization="Renegade"/>, so it is important to make sure other members of you party can help to cover the gaps.

<Divider text="Equipment"/>

Due to being a power build, it massively benefits from slaying sigils and potions. Check out the [Cheat Sheet](/guides/cheat-sheet) to see all the combinations.

If you are struggling to maintain boons, consider replacing Berserker gear with Diviner to increase your <Attribute name="Boon Duration"/>,

This build uses 162 <Attribute name="Agony Resistance"/>, if you have more feel free to use our [Gear Optimizer](https://optimizer.discretize.eu/?m=fractals) to adjust your gear (Currently <Specialization name="Mechanist"/> damage calculations are not accurate, however it can still be used for <Attribute name="Precision"/> and <Attribute name="Concentration"/> calculations).

<Divider text="Build"/>

<Grid>
<GridItem sm="7">
<Traits traits1Id="38" traits1="Firearms" traits1SelectedIds="1914,1923,526" traits2Id="6" traits2="Explosives" traits2SelectedIds="1882,482,1947" traits3Id="70" traits3="Mechanist" traits3SelectedIds="2279,2294,2292"/>
<Card title="Situational Traits">

|                                                              |                                                                                         |
| ------------------------------------------------------------ | --------------------------------------------------------------------------------------- |
| <Trait name="Pinpoint Distribution" size="big" disableText/> | Can be used to help generate some <Boon name="Might"/> for your party if uptime is low. |

<Traits traits1Id="70" traits1="Alac Mechanist" traits1SelectedIds="2296,2276,2281" unembossed/>

When playing <Specialization name="Mechanist" text="Power Alacrity Mechanist"/>, your other traitlines remain the same as <Specialization name="Mechanist" text="Power Mechanist"/>. By swapping Mechanist traits, you gain access to new jade bot skills, most importantly <Skill id="63293"/> and <Skill id="63141"/>, which are a large source of your boon generation.

<Traits traits1="Scrapper" traits1Selected="Gyroscopic Acceleration, Kinetic Accelerators" unembossed />

For many skips in Tier 4 fractals, you can swap to Scrapper for more <Effect name="Stealth"/> and <Effect name="Superspeed"/>. <Effect name="Stealth"/> can be provided through <Skill name="Sneak Gyro"/>. <Effect name="Superspeed"/> is provided through Gyros with a delay due to <Trait name="Gyroscopic Acceleration"/>. <Skill name="Medic Gyro"/> also provides some instant <Effect name="Superspeed"/> on top. <Skill name="Bulwark Gyro"/> and <Skill name="Purge Gyro"/> can be used without drawing aggro from enemies. <Skill name="Bypass Coating"/> can provide some instant <Effect name="Superspeed"/> as well.
</Card>
</GridItem>

<GridItem sm="5">
<Card title="Additional DPS Skills">

|                                           |                                                                                                                                                                                                               |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Jade Mech                                 | <Skill id="63188" size="big" disableText/><Skill id="63345" size="big" disableText/><Skill id="63121" size="big" disableText/>                                                                                |
| <Skill id="6020" size="big" disableText/> | <Skill id="5882" size="big" disableText/><Skill id="5807" size="big" disableText/><Skill id="5808" size="big" disableText/><Skill id="5809" size="big" disableText/><Skill id="5806" size="big" disableText/> |

</Card>
<Card title="Additional Alac Skills">

|                                           |                                                                                                                                                                                                               |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Jade Mech                                 | <Skill id="63365" size="big" disableText/><Skill id="63293" size="big" disableText/><Skill id="63141" size="big" disableText/>                                                                                |
| <Skill id="6020" size="big" disableText/> | <Skill id="5882" size="big" disableText/><Skill id="5807" size="big" disableText/><Skill id="5808" size="big" disableText/><Skill id="5809" size="big" disableText/><Skill id="5806" size="big" disableText/> |

</Card>
<Card title="CC skills">

|                     |                                          |
| ------------------- | ---------------------------------------- |
| <Skill id="63345"/> | 232 damage                               |
| <Skill id="63121"/> | 100 damage                               |
| <Skill id="6154"/>  | 232 damage                               |
| <Skill id="63253"/> | 150 damage                               |
| <Skill id="5811"/>  | 232 damage                               |
| <Skill id="6004"/>  | <Condition name="Immobile"/> 50/s damage |
| <Skill id="5808"/>  | <Condition name="Blinded"/> 20/s damage  |
| <Skill id="5809"/>  | <Condition name="Chilled"/> 33/s damage  |
| <Skill id="63365"/> | <Condition name="Weakness"/> 20/s damage |

</Card>
<Card title="Situational Skills">
If you need to swap out a utility skill, <Skill name="Grenade Kit"/> should first be swapped. However, <Skill name="Shrapnel Grenade"/> is a big part of your damage and should only be swapped out if necessary.

|                                                     |                                                                                                                                                                     |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <Skill id="5857" size="big" disableText/>           | An alternative heal skill if condition cleanse is needed and a small amount of group healing. Its flip skill, <Skill id="5961"/> can be used to blast combo fields. |
| <Skill id="5811" size="big" disableText/>           | Can be taken if extra CC is required                                                                                                                                |
| <Skill name="Tool Kit" size="big" disableText/>     | Has access to a block with <Skill id="5998"/> and a pull with <Skill id="5996"/>                                                                                    |
| <Skill name="Sneak Gyro" size="big" disableText/>   | A <Specialization name="Scrapper"/> skill, used for group <Effect name="Stealth"/> in T4 fractals.                                                                  |
| <Skill name="Rocket Boots" size="big" disableText/> | Can be used for mobility and some skips in T4s                                                                                                                      |

</Card>
</GridItem>
</Grid>

<Divider text="Rotation / Skill Usage"/>

<Grid>
<GridItem sm="7">
<Card title="General Rotation">

As previously mentioned, <Specialization name="Mechanist" text="Power Mechanist"/> has an extremely simple rotation, that consists of pressing certain skills pretty much off cooldown past your opener.

### Opener

Your general opener is as follows, this applies to most encounters and phases that start with a CC bar:

1. <Skill id="63345"/> (Jade mech F2)
2. <Skill name="Overcharged Shot"/> (Rifle 4)
3. <Skill name="Blunderbuss"/> (Rifle 2)
4. <Skill name="Shrapnel Grenade"/> (<Skill name="Grenade Kit"/> 2)
5. <Skill name="Poison Grenade"/> (<Skill name="Grenade Kit"/> 5)
6. <Skill name="Freeze Grenade"/> (<Skill name="Grenade Kit"/> 4)
7. <Skill name="Net Shot"/> (Rifle 3)
8. <Skill name="Jump Shot"/> (Rifle 5)
9. <Skill id="6003"/> (Rifle 1)

### Jade Mech Priority

Your Jade Mech skills should be pressed in most stuations off cooldown with the priority below. However, these should be delayed in needed, for example saving <Skill id="63345"/> to CC with.

1.  <Skill id="63345"/> (Jade mech F2)
2.  <Skill id="63121"/> (Jade mech F3)
3.  <Skill id="63188"/> (Jade mech F1)
4.  <Skill id="63095"/> (Elite Skill)

### General Rotation

On Rifle

- Use <Skill name="Blunderbuss"/> (Rifle 2) into <Skill name="Shrapnel Grenade"/> (<Skill name="Grenade Kit"/> 2)
- Press your other rifle skills off cooldown
- In low gravity, skip <Skill name="Jump Shot"/> (Rifle 5)

In <Skill name="Grenade Kit"/>

- Use <Skill name="Freeze Grenade"/> (Skill 4) and <Skill name="Poison Grenade"/> (Skill 5) when off cooldown
- Use <Skill name="Shrapnel Grenade"/> (Skill 2) after using <Skill name="Blunderbuss"/> (Rifle 2)

</Card>
</GridItem>

<GridItem sm="5">
<Card title="Alacrity Mechanist">
  
As a <Specialization name="Mechanist" text="Power Alacrity Mechanist"/> your general weapon rotation does not change. However, you do gain a new set of Jade Mech skills. These should be used with the following priority in mind:

1.  <Skill id="63293"/> (Jade mech F2)
2.  <Skill id="63141"/> (Jade mech F3)
3.  <Skill id="63365"/> (Jade mech F1)
4.  <Skill id="63095"/> (Elite Skill)

Your boon generation is mostly passive and will be maintained by attacking and pressing your Jade Bot skills off cooldown. However, if you are starting from zero stacks of <Boon name="Might"/>, you can instantly ramp to 25 stacks by using <Skill id="63141"/> and <Skill name="Blunderbuss"/>.

If you are on movement heavy fights, traveling through portals or using forced movement mechanics like the updrafts on Skorvald, you mech may get left behind. Remember to let it catch up, resummon it or use <Skill name="Shift Signet"/> to port it before sharing boons.

</Card>
</GridItem>
</Grid>
