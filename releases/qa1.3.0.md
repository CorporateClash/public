### Beta v1.3.0, QA #8 (September 16th, 2022)
 
These patch notes are for our eighth (and final!) Partner QA session. We thank all of our testers for providing significant help for us these last couple weeks! From these sessions, we've been able to put together a whole catalogue of bugs and features we need to address in order to make sure v1.3.0 is as smooth as can be.
 
**Gag Rebalances**
Wait, there's more?
 
- Squirt
  - Squirt has a new passive ability: Splash Damage!
    - When using Squirt on a Cog, the adjacent Cogs will take a bonus 15% damage of the Squirt's damage.
    - This damage is affected by other boosts, such as IOUs.
    - Note: The Toontorial has not been updated to include explanation for this ability yet.
  - Prestige Squirt no longer applies Drenched. Rather, it boosts the Splash Damage from 15% up to 30%.
 
**Battle**
- Knockback damage of Throw & Squirt Gags is now not calculated on Cogs to be hit by a Trap.
- Tweaked ToonTask positions on the reward panel.
- Cleaned up some more cutscenes for Cogs joining battle.
 
**Bosses**
- Improved the Speedchat menu for the C.E.O..
- Added special Cog Voices to the D.O.P.A and P.R.R..

**Misc**
- Added new music to the new Ye Olde Toontowne sigils.
- Updated Needlenose level range in the final O.C.L.O. round.
- Enforced a max camera height for Cog Buildings.
- Gag-Up Unite reward icons now use the Level 8 Gag for their icon.
  - They also will use the right icon this time.
- Fixed some I.O.U. sorting issues.
- Minor text fixes.

---

### Beta v1.3.0, QA #7 (September 14th, 2022)
 
These patch notes are for our seventh Partner QA session.
 
**Clubs**
- Toons will no longer be able to donate 0 Jellybeans to the Club.
- Changed several mentions of S.O.S. Cards in Club Items to I.O.U.s.
 
**Battle**
- Tweaked the positions of Cogs in a 5-Cog battle.
- The direction the Cogs are facing are now based on how far away they are from the center of the battle field.
- Tweaked animation duration for multiple Drops.
- Fixed an issue where Unites could be used by the Toon going sad while going sad.
 
**Bosses**
- When jumping on a Banquet Table during the C.E.O.'s Final Battle, the Toon's initial seltzer angle will be set based on where the Toon jumped onto the table.
- Fixed a District Reset related to Level 1 Toons in Boss Battles.
 
**Misc**
- Fixed an issue where throwing Snowballs at Steve would not cause him to grow.
- Fixed an issue where turning in a completed ToonTask does not fill the Toon's Laff Meter.
- Fixed various client crashes in the Toontorial.
- Minor text fixes.

---

### Beta v1.3.0, QA #6 (September 12th, 2022)

These patch notes are for our sixth Partner QA session. 

**Clubs**
- Fixed an issue where a club's name wouldn't update after the club name change was approved.

**Chatbox**
- Added the ability to mention group member names in the group chat channel.
- Re-added the ability to clear your current message by sending ".".
- Added the filter UI for certain Shortcuts.
- Fixed an issue where SpeedChat messages weren't logged.
- Fixed an issue where the toon sound configuration wouldn't work.
- Removed the transparent focus mode.
  - Users who were using the minimal focus mode may experience a crash, if this is the case please delete your preferences.json file and relaunch the game.

**Battle**
- Updated the prestige description for Drop.
- The Gag track order on the reward panel and the toon info tooltip in battle have been updated.
- The unsoak animation will no longer occur when Drenched is applied to a Soaked Cog.
- Some single target Toon attacks will now run in parallel.
- Adjusted some of the electricity scales for Zap Gags.
- Fixed an issue where Gag levels would switch when typing while the Gag Switcher is open.

**CEO**
- Instead of going in order from the front to the back of the Banquet Hall, the diners which join the battle are now randomly chosen.
- The diner level ranges for each tier have been adjusted.
  - Tier 1: Levels 13 - 15 -> 11 - 15
  - Tier 2: Levels 14 - 16 -> 12 - 16
  - Tier 3: Levels 15 - 17 -> 13 - 17

**Misc**
- Added a new settings loading system.
- Fixed a crash when entering the elevator at the end of a Lawfice floor.
- Fixed an issue where some of the hovers on the Calendar page would appear behind the Shtickerbook.

---

### Beta v1.3.0, QA #5 (September 10th, 2022)

These patch notes are for our fifth Partner QA session. 

**Battles**
- Added a new Gag Quick-Changer on the Gag Picker Panel to allow Toons to quickly switch Gags in the same track after selecting the Gag.
  - If the player picks a Gag in a track where different Gag levels targets single/multiple targets (Toon-Up and Lure), the quick-changer will only show Gags with the same target type. For example, if a player picks a Hypno-Goggle (group Lure), the Quick-Changer will only switch to other Lure gags that is also a group Lure gag.
- Added a new animation on the Gag Picker Panel to transition between Gags when hovering over different gags.
- Fixed an issue where Bayou Bellow was not removing the Dazed Status Effect. 
- Fixed various issues in the Gag-Picker UI where the knockback damage was incorrectly applied / shown.
- Fixed Rain's IOU description when hovered over.
- Fixed an issue where the Cheer Status Effect would still be shown if the Toon-Up Gag misses.
- Fixed an issue where the Drop prestige boost was applied more than once.
- Fixed a crash when a player goes sad inside the Overclocked C.L.O..

**Chatbox**
- Messages which don't display in the Chat Display are no longer stored to be displayed.
  - This means every tab will now only store the last 100 messages to be displayed.
- Fixed an issue where messages would "clump" together in the battle tab.
- Fixed an issue where old chat messages would reappear in the Chat Display.
- Reordered the Gag-up Unites to reflect the attack order change.

**Misc**
- Tweaked the length of the Tesla SFX.
- Tweaked the audio balancing of the Wrecking Ball SFX.
- Potentially fixed an issue where Kiwi heads would sometimes be partially transparent.
- Fixed an issue where the underwater music and water SFX would keep playing after teleporting to another area without water with the /tp shortcut.
- Fixed some crashes with Picnic Games.
- Minor text fixes.

----

### Beta v1.3.0, QA #4 (September 8th, 2022)

These patch notes are for our fourth Partner QA session. 

**Battle Rebalances**

More gag rebalances based on testing & feedback.

- Sound
  - You want a Sound buff? The monkey's paw grants your wish.
    - Sound now comes after Throw in the Gag Track order.
    - Reverted the base damage nerfs for Sound.
      - Kazoo: 4 -> 5
      - Bike Horn: 7 -> 10
      - Whistle: 12 -> 16
      - Bugle: 18 -> 23
      - Aoogah: 25 -> 30
      - Elephant Trunk: 40 -> 50
      - Foghorn: 55 -> 70
      - Opera Singer: 75 -> 90
    - Adjusted Encore.
      - Unprestige Sound: 15% for 1 round -> 10% for 1 round
      - Prestige Sound: 15% for 2 rounds -> 20% for 1 round
      - The visual effect now displays 1 or 2 bugles, depending on prestige.
    - Adjusted Winded.
      - Removed the effect that causes Winded to persist when Sound is used.
      - Reduced the damage penalty from 75% to 50%.
- Squirt
  - Adjusted wording of Soaked/Drenched status effects.
  - Nerfed Soak's dodge debuff from 15% to 10%.
