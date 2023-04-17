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
- [Support](#support)

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
2. Certain elements of gameplay like combos, scores, rave, etc do not match SSRG rules for now, as it will take time to work around some limitations of Sonolus to implement them.

-----

## Tentative Roadmap

### Phase 1: SSRG-compatible level trainer

#### Engine
- [x] Basic SSRG input rules
- [x] Adjust level/note speed
- [ ] Autoplay
- [ ] Choice of x or y axis input judgment modes (currently y-axis)
- [ ] Scores and Rave system
- [ ] SSRG-style score/rave UI
- [ ] Release engine code under open source license

#### Aesthetics
- [x] Minimal-working SSRG-style skin/effects
- [x] Default in-game backgrounds
- [ ] Lobby backgrounds
- [ ] Improved SSRG-style skin/effects
- [ ] SuperStar Iz*one style skin

#### Levels
- [x] SuperStar Gfriend
- [x] SuperStar Loona (continual updates)
- [ ] Others

#### Services
- [x] Static sonolus test server
- [ ] Dedicated sonolus server


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

### Phase 3: Level Generator

#### Levels
- [ ] beatmap generator algorithm
- [ ] generated levels for community-requested music (typically newly released music,
  	  before human chart-makers get to it)

#### Services
- [ ] online beatmap generator for user-submitted music

-----

## FAQ

1. Q: Can you fix this issue with the Sonolus app?
   A: I am not the developer of the Sonolus app, but you can ask for help with Sonolus in their [discord](https://discord.gg/zStqbJahH7).

2. Q: When will you add levels from the SuperStar XXX app or from XXX group?
   A: I can't commit to a timeframe, but will try to consider requests from the community

-----

## Support

I will start taking bug reports at a later time, but presently there are issues that I am already aware of and will be working on.
