# wry-mobile

This is the mobile template setup by cargo mobile.

## Cargo mobile

Build with [cargo mobile](https://github.com/BrainiumLLC/cargo-mobile) for our tests and simplicity of use.

```bash
cargo install --git https://github.com/BrainiumLLC/cargo-mobile
```

## iOS

### Open the project in XCode

```bash
cargo apple open
```

**Important: You need to link Webview Framework in build settings**

wry-mobile > General > Frameworks, Libraries, and Embedded Content > Webkit.framework 

### Run on your connected phone

```bash
cargo apple run
```

If you haven't trusted the device, go to Settings > General > VPN 與裝置管理(what's the english name of this lol) to trust the device.

## Android

TODO