- Drop
  - Increased Drop's base accuracy from 55% to 60%.
  - Instead of buffing Drop accuracy, Drop's prestige now gives it a 15% damage bonus when used against enemies with debuffs.

**Chatbox**
- Added 2 new emotes: Agree and Disagree.
- The sticker menu now hides upon usage.
- Added an option to configure Sticker messages being logged in the Chatbox.
- The Chatbox always opening to the Main Tab is now configurable.
- Stickers will now reflect the Toon's size from Cheesy Effects.
- Added a 3-second rate limit to Stickers.
- Fixed some issue with NPC message splitting.
- Fixed whispered emotes rendering weirdly in the chatlog.
- Fixed some animation issues with stickers.

**Toons**
- Player occlusion now applies to cog disguises as well.

**Cogs**
- Fixed district reset with Level 10 Needlenoses.
  - Also -- we forgot to say that we added Level 10 Needlenoses.
- Fixed issues with Litigator's retaliation targeting.
- Prestige Lure no longer plays the stun head animation on Cogs.

**CLO**
- Fixed FOV in the first battle round.
- Fixed an issue with the 2nd battle positions.
- Added support for 4-man OCLO groups.

**Clubs**
- Club tasks are now blue.
- Adjusted some price scaling for Clubs.
- Added some scavenge icons for Club Task statuses and Club Level Ups.
- The notification window for purchasing a Club Task now syncs with your currently selected Club Task.
- Fixed a major oversight where skipping Trolley Games would net an insanely high amount of Club Coins.

**Chairs**
- Fixed an issue where a single Toon could unseat everyone in the area.
- Fixed an issue where Toon positions weren't being interpolated upon unchairing oneself.

**Misc**
- Made sure that Kart Battery was Kart Battery in racing.
- Potentially fixed a Toono crash.
- Fixed several Toontorial issues.
- Fixed an issue where you could force-join a tiered Boss Group without the right suit level.
- Fixed an issue where Club and Group state wasn't cleaning up upon logout.
- Added some scavenge icons for Daily Tasks.

----

### Beta v1.3.0, QA #3 (September 6th, 2022)
 
These patch notes are for our third Partner QA session.
 
**Battle Rebalances**
We have some more battle rebalances for this session, hot off the presses! We've been in touch with our Community QAers to help come up with these, but we've got some surprises for 'em here too.
 
- Virtual Skelecogs
  - While these guys are feeling pretty good to fight, they still feel just a little overtuned -- especially during OCLO round 1.
    - Max HP range has been tweaked from 80%-120% to 70%-110%.
- IOUs
  - We love 'em, but we need to nerf them a bit. They were originally designed for only one boost, and we didn't compensate when allowing two Toons to be boosted.
    - Fixed a bug where you could combine same-level IOUs in the same turn.
      - While this was a bug, this will cause certain IOU setups to take an additional turn to set up.
    - Nerfed IOUs by around 30% across the board (but still be generous).
    - Buffed 2-use IOUs to give them a bit more relevancy.
    - Sorry, Drop IOUs.
    - The new IOU boosts are as follows:
      - Toon-Up: 90/45/35 -> 60/35/25
      - Trap: 250/125/85 -> 170/90/65
      - Lure: 40/20/15 -> 30/18/15
      - Sound: 50/25/20 -> 35/20/15
      - Squirt: 80/40/30 -> 60/35/25
      - Zap: 80/40/30 -> 60/35/25
      - Throw: 100/50/35 -> 70/40/30
      - Drop: 150/75/55 -> 80/45/35
      - Rain: 20 -> 15
    - By the way, IOUs no longer count as a stun. They already haven't been, but seems important to mention.
- Toon-Up
  - We realized that "toon-up stunning" was removed with the new battle system. So, we're bringing it back, but making it a base Toon-Up effect.
    - Toon-Up now provides the "Cheer" buff on Toons for the round.
      - Provides +20% accuracy for the turn
      - Applied to any targets healed by Toon-Up
      - Does not stack
- Lure
  - Group Lure accuracy has been increased by 5%.
- Sound
  - Since our big changes to Sound, we've been able to properly see how this Gag Track plays out in battle without the community divide between Unprestige and Prestige Sound. We found that the Encore buff of Prestige Sound was particularly interesting, and opened up a lot of interesting battle potential. However, there were still lots of clear issues with Sound, especially in the endgame -- it was either so good that you didn't even have to think, or Cog Levels were too high and there was never a good opening to use Sound.
  - To help give it a bit more relevancy, we've made the following changes to help make Sound feel more like a combo setup track, rather than a full-on AOE damage track.
    - Unprestige Sound now receives the Encore buff for one round.
      - Prestige Sound will receive the Encore buff for two rounds.
    - Encore now gives a +15% Gag effectiveness buff to all Gags, including Sound.
    - Using Sound while Encore is active will clear it and replace it with a new debuff: Winded.
      - Winded lasts for two rounds, and reduces your Sound damage by 75%.
      - The duration of Winded resets if Sound is used.
        - You do not gain Encore if you are Winded.
    - Reduced Sound's base damage.
      - Kazoo: 5 -> 4
      - Bike Horn: 10 -> 7
      - Whistle: 16  -> 12
      - Bugle: 23 -> 18
      - Aoogah: 30 -> 25
      - Elephant Trunk: 50 -> 40
      - Foghorn: 70 -> 55
      - Opera Singer: 90 -> 75
- Squirt
  - While Squirt feels good, alternating single and AOE soak for the gag doesn't actually provide the usability buff that we were expecting. In fact, it actually makes Squirt even more awkward to use with most Zap combos. So, we've reverting that change, but we also have some changes to make Prestige Squirt a bit more enticing too.
    - All Squirt Gags now provide area-of-effect soak.
    - Reduced the damage of the following Squirt Gags:
      - Squirting Flower: 5 -> 4
      - Squirt Gun: 16 -> 12
      - Seltzer Bottle: 40 -> 30
      - Storm Cloud: 95 -> 85 (fine, you can keep your 82 storm)
    - Changed the scaling of soak rounds.
      - Old: 3/3/4/4/5/5/6/6 for Level 1-8 Squirt Gags
      - New: 3/3/3/3/4/4/4/4 for Level 1-8 Squirt Gags
    - Zap will now remove only one round from Drenched, regardless of how many Zaps the Cog receives.
      - This will help keep the Drenched effect on Cogs after zap combos.
- Zap
  - Surprise: we're adding a brand new Zap Gag!
    - Meet the Stagelight, a brand-new Level 6 Zap Gag!
      - The Stagelight was a community-concepted Zap Gag made by toona#1351 around a month ago in our Public Discord.
      - We liked it so much, and with their permission, we took the time to make it!
    - Carpet has been removed, and the old Level 3 to Level 6 Zap Gags have been moved down to replace it.
    - The new Zap Gag order is as follows:
      - Joybuzzer, Lightbulb, Broken Radio, Kart Battery, Broken TV, Stagelight, Tesla Coil, Lightning
    - Tweaked the Broken TV sound effect.
- Throw
  - We're still brainstorming and discussing how we feel about the viability of Throw in certain combos, including how we might make single Throw more viable. Stay Tooned!
