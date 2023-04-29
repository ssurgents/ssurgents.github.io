# SSuRGents Test Server

> surgent: (adjective) rising in a surge

SSuRGents is a work in progress that hopes to be a 3rd-party clone/extension of the engine in SuperStar Rhythm Games (SSRG).
It runs on the existing [Sonolus](https://sonolus.com) app, a generic rhythm game app already used for other engines like Bandori and Project Sekai clones.
(See [Bestdori](https://bestdori.com) and [SweetPotato](https://wiki-en.purplepalette.net/home) for communities based around those engines.)
The Sonolus app gives SSuRGents some nice features for free, like offline play and customizations.

This test server currently contains levels from

- SuperStar Gfriend (SSG)
- SuperStar Loona (SSLO)

More can be added in the future.

-----

## Contents

- [Objectives](#objectives)
- [How to play](#how-to-play)
- [Known Issues](#known-issues)
- [Tentative Roadmap](#tentative-roadmap)
- [FAQ](#faq)
- [Bugs](#bugs)
- [Supporting the project](#supporting-the-project)

-----

## Objectives

Neither the SSuRGents engine nor the Sonolus app has any concept of theme cards or storing score records.
They are NOT intended to replace the full experience of the original SuperStar rhythm games.

Instead, this project is intended to be enjoyed solely for the rhythm gameplay itself,
and (in the future) as a space for creative extensions of the gameplay.
It hopes to provide a way to play any song and any beatmap, free from the following:

- ❌ gacha elements or payment-based advantages
- ❌ rate limit on gameplay attempts by requiring the spending of a token
- ❌ incentive to grind particular songs rather than playing whichever you enjoy
- ❌ dependence on a single provider of songs/beatmaps
- ❌ withholding of any song(s) for reasons like "end-of-service" or "injunction"
- ❌ guilt/uncertainty of potentially supporting companies under boycott

-----

## How to play

### Step 1: Get the Sonolus app (version 0.6.x)

Since the app is still in beta, it is not yet available from the usual app stores.
Visit the Sonolus [website](https://sonolus.com) for sideloading instructions:

- [Android](https://wiki.sonolus.com/getting-started/installing/android.html)
- [iOS](https://wiki.sonolus.com/getting-started/installing/ios.html)

### Step 2: Add custom server

Add the following as custom servers in the sonolus app

- https://ssurgents.github.io/gfriend
- https://ssurgents.github.io/loona

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

-----

## Tentative Roadmap

### Phase 1: SSRG-compatible level trainer

#### Engine
- [x] Basic SSRG-style game and rules (mostly)
- [x] Adjust level/note speed
- [x] Autoplay
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
- [x] SuperStar Loona (continual updates)
- [ ] Others

#### Services
- [x] Static sonolus test server
- [ ] Dedicated sonolus server (required to scale project up, but comes with recurring costs)


### Phase 2: Community-made custom levels

#### Engine
- [ ] Extended features (to be decided)
- [ ] Engine rewrite for new scripting system in Sonolus-0.7.x

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

   	  A: I can't commit to a timeframe, but will try to consider requests from the community

-----

## Bugs

For now, all bugs will be tracked on [github](https://github.com/ssurgents/ssurgents.github.io/issues), so first check if it is already listed there.
You may also report bugs through this [google form](https://docs.google.com/forms/d/e/1FAIpQLSfB6Tnbi6_VkDJRR3mI3JWKGbiPRMeuRBQRqoeBslfOyzf3aw/viewform?usp=sf_link).

-----

## Supporting the project

If you like this project and want to drop me a tip, my paypal is loonarorbiter at gmail dot com.
Currently, donations will help me spend more time working on the project,
but in the future it will also pay for recurring costs of a dedicated server.