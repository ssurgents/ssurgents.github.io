# SSuRGents Test Server

> surgent: (adjective) rising in a surge

SSuRGents is a work in progress that hopes to be a 3rd-party clone/extension of the engine in SuperStar Rhythm Games (SSRG).
It runs on the existing [Sonolus](https://sonolus.com) app, a generic rhythm game app already used for other engines like Bandori and Project Sekai clones.
(See [Bestdori](https://bestdori.com) and [SweetPotato](https://wiki-en.purplepalette.net/home) for communities based around those engines.)
The Sonolus app gives SSuRGents some nice features for free, like offline play and customizations.

This test server currently contains levels from

- SuperStar Gfriend (SSG)
- SuperStar Pledis (SSP)
- SuperStar FNC (SSF)
- SuperStar Woollim (SSW)
- SuperStar Loona (SSLO)

More can be added in the future.

-----

## Notice regarding official Sonolus release (1.x.x)

This engine is based on an old version of Sonolus (0.6.x) and will not work with newer versions, including the official release on App Store/Google Play.

If you see a message saying that the engine is not compatible, you probably installed/updated to a newer incompatible version.
To play ssurgents, the current workaround is to avoid updating for now, or see the [How to play](#how-to-play) section for the v0.6.x download link.

The official Sonolus requires a new engine that (realistically) might not be available for a while, but the author hopes to have the time someday to complete.

-----

## Contents

- [Objectives](#objectives)
- [How to play](#how-to-play)
- [Known Issues](#known-issues)
- [Tentative Roadmap](#tentative-roadmap)
- [FAQ](#faq)
- [Bugs](#bugs)
- [Supporting the project](#supporting-the-project)
- [Special thanks to](#special-thanks-to)

-----

## Objectives

Neither the SSuRGents engine nor the Sonolus app has any concept of theme cards or storing score records.
This project is *NOT* intended to replace the full experience of the original SuperStar rhythm games.

Instead, this project is intended to be enjoyed solely for the rhythm gameplay itself,
and (in the future) as a space for creative extensions of the gameplay.
It hopes to provide a way to play any song and any beatmap, free from the following:

- ❌ gacha elements or payment-based advantages
- ❌ resource-based limit on gameplay attempts
- ❌ incentive to grind particular songs rather than playing whichever you enjoy
- ❌ dependence on a single provider of songs/beatmaps
- ❌ withholding of any song(s) for reasons like "end-of-service" or "injunction"
- ❌ guilt/uncertainty of potentially supporting companies under boycott

-----

## How to play

### Step 1: Get the Sonolus app (version 0.6.x)

**Currently, the engine will only work on version 0.6.x of the app (NOT v0.7.x to the official v1.x.x),
so be sure to download the correct version below.**
- [Android v0.6.5 apk download](https://drive.google.com/file/d/1ZV4iejeTJbKSjhfIFZ2_iKddwsdLi-y0/view?usp=sharing)
- [iOS v0.6.5 ipa download](https://drive.google.com/file/d/1buUl-lokkT-tP5zp7P-H8cpbXyv_AInZ/view?usp=sharing)

With the official release, the Sonolus [website](https://sonolus.com) no longer provides **sideloading** instructions,
but you may be able to find instructions elsewhere for sideloading the old version of the app onto your device.


### Step 2: Add custom server

Add the following as custom servers in the sonolus app.
If you already have Sonolus installed, clicking the link will go directly to the page in the app.


- SuperStar Gfriend
  - [https://ssurgents.github.io/gfriend](sonolus://ssurgents.github.io/gfriend)
- SuperStar Pledis
  - [https://ssurgents.github.io/pledis/afterschool](sonolus://ssurgents.github.io/pledis/afterschool)
  - [https://ssurgents.github.io/pledis/bumzu](sonolus://ssurgents.github.io/pledis/bumzu)
  - [https://ssurgents.github.io/pledis/nuest](sonolus://ssurgents.github.io/pledis/nuest)
  - [https://ssurgents.github.io/pledis/pristin](sonolus://ssurgents.github.io/pledis/pristin)
  - [https://ssurgents.github.io/pledis/seventeen](sonolus://ssurgents.github.io/pledis/seventeen)
- SuperStar FNC
  - [https://ssurgents.github.io/fnc/aoa](sonolus://ssurgents.github.io/fnc/aoa)
  - [https://ssurgents.github.io/fnc/cherrybullet](sonolus://ssurgents.github.io/fnc/cherrybullet)
  - [https://ssurgents.github.io/fnc/cnblue](sonolus://ssurgents.github.io/fnc/cnblue)
  - [https://ssurgents.github.io/fnc/ftisland](sonolus://ssurgents.github.io/fnc/ftisland)
  - [https://ssurgents.github.io/fnc/nflying](sonolus://ssurgents.github.io/fnc/nflying)
  - [https://ssurgents.github.io/fnc/p1harmony](sonolus://ssurgents.github.io/fnc/p1harmony)
  - [https://ssurgents.github.io/fnc/sf9](sonolus://ssurgents.github.io/fnc/sf9)
- SuperStar Woollim
  - [https://ssurgents.github.io/woollim/infinite](sonolus://ssurgents.github.io/woollim/infinite)
  - [https://ssurgents.github.io/woollim/lovelyz](sonolus://ssurgents.github.io/woollim/lovelyz)
  - [https://ssurgents.github.io/woollim/goldenchild](sonolus://ssurgents.github.io/woollim/goldenchild)
  - [https://ssurgents.github.io/woollim/rocketpunch](sonolus://ssurgents.github.io/woollim/rocketpunch)
  - [https://ssurgents.github.io/woollim/drippin](sonolus://ssurgents.github.io/woollim/drippin)
  - [https://ssurgents.github.io/woollim/kwoneunbi](sonolus://ssurgents.github.io/woollim/kwoneunbi)
- SuperStar Loona
  - [https://ssurgents.github.io/loona](sonolus://ssurgents.github.io/loona)

### Step 3: Choose level and play

Select the desired custom server and choose from the list of levels available.

-----

## Known Issues

1. Specific values for timing ranges/hitbox sizes might need further tuning to match SSRG exactly. Please file a bug report if you feel a mismatch (currently beyond my ability to tell if there is a difference).

2. Certain elements of UI do not match SSRG for now, as it will take time to work around some limitations of Sonolus to implement them.

       - Sonolus' default Perfect/Great/Good judgments instead of SPerfect/Perfect/Good
   	   - Combo is broken on Good
   	   - Scores/Rave not ready

3. Search functionality in the level listing does not work in this static test server, but will work once we move to dedicated hosting in the future

4. Judgment of slider start notes are delayed until the end of the entire slider.
   This is a workaround to allow the engine to deduct health at the exact time of a "miss"
   anytime along the slider.

-----

## Tentative Roadmap

### Phase 1: SSRG-compatible level trainer

#### Engine
- [x] Basic SSRG-style game and rules (mostly)
- [x] Adjust level/note speed
- [x] Autoplay
- [ ] Engine rewrite for new scripting system in Sonolus-0.7.x (in progress)
- [ ] Choice of x or y axis input judgment modes (currently y-axis only)
- [ ] Internal scores and rave system
- [ ] SSRG-style score/rave UI
- [ ] Release engine code under open source license

#### Aesthetics
- [x] Minimal-working SSRG-style skin/effects
- [x] Default in-game backgrounds
- [ ] Other backgrounds
- [ ] Improved SSRG-style skin/effects
- [ ] SuperStar Iz*one style skin?

#### Levels
- [x] SuperStar Gfriend
- [x] SuperStar Pledis
- [x] SuperStar FNC
- [x] SuperStar Woollim
- [ ] SuperStar PNation (in progress)
- [ ] SuperStar BrandNew (in progress)
- [x] SuperStar Loona (continual updates)
- [ ] Others

If you would like to play songs from a certain group, please do let me know by submitting a feature request.
(See the [Bugs](#bugs) section)
I want to be sure that there is support from the respective fandom before making it available.

#### Services
- [x] Static sonolus test server
- [ ] Dedicated sonolus server (required to scale project up, but comes with recurring costs)


### Phase 2: Community-made custom levels

#### Engine
- [ ] Extended features (to be decided)

#### Aesthetics
- [ ] Community-made backgrounds/skins/effects

#### Levels
- [ ] Community-made levels

#### Services
- [ ] online level simulator
- [ ] online chart-maker
- [ ] online repository for community-made levels
- [ ] online level browser with rating and sorting
- [ ] in-app chart-maker (after Sonolus-0.7.x)

### Phase 3: Level Generator?

Intended for newly released or less well-known music, until human chart-makers get to it.
Human-made beatmaps are still better in general, but generated beatmaps could be useful as a base to start on.

#### Levels
- [ ] develop and release beatmap generator code
- [ ] generated levels for community-requested music

#### Services
- [ ] online beatmap generator for user-submitted music

-----

## FAQ

1. Q: Can you fix this issue with the Sonolus app?

   	  A: I am not the developer of the Sonolus app, but you can ask for help with Sonolus in the help-and-support channel of their [discord](https://discord.gg/zStqbJahH7).

2. Q: When will you add levels from the SuperStar XXX app or from XXX group?

   	  A: I can't commit to a timeframe, but will try to consider requests from the community.

3. Q: My timing seems to be significantly off compared to my performance in the SuperStar apps. How do I calibrate my touch timing?

   	  A: If you scroll down the results page after playing a level, you can see a few graphs showing your touch offsets.
	  Peaks left of center means tapping too early, and right of center means too late.
	  To calibrate, try setting the Engine Input Offset at the bottom of the level configuration page to how far your graph peaks are from the center.

-----

## Bugs

For now, all bugs will be tracked on [github](https://github.com/ssurgents/ssurgents.github.io/issues), so first check if it is already listed there.
You may also report bugs through this [google form](https://docs.google.com/forms/d/e/1FAIpQLSfB6Tnbi6_VkDJRR3mI3JWKGbiPRMeuRBQRqoeBslfOyzf3aw/viewform?usp=sf_link).

-----

## Supporting the project

Everything made in this project will always be available for free,
I do this only because I can't bear to see people deprived of playing their favorite songs.

This project would not be possible at all without the Sonolus app, so please consider supporting its development as well.

If you like this project, please help share it with other players that will like it too!

-----

## Special thanks to

- Author of the [SSRG Tools](https://ssrg-tools.anhnhan.de) website for archiving SSG and SSP data
- Discord users @ddm135, @remi1111, @lingonberrylatte for help with testing and finding bugs