- Drop
  - A couple nights ago, we watched a Scapegoat with 2462 HP get literally one-shot by 3 Boulders and 1 Piano with 4 Prestige Drop with IOU boosts. Yeaaah, no. We're nerfing Drop Combos to a complete baseline to see how the track feels without the temptation of damage values beyond ones comprehension. If you're concerned, don't worry, we're likely to rebuff this track later (unless it somehow feels perfect). For nowm we need a basis to balance the rest of the track off of. Drop is still really, really good outside of 4-drop combos, after all.
    - Combo Damage no longer ramps up with the number of Drops used.
      - Old: 30%/40%/50% for 2-4 drops
      - New: 30%/30%/30% for 2-4 drops
        - While this may seem like a strange change, there really is no reason to scale combo damage this high anymore, especially when rolling for individual accuracy as opposed to total risk vs. reward.
    - Removed Prestige Drop's combo damage modifier.
      - Old: +10% combo damage per Prestige Drop
      - New: +0% combo damage per Prestige Drop
 
**Battles**
- Fixed some movie issues.
- Fixed some Toon animation issues.
- Toon-Up IOUs are now used even when the Toon-Up misses.
- Improved Cogs walking out of the elevator in Cog Buildings.
 
**Chatbox**
- Fixed an issue where friends weren't listed when using the "ftp" Shortcut.
- Fixed an issue where Shortcuts were shown when they weren't meant to be.
- Fixed an issue when attempting to whisper a user from the friends list.
- Added the option to disable whisper popups.
- Added whisper locking.
- Club and Group messages can now be displayed as a popup message.
    - This can be configured and is enabled by default.
- Introduced the `Club Shout` Shortcut.
    - Club members with the "Use Club Shouts" can now send a shout message once every 10 seconds.
- The Chatbox will now always open in the Main tab.
 
**Clubs**
- Added a Universal Booster category to the Club Shop.
- Removed the announcement toggle from options.
- Optimized the server club manager a bit.
 
**Gag n' Go**
- Tweaked Reid Stock's nametag.
 
**Litigation Team**
- Fixed a district reset when attempting to do an OCLO with an open Group.
- Fixed a server memory leak with the Litigation Team.
- Fixed issue with Scapegoat's Rage being bad and also stupid.
- Fixed Court Record's status effect not cleaning up upon Stenographer's destruction.
- Fixed animation issues with Bayou Bellow.
 
**Settings**
- Reorganized the "social" settings page.
 
**Schoolhouse**
- Fixed an issue where the Tutorial zone was not deallocating.
- Fixed an issue where Districts were selectable in the Tutorial.
- Fixed an issue where Teleport Shortcuts could be used inside the tutorial.
- The Desk Jockey now has a bowtie.
 
**Audio**
- Fixed a slight audio desync during the music transition when stunning a boss.
- Reverted Almond Avenue to use the normal music for Acorn Acres streets.
 
**Chairs**
- All of the chairs around the Big Desk are now sittable.
- Fixed various issues when playing Toono on chairs.
 
**Misc**
- The Unite Cooldown timer now cleans up properly upon logout.

----

### Beta v1.3.0, QA #2 (September 4th, 2022)

These patch notes are for our second Partner QA session. 

**Toons**
- Fixed issues with occlusion spheres.

**Cogs**
- Fixed status effects going down to 0 rounds on Skelecogs.
- Adjusted the health variance for Skelecogs:
  - Skelecogs: 90% to 110% (from 85% to 99%)
  - Virtual Skelecogs: 80% to 120% (from 65% to 110%)

**Chatbox**
- Fixed some issues using Enter as the chat hotkey.
- The Unite Cooldown Timer now scales vertically from the chatbox.
- Added an option to close the Chatbox after sending a message from using only the Chat Key.
- Closing the Chatbox now clears whisper targets and clears out chat entry.
- The chat entry now indicates where your chat message is going to.
- We've done a major backend overhaul on our chat filter system. Please let us know if you notice any issues with it! 
- Some bugs relating to the chat filter were fixed as well:
   - You are once again able to use text-based emoticons while chatting.
   - You are once again able to say the names of other Toons nearby while sending local messages.
   - Additionally, you're now able to say the names of your fellow clubmates while sending messages to your club!
- Battle tab is now functional.

**Groups**
- Added a stronger ratelimit to creating and joining groups.
- Toon status on the Group Viewer now respects district when determining if a Toon is in the right area.

**Clubs**
- Rebalanced Club Coin earnings a bit.
  - Natural Club Coins earned while playing with other Clubmates has been multiplied by 5.
  - Reduced the Club Coins earned from particularly difficult Club Tasks.
  - Club Coins earned from Club Tasks now award Club Experience.
  - Potentially fixed Club Experience.
- Fixed an issue where Club Nametags would show in suits.
- Fixed an oversight where gradient Club Colors would process their color changes uselessly on the server.

**Battles**
- Fixed an issue where Trap Experience was awarded to the Toon who used Lure.
- Fixed an issue where Cogs could be double-lured on a Trap in the same turn to preserve its Lure state.
- Fixed a server memory leak with Toon attacks.
- Fixed an issue where prestige stars were persisting when they shouldn't have.
- Fixed an issue where Toons would still have their Laff adjusted from a battle, even when leaving it.
- Fixed some reward panel crashes with Daily Tasks.
- Fixed some issues with cog spacing.
- Fixed a minor memory leak with Broken TV.
- Fixed an issue where Gags used on Cogs that were destroyed would be removed from the inventory.
- Fixed an issue where unites would continue to be disabled despite the status effect having expired.
- Fixed various instances of incorrect Cog rotations.
- Fixed an issue where damage taken modifiers would apply twice to Trap Gags.
- Fixed an issue where double luring a Trapped Cog would keep them lured.
- Fixed an issue where a Cog's 'game over' dialogue would be cleared out prematurely.
- Fixed LOTS of crashes.

**Litigation Team**
- Fixed an issue where Insurance Plan would not target the Case Manager.
- Fixed an issue where the Gags disabled by Court Record were not being tinted red.
- Fixed an issue where the Litigator would use Snap after having been destroyed.
- Fixed some targeting issues with Snap and Court Sanction.

**Schoolhouse**
- Fixed the chalkboard SFX playing in the training room.
- Tweaked the tutorial dialogue a bit.

**Other**
- 'Improved' a bug with unite cooldown.
- Fixed an oversight with Daily Tasks where another Task would not be granted if you were full on maintasks/sidetasks.
- Fixed some chair memory leaks.
- Fixed a crash with table games.
- Fixed some trolley crashes.
- Fixed boss dialogue not showing up.
- Fixed a crash with backing out of reporting clubs.
- The text to interact with a chair text will no longer show up if there is someone already seated.


### Beta v1.3.0, QA #1 (September 2nd, 2022)
 
These patch notes are for our initial Partner QA session. They have been stripped down from the complete v1.3.0 Patch Notes, and include only what is present in the QA sessions.
 
**Social Panel**
- The Social Panel is a brand new interface to replace the old Friends List!
- The Friends List icon has been remade.
- The Social Panel is broken up into three tabs: the Friends Tab, the Groups Tab, and the Clubs Tab.
- Friends Tab
  - The Friends Tab boasts the new and completely overhauled Friends List!
  - While similar old functionality remains, there are several new improvements that are worth noting.
  - There are there sections for filtering Toons in the Friends List: Nearby Toons, Online Friends, and All Friends.
    - When you are in a Club, you can even view Online Clubmates and All Clubmates!
  - You can now enter a configuration mode, which will empower you to make massive edits or other quick configurations to specific friends!
    - While in configuration mode, you can quickly view a Toon's stats, send them a whisper, invite them to your Club/Group, and more!
    - You can even select multiple toons, and send whispers to all of them! Mass friend removal is also supported.
    - You can now promote your friends to be Favorite Friends, which gives them a distinct appearance amongst all your friends.
