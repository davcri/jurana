# jurana

simple frogger clone made in Haxe/Heaps

## How to Run
Prerequisites:
- [Haxe](https://haxe.org/download/) installed (used version 4.1.2 while developing).
- [Hashlink](https://hashlink.haxe.org/) installed (if you want to use the SDL version)

To install dependencies
```
haxelib install build.hxml
```

**Build**

**Hashlink**

To build it as **hashlink-sdl** target: `haxe build.hxml`
This will generate `build/game.hl` that will be runnable with `hl build/game.hl`

**Web/JS**

To build it as **web/js** target: `haxe js.hxml`
This will generate `web/game.js` that will be runnable by opening the `web/index.html` with a browser.


