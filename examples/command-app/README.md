# zero-native command-app example

This example shows one `app.sync` command handled from each user-facing entry point:

- Native toolbar button.
- Native menu item.
- App shortcut.
- WebView bridge call.

Run with the system backend:

```sh
zig build run -Dplatform=macos -Dweb-engine=system
```

Run the headless test path:

```sh
zig build test -Dplatform=null
```