- Groups Tab
  - The Groups Tab holds an in-game Group Tracker, connecting you to be able to join Groups from anywhere in-game!
  - Groups are discussed in detail further below.
- Clubs Tab
  - The Clubs Tab holds a ton of information about your Club, such as active boosters, current Club Task, member list, club history, and more!
  - Clubs are discussed in detail further below.
 
**Notification Panel**
- Most in-game notifications now route themselves to an exclusive dropdown menu that appears alongside the Social Panel.
- The Notification Panel is designed to help organize these notifications, reducing the screen space that they take up.
- The following types of notifications have been reworked to use the new Notification Panel:
  - New Cattlelogs and Deliveries
  - Friend Requests
- In addition, you'll be seeing these use the Notification Panel as well:
  - Group Invites
  - Club Invites
  - Group Status Updates
  - Group Join Responses
  - Club Jellybean Donation
  - Club Task Purchase
  - Club Task Rerolls
 
**Groups**
- Boarding Groups have been deprecated in favor of a brand-new, in-game Group Tracker!
  - This new Group Tracker is built into the new Social Panel.
- You can join Groups anywhere in-game, cross-district.
- You can make groups if you are in the relevant area (i.e. standing around a Cog Building will allow you to create Cog Building groups).
- You can only join Groups that are available to you (i.e. you cannot join C.E.O. groups if you do not have your Bossbot Cog Disguise and sufficient merits).
- Upon joining or creating a Group, you can enter a chat exclusive to that Group by clicking the wing that appears on the Chatbox.
- Extensive options have been provided for group filtering!
  - By default, you can only see the groups that you can currently join. You can change the setting to view all available groups.
  - You can also filter by different group types or by location.
- We expect this feature to have a major impact on how Toontown: Corporate Clash is played. If you have any suggestions for the system, community suggestions can be submitted in our public Discord server!
 
**Clubs**
- It's been a long time coming, and Clubs are finally back in Toontown: Corporate Clash!
- To get started with making a Club, talk to Doe Vinci in Toon Hall to make your Club.
  - Alternatively, a friend can invite you to their Club!
- When you make your Club, you'll be prompted to create your own Club Icon!
  - You can pick a unique icon image and background detail, along with a theme color and background color!
  - From there, once you've picked out a good name, all you have to do is pay 20,000 Jellybeans and you've got a Club!
  - Club Names are approved manually by our Moderation Team.
- Once you're in a Club, you'll be bestowed a Club Nametag bearing the name of the Club.
  - The color of the Club Nametag depends on your Club's theme color.
  - If your Club has a gradient theme color, your Club Nametag will have a gradient color as well.
- You can use the exclusive Club Tab in the Chatbox to easily communicate with all online players in your Club.
- By playing with other Toons in your Club, you'll begin to accumulate Club Coins!
  - Earning Club Coins by playing with clubmates will level up your Club!
- You can view the Club tab on the Social Panel to view all things about your Club!
  - Main Page
    - The main page for your Club shows your Club Icon, number of online members, the amount of Jellybeans/Club Coins owned, along with your Club's level and description.
    - From this page, you can invite members, donate Jellybeans, perform a Club Shout, or report your Club to the Moderation Team.
    - You can also view your Club's current Club Task progress, and see its active Boosters.
  - Task Page
    - Clubs can now purchase an exclusive, randomized ToonTask that all members of the Club can contribute to!
    - Club Tasks are offered by Easy, Medium, and Tough. The difficulty of these tasks depends on how many people are in your Club.
      - Large Clubs will find challenge in the massively-scaled Tasks that can be offered!
    - You can purchase a Club Task with Jellybeans or Club Coins.
    - The current selection of Club Tasks can be rerolled with Club Coins.
    - Once you've purchased a Club Task, it's up to your Club to work together to complete it!
      - Upon completion, your Club will receive a worthwhile lump sum of Club Coins!
      - If your Club cannot finish the Club Task in time, it will expire with no reward.
  - Members Page
    - On this page, you'll find the complete roster of members in your Club!
    - All Toons, including their level, rank, online status, and Club join date are present on this page.
    - In addition, you can view the panel of each Toon from this page.
    - If you have the ability to kick Toons, you can kick them from the Club in this page.
    - If you are the owner of the Club, you can change the permissions of each member here.
      - Alongside being able to promote/demote people between roles, you can transfer ownership of the Club as well.
  - History Page
    - The History page keeps track of events that happen within your Club!
      - You can use this page to keep up with all events that happen within your Club.
      - In addition, it doubles as a type of audit log to help Club Owners moderate any suspicious activity within their Club.
    - The following events are logged for your Club:
      - The Club's initial creation
      - Purchasing any item from the Club Shop
      - Club level ups
      - Toons joining/leaving the Club
      - Club Task purchases, completions, rerolls, and failures
      - Club Name approval and denial
      - Club member promotions and demotions
    - Your Club can have up to 100,000 events logged.
  - Settings Page
    - The Settings Page is where local settings and role permissions can be configured.
    - You can toggle the visibility of your Club Nametag on this page.
    - You can also disable any incoming Club Coin notifications on this page.
    - You can view the permissions of all Roles in your Club, and can change them if you are the Club Owner.
    - At the very bottom of the Settings Page is the Leave Club button.
      - If the owner leaves the Club, the Club's ownership is automatically transferred to the highest ranking & most veteran Club Member.
- If you're interested in expanding your Club further, you can talk to Bro Vinci in Toon Hall for some unique expansions!
  - Items from the Club Shop will cost either Jellybeans or Club Coins to purchase.
  - These items don't come cheap, though! You'll need to work hard with your fellow Clubmates to get them.
  - In addition, certain items are locked by Club Level, requiring your Club to level up before being able to receive some items.
  - The Club Shop offers three categories for items for your Club.
  - Items & Upgrades
    - By default, your Club has a member capacity of 10.
      - From the Club Shop, you can upgrade it in increments of 5, all the way up to 50 members!
    - You can upgrade your Club's active booster slots from 1 to 3.
    - In addition, you can purchase a Name Rewrite for your Club, which will allow you to talk to Doe Vinci to change your Club's name!
  - Club Boosters
    - Your Club can purchase 48-hour real-time Boosters that affect EVERY member in the Club!
    - Club Boosters stack with your individual Boosters.
    - You can get any type of Booster from the Club Shop, given you meet the level requirement and cost!
  - Customization
    - The Customization category allows you to greatly customize and decorate your Club Icon!
    - We have provided the following to help you make the PERFECT Club Icon:
      - 110 unique Icon Images
      - 47 unique Icon Details
      - 104 basic Theme Colors
      - 104 basic Detail Colors
      - 37 gradient Theme Colors
      - 37 gradient Detail Colors
    - All in all, there are over 100,000,000 unique combinations for your Club Icon! Get creative!
