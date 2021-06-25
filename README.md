

<div align="center">
  <h1>
    <sub><img src="https://hjjg200.github.io/twitch3d/logo.png" height="34px"></sub>
    Twitch3D
  </h1>
  
  <p>
Watch multiple streams and move or scale them as you please. 
<br>https://hjjg200.github.io/twitch3d
  </p>
</div>
  
## Known Issues

- Embedded Twitch players tend to show some purple screen due to Twitch's embedding policies. https://discuss.dev.twitch.tv/t/getting-a-message-on-my-embeds-that-goes-away-after-a-while/29592
- Autoplayed players often start muted in Chromes. https://developers.google.com/web/updates/2017/09/autoplay-policy-changes

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
- [x] Refine anchor feature
- [x] Fix group handlers for fully maximized windows
- [x] Must consider actual position when using boundingclientrect because of css transition
- [x] Chat dark mode
- [x] Better handling of auto-mute policy for better UX
- [x] Open chat menu for players
- [x] Make measure for: streams don't support Source quality when it just got online
- [x] Better `#introduction`
- [ ] Fix bug: sometimes streams don't start when it got online
- [ ] Import font css dynamically depending on language
- [ ] Layout put as query string (compressed json)
- [ ] Add opacity to window options
- [ ] Safari support
    - `webkitEnterFullscreen`
