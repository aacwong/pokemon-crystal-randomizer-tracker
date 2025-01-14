# EmoTracker pack for Pokémon Crystal Randomizers

Based on the tracker by StormRider, modified by DillonIsMyName and Vicendithas

It's an EmoTracker pack with map for\
[ERC's Pokémon Crystal Item Randomizer](https://github.com/erudnick-cohen/Pokemon-Crystal-Item-Randomizer)

## Requirements
[EmoTracker](https://emotracker.net/)

## Installation

1. Download through the Package Manager in EmoTracker.

OR

1. Download the latest release from the Releases section on GitHub.
2. Place the downloaded zip file in the EmoTracker packs directory (defaults to ``My Documents\EmoTracker\packs``).

OR (for the development version)

1. Clone the repository to your computer
2. Place the downloaded zip file (or directory) in the EmoTracker packs directory (defaults to ``My Documents\EmoTracker\packs``). Note: if you download a zip of the repository, you may need to unzip it first.

## Usage

This tracker has a wide variety of variants to support the options available in ERCs Crystal Item Randomizer, including the following features:

1. A map containing locations of items and badges to acquire.
2. A tracker of items and badges acquired
3. Maps of several caves to help find items or traverse without Flash
4. Settings options for various randomization features
5. Preset buttons to quickly set the options

It is recommended to turn on Fast Tool Tips to see the descriptions of the items and settings options.

### Settings Options

If the option is crossed out, it is disabled and not part of the logic of the tracker.

1. ![Full Item](images/other/full_item.png "Full Item") All items are randomized, otherwise only Key Items are randomized. This does not include PokeGear, PokeGear Cards, Pokedex, or Rainbow Wing (see the other options below for these).
2. ![Hidden Items](images/other/hidden_items.png "Hidden Items") Adds hidden items into the pool (only makes sense to use with Full Item). Does not include the Machine Part location, since that is included by default.
3. ![Ilex Cut Tree](images/other/cut_tree.png "Ilex Cut Tree") The tree in Ilex Forest is present, requiring access to Cut to pass.
4. ![Vanilla Clair](images/other/vanilla_clair.png "Vanilla Clair") Clair forces you to go to Dragon's Den and pass the test before giving you the badge and item (requires Surf and Whirlpool).
5. ![Backward Kanto](images/other/backward_kanto.png "Backward Kanto") Going into Western Kanto via the Victory Road gate is in logic (requires Surf, Waterfall, and waking up Snorlax, which requires the PokeGear, Radio Card, and Expansion Card).
6. ![Elite Four Required](images/other/trophy.png "Elite Four Required") Fighting the Elite Four is required for Red to appear.
7. ![Berry Trees](images/other/berry_tree.png "Berry Trees") Berry and Apricorn trees are added to the randomized item pool.
8. ![Tin Tower and Ho-oh Chamber](images/other/tin_tower.png "Tin Tower and Ho-oh Chamber") The Rainbow Wing is added to the randomized item pool. Tin Tower and the Ho-oh Treasure Room are in logic. Access to the base of Tin Tower requires the Clear Bell and access to the upper floors requires the Rainbow Wing. Ho-oh spawns once the Elite Four have been defeated. The Ho-oh Treasure Chamber opens when Ho-oh has been defeated (requires Surf and Strength).
9. ![Day and Happiness Items](images/other/clock.png "Day and Happiness Items") Items locked by day, time, or happiness are added to the randomized item pool (requirements changed to always be available).
10. ![Open Mt. Silver](images/other/mountain.png "Open Mt. Silver") Opens Mt. Silver so that the player can access it as soon as the League Gate is reachable.
11. ![Bug Catching Contest](images/other/bug_catching.png "Bug Catching Contest") Adds the Bug Catching Contest (4 items for 1st, 2nd, 3rd, and last places).
12. ![Phone Call Trainers](images/items/phone_card.png "Phone Call Trainers") Adds the trainers that will give you their phone number and offer items.
13. ![Pokemon Locked Items](images/other/eevee.png "Pokemon Locked Items") Adds the checks locked by specific Pokemon (Bill's Grandfather, Elm's Everstone, Lake of Rage Biggest Magikarp, and some of the phone call trainers).
14. ![Pointless Checks](images/other/question_mark.png "Pointless Checks") Adds a few less than useful checks into the pool.
15. ![Required Badges for Red](images/badges/boulder_badge.png "Required Badges for Red") Value can be modified to indicate how many badges are required before Professor Oak in Pallet Town will allow access to Mt. Silver.

Notes:
1. With the "Hidden Items" modifier and/or the "Day and Happiness Items", the items underneath Wesley (Lake of Rage) and Frieda (Route 32), are moved to be in front of them.
2. With the "Hidden Items" modifier, Mt. Moon Clefairy Square Moon Stone is not included.
3. However, with "Hidden Items" and "Day and Happiness Items" modifiers, Clefairy Square item is available.

### Settings Presets

Presets have been added under the gear icon at the top right of the item tracker, corresponding with the presets in ERC's Item Randomizer.

1. ![Easy Full Item](images/presets/full_easy.png "Easy Full Item") Easy Full Item randomizer (same as Standard Full Item, but with a few Easy settings, see below).
2. ![Standard Full Item](images/presets/full_standard.png "Standard Full Item") Standard Full Item randomizer.
3. ![Vintage Full Item](images/presets/full_vintage.png "Vintage Full Item") Vintage Full Item randomizer (replicates vanilla Crystal in some ways).
4. ![Tricky/Extreme Full Item](images/presets/full_tricky_extreme.png "Tricky/Extreme Full Item") Standard Full Item randomizer, but with some extra twists (see below)
5. ![Extreme with Hidden Items](images/presets/full_extreme_hidden.png "Extreme with Hidden Items") Extreme, but hidden items locations are added.
6. ![Crazy Full Item](images/presets/full_crazy.png "Crazy Full Item") Crazy Full Item randomizer (same as Extreme, but day and happiness locked items and berry trees are added).
7. ![Crazy with Hidden Items](images/presets/full_crazy_hidden.png "Crazy Chaos Full Item") Crazy, but hidden items locations are added.
8. ![Maximum Full Item](images/presets/full_maximum.png "Maximum Full Item") All item locations from the previous presets are included.
9. ![Nightmare Full Item](images/presets/full_nightmare.png "Nightmare Full Item") Nightmare Full Item randomizer. Do you like fun? Well, too bad.
10. ![Nightmare with Hidden Items](images/presets/full_nightmare_hidden.png "Nightmare with Hidden Items") Nightmare plus Hidden Items. And you thought Nightmare couldn't get worse...
11. ![Easy/Classic Key Item](images/presets/key_easy_classic.png "Easy/Classic Key Item") Easy or Classic Key Item randomizer. (see below)
12. ![Tricky/Extreme Key Item](images/presets/key_tricky_extreme.png "Tricky/Extreme Key Item") Tricky or Extreme Key Item randomizer. (see below)

The Tricky variant adds PokeGear, Radio/Expansion Cards, Pokedex, and Tin Tower into the item pool.\
The Extreme variants mixes badges into the item pool.\
The Easy variants guarantee early Fly access (follows early Bicycle logic), Backwards Kanto is never required, and none of the Kanto Gym leaders (except Janine) will be required until access to 7 other badges.

Note: After using these presets, you can further customize your settings options as normal.

## Bugs? Suggestions?

Feel free to report them by opening an issue on
[the GitHub repository](https://github.com/Vicendithas/pokemon-crystal-randomizer-tracker).

## Thanks
StormRider for the original tracker\
ZaidusRecon for the detailed maps\
ERC for his work on the Crystal Item Randomizer\
Chaotix on their work adding even more items to the Crystal Item Randomizer\
Pret whose combined efforts on Pokemon disassembly have made these kinds of randomizer possible\
Dabomstew for the Universal Pokemon Randomizer and the Crystal Speedchoice projects that make randomization and speedrunning easier\
Pokemon Randomizer community