- Clubs are split into four ranks: Member, Scouts, Captains, and Owner.
  - The Owner has the ability to do all things in their Club, and can configure the permissions for Members, Scouts, and Captains.
  - The way your Club is expected to use these roles is entirely up to the Club Owner!
    - We encourage players to create a type of role hierarchy for their Club that best fits their needs.
  - The following permissions can be adjusted per role:
    - Purchasing or Rerolling Club Tasks
    - Purchasing Club Shop Items
    - Performing Club Shouts
    - Using the Club Chat
    - Inviting other Toons to the Club
    - Kicking lower-ranked Toons from the Club
      - Members cannot be given this permission.
    - Updating the Club's Description
 
**Chatbox**
- We have completely overhauled and rebuilt the game's chat system from the ground up!
  - The Chatlog has been replaced with a modernized Chatbox!
  - This change combines the Chatlog and type-chat entries into a single GUI piece.
- You can now filter chat by various categories (Whispers, Alerts, and NPC).
- When you are in a Group, an exclusive wing tab will open, allowing you to communicate to all members of that Group.
- When you are in a Club, you can use the Club Tab to freely speak to all online members of your Club.
- When you are in battle, an exclusive wing tab will open, filtering all messages from other Toons in your battle for easier communication.
- Unites have been moved out of the Speedchat menu and into their own exclusive dropdown.
- Whispers can now be sent to up to four separate Toons simultaneously.
  - Group whispers are sent individually to each person.
- The Options page provides several useful focus modes for the Chatbox.
  - By default, the chat focus mode is Always Shown, which shows the full Chatbox when it is open.
  - When set to Transparent, the Chatbox elements will be transparent. The amount of transparency can be adjusted.
  - When set to Minimal, the majority of the Chatbox will become fully invisible, and the background for chat messages can have its transparency adjusted.
    - Hovering over the Chatbox in both Transparent and Minimal focus modes will fully reveal it.
- The size of the Chatbox and the visible line count can be tweaked in the Options.
- Meet the paragon of social interaction: Stickers!
  - Stickers are a brand new way to express your emotions to nearby Toons that can be used similarly to Emotes.
  - By using a sticker, your Toon will hold out the exact expression in their hand to show off to the world!
  - We've provided a default suite of 16 stickers.
- We have also rebuilt our command system to empower players with their own suite of chat commands!
  - By pressing slash, a dropdown menu will open for relevant chat commands.
  - Full autocompletion and command argument suggestions have been implemented.
  - Below is a complete list of all of the new Shortcuts, available to our QA Testers:
    - /whisper {friend}: Sets a whisper target on a currently online friend. Aliases: /msg, /dm
    - /emote {emotion}: Plays a Toon emote.
    - /friend {toon}: Sends a friend request to a Toon.
    - /home: Teleports you to your estate. Aliases: /estate
    - /logout: Logs you out.
    - /tp {playground}: Allows you to teleport to a playground, given you have teleport access to it.
    - /ftp {friend}: Allows you to teleport to a friend.
    - /district {district}: Switches the district that you are in.
  - We plan on adding more by the release of v1.3.0.
 
**Battles**
- Several major parts of the battle system have been rewritten from the ground up, including massive architectural redesigns of our Battle Calculator!
- These changes are made to allow more versatility in designing battles, while also making them easier to develop.
  - Yes, as it turns out we, once again, have refactored several major parts of the battle system. Shocker.
- The battle system now supports movie cutscenes and events, along with environmental effects and direct manipulation of the fourth dimension.
 
**Something Is Coming...**
- Who is lurking in the basement of the Schoolhouse?
- The fog rolls in around the Lighthouse on Lighthouse Lane.
- Faint embers can be seen above the walls of Ye Olde Toontowne.
- A new office has been opened in the Sellbot Towers. However, it appears to be blocked off.
- The off-key crashing of cymbals can be heard from an all new music hall on Tenor Terrace.
- A new pizza place has arrived on Sleet Street. However, the doors are locked.
- Nothing has changed in Acorn Acres... for now.
- Guitar solos can be heard from inside All-Star Suites on Lullaby Lane.
 
**Gag and Go**
- Reid Stock has opened up a new street-vendor Gag Shop van in every street!
  - Easily restock your Gags while doing tasks or between taking down Cog Buildings at the nearest Gag and Go!
  - As Reid's Gags are home-grown, they cost double to purchase. (The "Buy One, Get One Free" sign applies to her, not you.)
- The Gag and Go van replaces all of the street Toon Headquarters, with the exception of Anchor Avenue.
 
**Schoolhouse**
- Visit the brand new Toontown Schoolhouse, dedicated for teaching new players how to fight the Cogs!
- The Toontorial has been given a major overhaul!
  - The Toontorial should now much more clearly explain Corporate Clash's battle mechanics to the player, creating a smoother gameplay experience for new players.
 
**The G.U.M.B.A.L.L. Project**
- The scientists of Loony Labs are ready to reveal their latest invention, classified under The G.U.M.B.A.L.L. Project!
  - Short for "Granting Users Magnificent Boosts, Accessories, and Lots of Laughs".
- The magnificent Gumball Machine is now present inside all Toon HQs.
  - However, the Gumball Machine is currently not functional. But you are safe to admire it!
- The interiors of Toon Headquarters has received a few construction overhauls.
 
**Boosters**
- The Booster system has been greatly expanded!
- There are new types of Boosters available:
  - Individual activity experience boosters for Racing, Trolley, Golf, and Fishing
  - Individual department experience boosters for Sellbot, Cashbot, Lawbot, and Bossbot
  - Individual boss reward boosters for the V.P., C.F.O., C.L.O., and C.E.O.
  - Power Gag Experience Booster for Trap, Zap, Throw, and Drop
  - Support Gag Experience Booster for Toon-Up, Lure, Sound and Squirt
  - The All-Out Booster, which boosts everything!
- Boosters will now only subtract time while you are online.
- Boosters will no longer stack duration if the duration of the Booster is greater than one week.
  - This does not apply to active Boosters that are currently greater than a week in duration.
  - You know who you are.
 
**Holidays**
- Due to time constraints and Count Erclaim missing his flight, we will not be having our Halloween event for 2022.
  - We apologize for the short notice on this! We don't believe we can properly set up a substantial Halloween event this year due to time constraints.
  - Expect something spooky this December...!?
- All Wednesdays are now Wealthy Wednesdays!
  - Enjoy 25% increased Jellybean gains from all sources.
- Fish Bingo is now permanent.
  - The Jellybeans rewarded from completing a bingo card have been reduced.
 
**Barnacle Boatyard**
- The sights of Barnacle Boatyard has expanded! Feel free to gaze into the beautiful shorelines of Toontown.
- The Tell-Tale Carp has been moved out of Anchor Avenue and into a dedicated building in the Barnacle Boatyard playground!
- Content Pack creators: Many Boatyard assets, including The Captain's iconic boat, have been repalettized and centralized to a single folder.
 
**Job Market**
- Hired an intern in the Ye Olde Toontowne Toon HQ.
- 🐊
 
**Toons**
- Added brand new eyelash variants for all Toons!
  - A free redraw has been granted to all Toons to encourage trying them out.
- Toon-to-Toon collisions have now been disabled.
  - Toons that are colliding with your own Toon will be occluded.
  - If there are 5 or more Toons present nearby your Toon, all of them will be occluded.
- Increasing your Activity and Department levels will now only play the level-up jingle every ten levels, as opposed to every level.
- Doodles have been temporarily disabled.
 
