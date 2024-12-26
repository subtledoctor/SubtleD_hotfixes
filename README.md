# SubtleD_hotfixes
 various little hotfix mods

v1. z_MnG_4_5_bard_flag_hotfix

If your MnG Revised bards - or Enchanters - cannot cast illusion spells, this will remove the exclusion flag that is stopping them.

DEPRECATED - This has become unnecessary with the latest versions of MnG.

v2. Revert some SR changes

DEPRECATED - This was done as a favor to undo a few changes made by Spell Revisions. Don't generally use this.

v3. zz_Bard_Slot_Fix

This will fix the way MnG Revised Bards' casting slots work, so they don't get screwed up if someone leaves the party and then re-joins.

DEPRECATED - This will be irrelevant as of MnG v4.9.5. 

v4. 5E_Spellcasting_hotfix

Fixes a pretty serious flaw in the 0.6 version of the 5E Spellcasting Conversion mod. 

This will be irrelevant as of v0.7 of the 5E Casting mod.
For the Arcanist kit, this will be irrelevant as of Tome & Blood v0.9.8.
For Revised Bards, this will be irrelevant as of Might & Guile v4.11.1

v5. Revised Identify Hotfix

This makes the Revised Identify spell work if you installed it via Tome & Blood 0.9.6 - 0.9.9.

This is irrelevant as of Tome & Blood v0.9.10.

v6. 5E Casting Priests

This fixes v0.9 of the 5E Casting mod such that priest spell slots are properly affected.

This is irrelevant as of v1.0 of the 5E Casting mod.

v7. FnP Hivekeeper Rhino Beetle Form

This fixes a bug that crashes the game when you shapeshift into a Rhino Beetle

This is irrelevant as of v0.79.30 of Faiths & Powers.

v8. SoB Robes Spellcasting Hotfix

This fixes items of type=2 ("armor") such as mage robes that had an errant opcode 145 effect applied by the YARAS component of Scales of Blance v5.33.

This is irrelevant as of v5.33.2 of Scales of Balance.

v9. SoB Crossbow Crash Hotfix

This fixes light crossbows which had their "2-handed" flag removed by the "Functional Weapon Tweaks" component of Scales of Blance v5.33. This hotfix only installs on the pre-EE engine, where the missing flag will cause a crash.

This is irrelevant as of v5.34 of Scales of Balance.

v10. Spell Revisions and breaking invisibility in EE v2.6+

This sets the appropriate flags in spells overwritten or added by SR 4b18, such that they break invisibility and sanctuary properly in the EE v2.6 engine.

This is irrelevant as of Spell Revisions v4 beta 19

v11. NPC_EE Upgrade from v4 -> v5

This can be installed over NPC_EE v4 on an existing game and will update the functionality to v5. On new games, just install NPC_EE v5.

v12. Sorcerer spell learning fix for Tome & Blood v0.9.23

This fixes single-class sorcerer spell learning when "Sorcerer Spell Switching" is installed from Tome & Blood v0.9.23.

This is irrelevant as of Tome & Blood v0.9.24

v13. 5E casting fatigue fix

This fixes the Prepare Spells ability in certain edge-case circumstances for 5E Casting v1.5.2, Might & Guile v4.17.2, and Tome & Blood v0.9.25.1.

This is irrelevant as of 5E Casting v1.5.3, Might & Guile v4.17.2, and Tome & Blood v0.9.25.2

v14. Fix for 5E slot-doubling in armor

Attempted fix for occasional superficial slot-doubling bug with MnG bards in leather armor

This should be irrelevant as of 5E casting v1.7.1 and Might & Guile v4.18.4

v15. MBR sectype fix

This fixes the interactions of various spells modified by the Magic Battles Revised v1.3 mod (Breach, Spell Shield, etc.) with secondary types when using opcodes 221 and 230.

This is irrelevant as of Magic Battles Revised version 1.4.

v16. 5E Casting armor hotfix

This fixes elven chain and other "caster armors" that allow arcane spellcasting, in tnhe context of the spellcasting mods.

This is irrelevant as of 5E Spellcasting v1.7.2, and Might & Guile v4.18.6, and the Tome & Blood Arcanist kit v0.9.26.5.

v17. Mod to normalize kit table columns

To be used before SCS v34's "NPC Customization" component.

v18. Set Some Buffs to Power Level 10

This is a hotfix for games with Bartimaeus' SRR variant of SR and the Magic Battles revised mod. SRR sets the power levels of some buffing spells to 0, so they can be cast on someone who has a Spell Deflection up. However this makes the MBS version of Remove magic unable to dispel those buffs. This *should* make Remove Magic work again.

