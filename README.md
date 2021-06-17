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
- [x] `mouseup` -> `click` for windows controls
- [x] Maximizing transition
- [x] Window specific context menu
- [x] Implement `alternate when maximized`
- [x] Store changed info after changing options
- [x] Prevent context menu from getting out of boundary
- [ ] Better handling of auto-mute policy for better UX
- [ ] Better `#introduction`
- [ ] Layout put as query string (compressed json)
- [ ] Prevent dropdown menu from getting out of boundary
- [ ] Must consider actual position when using boundingclientrect because of css transition
- [ ] Chat dark mode
- [ ] Make measure for: streams don't support Source quality when it just got online
- [ ] Player specific context menu
    - Play/Stop
    - Volume range
    - Quality
- [ ] Refine anchor feature
    - [ ] Use epsilon for anchor evaluation
    - [ ] Top-bottom anchor types: top, middle, bottom, top-bottom
    - [ ] Left-right anchor types: left, middle, right, left-right
    - [ ] Handling when resized
        - Top, left: maintain top, left
        - Middle: maintain position ratio but put it inside boundary
        - Bottom, right: maintain bottom, right
        - Top-bottom, left-right: maintain both by resizing the window
- [ ] Fix group handlers for fully maximized windows
    - [ ] Make temporary rect for fully maximized windows when grouping
- [ ] Add opacity to window options
- [ ] Discord for communication
- [ ] Firefox, Edge, and Safari support
