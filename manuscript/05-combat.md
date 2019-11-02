-# Combat

Occasionally, everything will go very wrong (or, more rarely, very right) and characters will find themselves in a fight.
The rules in this chapter explain how combat works, building on top of the core rules.

## Moment By Moment

When combat breaks out, time is counted mechanically in moments - roughly three seconds each - during which initiative order is followed.

At the beginning of each moment, everyone involved in the combat makes an opposed Flax test.
From worst result to best, the players declare their characters' intended actions and reactions.
In reverse order the actions take place and are adjudicated; reactions take place when triggered.

In a moment, a character can make one action and reaction without penalty.
If a character wants to perform two actions they may forego their reaction and vice versa.
A character may take an additional action or reaction without forgoing another, but all of their tests are one step harder as a result.
A character may also forego an action or reaction to focus on just the one thing, making the test one step easier.

- Actions include, but are not limited to, the following:
  - **Attacking:** an attacking character makes a Bone test adding a skill or vocation bonus as normal.
    If the target doesn't use a reaction against the attack and the test result is a success, the character inflicts damage per their weapon on the target.
    Alternatively, an attack can be used to reposition, disarm, or grapple an opponent or otherwise impose your will on them.
  - **Moving:** a character can move somewhere nearby as an action, or somewhere distant if they use both their action and their reaction.
  - Other actions, like throwing a grappling hook, drinking a potion, using a matrix or scroll - they don't require specific rules, the referee can make sensible rulings as the game goes - but it **is** important that those rulings remain _consistent_ during play.
- Reactions include, but are not limited to, the following:
  - **Parrying:** choose to bat aside an incoming attack by making an opposed Bone test.
  - **Blocking:** choose to position your shield in front of an incoming attack by making an easy opposed Bone test; if successful, reduce the usage die of the shield by one step.
  - **Dodging:** choose to try to move out of the way of an incoming attack by making a hard opposed Bone test.
  - Interfering with another action will always be contextual and require a ruling from the referee, but normally an opposed test of some sort will be the right call.

## Injury and Recovery

When a character takes damage that their armor points can't soak, they lose hit points.
When a character reaches 0 hit points they are dead.

<!-- TODO: Add an option for not-dying at 0 and one less brutal? -->

### Major Wounds

If a character loses at least half their _current_ hitpoints from a single instantaneous source they suffer a major wound per the table below.
Some results on the table includes a value for a dice roll in parentheses, like `(d6)`.
After a character suffers a major wound they make a death test by rolling that die and adding any listed bonus; if the result is greater than or equal to the size of the die, the character dies from their wound.
Otherwise, they'll survive, provided they get competent medical attention quickly.

If the result on the table is something that could be on either side of the body, it is on the left if the last rolled test result was even and on the right side if it was odd.

| Roll d12 | Body Part | Crushing                                             | Slicing                           | Piercing                                                                    |
|:--------:|:---------:|:-----------------------------------------------------|:----------------------------------|:----------------------------------------------------------------------------|
|     1    | Foot      | Foot crushed, walk slowly with a limp                | Foot cut off (d6)                 | Foot stabbed through, limp til healed (d3-1)                                |
|     2    | Leg       | Femur cracked, walk slowly until healed              | Femoral artery sliced (d6+2)      | Thigh pierced,  painful flesh wound, slowing movement til healed (d6)       |
|     3    | Hand      | Fingers crushed, unable to hold anything securely    | Hand cut off (d6)                 | Hand stabbed through, unable to hold anything til healed (d3-1)             |
|     4    | Arm       | Forearm broken, can't hold anything heavy til healed | Arm cut off at the elbow (d6+2)   | Forearm pierced, painful flesh wound, hard to hold anything til healed (d6) |
|     5    | Belly     | Ruptured Spleen (d6)                                 | Intestines falling out (d3)       | Aorta severed (d6+4)                                                        |
|     6    | Chest     | Collapsed Lung (d6+1)                                | Sliced pectoral (d3-1)            | Pierced Heart, death                                                        |
|     7    | Neck      | Broken Neck (d6+3)                                   | Slit throat, death                | Stabbed in the throat (d6+3)                                                |
|     8    | Cheek     | Shattered cheek, concussion (d3)                     | Cheek sliced open to mouth (d3-1) | Broken teeth and severed tongue (d6)                                        |
|     9    | Eye       | Broken eye socket, eye pulverized (d3)               | Eye sliced open, useless          | Lost eye (d6-1)                                                             |
|    10    | Skull     | Shattered skull (d6+2)                               | Skull split (d6+1)                | Pierced skull (d3)                                                          |
|    11    | Nose      | Crushed face (d6+1)                                  | Nose cut off (d3-1)               | Nose split (d3)                                                             |
|    12    | Ear       | Oozing Brains, death                                 | Ear cut off (d3-1)                | Ear split (d3)                                                              |

### Medical attention

Anyone can try to provide medical attention to an injured character by making a hard Flax test for each wound sustained.
For each success, they heal 1d3 HP up to the injured character's maximum HP.

If the test is a failure, no HP are restored and the character may not try to heal that wound again until they improve a medical skill or vocation.

### Natural Healing

For every week of relative rest a character regains 1HP.
