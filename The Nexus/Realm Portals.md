_[The Nexus](/The%20Nexus) / Realm Portals_

# Realm Portals

There is significant issue with the way realms currently work from the nexus. Each server is given 1-2 portals to a realm, each realm is one of 16 random maps, with 40-50 Heroes of Oryx. There is no distinction between realms aside from name.

There are a few issues with this approach:
* Having multiple realms in multiple servers with a small player base far too easily divides those few players
* No incentive to choose certain realms
* Starting each realm with large Heroes of Oryx counts serves only as a barrier to endgame content

Let's dissect the first one, as it is generally separate from the other two.

## Issue 1 - Too Many Realms!

Right now, the RotMG community is mostly stagnant, trending down. The active player demographics are comprised of the following groups:
* The masochistic white stars who "quit" and come back from time to time
* The ["yellow star slump"](/Glaring%20Issues/Yellow%20Star%20Slump.md)
* The [majority of the active players](https://www.realmeye.com/number-of-active-players-by-rank) - orange, red and dark blue stars
* A meat grinder / revolving door of light blue stars

However, looking at the [active playerbase stats](https://docs.google.com/spreadsheets/d/e/2PACX-1vQmvQlQ-H1U472ekxtdwyhOdVjvE18QdeX_mWTc-kq76MEmihsL_7m8T7Y8cGy5hVEU0AmjIcsRuWCe/pubhtml#), roughly 45-55k players actually play the game at the time of writing. I would imagine the number of bot accounts seen throughout lower this to around 45-50k.

From anecdotal, personal experience, this definitely doesn't feel like accurate tallying. Every server save for the trade/pop servers has two realms, and at least one of them is nearly empty, save for the two bots. Certain servers are outright deserted depending on when/where you look, both realms having been there over an hour with 35+ rem.

One potential solution to this dispersal of the playerbase is to reduce the number of realms, and have it scale depending on server traffic. Got a dead server? Keep one realm open. In USW3/4? 2-4 realms. Have it scale with server population, as well as the status of the other realms. It seems like that's generally the case already, but reducing the minimum from two to one, as well as having it be more reactive would improve cohesion for smaller servers.

Another option is cross-server realms. That is a massive technical decision however, so we will, for now, omit that from consideration.

## Issue 2 & 3 - Monotony Kills Retention

Right now, generally speaking, most players can play on most servers. The only exception is non-Oceanic players on AUS, and non-Asia players on the Asia server. The latency is felt a little, sure, but generally the game is playable if you have decent internet. This is why discord raids are organized across US and EU servers, aside from space limitations. If it were unplayable, they would work out a system amongst themselves.
Furthermore, because players can broadly access most servers comfortably, and each realm in each server is basically identical, there is zero variability, and the core game loop quickly feels as monotonous as watching a six-hour timelapse of the moon orbiting the earth a few thousand times.

There needs to be far more variability in the gameplay experience, and while there have been some attempts, none actually address the core issue. Here were some past attempts:
* Event Bosses
* Dungeon Modifiers
* Special/Seasonal Events

Here are some potentially-viable alternatives and additions to actually fix what's wrong with this aspect of the game:

## **Proposal 1** - Realm Modifiers

In this proposal, we extrapolate upon the base concept of dungeon modifiers, and expand them. In stark contrast to the complaints in the first issue, this would actually entail creating MORE realms per server. Each realm would be given 0-4 modifiers that would affect rems, difficulty, events, loot, and more. There would be three grades of difficulty which are represented by the existing gravestone system used for dungeons, and would appear underneath the name of the realm portal, as well as in the Log dropdown by the name of the realm.
Every server would guarantee one portal for each difficulty, also highlighted by a colored outline (white for easy, Grade S dungeon color for hard, Grade A dungeon color for "exalted").
Here are some potential modifiers, as well as the tier they can exist in:

| Modifier Name     | Realm Grades | Possible Levels | General Description                                                                                     | Side Effects                                                                                                                    |
|-------------------|--------------|-----------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| Derelict Court    | 1-3          | 1, 2, 3         | Fewer Heroes of Oryx required to clear the realm (starts at 35 / 27 / 20 rems)                          | Removes evenly from dupe rems (e.g. I would get rid of some liches and ent ancients, II would also get rid of some ghost kings) |
| Deforestation     | 1-3          | 1, 2, 3         | Fewer Ent Ancients, more sparse foliage in lowlands through highlands                                   | Very similar to Derelict Court, but specifically reduces the amount of ent ancients                                             |
| Hunted            | 1-3          | 1, 2            | Event bosses have a (20 / 40)% chance of spawning The Wanderer                                          |                                                                                                                                 |
| Drunken Tyrant    | 1-3          | 1               | Wine Cellar automatically opens                                                                         | Should be incompatible with Careless Tyrant                                                                                     |
| Fearful Tyrant    | 1-3          | 1, 2, 3         | Each OSanc pillar is (5 / 15 / 25)% likely to be automatically activated                                |                                                                                                                                 |
| Careless Tyrant   | 1-3          | 1               | Janus the Doorwarden is automatically exposed                                                           | Should be incompatible with Drunken Tyrant                                                                                      |
| Vengeful Tyrant   | 1-3          | 1               | Oryx Castle resurrects enemies from the godlands to haunt his castle                                    | Replaces half of castle minions with gods from godlands                                                                         |
| Blessed Champion  | 2-3          | 1, 2            | Acts as if all players in realm (not dungeons) have Loot Tier potion, boosting tier by (1 / 2) globally |                                                                                                                                 |
| Affluent Champion | 2-3          | 1, 2            | Acts as if all players in realm (not dungeons) have Loot Drop potion, boosting frequency by (15 / 25)%  |                                                                                                                                 |
| Scholar           | 1-3          | 1               | Higher chance of blueprint drops (not just event whites, across the board)                              |                                                                                                                                 |

Furthermore, many Dungeon Modifiers can apply to realms. This allows a more diverse range of play experience and difficulty. The key thing to put into consideration when implementing these types of changes is to balance risk and reward. Scaling up the difficulty should provide better rewards, and scaling down difficulty should decrease it.

## **Proposal 2** - Themed Realms

TBD

## **Proposal 3** - Mad God Mayhem?

TBD - basically allow some realms to replace Heroes of Oryx with dungeons that have to be completed to close the realm

