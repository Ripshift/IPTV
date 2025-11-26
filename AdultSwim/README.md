# Adult Swim IPTV Playlist

A curated collection of 24/7 Adult Swim streaming channels with EPG (Electronic Program Guide) support.

## Overview

This project provides an M3U playlist file containing 20 Adult Swim channels streaming continuously from the official Adult Swim CDN. Each channel features content from specific Adult Swim shows, including classics and current favorites.

## Features

- **20 Live Channels** - Continuous streaming of Adult Swim content
- **EPG Support** - Electronic Program Guide with 1-hour time blocks for easy navigation
- **High Quality Streams** - All channels use stream_5.m3u8 (high quality)
- **Channel Logos** - Custom logos for each channel
- **Organized Categories** - Channels grouped by Animated Series, Comedy, Experimental, and Variety

## Channel List

1. **Adult Swim** - Main Adult Swim stream
2. **Robot Chicken** - Stop-motion animated sketch comedy
3. **Infomercials** - Adult Swim's signature infomercials and experimental content
4. **Off the Air Smalls** - Psychedelic art compilation series
5. **Channel 5** - Adult Swim's livestream channel
6. **Metalocalypse** - Death metal band animated series
7. **Superjail** - Surreal adult animated series
8. **Aqua Teen Hunger Force** - Animated comedy series
9. **The Venture Bros** - Action/adventure parody series
10. **Squidbillies** - Animated hillbilly comedy
11. **Rick and Morty** - Sci-fi animated comedy
12. **Rick and More Morty** - Secondary Rick and Morty stream
13. **Black Jesus** - Live-action comedy series
14. **Mr. Pickles** - Dark animated comedy
15. **Apollo Gauntlet** - Animated action-comedy
16. **Your Pretty Face Is Going to Hell** - Live-action comedy about Hell
17. **The Eric Andre Show** - Absurdist talk show parody
18. **Samurai Jack** - Animated action-adventure series
19. **Primal** - Animated prehistoric fantasy
20. **Secondary Primal** - Alternative Primal stream

## File Structure

```
AdultSwim/
├── AdultSwim.m3u      # IPTV playlist file
├── epg.xml            # Electronic Program Guide
├── logos/             # Channel logo images
└── README.md          # This file
```

## Usage

### Using with IPTV Players

1. **VLC Media Player**
   - Open VLC
   - Media → Open Network Stream
   - Paste the raw GitHub URL to `AdultSwim.m3u`

2. **IPTV Smarters / TiviMate / Perfect Player**
   - Add playlist using the raw GitHub URL
   - Add EPG using the raw GitHub URL to `epg.xml`

3. **Kodi**
   - Install PVR IPTV Simple Client
   - Configure with M3U URL and EPG URL

### Raw URLs

M3U: https://raw.githubusercontent.com/Ripshift/IPTV/refs/heads/main/AdultSwim/AdultSwim.m3u
EPG: https://raw.githubusercontent.com/Ripshift/IPTV/refs/heads/main/AdultSwim/epg.xml
```

## EPG Information

The EPG file contains 1-hour programme blocks for each channel, making it easy to navigate through the guide although they are not accurate for intermissions. Each block shows:
- **Title**: Channel name
- **Description**: "24/7 continuous streaming"
- **Duration**: 1 hour blocks (00:00-23:00)

## Stream Source

All streams are sourced from the official Adult Swim CDN:
```
https://adultswim-vodlive.cdn.turner.com/live/{channel-name}/stream_5.m3u8
```

## Categories

- **Animated Series** - Cartoon and animated shows
- **Comedy** - Live-action and animated comedies
- **Experimental** - Art and experimental programming
- **Variety** - Mixed content and special programming

## Notes

- Streams are provided by Adult Swim and may be subject to availability
- Content loops continuously and may include intermission screens
- Stream quality is set to stream_5 (high quality)
- Some channels may show similar or repeated content


## License

This is a playlist aggregator for publicly available streams. All content is owned by Adult Swim / Warner Bros. Discovery.

## Contributing

Feel free to submit issues or pull requests to improve the playlist organization or add new working channels.

---

**Disclaimer**: This project is not affiliated with Adult Swim or Warner Bros. Discovery. All stream URLs are publicly available and sourced from official Adult Swim CDN servers.
