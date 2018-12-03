-# Core Mechanics

In Pentola, there are a few things which make up the core mechanics:

- Action Resolution: How you determine if a character succeeds or fails at something
- The Usage Die: Determining whether or not resources are expended

# Action Resolution

In Pentola ambiguous actions are resolved by following the Intent-Approach-Adjudicate workflow:

## Intent

The player declares what their character is trying to accomplish - what outcome they want from the action or scene.

{icon=dice-d20}
G> #### Declaring Intent
G>
G> Chris is playing as Giuseppe "Porkslope" Esposito, a guerilla art-mage who uses his skill and magic boots to lay traps.
G> Porkslope needs to get up on the side of a spire in order to design his next graffiti-spell, but a guard thinks he is suspicious.
G>
G> Chris says that he wants to convince the guard that he is actually here to _clean_ the spire's walls.
G>
G> At this point, Chris has declared Porkslope's intent.
{{% /example %}}

{pagebreak}

## Approach

Once the intent is known, the player must explain their approach - how the character will attempt to realize their intent through action.

{icon=dice-d20}
G> #### Explaining Approach
G>
G> Chris is playing as Giuseppe "Porkslope" Esposito, a guerilla art-mage who uses his skill and magic boots to lay traps.
G> Porkslope needs to get up on the side of a spire in order to design his next graffiti-spell, but a guard thinks he is suspicious.
G>
G> Chris previously declared that Porkslope intends to convince the guard that he is actually here to clean the spire's walls.
G>
G> The referee asks Chris to explain how Porkslope will do this and Chris responds by saying Porkslope will hold up his bucket and a dirty rag, point to his own poor clothes, and try to play it off like he's some contract-cleaner.
G>
G> Other approaches Chris could've tried to fulfill Porkslope's intent:
G>
G> - Having Porkslope explain in great and boring detail the series of events that led to the spire needing to be cleaned, his guild being hired, and him being assigned this dangerous work.
G> - Having Porkslope play it off as a dead-eyed service worker who just _really_ wants to get this over with.
G> - Having Porkslope try to hand off his bucket and tools and get the guard to try to go out the window to clean the tower herself.
G> - Innumerable other options constrained only by Chris's ability to think up new approaches.

{pagebreak}

## Adjudicate

Once the intent and approach are known the referee is then - and only then - able to begin to adjudicate the action.

First, the referee will decide if a test of some sort is neccessary.
A test is necessary only under the following conditions:

1. The action as defined by the intent and approach together can fail.
   - If the combination of intent and approach can't reasonably fail - for example, reaching the second level of a tree house by climbing the ladder - there's _no_ reason to call for a test.
2. The action as defined by the intent and approach together can succeed.
   - If the combination of intent and approach can't reasonably succeed - for example, reaching the second level of a tree house by digging at the base of the tree - there's _no_ reason to call for a test.
3. The action as defined by the intent and approach can succeed, could fail, and failure has meaningful consequences.
   - If the consequences of failure are that the character must try again and again until success, those are not meaningful consequences.
    Note that the same intent and approach may have meaningful consequences under one set of conditions but not under another.

{icon=dice-d20}
G> #### Adjudicating Actions
G>
G> Chris is playing as Giuseppe "Porkslope" Esposito, a guerilla art-mage who uses his skill and magic boots to lay traps.
G> Porkslope needs to get up on the side of a spire in order to design his next graffiti-spell, but a guard thinks he is suspicious.
G>
G> Chris previously declared that Porkslope intends to convince the guard that he is actually here to clean the spire's walls by holding up his bucket and a dirty rag, pointing to his own poor clothes, and trying to play it off like he's some contract-cleaner.
G>
G> Depending on the referee and the game, here are a few ways this could go:
G>
G> - The referee decides that the guard knows the spire is due for a cleaning and that Porkslope's explanation seems to fit right in.
G>   There is no reasonable chance of failure, so the referee announces that the guard lets Porkslope pass.
G> - The referee decides that the guard has already worked with the spire-cleaners' guild before and knows their customs and attire - and Porkslope matches neither.
G>   There is no reasonable chance of success, so the referee announces that the guard is going to try to detain Porkslope for further questioning.
G> - The referee decides that the guard's neither particularly knowledgeable nor lax in her duties, so Porkslope can try to convince her and this will require a test.
G>   Note that in this example Porkslope could succeed, in which case he can continue, or could fail, in which case the guard's suspicions will be aroused.
G>   Porkslope can't just try again over and over, there are meaningful consequences for each failure.

{pagebreak}

## Tests

If the referee decides that a test is called for, they will then specify the appropriate characteristic.
The player should add their _highest_ relevant bonus to their goal.
In cases where it is ambiguous if a bonus should apply, the referee will decide.

In order to successfully pass a test a player must roll **below** their goal for the specified characteristic on a d100.

