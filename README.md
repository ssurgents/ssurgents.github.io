# SSuRGents Test Server

> surgent: (adjective) rising in a surge

SSuRGents is a work in progress that hopes to be a 3rd-party clone/extension of the engine in SuperStar Rhythm Games (SSRG).
It runs on the existing [Sonolus](https://sonolus.com) app, a generic rhythm game app already used for other engines like Bandori and Project Sekai clones.
The Sonolus app gives SSuRGents some nice features for free, like offline play and customizations.

This test server currently contains levels from

- SuperStar Gfriend (SSG)
- SuperStar Loona (SSLO)

More can be added in the future.

-----

## Contents

- [How to play](#how-to-play)
- [Known Issues](#known-issues)
- [Tentative Roadmap](#tentative-roadmap)
- [FAQ](#faq)
- [Bugs](#bugs)

-----

## How to play

### Step 1: Get the Sonolus app (version 0.6.x)

Since the app is still in beta, it is not yet available from the usual app stores. Visit the Sonolus [website](https://sonolus.com) for sideloading instructions:

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

1. Search functionality does not work in this test server, but will work once we move to dedicated hosting in the future

2. Certain elements of gameplay/UI do not match SSRG for now, as it will take time to work around some limitations of Sonolus to implement them.

       - Sonolus' default Perfect/Great/Good instead of SPerfect/Perfect/Good
   	   - Combo broken on Good
   	   - Scores/Rave not ready

-----

## Tentative Roadmap

### Phase 1: SSRG-compatible level trainer

#### Engine
- [x] Basic SSRG-style game and rules
- [x] Adjust level/note speed
- [x] Autoplay
- [ ] Choice of x or y axis input judgment modes (currently y-axis)
- [ ] Internal scores and rave system
- [ ] SSRG-style score/rave UI
- [ ] Release engine code under open source license

#### Aesthetics
- [x] Minimal-working SSRG-style skin/effects
- [x] Default in-game backgrounds
- [ ] Lobby backgrounds
- [ ] Improved SSRG-style skin/effects
- [ ] SuperStar Iz*one style skin?

#### Levels
- [x] SuperStar Gfriend
- [x] SuperStar Loona (continual updates)
- [ ] Others

#### Services
- [x] Static sonolus test server
- [ ] Dedicated sonolus server (required to scale project up, but comes with costs)


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
Human-made beatmaps are still better in general, but generated beatmaps could be useful as a starting point.

#### Levels
- [ ] beatmap generator algorithm
- [ ] generated levels for community-requested music

#### Services
- [ ] online beatmap generator for user-submitted music

-----

## FAQ

1. Q: Can you fix this issue with the Sonolus app?

   	  A: I am not the developer of the Sonolus app, but you can ask for help with Sonolus in their [discord](https://discord.gg/zStqbJahH7).

2. Q: When will you add levels from the SuperStar XXX app or from XXX group?

   	  A: I can't commit to a timeframe, but will try to consider requests from the community

-----

## Bugs

For now, all bugs will be tracked on [github](https://github.com/ssurgents/ssurgents.github.io/issues), so check there first. You may also report bugs through this [google form](https://docs.google.com/forms/d/e/1FAIpQLSfB6Tnbi6_VkDJRR3mI3JWKGbiPRMeuRBQRqoeBslfOyzf3aw/viewform?usp=sf_link).

