# twitch3d

Watch multiple streams and move or scale them as you please.

## Known Issues

- Embedded Twitch players tend to show some purple screen due to Twitch's embedding policies. https://discuss.dev.twitch.tv/t/getting-a-message-on-my-embeds-that-goes-away-after-a-while/29592

## TODO
- [x] Make `Rem` class for clean px and rem management
    - `Rem.pixels()`
    - `static Rem.fromPixels(px)`
- [ ] Make `Window` class for window management
    - `Window.create({top: Rem, left: Rem, width: Rem, height: Rem, xOffset: Rem, yOffset: Rem}) => Window`
        - Fires `WindowCreateEvent`
    - `Window.reposition()`
    - `Window.setTitle(title)`
    - `Window.maximize(xAxis: boolean, yAxis: boolean)` fires `WindowMaximizeEvent`
        - When a window gets unmaximized a WindowUnmaximizeEvent is fired
        - Horizontally maximized windows only take left and right into account when repositioning
    - `Window.close()` fires `WindowCloseEvent`
    - `Window.focus()` fires `WindowFocusEvent`
    - `Window.blur()` fires `WindowBlurEvent`
    - `WindowMoveEvent`, `WindowResizeEvent`
    - `Window.element()`
        - Element id: `window-1`, `window-2` ...
- [x] Chat support
- [ ] Make offline channels transparent when cursor is still
- [ ] Remember volume and quality when maximized and normal separately
- [ ] Change from non-interactive iframe to interactive embedded players
- [ ] Discord for communication
- [ ] Firefox, Edge, and Safari support