**Cogs**
- At the request of the Suit Safety Inspection Association, C.O.G.S. Incorporated has issued new improved body models for all employees of the company.
  - Cogs and Skelecogs now sport new high-quality models, fixing many visual issues with their old models and bringing their visual quality up-to-par with modern standards.
  - Skelecogs now have a unique head model with full unique animations per suit type.
  - Skelecogs now have the ability to have custom Cog-specific head types.
  - The cog propeller is now HD, by extremely, extremely popular request.
- Skelecogs now have all negative status effects (Lured, Soak, etc.) reduced in duration by 1 round.
- Laser Skelecogs now have all negative status effects (Lured, Soak, etc.) reduced in duration by 2 rounds.
- Both Skelecogs and Laser Skelecogs now have slightly variable HP values based on their normal HP.
- The Barnacle Boatyard and Ye Olde Toontown taskline minibosses have been renamed to the Land Acquisition Architect and the Public Relations Representative respectively.
- The Drowsy Dreamland taskline miniboss instance will now be referred to as "The Directors."
- All of the taskline minibosses have now been given unique head models.
- HP values of the Land Acquisition Architect and the Public Relations Representative have been rebalanced to more closely fit the intended difficulty curve.
- The Chairman has been given an updated head model.
- Boardbot Cogs now have a new emblem that is more fitting for their department.
- The cutscenes for Derrick Man, Land Acquisition Architect, Public Relations Representative, and The Directors have been updated.
- Tier 5 Cogs (Mover & Shaker, Number Cruncher, etc) can now spawn up to level 10.
  - This also influences Cog Disguise promotions for Tier 5 Cogs, requiring an extra promotion to max. This only affects those who have not reached a Cog Disguise past Tier 5.
- Cog HQs have now had their level ranges tweaked.
- Certain minibosses now have unique dialogue phrases for their normal attacks.
- Cogs will now walk directly to their active battle positions when there are no active Cogs present.
- Cogs will now better distance from each other in battle.
- Fired Suits (from Pink Slips or through... uh, other means!) now get an unemployed suit and lose their respective department label.
 
**Cog HQs**
- Tier 8 Cogs can now rarely spawn in the 'exterior' zones of Cog HQs (or the main HQ if they are lacking one).
- Cogs outside of their relevant departments now have a very rare chance to spawn in Cog Buildings and Cog HQs.
 
**Cog Gallery**
- The Cog Gallery has had some of its textures adjusted to reflect the changes to the Boardbot department.
- Hovering over Cogs in the Cog Gallery will now show what summons are available.
- Sweeteners are now available from many Manager Cogs, which can be claimed by defeating them daily!
  - Sweeteners can be claimed for a boost of Jellybeans, Toon Experience, and Gumballs.
  - Gumballs gained from Sweeteners have a weekly cap that resets on Sunday.
 
**Cog Bosses**
- At the V.P.'s request, C.O.G.S. Incorporated has devoted funds to an enhancement project for the Sellbot Towers Rooftop.
  - Many visual updates have been made to the V.P.'s battle arena, improving quality and visual clarity.
- The V.P.'s health bar now shows a percent, rather than actual 'health'.
- The V.P. will now open up to stun from the back only on the ramps in the active round.
- The C.E.O. has BANISHED all Version 2.0 Cogs from attending his banquet, and higher level Cogs have now taken their place.
  - Executive Cogs that attend tend to be seated near the C.E.O. himself.
- All boss themes will now crossfade into a unique "stun" theme while they are stunned.
 
**Gags**
As discussed in a recent blogpost, we have made several massive changes to various Gag Tracks. Since then, we've been listening to community feedback and have been having conversations with our Partner and Community Testers in order to refine some of the Gag changes even further. As such, you will see a few new additions and changes made here that were not present in the original blog post.
 
Here are the general changes that we have made relative to the original Gag Balancing blogpost:
- Tweaked some Toon-Up healing values.
- Added a new debuff to Trap.
- Removed the conditional requirement for Trap's prestige.
- Lure Knockback now adds to the Gag's combo damage.
- Big Magnet, Hypno Goggles, and Presentation have been given +5 knockback.
- Prestige Lure now affects group Lure more than single Lure.
- Completely reworked the Squirt prestige.
- Tweaked the jump damage pool for Zap from 80% unpres/100% pres to be 90% unpres/110% pres.
- Tweaked the base damage of Zap.
- Removed the 90% accuracy cap of Drop.
- Increased the base damage of Drop.
- Increased the combo damage of Drop.
- IOUs now give the boost to both you and your target.
- Slightly tweaked the values of Lure IOUs.
 
- Completely overhauled the Gag Training page GUI to make it easier and more comfortable to use.
- The Gag EXP requirements have been adjusted across the board, the requirements below reflect all requirements from getting to Level 2 to maxing your Gag Tracks.
  - 20/100/500/2000/5000/9000/14000/20000
- Toon-Up
  - Lowered the self heal from prestige Toon-Up to 40%.
  - Increased the base heal from a missed Toon-Up Gag to 40%.
  - Heal values:
    - Bamboo Cane: 39 -> 45 Laff
    - Pixie Dust: 50 -> 60 Laff
    - Juggling Cubes: 78 -> 84 Laff
    - Confetti Cannon: 95 -> 90 Laff
  - Self-Heal from prestige Toon-Up will now show when the Toon in question is healed, rather than at the beginning of the battle movie.
  - Fixed various animation issues with Feather, Lipstick, and High-Dive.
  - After the Toon-Up animation finishes, the chat will no longer be cleared.
- Trap
  - A new debuff is inflicted upon a Trap's activation: Dazed!
    - Similar to Soaked, Dazed provides a 10% dodge chance decrease to the affected Cog.
    - This debuff lasts for two rounds (the round of application and the round after).
  - Removed the conditional requirement for Trap's prestige.
  - The shoes now fly off of Cogs when they are destroyed by a Wrecking Ball.
  - Tweaked the grow and shrink animations for various Trap props.
- Lure
  - Lure Gags now feature a flat knockback damage per gag, rather than a knockback percentage.
  - The knockback damage that the Lure provides is added to the base damage of every Throw or Squirt Gag used on the Cog.
    - Consequentially, this increases the amount of combo damage dealt.
    - For example, if two Throw Gags are used on a Cog that is lured for 40 Knockback damage, they will take 80 total Knockback damage, and will take more combo damage.
  - Prestige Lure now increases the knockback damage of single target Lure Gags by 15%, and group target Lure Gags by 25%.
  - Lure Gags have also had their accuracy adjusted, offering more incentive to use single-target Gags over always favoring group target Gags.
  - Lowered the rounds of each Lure Gag by 1.
  - Lure decay has been entirely removed.
  - Knockback values:
    - $1 Bill: 5 Knockback, 70% accuracy, 2 rounds
    - Small Magnet: 10 Knockback, 60% accuracy, 2 rounds
    - $5 Bill: 15 Knockback, 75% accuracy, 3 rounds
    - Big Magnet: 30 Knockback, 65% accuracy, 3 rounds
    - $10 Bill: 55 Knockback, 80% accuracy, 4 rounds
    - Hypno Goggles: 45 Knockback, 70% accuracy, 4 rounds
    - $50 Bill: 100 Knockback, 85% accuracy, 5 rounds
    - Presentation: 75 Knockback, 75% accuracy, 5 rounds
