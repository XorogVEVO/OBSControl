# <img src="/BeatRecorder/Assets/Icon.png" alt="drawing" width="30"/> BeatRecorder



## Table of Contents  

#### General info and instructions
* **[What is this?](#what-is-this)**
* **[Requirements](#requirements)**
* **[How to set up](#how-to-set-up)**
#### Troubleshooting
* **[BeatRecorder not connecting?](#beatrecorder-not-connecting)**
* **[Contributing or forking](#contributing-or-forking)**

## Important info regarding OBS Websocket 5.x.x

**OBS Websocket 5.X.X is currently not supported. Please download and use [4.9.1](https://github.com/obsproject/obs-websocket/releases/tag/4.9.1-compat) for now.** 5.x.x support will be added soon, so stay tuned for that.

## What is this?

This application is for people who record their BeatSaber gameplay using OBS. It connects to **[HttpSiraStatus](https://github.com/denpadokei/HttpSiraStatus)** (**[beatsaber-http-status](https://github.com/opl-/beatsaber-http-status/)** for older Beat Saber versions), **[BSDataPuller](https://github.com/kOFReadie/BSDataPuller)** or **[BeatSaberPlus](https://github.com/hardcpp/BeatSaberPlus)** to detect the current game-state and **[obs-websocket](https://github.com/obsproject/obs-websocket/releases/tag/4.9.1)** to automatically start and stop the recording.

Files are saved where-ever you set your output folder to in OBS.

**If you have encountered any bugs or issues with this application, feel free to create an issue with your problem.**

**If you want to get it fixed faster or it's something urgent, you can join [my Discord](https://discord.gg/gzEjZE9Mre) and hit me (`Mira#2000`) with a ping.**


## Requirements

* **[HttpSiraStatus](https://github.com/denpadokei/HttpSiraStatus)** (**[HttpStatus](https://github.com/opl-/beatsaber-http-status/)** for older BS versions), **[BSDataPuller](https://github.com/kOFReadie/BSDataPuller)** or **[BeatSaberPlus (experimental)](https://github.com/hardcpp/BeatSaberPlus)**
    - **BeatSaberPlus support is incomplete as it does not provide a way of knowing if a song was failed or finished.**
<br></br>
* **[obs-websocket v4.9.1](https://github.com/obsproject/obs-websocket/releases/tag/4.9.1)**

## How to set up

1. Install all the previously mentioned dependencies.
2. Download and unzip this application.
3. Run it once, it'll ask you to input your settings. Do so.
4. Profit

## BeatRecorder not connecting?

**AVG Antivirus is known to cause all kinds of issues** with connection-related things. (Credit to `Arro#6969`. They discoverd and reported this issue.)

If you have AVG Antivirus installed, please uninstall it and find a better antivirus solution.

If you ruled out your antivirus (through uninstalling it or deactivating it's protection), just create an issue or join my Discord like mentioned before.

## Contributing or forking

Before building, you'll need [Xorog.Logger](https://github.com/Fortunevale/Xorog.Logger) and [Xorog.UniversalExtensions](https://github.com/Fortunevale/Xorog.UniversalExtensions).

From there on, it should be as easy as cloning the repository and running `dotnet restore`.