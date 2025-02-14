# Warhammer 4e Character Sheet (Djjus)

This is a fork of https://github.com/vicberg/Roll20-Warhammer-4e-Character-Sheet, which itself is a port of a original WHFRP2e Template.

This Character Sheet has been updated to fix and enhance mostly in the original style. And uploaded to Roll20 for all to use. 
I'm a active WFRP player and I plan to further enhance this sheet at time goes on.


///// ============ Change Log ============ ///// 

January 11th 2021 v1.31

- Reroll clicky buttons now integrated into the roll template output for most rolls, including all repeating sections. This is displayed in the Test value row.
- NPC Tab rework, a number of modifications have been made to increase performance when a lot of NPC hare created. All NPC rolls are now integrated into the crit and reroll buttons. Weapons have been split into Melee(upto 3)/Ranged(upto 2) and Spell into Magic(upto 3)/Prayer(upto 2). Notes now no longer has a hider checkbox and is always shows and the Roll outcome modifier are removed entirely, both were to greater performance hogs within the repeating section. Use the quality text field instead. 
- Channelling Roll template has been altered to be more inline with other rolls to allow the reroll intergation.
- Spell Tab now has lvl selectors for Talents: Aethyric Attunement, Instinctive Diction, Perfect Pitch and Holy Hatred.  This are coded into he roll template to display their appropriate Modifiers. And hide/show miscast clicky's on crit when not trained.
- Weapons & Spells Tab now have added a Mod and Target display fields which matches the roll target.
- All Mod fields will now prepopulate the Roll Modifier popup with the set value.
- Chenged Sturdy Talent field in the Encumbrance section to a selector and added Strong Back Talent next to it.
- Fixed the Talents tab text field dragging issue from the last update.
- Character Status will now display in the banner of Charm, Gossip, Intimidate and Leadership Rolls.
- New GM whisper button in the Combat Actions title row, and adjusted matched the Conditions hider button to match it.
- The sheet will perform a repeating section ID scan and set them as attributes inside the sections on first opening after this update to populate the required ID's of existing sections to allow new features to function correctly. There is a check to only allow this to happen once as it does take a few seconds to complete.


December 28st 2020 v1.3

- Roll Modifier Text: Most roll buttons now have a optional configuration cog next too them allow players to add text to the roll template output (can be conditional on test outcome, ie success/fail). This includes Skills/Weapons/Spells & NPC tabs. Handy for adding text related to Talent based roll outcomes, i.e. +1 SL on success or Reverse Result on fail.
- Skill Tab rework, decluttered Melee/Ranged/Channelling/Language Magick Specialisations groups, these skills are now hidden by default and have to be checked to be visible. Removed the Cast group, Language Magick is now in Language group, and Pray is now a ungrouped advanced skill.
- Crit/fumble logic update: Auto Failure on 99 roll result, will always result in a fumble, even if target is above 100.
- Renamed critical success/failure to auto success/failure, so not to confuse with critical hit.
- Roll template now has Critical / Fumble(Oops) / Miscast / Wrath buttons integrated, they only show when these events happen and are useable by anyone with control of that character sheet.
- Advanded Skills will now always have base skill 0 (unmodified) when they are not Taken (i.e. trained). This is intended to prevent any untaken advanced skills to be rolled by accident. Note Ranged Crossbow and Ranged Thrown are always rollable as per core rules. Also fixed Rt header display for advanced grouped skills which will now display the user entered name field as well as the grouped skill name.
- Marginal fail rolls (-0) will now show correctly in SL results
- Corruption Section now has a Max Corruption value field, based on TB+WPB.
- New hard coded skills for Channelling Witch, Dark & Chaos added.
- Roll Tags have been added to the formulas for all combat skills. Other skills to follow.
- Added some further missing translation tags.


December 21st 2020 v1.23.4

- Cleaned up critical roll text for casting and channeling to make it clearer that theses are happening.
- PC & NPC Characterisitc rolls now show success/failure message.
- Added some further missing translation tags


November 2nd th 2020 v1.23.3

- Added translation tag for modifier text in the roll template.


October 12th 2020 v1.23.2

- translation.json update, attempting to fix the translation issue which was introduced last week which prevent the new json from use on the live server sheet.
- Fixed issue with Heavy Head armor capping at 1 carried Enc.


October 5th 2020 v1.23.1