- Sound
  - The base damage of Sound Gags has been increased.
  - Sound Gags no longer have combo damage when multiple are used in a turn.
  - Damage values:
    - Kazoo: 4 -> 5 damage
    - Bike Horn: 7 -> 10 damage
    - Whistle: 11 -> 16 damage
    - Bugle: 16 -> 23 damage
    - Aoogah: 21 -> 30 damage
    - Elephant Trunk: 32 -> 50 damage
    - Foghorn: 50 -> 70 damage
    - Opera Singer: 65 -> 90 damage
  - Introducing Sound's new prestige effect: Encore!
    - Whenever a prestige Sound Gag is used, the Toon who used the Gag will get 10% increased damage to non-Sound Gags for the next turn.
    - Prestige Sound no longer increases the damage of Sound Gags.
  - Instead of disappearing, the Sound gag megaphone will now shrink after usage during battle movies.
  - Fixed a longstanding issue where the camera angles for the Fog Horn and Opera Singer gags were swapped.
- Squirt
  - Instead of soaking multiple Cogs, prestige Squirt now provides a new debuff: Drenched!
    - Drenched is a more potent version of Soaked, providing some better benefits.
    - Drenched Cogs have a 20% dodge chance decrease.
    - Drenched Cogs will deal 15% less damage.
    - Zap Gags will only remove a single round of Drenched on use.
    - Drenched is applied only to the Cog targeted by the Squirt Gag used.
  - By default, every other Squirt Gag (levels 2, 4, 6, and 8) now soak 3 Cogs.
  - The other Squirt Gags (levels 1, 3, 5, 7) now do increased damage to make up for their lack of triple soak.
  - Damage values:
    - Squirting Flower: 4 -> 5 damage, soaks 1 Cog.
    - Glass of Water: 8 damage, soaks 3 Cogs.
    - Squirt Gun: 12 -> 16 damage, soaks 1 Cog.
    - Water Balloon: 21 damage, soaks 3 Cogs.
    - Seltzer Bottle: 30 -> 40 damage, soaks 1 Cog.
    - Firehose: 56 damage, soaks 3 Cogs.
    - Storm Cloud: 80 -> 95 damage, soaks 1 Cog.
    - Geyser: 115 damage, soaks 3 Cogs.
  - The Firehose's water stream now follows the Cog as it is being attacked during battle movies.
- Zap
  - Zap's jump damage now acts as a "pool" of damage.
    - This damage pool is split between the Cogs which it jumps onto.
    - This damage pool is 90% of the damage of the Zap gag used.
  - The nature of Zap's jump targeting has been greatly simplified.
    - There are now only two ways that Zap can deal damage across three soaked Cogs: Xxx and xxX.
      - The capital X represents the Cog that has been targeted directly by the Zap gag.
      - The lowercase x reflects the Cog targeted by Zap jumps. Jump damage is split between all of these cogs.
      - Zap will prioritize jumping to soaked cogs to the left if possible. If not, it will go right.
    - As a consequence, the following has changed:
      - Zap can no longer switch directions while jumping.
      - Zap Gags can now target Cogs which have been jumped to by a previous Zap Gag, rather than jumping over them.
      - Zap Gags will now damage Cogs killed by other Zaps in the same turn.
      - Zap can no longer jump over cleared sets of Cogs in general (i.e. no more X-x). The soaked Cogs must be adjacent.
      - Some double Zap combos become infeasible for defeating full sets of Cogs (such as X-X-), while others are now more feasible (such as X--X, or --XX).
      - Zap damage falloff has been reworked.
      - The soaked cog bonus of 3x damage is now 1x damage (as the base damage now has the damage boost accounted for).
  - Zap gags now have 0% accuracy against unsoaked cogs.
  - Prestige Zap now increases the total jump damage from 90% base damage to 110% base damage.
  - Using Zap on a soaked Cog now removes the soak, instead of reducing its duration by one round.
  - The Gag Shop has decided to replace the Balloon and Taser gags with some Toonier alternatives: Lightbulb and Broken Radio!
    - In addition, the Gag order has been slightly altered, with the level 4 and 5 Gags having swapped places.
  - Soaked Zap damage has been adjusted, as follows:
    - Level 2: 18 -> 22 damage
    - Level 3: 30 -> 40 damage
    - Level 4: 48 -> 62 damage
    - Level 5: 72 -> 92 damage
    - Level 6: 120 -> 140 damage
  - Several Zap Gags have gotten overhauled animations!
    - The Rug animation is now much faster.
    - The Kart Battery is now thrown.
    - The Broken TV is now placed.
    - Lightning is now more instant, with its lighting effect removed.
    - Zap beams now look like electricity flowing, as opposed to gigantic yellow triangles.
    - Zap beams are now shown between Cogs that are being jumped to.
    - Zap Gags now have new sound effects.
  - Cogs now react to various Zap Gags in new ways!
    - When defeated by a level 5+ Zap Gag, Cogs will now disintegrate.
- Throw
  - Whole Fruit Pie has had its damage increased from 50 to 55.
  - Throw has gotten a new prestige: Caramelize!
    - Prestige Throw will now give a self-heal to the user for 20% of the Gags base damage upon usage.
    - For example, a 130 damage Birthday Cake will heal the user for 26 Laff.
- Drop
  - Drop Gags now roll their accuracy individually per Drop Gag used, instead of being "all or nothing".
  - The accuracy bonus found on prestige Drop is now always +15%, as opposed to only +15% when used solo.
  - Damage values:
    - Flower Pot: 12 -> 15 damage
    - Sandbag: 20 -> 25 damage
    - Bowling Ball: 35 -> 40 damage
    - Anvil: 55 -> 60 damage
    - Big Weight: 80 -> 90 damage
    - Safe: 125 -> 140 damage
    - Boulder: 180 -> 200 damage
    - Grand Piano: 220 -> 240 damage
  - Combo damage values for Drop have also been changed as follows:
    - 2 Drops: +30%
    - 3 Drops: +40%
    - 4 Drops: +50%
  
**IOUs**
- SOS Cards have been rebranded entirely to become IOUs!
- IOUs are single-target, high-power stack-based Gag effectiveness buffs.
- If an IOU is used on another Toon, the Toon who used it will also profit from the boost provided, given that they have access to the Gag track in question.
  - Using an IOU on yourself will only provide the base effects of the IOU.
- IOUs work on a "stack" system, giving buffs to the next few Gags rather than giving a buff for the next few rounds.
- IOU values:
  - Toon-Up:
    - Madam Chuckle: +35 Toon-Up to the next 3 Toon-Up Gags.
    - Daffy Don: +45 Toon-Up to the next 2 Toon-Up Gags.
    - Flippy: +90 Toon-Up to the next Toon-Up Gag.
  - Trap:
    - Clerk Will: +85 damage to the next 3 Trap Gags.
    - Clerk Penny: +125 damage to the next 2 Trap Gags.
    - Clerk Clara: +250 damage to the next Trap Gag.
  - Lure:
    - Stinky Ned: +15 Knockback damage to the next 3 Lure Gags.
    - Nancy Gas: +20 Knockback damage to the next 2 Lure Gags.
    - Lil Oldman: +40 Knockback damage to the next Lure Gag.
  - Sound:
    - Barbara Seville: +20 damage to the next 3 Sound Gags.
    - Sid Sonata: +25 damage to the next 2 Sound Gags.
    - Moe Zart: +50 damage to the next Sound Gag.
  - Squirt:
    - Sid Squid: +30 damage to the next 3 Squirt Gags.
    - Sanjay Splash: +40 damage to the next 2 Squirt Gags.
    - Sharky Jones: +80 damage to the next Squirt Gag.
  - Zap:
    - Dentist Daniel: +30 damage (per target) to the next 3 Zap Gags.
    - Electra Eel: +40 damage (per target) to the next 2 Zap Gags.
    - Nat: +80 damage (per target) to the next Zap Gag.
  - Throw:
    - Cleff: +35 damage to the next 3 Throw Gags.
    - Cindy Sprinkles: +50 damage to the next 2 Throw Gags.
    - Pierce: +100 damage to the next Throw Gag.
  - Drop:
    - Clumsy Ned: +55 damage to the next 3 Drop Gags.
    - Franz Neckvein: +75 damage to the next 2 Drop Gags.
    - Barnacle Bessie: +150 damage to the next Drop Gag.
  - Rain:
    - +20 damage to the next Gag.
    - Rain's IOU has been removed from the Derrick Man and is now given as a constant extra reward from each completed V.P. battle.