{icon=dice-d20}
G> #### Actions and Tests: Locked Door
G>
G> Cerise, a strong and experienced mercenary, is attempting to get past a locked door by kicking it down in several scenarios:
G>
G> 1. Cerise reaches an abandoned warehouse on the outskirts of town to look for clues but the side door is locked.
G>    Even though it is possible that Cerise's first attempt to break down the door might fail in this scenario the referee decides there are no meaningful consequences to that failure, nor to retrying until she _does_ kick the door down.
G>    The referee declares that Cerise successfully kicks the door in.
G> 2. Cerise is chasing a fleeing bandit who has slipped into the building and barred the door behind him to buy himself more time to escape.
G>    In this scenario not only can Cerise fail to kick in the door but each failed attempt gives the fleeing bandit more time to escape.
G>    The referee decides that a test is required and directs Cerise to test against her BOD, adding any relevant bonuses she may have.
G> 3. Cerise is locked into a steel vault and needs to escape.
G>    In this scenario failure to kick open the door means that Cerise remains locked in the vault.
G>    However, the referee notes that the vault door is nearly a foot thick and that Cerise's stated approach - kicking down the door - is simply impossible.
G>    The referee declares that Cerise kicks the steel door but fails to open it.

Some tests are **easy**, doubling the chance of success.
Other tests are **hard**, halving the chance of success.

{icon=dice-d20}
G> #### Tests: Easy and Hard
G>
G> Caleb is attempting to convince the guard to share some gossip using several different approaches:
G>
G> 1. Caleb wants to share false gossip about the topic to prompt the guard to share his own knowledge.
G>    The referee decides that this approach _could_ work, but isn't particularly more or less likely to do so.
G>    The referee therefore calls for an INT test to pull off the minor deception.
G> 2. Caleb wants to approach the guard with a smoke and a friendly smile before mentioning the topic of gossip off-handedly.
G>    The referee knows that the guard is young and slightly ill disciplined  - and decides that the guard is particularly susceptible to this method.
G>    The referee therefore calls for an easy INT test, allowing Caleb to double his goal for this test.
G> 3. Caleb wants to intimidate the guard into sharing the gossip by being physical and not-quite threatening him.
G>    The referee knows that the guard is young, slightly ill disciplined, and has a lot to prove - and therefore determine that this method is particularly unlikely to get the fulfill the desired intent.
G>    The referee therefor calls for Caleb to make a hard INT test, forcing Caleb to cut his goal for this test in half.

If the result of the test is less than 1/10 the test's goal, it is a critical success - the _best possible_ result based on the character's intentions.

If the result of the test is 100, it is a fumble - the _worst possible_ result based on the character's intentions.

## Opposed Tests

Opposed tests are made by both sides who are in direct competition with each other.
Both characters make the tests as normal and the results depend on how well both sides do:

- **One Side Succeeds:**
  If one side succeeds their test and the other fails then the successful side has won the opposed test.
- **Both Characters Succeed:**
  If both sides succeed then whoever rolled the highest in their test wins the opposed test.
  However, if one side rolls a critical while the other rolls an ordinary success then the side that rolled the critical wins.
- **Both Sides Fail:**
  Whoever rolled the highest without fumbling in their test wins the opposed test.
  In the case of ties for both the Player wins.
  If the action is player-against-player, the defender wins.

{icon=dice-d20}
G> #### Opposed Tests: Vying for Crowd Favor
G>
G> Caleb and Cerivny are vying for the favor of the crowd during a debate.
G> Cerivny relies on her natural charm and skill at persuasion to sway the crowd, rolling against a goal of 80%.
G> Caleb draws on their deep experience and leverages the crowd's emotions through recalling their historic heroines and bringing to mind their greatest triumphs and struggles, making their test easy and rolling against a goal of 140%.
G>
G> Here are a few ways this could play out, depending on the results of each characters' test:
G>
G> 1. Cerivny rolls an 87, failing, and Caleb rolls an 83, succeeding.
G>    Caleb wins over the crowd.
G> 2. Cerivny rolls a 68, succeeding, and Caleb rolls a 32, succeeding.
G>    Because both characters succeeded at their test and Cerivny's roll was higher, Cerivny wins over the crowd.
G> 3. Cerivny rolls a 41, succeeding, and Caleb rolls a 12, critically succeeding.
G>    Even though both character succeeded Caleb had a critical success and therefore wins over the crowd.
G> 4. Cerivny rolls a 91, failing, and Caleb rolls a 100, fumbling.
G>    Even though both characters failed, Caleb actually fumbled and therefore Cerivny wins over the crowd.

# Usage Die

Some special abilities and items will specify that they have a usage die.

Immediately after using an ability with a usage die, or one minute after using an item with one, roll the appropriate usage die.
If the roll is a 1 then the usage die is downgraded to the next lower die in the following chain:

C> **D20 > D12 > D10 > D8 > D6 > D4**

When you roll a 1 on a D4 the item or ability is expended and the character has no more uses of it left.

{icon=dice-d20}
G> #### Using Your Usage Die
G>
G> After Carina uses herbs from her kit to brew a tea to make the shopkeep more susceptible to her influence she must roll the usage die for her herbs, a D8.
G> Carina rolls the D8 which lands on a 1, meaning that one use from her herbal kit is gone.
G> The kit's usage die is reduced by one step to a D6, meaning the next time it is used Carina will roll that die instead.
G>
G> If instead Carina had rolled a 2 or higher the usage die would remain a D8.
