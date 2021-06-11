# twitch3d

Watch multiple streams and move or scale them as you please.

https://hjjg200.github.io/twitch3d

## Known Issues

- Embedded Twitch players tend to show some purple screen due to Twitch's embedding policies. https://discuss.dev.twitch.tv/t/getting-a-message-on-my-embeds-that-goes-away-after-a-while/29592
- Autoplayed players start muted in Chromes

## Features

- Grouping windows
- Maximizing control of windows resembles that of Windows
- Make offline streams invisible
- Store layout for later visits
- Repositioning windows when the browser is resized
- Windows snapped to 16:9 ratio or nearby windows
- Remember volumes and quality of streams when its window is maximized and not maximized separately
- Making the page fullscreen

## TODO
- [x] Make `Rem` class for clean px and rem management
- [x] Make `Window` class for window management
- [x] Chat support
- [x] Make offline channels transparent when cursor is still
- [x] Remember volume and quality when maximized and normal separately
- [x] Change from non-interactive iframe to interactive embedded players
- [ ] Maximizing transition
- [ ] Better handling of auto-mute policy for better UX
- [ ] Better `#introduction`
- [ ] Layout put as query string (compressed json)
- [ ] Discord for communication
- [ ] Firefox, Edge, and Safari support