v19 Dagger of the Undergrowth

This is a proof-of-concept for having a weapon apply effects to that struck target based on the attacker's status.

v20 Fix Temples Selling Greater Restoration

This fixes a crash in some temple stores when you try to buy a cure. Some mod prevents JTweaks from copying in J8#GRNF.spl, and stores try to sell the missing spell. This hotfix simple adds the spell.

v21 DLG_TST

This is a test mod to debug a crashy dialogue in a forthcoming Scales of Balance component.

v22 SoB Postures Fix

This stops the 'cancel posture' innate ability from multiplying.

This is irrelevant as of Scales of Balance v6.2.2.

v23 Bastard Sword Item Type hotfix

If for some reason bastard swords are type 0, this will change them to type 69. For use only if Faiths & Powers and Scales of Balance are already installed.

v24 FnP Elemental HLA fixes

This improves the function of the Elemental Transformation druid HLAs in Faiths & Powers, making sure that using the "Natural Form" ability fully removes all HLA effects. It also changes the 6th-level Conjure Water Elemental spell to actually summon a water elemental instead of a fire elemental. It also gives a non-gobbledegook name string to Ben-Hadar, the Water Elemental Prince, and also to small beetles, small spiders, and rhinocerous beetles.

This will be irrelevant as of the full release of Faiths & Powers v0.85.

v25 Fixes for Scales of Balance v6.3 Combat Skills

This fixes the Parrying stances, the Leadership stance, and the Lore Bonus skill.

This is irrelevant as of Scales of Balance v6.3.2.

v26 Add HoW-in-EET Hjollder to Bridge District 

If tipun's HoW-in-EET mod is installed, this will add Hjollder to the Bridge District in hte BG2 campaign. He will still be in Ulgoth's Beard; if you ignore him there, you can play HoW in the SoA portion of the game. If you talk to Hjollder and play HoW in the BG1 portion, then Hjollder will disappear from the Bridge District.

This is COMPLETELY untested!!

v27 Sleep fix for Spell Revisions v4b19rc1

This should fix people waking up early from the Sleep spell.

v28 MnG v5alpha12 Ninja ki abilities fix

This fixes a mismatch in the files that prevents the Ninja kit from getting its ki pool abilities.

This is irrelevant as of Might and Guile v5alpha12.9.

v29 Fix Creature Script Names

Some mod out there is altering various creatures' script names to "cre_strref." This hotfix changes the script name of all such creatures from "cre_strref" to their filename.

v30 Fix SoB 'dirty fighting' combat skill

This will fix the Scales of Balance 'dirty fighting' combat skill so that it affects enemies instead of allies. 

This is irrelevant as of SoB v6.5alpha6

v31 Fix Elven Archer missing from kit menu

This will add Might & Guile's Elven Archer kit to the elven ranger kit menu

This is irrelevant and not needed as of MnG v5.3.3

v32 Fix Scroll Cases

This will allow Scroll Cases to accept all kinds of scrolls in games with SubtleDoctor's UMD modification

v33 Fix NPC_EE Proficiency Dialogues

This will allow you to put more than one point into proficiencies when it is appropriate.

This will be irrelevant as of NPC_EE v6.3

v34 Fix Too Many Cantrips

This will prevent innate cantrips from piling up, properly removing those that you do not intend to prepare in a given day.

This should be irrelevant as of SubtleD's Spell Tweaks v2.6

v35 Fix Proficiency Dialogue Not Disappearing

This will fix the 'advance proficiency' dialogue from SubtleD's Stat Overhaul, which should be one-use-only but instead is once-per-day.

This should be irrelevant as of SubtleD's Stat Overhauls v1.3.2

v36 Fix Divine Spell Slots

This will fix a bug in SubtleD's Stat Overhauls v1.5 which causes divine spellcasters to have fewer spell slots than they should. 

This should be irrelevant as of SubtleD's Stat Overhauls v1.5.3

v37 Psionic Lightning Fix

This fixes a bug that prevents the "Generate Lightning" psionic power from working under certain circumstances.

This should be irrelevent as of Will to Power v2.9.

v38 Mirror Shard Fix

This fixes a bug in version 0.3 of the Reflections of Destiny mod, which made the Mirror Shard unusable. 

This is irrelevant as of Reflections of Destiny v0.4.

v39 Will to Power High Sciences fix

This fixes a bug that prevents you receiving the chosen High Science psionic powers.

This is irrelevant as of Will to Power v2.10

v40 BP Ambush Najim dialogue fix

This fixes a bug that may prevent the BP-in-BG ambush from happening. 

This is irrelevant as of BP-in-BG v1.2