- Further modification of how Armor tab works. Worn? check will now add/remove ENC and AP appropriately. Some descriptive text has been added to these sections too.
- Continued adding IL8N tags that were missing from a lot of the new content. This work is now mostly complete.
- Workable Italian translation is now implemented (Translation credit to Andrezzo/Roll20). (change language to Italian on Roll20 website/account config, then start server to see it). I am more then willing to work with others to implement more languages, but can not do this by myself.


September 7th 2020 v1.22

- Fixed issue which stoped the Initiative button from working correctly on a newly created character sheet.
- Added numerious IL8N tags that were missing from alot of the new content. This is a work in progress to enable high quality custom translation to be added later. Italian translation is being worked on by the 3rd party.


August 24th 2020 v1.21

- fencing skill roll fixed  ( issue #7214  )
- hit location was not inverting target result fixed


August 3rd 2020 v1.2

NEW - Mutation Roll button added for Physical/Mental Mutation rolls, with a selection between all chaos powers or individual gods. Also includes Fixation table roll selection.

- NPC pages 2,3 & 4 weapon/spell rolls fixed
- Firefox spin button showing fixed
- When rolling a critical in combat the roll template text will now show "Critical Hit" rather then just "Critical", when a Ranged weapon is used it will show "Critical Hit (Impaled)"
- Combat Advantage +X display in the roll template is no longer value at locked
- SL display in roll template extended to roll target of 259 (Maximum SL +25), critical failure will always be SL -1
- Containers updated with worn checkbox, and vehicle toughness/wounds options.
- Removed old 2e lines from the translations file

July 27 2020 - v1.1

NEW - Condition Tracking full implementation, now adds up Multiple Conditions correctly as per the rule book. Meaning only one (highest) condition will be added to the roll template Automatically. Also changed the setting description to clarify this.
NEW - Expandable Packs, Containers & Vehicle section added under Inventory Tab. Allows for simple separation of carried and non-carried items, in Packs & Vehicles. Separate weight calc built in. Container with Enc now add to Total Character Enc too. (Great for any sort of travel heavy stories, e.g. Death on the Reik!)

- Missing Impale code added from last update.
- Manual Roll Modifier now displays in the Roll Template for most rolls.
- Pursuit Roll Rule text changed to be clearer to read.
- Weapon Reach now displays in the roll template, similar to Range for Ranged Weapons.
- Ranged Ammo now displays properly in the roll template.
- Talents now have a roll template which displays their info in chat.
- Critical & Injuries section title in the Core Stats tab renamed to Injuries & Other Ailments.
- Fate/Fortune/Resiliance/Resolve value mininum is now locked to 0.
- Tab Menu inactive buttons shadowed.
- NPC tab characters weapon & spells selection is now persistant
- All spell types now have a custom name option and input field next to the selector (requested feature)


July 20 2020 - v1.01 

- Endurance test in Combat Action no longer rolls a Heal test
- Impale mechanics tiedied up for Attack/Opposed/Shoot rools and made more obvious when it occurs.
- NPC pages 2/3/4 fixes which were only applied on page 1 before


July 13 2020 - v1.0

- Major Art overhaul -  in style of the rule book, removed the black banners and reworked section titles, new background for all themes. Overall effect is less contrast and more white space. Easier on the Eyes.
- Weapons Tab overhaul - Weapons must now be selected to use them, and will fire of from the new Attack/Opposed/Shoot buttons. This should be fairly obvious when the Player next tries to use a weapon after this update. This feature is supported by new sheetworkers. This allows using weapons outside the Weapons reaping sections which is the main reason this was implemented.
- Combat Actions section overhaul - Added custom roll field, core rule based movement rolls for Athletics/Climbing/Falling/Leaping/Pursuit/Sprinting in drop-down menu, current active Attack/Opposed/Shoot display and buttons which are underpinend by the new Weapons mechanic.
- And a number of minor bug fixes


July 5 2020

- Add Armor value to NPC boxes
- Overburdened value now correctly increments when you go over the max encumbrance value, rather then at max encumbrance value.
- Sturdy value now is correctly adds x2 per level to encumbrance
- Character Armor Arm & Leg encumbrance is now linked to avoid confusion of adding too much enc. (right arm/leg enc attributes are now deprecated)


June 29 2020

- Buttons & Banners further improved look
- Combat Initiative roll now allows Modifier for the Init Char.
- Crit Roll fixed so it doesnt go negative.
- NPC tab reworked, look improved, added Condition tracker section and 2 custom skill rolls
- Condition Tracking integration into roll template, first pass. Option to choose between Advantage +xx showing only (new default) on all combat rolls and all non-situational roll modifying conditions (e.g. Broken, Fatigued Stuned, Prone..) to be add to appropriate rolls automatically. Includes NPC tab support too. It should be noted that some conditons can we highly situational, like Perception test could be impacted by Blinded/Deafened or not depending on what is being percived, such situational occasions will have to be handled by the GM and no attempt is made to add complication. 

Condition effects are currently bound as follows:

Broken/Fatigued/Poisoned/Stunned = Effects all Melee/Spellcast and skill rolls (only excludes roll tables like Misscast/Oops etc.)
Entangled/Prone = Effects Movement based rolls, so melee/spells, combat actions and any skill which would require movement like dodge/athletics/climb etc.
Blinded = Effects Weapon/Spells casts rolls
Deafened = Effects Spells casts rolls
Unconscious = Effects all rolls (Effectively blocks rolling with buttons)

Note conditions are not inteneded for out of combat situations, GM simply make the roll difficulty harder (-20 etc) if any condition is to apply to a situation.


June 22 2020

- Button color now added to themes.
- NPC repeating sections can now minimize, helps management for GMs.
- Other minor code fixes


June 15 2020

- New UI Themes - Empire, Dwarf & Elf
- Condition Tracker added! This has TokenMod integrated (TokenMod API needs to be install in the game!) buttons which can set/unset conditions, it also requires my custom WFRP4e Tokens  (download @ https://github.com/Djjus/Vault/blob/master/Warhammer%204e%20Character%20Sheet/markers/WFRP4eset1.0.zip)

- Button cleanup/overhaul
- Fixed NPC tab spacing issue with Advantage value field
- Fixed NPC tab Opposed Melee roll using wrong name on NPC page 1
- Fixed Advantage not adding on Ranged Weapon target number in rolls
- Fixed bug preventing Characteristic Bonus Modifier value from adding to the Characteristic Bonus Current value, due to javascript omission
- Removed an extra curly bracket (This should fix the problem behind issue Roll20#6152)


Feb 24 2020

- NPC tab added, this new tab allows simple contained NPC mini-cs creation with template integration, featured with up to 5 weapons & spells for each NPC. Good for GMs and players.
- All skill rolls now have Success/Fail msg
- Heal Adv-Skill: Added new Heal template which displays IntBonus
- Optional Advantage Rule selection (core book). See settings tab
- SL modifier for all simple and dramatic rolls, displays after the SL result {e.g. Success Level -3 | +Mod 0}. SL results now also in Bold.
- Removed Hit location from opposed rolls.
- Defensive Melee weapon tick now adds +1 SL when opposing as per rulebook, uses new SL modifier field (rather then +10 to the target roll as before)


Feb 17 2020

- init test not visable fixed
- Ranged Weapon SB? check box now useable



Feb 10 2020

- Banner rework, added light/dark mode to settings
- Roll test clean up and rules, Crit Success/Failure added
- Crit roll fixed
- Wounds updated, locked between 0 and max wounds
- Roll template rework
- Roll public/whisper chooser moved to settings
- Fields for Career level and Career Path added.
- Perception/Stealth rolls influence from armour fixed
- Critical Hit roll fixed



Jan 20 2020

- Asset and Color palate rework, light/dark mode
- Clean up of global rolls mechanic
- Xp spend log tab added, these fields interact with Xp current/earned/spent fields.
- Bug fixes



Jan 13 2020

- Reworked Initiative Roll button, with 3 Core book rule options. See Settings cog.
- Moved Wounds/Advantage/Fate points out of the tabs to the top of the sheet for better access.
- Rework on the Skills tab, Mostly for Skills which require working Attrbutes for macros.
- Background Tab moved
- Rework of Weapons (formerly Combat) Tab. With Skill selector for Melee/Ranged specilizations.
- Rework of Spellbook Tab. Removed unused 2e spell sub tabs. Spells now work correctly and added Channelling Test button for Arcane spells.



Dec 24 2019

- Project Forked from https://github.com/vicberg/Roll20-Warhammer-4e-Character-Sheet



Features:

- Attack / Opposed / Ranged Seprated combat sytem with roll template which relevant information

- Skill system, Basic / Advanced Skill List is fully implemented

- Armor system with Enc, AP and Damage tracking

- Spell book system, with core book spell name list, and optional custom spell function.

- SL indicator for all rolls, also aids manual calculation for opposed rolls (due underlying limits with Roll20 full Opposed SL resolution is not a straight forward matter for now, i have chosen the visual self calcualted approach while providing the maximum possible information in miminal mouse clicks to enable that easily.)

- Advantage & Condition Tracking

- Full Encumbrance Management system 

- Cointainer & Vehicle carry space Management

- Roll Table integration for Critical / Oops / Miscast & Wrath of the God


Usage Notes:


- SETTING: Check setting (cog) tab ever time when setting up any new Char sheet for all players, and select correct options for your game.
- Wounds: ensure correct Race and Hardy level are chosen. Wounds are subtracted by adding damage, and given back by subtracting it. Will not go our of 0-Max Wounds range.
- Advantage Field applied to Attacks and appropriate Combat Skills (Cool & Dodge) automatically, and shows i the roll result.
- For an advanced Skill you must select the taken checkbox in order for target to be above 0.
- On Weapons ensure you select the coresponding skill (e.g. Melee Basic, Melee Parrying, Ranged Bow, Ranged Blackpowder etc), and that the correct skill is learned and advance points in it.
- Themes, see setting tab for various theme which change the look of the char sheet overall. Inclung Emprie/Dwarf & Elf themes.
- Arcane Spells need to have a number in CN and Damage Field or they will not roll correctly, both fields will default to Zero.
- Extended Channelling Test (spellbook tab, Arcane Spells only), set Accu Ext SL to 0 before beginning a new Channelling action. Increment with Success level of roll until finished. Allows easy tracking of CN v Accu Ext SL for all players. (NPC tab has channelling on all spells for simplicity)
- NPC tab is intended of quick persistent and contained NPC creation without the need for full character sheets for each of them. With template integration, semi featured with contained Name / Characteristic / Condition / Advantage ingration and up to 5 weapons & spells for each NPC, and a collapsible notes section. Good for GMs and players. (I would still recommed seperate character sheet for actual NPC bosses/major characters). 
- Condition Tracking integration into roll template, first pass. Option to choose between Advantage +xx showing only (new default) on all combat rolls and all non-situational roll modifying conditions (e.g. Broken, Fatigued Stuned, Prone..) to be add to appropriate rolls automatically. Includes NPC tab support too. 

This has TokenMod integrated (TokenMod API needs to be install in the game!) buttons which can set/unset conditions, it also requires my custom WFRP4e Tokens  (download @ https://github.com/Djjus/Vault/blob/master/Warhammer%204e%20Character%20Sheet/markers/WFRP4eset1.0.zip) 

It should be noted that some conditons can we highly situational, like Perception test could be impacted by Blinded/Deafened or not depending on what is being perceived, such situational occasions will have to be handled by the GM and no attempt to add complication is made. 

Condition effects are currently bound as follows:

Broken/Fatigued/Poisoned/Stunned = Effects all Melee/Spellcast and skill rolls (only excludes roll tables like Misscast/Oops etc.)
Entangled/Prone = Effects Movement based rolls, all Melee/Spellcast, combat actions and any skill which would require movement like dodge/athletics/climb etc.
Blinded = Effects Weapon & Spells casts rolls
Deafened = Effects Spells casts rolls
Unconscious = Effects all rolls except endurance (Roll block essentially)

Multiple condtions: You can be subject to the same Condition more than once; indeed, sometimes you will receive multiples of the same Condition from a single event. If this occurs, any penalties suffered are stacked. So, if you have three Bleeding Conditions, you’re losing a worrying 3 Wounds per Round; or if you have 3 Fatigued Conditions, you suffer –30 to all Tests. You can also be subject to multiple, different Conditions at once. When thisoccurs, the effects do not stack; you suffer the highest of the two penalties and apply it. So, if you had the Fatigued and Prone Conditions, you would suffer a –20 penalty to all active Tests, not –30.

Note conditions are not inteneded for out of combat situations, GM simply makes the roll difficulty harder with a custom roll modifier (-20 etc) if any particular condition is to apply to a situational roll.




Future release wish list :

- Optional integrated Fast SL, this has been request a number of times, but it's hard to implement a secondary SL system. (maybe)
- More themes. (v1.4)
- WFRP 4e Roll API, fully integrated. This is the dream, very hard to do.. (x.x)



Enjoy.