- These changes have been made to make using these rewards feel more impactful, and allow users to use the full value of the reward. Rather than potentially missing some of the value by using another Gag track, or by missing their Gags, players will now be able to consistently take full advantage of these rewards.
- Former SOS card types not listed (such as Restock All, Cogs Damage Down, and Toons Accuracy Up) have been removed.
  - If you own any of these SOS cards, they will be rerolled into one of the aforementioned IOUs from this list.
 
**Unites**
- Single Gag-Up unites now restock up to level 8 gags.
  - However, the amount of Gags that these unites restock has been decreased to 6, so be careful with how you use them!
- The unite cooldown of Gag-Up unites has been increased by 1 round.
 
**Cease and Desists**
- C&Ds will no longer be refreshed to their maximum rounds upon being hit with a Gag. Instead, the rounds will be incremented by one (1) for each Gag used.
- The initial rounds of a C&D has been decreased to 4, however, the maximum amount of rounds that a C&D can have is 5.
 
**Music**
- Corporate Clash has received over 150 new music tracks!
- Many new music tracks have been added, though some older tracks have also gotten touch-ups.
  - All Cog HQs have been given brand new music.
    - Except for Lawbot HQ, who has only received a few new tracks.
  - All Gag Shop tracks have been updated.
  - Drowsy Dreamland and The Brrrgh have received new interior themes.
  - The Tell-Tale Carp has received a custom interior theme.
  - The main menu theme has been changed.
  - Not all of these tracks are present in the QA.
- Music.json now supports new functionality for specific miniboss themes inside of each facility type.
  - For example, the Mint Supervisor inside of a Coin Mint and inside of a Bullion Mint can have two different themes set via Music.json keys.
 
**ToonTasks**
- Many visual aspects of ToonTask posters have gotten an overhaul!
  - Tasks are now color-coded based on what type of task they are.
    - For example, Mainline Tasks will have a different colored Task poster to indicate what type of task they are to the player.
  - The Task rewards magnifying glass has gotten a toony facelift, offering a more stylistic hover menu with some cute little icons to boot.
- Many new types of Task objectives have been implemented, including:
  - General Cog Boss objectives
    - Stun
    - Deal damage
  - Specific Cog Boss objectives
    - V.P.
      - Throw pies
    - C.F.O.
      - Deal damage with goons
      - Deal damage with safes
      - Deal damage with unstunned goons
    - C.L.O.
      - Destroy normal and executive lawyers, either with a cannon or with Sound Gags
      - Collect sound evidence with a cannon
    - C.E.O.
      - Hit the boss with Golf balls
      - Feed normal and executive diners
  - Cog Objectives
    - Defeat Managers
      - This includes tasks for defeating Managers by Cog Department and defeating Managers with a level minimum.
 
**Daily Tasks**
- The Daily Task system has gotten a significant upgrade!
- You can now hold up to three Daily Tasks, one per day.
- Completion of a Daily Task will now reward a significant amount of Gumballs, as opposed to a random booster.
  - Short boosters will be obtainable in the future through the Gumball Machine for a similar price.
- The streak system has been removed.
  - All unique items that could be earned through weekly streak completion will be obtainable through the Gumball Machine.
- In addition, you can now hold up to two Daily Task Rerolls!
  - Spending a Daily Task Reroll will allow you to reroll any Daily Task into any other.
  - One Daily Task Reroll is given to you every day.
- The Daily Task system now uses the new task system introduced in v1.2.8.
  - This means that you will now be seeing new types of Daily Tasks being given out!
- The Daily Task page has been redone to accommodate all of these changes.
 
**Tweaks**
- By popular demand, various chairs throughout the entirety of Toontown can now be sat on!
  - In addition, there is a dedicated interact key for chairs.
- Some battle camera shots have been swapped with dramatic intervals.
- The play-by-play text during battles now has a pop-in and fade-out animation.
- Gag barrels now play Gag sounds on collision.
- Toon Tips now use the scavenge system.
- The Options page has received a few tweaks.
  - The Privacy section of the Options page has been renamed to Social, and the options have been rearranged as such.
  - Added a new "Enable Shaders" toggle.
  - The arrow buttons in the Options Page now move by page, rather than by row.
  - Added a new option to reduce GUI movement.
  - Certain options are now saved on the Toon, rather than being saved on the local computer (such as accepting friend requests).
- Implemented a new on-screen GUI positional manager to reduce overlap in all of the new GUI elements.
- Adjusted fog in all areas of the game.
- Changed the order of C&Ds and Pink Slips in the inventory.
- Added roll-over hover information for different attacks in battle.
- Updated the appearance of the instance sigils, such as the ones used in the Ye Olde Toontowne Dungeon.
- Updated many general UI assets around Toontown.
 
**Bugfixes**
- Fixed an issue that could cause Toons to fall into the void on Twilight Terrace.
- Fixed a minor memory leak related to the Wardrobe.
- Too many more to count!
 
**Known Issues**
We are listing out known issues with this version of the game to make sure that our QA Testers know of certain issues that we plan to look into.
 
- Club Announcements no longer exist and should be removed from the Social Panel.
- Certain Club Boosters shouldn't be day gated.
- Joining and leaving Groups needs to have a strong ratelimit applied.
- Sometimes, the prestige stars for Gag hovers will stick around when they shouldn't.
- Logging out and swapping Toons will cause your club/group status to persist.
- The post-battle Reward Panel greatly struggles with the existence of Daily Tasks.
- Minibosses give double rewards, for some reason.
- Boss Cog dialogue is broken.
- Sometimes, the info text on various Task Posters can be misplaced.
- Unites seem to sometimes put the user on permanent cooldown.
- You can force your Club Nametag to appear while in a Cog Disguise.
- You can donate 0 Jellybeans to a Club.
- The promotion/demotion Club Logs look really great right now.
- Fog is present in the C.E.O. battle.
- There's some strange visual effect issues regarding Drenched.
- Bro Vinci's eyes.
- Client-sided Sticker usage needs to be ratelimited.
- Club Shouts don't work at the moment.
- The "Go to Group" functionality for Boss and Facility Groups does not work at the moment.
- Chat should be disabled in the Alerts/NPC categories.
- Speedchat isn't the most usable in the expanded Chatbox view.
- ToonTask dialogue looks very bad in the NPC tab.
- Club Name Rewrites do not work.
- Taking a screenshot will crash you.
- Toon occlusion turns lots of other Toons invisible.
- Text emoticons, such as :), do not work.
- Other minor polish and useful planned QoL features are missing.
