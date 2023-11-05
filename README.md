<h1 align="center">
  <img src="./src/assets/image/logo.png" alt="cl" width="128" />
  <br>
  cl v
  <br>
</h1>

<h3 align="center">
A <a href="https://github.com/Dreamacro/cl">cl</a> GUI based on <a href="https://github.com/tauri-apps/tauri">tauri</a>.
</h3>

## Features

- Full `cl` config supported, Partial `cl premium` config supported.
- Profiles management and enhancement (by yaml and Javascript). [Doc](https://github.com/zzzgydi/cl-v/wiki/%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)
- Simple UI and supports custom theme color.
- Built-in support [cl.Meta](https://github.com/MetaCubeX/cl.Meta) core.
- System p**** setting and guard.


</details>

安全

</details>

## Install

Download from [release](https://github.com/zzzgydi/cl-v/releases). Supports Windows x64, Linux x86_64 and macOS 11+

- [Windows x64](https://github.com/zzzgydi/cl-v/releases/download/v1.3.8/cl.v_1.3.8_x64_en-US.msi)
- [macOS intel](https://github.com/zzzgydi/cl-v/releases/download/v1.3.8/cl.v_1.3.8_x64.dmg)
- [macOS arm](https://github.com/zzzgydi/cl-v/releases/download/v1.3.8/cl.v_1.3.8_aarch64.dmg)
- [Linux AppImage](https://github.com/zzzgydi/cl-v/releases/download/v1.3.8/cl-v_1.3.8_amd64.AppImage)
- [Linux deb](https://github.com/zzzgydi/cl-v/releases/download/v1.3.8/cl-v_1.3.8_amd64.deb)
- [Fedora Linux](https://github.com/zzzgydi/cl-v/issues/352)

Or you can build it yourself. Supports Windows, Linux and macOS 10.15+

Notes: If you could not start the app on Windows, please check that you have [Webview2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section) installed.

### FAQ

#### 1. **macOS** "cl v" is damaged and can't be opened

open the terminal and run `sudo xattr -r -d com.apple.quarantine /Applications/cl\ v.app`

## Development

You should install Rust and Nodejs, see [here](https://tauri.app/v1/guides/getting-started/prerequisites) for more details. Then install Nodejs packages.

```shell
yarn install
```

Then download the cl binary... Or you can download it from [cl premium release](https://github.com/Dreamacro/cl/releases/tag/premium) and rename it according to [tauri config](https://tauri.studio/docs/api/config/#tauri.bundle.externalBin).

```shell
# force update to latest version
# yarn run check --force

yarn run check
```

Then run

```shell
yarn dev

# run it in another way if app instance exists
yarn dev:diff
```

Or you can build it

```shell
yarn build
```

## Todos

> This keng is a little big...

## Screenshots

<div align="center">
  <img src="./docs/demo1.png" alt="demo1" width="32%" />
  <img src="./docs/demo2.png" alt="demo2" width="32%" />
  <img src="./docs/demo3.png" alt="demo3" width="32%" />
  <img src="./docs/demo4.png" alt="demo4" width="32%" />
  <img src="./docs/demo5.png" alt="demo5" width="32%" />
  <img src="./docs/demo6.png" alt="demo6" width="32%" />
</div>

### Custom Theme

<div align="center">
  <img src="./docs/color1.png" alt="demo1" width="16%" />
  <img src="./docs/color2.png" alt="demo2" width="16%" />
  <img src="./docs/color3.png" alt="demo3" width="16%" />
  <img src="./docs/color4.png" alt="demo4" width="16%" />
  <img src="./docs/color5.png" alt="demo5" width="16%" />
  <img src="./docs/color6.png" alt="demo6" width="16%" />
</div>

## Disclaimer

This is a learning project for Rust practice.

## Contributions

Issue and PR welcome!

## Acknowledgement

cl v was based on or inspired by these projects and so on:

- [tauri-apps/tauri](https://github.com/tauri-apps/tauri): Build smaller, faster, and more secure desktop applications with a web frontend.
- [Dreamacro/cl](https://github.com/Dreamacro/cl): A rule-based tunnel in Go.
- [MetaCubeX/cl.Meta](https://github.com/MetaCubeX/cl.Meta): A rule-based tunnel in Go.
- [Fndroid/cl_for_windows_pkg](https://github.com/Fndroid/cl_for_windows_pkg): A Windows/macOS GUI based on cl.
- [vitejs/vite](https://github.com/vitejs/vite): Next generation frontend tooling. It's fast!

## License

GPL-3.0 License. See [License here](./LICENSE) for details.
