---
layout: app

permalink: /Media_Mate/
description: A full media server/player/downloader/etc - in one
license: MIT

icons:
  - Media_Mate/icons/128x128/media_mate.png

screenshots:
  - Media_Mate/screenshot.png

authors:
  - name: willyb321
    url: https://github.com/willyb321

links:
  - type: GitHub
    url: willyb321/media_mate
  - type: Download
    url: https://github.com/willyb321/media_mate/releases

desktop:
  Desktop Entry:
    Name: Media Mate
    Comment: A full media server/player/downloader/etc - in one
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: media_mate
    X-AppImage-Version: 1.3.3.130
    X-AppImage-BuildId: 2d34adc0-d8a5-11a7-1ecd-6120b54e0699
    Categories: AudioVideo
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
    url: https://williamblythe.info
  private: true
  license: MIT
  name: media_mate
  main: __shim.js
  productName: Media Mate
  description: A full media server/player/downloader/etc - in one
  version: 1.3.3
  dependencies:
    about-window: "^1.8.0"
    babel-plugin-source-map-support: "^1.0.0"
    blob-util: "^1.3.0"
    bulma: "^0.4.3"
    bytes: "^3.0.0"
    debug: "^3.1.0"
    devtron: "^1.4.0"
    dotenv: "^4.0.0"
    electron-collection: "^1.2.0"
    electron-compile: "^6.4.2"
    electron-compilers: "^5.9.0"
    electron-context-menu: "^0.9.1"
    electron-json-storage: "^4.0.2"
    electron-log: "^2.2.11"
    electron-notify: "^0.1.0"
    electron-unhandled: "^0.2.0"
    electron-updater: "^2.16.2"
    electron-window-state: "^4.1.1"
    episode-parser: willyb321/episode-parser.git#9008e1da6ed5152349e1d35ff65b68b9684a9b9e
    feedparser: "^2.2.4"
    font-awesome: "^4.7.0"
    fs-extra: "^4.0.2"
    global-tunnel: "^1.2.0"
    hover.css: "^2.2.1"
    is-electron-renderer: "^2.0.1"
    is-online: "^7.0.0"
    json-stringify-safe: "^5.0.1"
    klaw-sync: "^3.0.2"
    lru-cache: "^4.1.1"
    moment: "^2.19.2"
    mprogress: willyb321/MProgress.js
    nedb-core: "^3.0.6"
    node-dir: "^0.1.17"
    node-tvdb: willyb321/node-tvdb
    open-color: "^1.5.1"
    progressbar.js: "^1.0.1"
    pushstate-server: "^3.0.1"
    raven: "^2.2.1"
    raven-js: "^3.20.1"
    request: "^2.83.0"
    source-map-support: "^0.5.0"
    sweetalert2: "^7.0.0"
    send: "^0.16.1"
    parseurl: "^1.3.2"
    tableify: "^1.1.0"
    underscore: "^1.8.3"
    video.js: "^6.5.0"
    webtorrent: "^0.98.20"
  originalMain: main/es6-init.js
---