-# Core Mechanics

In Pentola, there are a few things which make up the core mechanics:

- Action Resolution: How you determine if a character succeeds or fails at something
- The Usage Die: Determining whether or not resources are expended
- Time: How time is mechanized
- Distance: How distance is abstracted

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

# Time

While playing it's sometimes useful to break time down mechanically - during fights or tense moments, for example.
Largely though, play passes at whatever speed makes sense for the adventure and action - minutes may pass, or hours, or weeks.

When you need to mechanize time, it breaks down like this:

- Action occurs every _moment_, which is roughly three seconds.
  In a moment, a character can make one action and reaction without penalty.
  If a character wants to perform two actions they may forego their reaction and vice versa.
  A character may take an additional action or reaction without forgoing another, but all of their tests are one step harder as a result.
  A character may also forego an action or reaction to focus on just the one thing, making the test one step easier.
- Actions include, but are not limited to, the following:
  - Exercising a knack
  - Making an attack
  - Moving
  - Applying a dweomer
  - Channeling a miracle
  - Throwing a grappling hook
  - Drinking a potion
  - Using a matrix or scroll
- Reactions include, but are not limited to, the following:
  - Parrying
  - Blocking
  - Dodging
  - Interfering with another action

## Initiative

In addition to time breaking down into moments you need to be able to determine what order actions and reactions happen.
In Pentola we use the _declare up, adjudicate down_ (**DUAD**) system for initiative.

Each character involved in the conflict first rolls against their intellect, adding a skill or vocational bonus if appropriate.
The initiative test is treated like a multiple-participant opposed test.

The participant whose result is _worst_ declare their actions and reactions first.
The participant whose result is _next worst_ declares their actions and reactions next, and so on until the participant with the best result declares their action and any reaction.

Then, in reverse order, the actions take effect - so the character who declared last acts first and the character who declared first acts last.

Note that initiative doesn't always mean combat - you might break into initiative when chasing someone, or racing to an objective, or trying to provide a distraction, etc.

{icon=dice-d20}
G> #### Example Initiative: Two Combatants
G>
G> Toph and Tarasi are sparring.
G> Toph has an INT of 13 (base test 39%) and a fencing skill bonus of 43% (total goal of 82%).
G> Tarasi has an INT of 10 (base test 30%) and a gearslinger skill bonus of 20% (total goal of 50%).
G>
G> At the beginning of the moment both characters roll an initiative test and their results are compared:
G>
G> Tarasi rolls a 79, failing her test, and Toph rolls a 31, succeeding.
G>
G> Tarasi therefore declares her action first: she decides to kick at Toph.
G> Toph declares next; since he knows Tarasi will kick at him, he declares he will use his reaction to dodge her kick and his action to elbow her in response.
G>
G> Toph is able to try to elbow Tarasi first.
G> He succeeds on his test, inflicting damage.
G> Tarasi attempts to kick Toph and succeeds on her test with a 21, but Toph also succeeds on his dodge (27) and his result is higher - therefore she does no damage.
G>
G> The next moment starts and they both roll for initiative again and repeat the cycle.
G>
G> #### Example Initiative: Three Combatants
G>
G> As in the last example, but there's now a third combatant, Galner (INT 10, Needlejutsu skill bonus  21%), who is teamed up with Tarasi against Toph.
G> Toph's result is a 31 (success), Tarasi's a 79 (failure), and Galner's a 10 (success).
G>
G> Tarasi declares her action first, deciding to kick at Toph.
G> Galner succeeded on his test but his result is lower than Toph's, so he declares next: he will tackle Toph.
G> Toph declares last and this time decides to focus on Galner, dodging his tackle and elbowing him.
G>
G> Toph acts first, successfully elbowing Galner.
G> Galner acts next, succeeding on his test to tackle Toph (rolling a 15), but Toph critically succeeds on his test (rolling a 2) and so avoids him.
G> Tarasi acts next, succeeding on her test to kick Toph and inflicts damage.
G>
G> At the beginning of the next round they all test initiative again and repeat the cycle.

{icon=wrench}
G> ####
G>
G> The initiative mechanic is one which is harder and longer to explain than it is to use.
G> In practice, it does a few things:
G>
G> - It keeps combat dynamic, ensuring each round the initiative order will likely change.
G> - It rewards players for paying attention to what everyone in the combat is doing - you can only react to actions lower in the initiative order, or play off other actions.
G> - It ratchets up tension - the unpredictability and potential for dangerous combinations of actions make for more lethal combat.
G>
G> It has a higher cognitive load on the referee and players than traditional or side-based initiative, but in practice it's manageable for fewer than a dozen combatants - which is where traditional initiative systems break down too.
G>
G> My method for tracking it is to record the results for each participant on a piece of paper or in a text document, putting lower results lower on the page than higher ones.
G> I then mark each result with an **S** for success (if the participant succeeded on their roll), a **CS** for critical success, or an **F** for a failure.
G> I then work my way up the document, starting with the lowest failure to the highest.
G> Repeat for the successes and then the critical successes.
G> I then flip the order and the actions are adjudicated as normal.
G>
G> If this is too complicated or fiddly for your table, pretty much any other initiative system can work here.
G> I do encourage you to try it though, first!

# Distance

Distances in Pentola are abstracted to a few ranges:

- Things and people are _close_ if you can reach out and touch them with no more than a few steps.
- Things and people are _near_ if you can walk to them within a few seconds - within about 30 ft / 10 meters.
- Things and people are _distant_ if they're further than nearby but still clearly perceptible - within about 150 ft / 50 meters.
- Things and people are _far_ if they're further than distant but you can still visible.

Characters can move somewhere near as an action in a moment.
If they forego their reaction, they can instead sprint to somewhere distant.