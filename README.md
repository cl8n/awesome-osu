# Awesome osu! resources

An opinionated list of awesome osu! resources for every part of the game and community. Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome) and [osu-translate-zh/awesome-osu](https://github.com/osu-translate-zh/awesome-osu).

This is still in its infancy. Anyone can contribute!

## Contents

- [Official](#official)
  - [Open source](#open-source)
  - [For developers](#for-developers)
- [Communities](#communities)
  - [Discord](#discord)
  - [Reddit](#reddit)
- [Gameplay](#gameplay)
  - [Performance points](#performance-points)
  - [Video and livestreaming](#video-and-livestreaming)
- [Profile customization](#profile-customization)
- [Beatmapping and modding](#beatmapping-and-modding)
  - [Storyboarding](#storyboarding)
  - [Audio](#audio)
- [Skinning](#skinning)
- [Alternative clients](#alternative-clients)
- [For developers](#for-developers-1)

---

## Official

- [Website](https://osu.ppy.sh)
- [Old website](https://old.ppy.sh)
- [peppy's development blog](https://blog.ppy.sh) (not updated often)

### Open source

- [ppy GitHub organization](https://github.com/ppy)
  - [osu](https://github.com/ppy/osu) (lazer)
  - [osu-web](https://github.com/ppy/osu-web)
  - [osu-wiki](https://github.com/ppy/osu-wiki)
  - [osu-framework](https://github.com/ppy/osu-framework)

### For developers

- [API v1 documentation](https://github.com/ppy/osu-api/wiki)
- [API v2 documentation](https://osu.ppy.sh/docs/index.html)
- [Beatmap and score data dumps](https://data.ppy.sh)
- [Development forum](https://osu.ppy.sh/community/forums/2)

## Communities

- [Twitch listing](https://www.twitch.tv/directory/game/osu!)

### Discord

- [osu!dev](https://discord.gg/ppy): Official osu! development server
- [osu!](https://discord.gg/0Vxo9AsejDkGlk3H): All-purpose kind-of-official osu! server
- [osu! Medal Hunters](https://discord.gg/8qpNTs6): Hub for medal and achievement farmers
- [Aiess Project](https://discord.gg/2XV5dcW): Realtime feeds for osu! news, mapping events, and usergroup changes
- [osu! storyboarder banquet](https://discord.gg/B8NX7YW): Hub for everything about storyboarding
- [osu!taiko Mapping and Modding Hub](https://discord.gg/8RJBXe8)
- [osu!catch Modding and Mapping Hub](https://discord.gg/ZuxFc4q)
- [osu!mania Mapping & Modding Hub](https://discord.gg/FqbDdYN)
- [Mapset Management Server](https://discord.gg/8BquKaS): Modding discussion and queues
- [skinship](https://discord.gg/AZ79xJb): Hub for everything about skinning

### Reddit

- [osugame](https://www.reddit.com/r/osugame/): Primary all-purpose osu! subreddit
- [osureport](https://www.reddit.com/r/osureport/): Branch of osugame for player reports
- [OsuSkins](https://www.reddit.com/r/OsuSkins/): Showing off and discussing skins
- [BestOfOsu](https://www.reddit.com/r/bestofosu/): Sharing lesser-known fun maps

## Gameplay

- [osu!search](https://osusearch.com/): Advanced search engine for beatmaps
- [CollectionManager](https://github.com/Piotrekol/CollectionManager): Tools for editing and creating beatmap collections
- [osekai medals](https://osekai.net/medals/): Information about how to get every medal and how difficult they are
- [osekai rankings](https://osekai.net/rankings/): Special leaderboards about medals, mappers, badges, and more
- [OpenTabletDriver](https://github.com/InfinityGhost/OpenTabletDriver): Cross-platform configurable tablet driver
- [osuplus](https://github.com/limjeck/osuplus): Miscellaneous addons for the osu! website
- [osu!chan](https://osuchan.syrin.me/): Configurable community leaderboards
- [osu! Miss Analyzer](https://github.com/ThereGoesMySanity/osuMissAnalyzer): Visual analysis of misses in replays
- [osu!ReplayAnalyzer](https://github.com/firedigger/osuReplayAnalyzer): CLI to detect possible cheating in replays

### Performance points

- [Tillerino](https://github.com/Tillerino/Tillerinobot/wiki): IRC bot to get beatmap recommendations
  - [ppaddict](https://ppaddict.tillerino.org/): Web frontend for Tillerino
- [ezpp!](https://github.com/oamaok/ezpp): Browser extension to calculate performance points
- [osu-pps](https://osu-pps.com/#/osu/maps): Overweighted beatmaps tracker
- [osu!track](https://ameobea.me/osutrack/): Historical view of best plays and user statistics
- [osu!Skills](http://osuskills.com/): Unofficial player performance rating split into skills

### Video and livestreaming

- [osr2mp4](https://github.com/uyitroa/osr2mp4-app): Converts replay files to video
- [StreamCompanion](https://github.com/Piotrekol/StreamCompanion): Customizable stream overlay with beatmap and gameplay data
- [osukps](https://github.com/yugecin/osukps): Key states and keys-per-second overlay
- [bongocat-osu](https://github.com/kuroni/bongocat-osu): "Bongo Cat" overlay imitating an osu! liveplay in real time

## Profile customization

- [Banner link adder](https://www.osustuff.org/banner-link-adder): Splits banner images and generates BBCode to link parts separately

## Beatmapping and modding

- [Mappers' Guild](https://mappersguild.com/): MMO-style guild system for encouraging mapping of featured artists
- [Mapset Verifier](https://github.com/Naxesss/MapsetVerifier): Successor to AiMod, AIBat, and Modding Assistant
- [Mapping Tools](https://mappingtools.seira.moe/): Miscellaneous tools to create and clean beatmaps
- [Ranking Criteria forum](https://osu.ppy.sh/community/forums/87): Proposals and discussions about RC
- [osumapper](https://github.com/kotritrona/osumapper): Automatic mapping tool using TensorFlow deep learning

### Storyboarding

- [storybrew](https://github.com/Damnae/storybrew): Storyboard editor with support for reusable effects and a C# API
- [SGL](https://osu.ppy.sh/community/forums/topics/118733): Simple programming language that compiles to osu! storyboards

### Audio

- [ffmpeg](https://ffmpeg.org/): Collection of audio/video encoding and decoding tools\
  If you don't care about how this works, `ffmpeg -i <input> -map 0:0 -map_metadata -1 -b:a 192k output.mp3` is probably all you'll ever need to use for osu!. `<input>` can be any kind of audio file.
- [Spek](http://spek.cc/): Audio spectrum analyser

## Skinning

- [skinship tutorial page](https://tutorial.skinship.xyz/tutorial/introduction)
- [skinship resources page](https://tutorial.skinship.xyz/resources)
- [osuskinner](https://osuskinner.com/): Online skin builder

## Alternative clients

- [McOsu](https://store.steampowered.com/app/607260/McOsu/): Practice client with a lot of options and customizability. Includes experimental mods and a VR mode
- [danser-go](https://github.com/Wieku/danser-go): Visualizer client for fancy effects
- [osugame.online / webosu](http://osugame.online/): osu! for your browser
- [osu!droid](http://ops.dgsrz.com/): Client and leaderboards for Android
- [opsu!](https://itdelatrisu.github.io/opsu/): Cross-platform Java client with similar design to official clients
- [osu!archive](https://archive.osu.hubza.co.uk): Archive of old official clients

## For developers

- [oppai-ng](https://github.com/Francesco149/oppai-ng) (C): Difficulty and performance points calculator
- [node-osu](https://github.com/brussell98/node-osu) (NodeJS): osu! API v1 library
- [gosumemory](https://github.com/l3lackShark/gosumemory) (WebSocket): Cross-platform osu! memory reader
- [OsuParsers](https://github.com/mrflashstudio/OsuParsers) (C#): Parses osu! files
- [ProcessMemoryDataFinder](https://github.com/Piotrekol/ProcessMemoryDataFinder) (C#): Finds and reads data from Windows processes, with osu! as an example
- [osrparse](https://github.com/kszlim/osu-replay-parser) (Python): Parses replays
- [osu-strain](https://github.com/jamuwu/osu-strain) (Python): Gets chunk strain values for a beatmap
