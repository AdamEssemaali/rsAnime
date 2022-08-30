# rsAnime

> **Warning**
> rsAnime is under development, may be unstable

![version](https://img.shields.io/badge/version-0.1.0b-blue)
![osx-workflow](https://github.com/AdamEssemaali/rsAnime/actions/workflows/gh-actions-osx.yml/badge.svg) 
![win-workflow](https://github.com/AdamEssemaali/rsAnime/actions/workflows/gh-actions-win.yml/badge.svg)
![linux-workflow](https://github.com/AdamEssemaali/rsAnime/actions/workflows/gh-actions-linux.yml/badge.svg) 

*A Simple tool to watch Anime with AnimeWorld as backend written in Rust*


## Install 🎁
if you want to install the program from binaries you can go in  [release section](https://github.com/AdamEssemaali/rsAnime/releases) and add the binary in your OS path

**Linux**
<br>
`export PATH="<BIN DIRECTION>/rsAnime:$PATH" >> ~/.bashrc`
<br>

**OSX**
<br>
`export PATH="<BIN DIRECTION>/rsAnime:$PATH" >> ~/.bashrc`
<br>

**Windows major than 8**
- press the windows key and then open "System (Control Panel)"
- Click "Advanced system settings"
- Under "System variables", find the `PATH` select it and click "Edit".
- Add `<BINARY DIRECTORY>\rsAnime.exe` to the beginning of the list.
- Click OK
- Restart any open terminal

## Compile from source 🚀
### Dependencies 📦
- Rust
- Cargo
- git
- any video player that support HTTP video stream
### Build Instructions 💾
- `git clone `[https://github.com/AdamEssemaali/rsAnime/](https://github.com/AdamEssemaali/rsAnime/)
- `cd `[rsAnime](https://github.com/AdamEssemaali/rsAnime/)
- `cargo build --release`


## Usage ⚡️
### Search Anime
`rsAnime -s <anime_name>`
or
`rsAnime --search <anime_name>`
### Download Anime
`rsAnime -d <anime_name>` or `rsAnime --download <anime_name>`
