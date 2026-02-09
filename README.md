# Awesome Yew [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[<img src="logo.svg" align="right" width="100" title="Awesome Yew">](https://github.com/yewstack/yew) ⭐ 32,399 | 🐛 153 | 🌐 Rust | 📅 2026-02-07

> A curated list of awesome things related to Yew.

[Yew](https://github.com/yewstack/yew) ⭐ 32,399 | 🐛 153 | 🌐 Rust | 📅 2026-02-07 is a modern Rust framework inspired by Elm and React for creating multi-threaded frontend apps with WebAssembly.

Contributions welcome! Read the [contribution guidelines](origin/CONTRIBUTING.md) first.

## Contents

* [Official](#official)
* [Projects](#projects)
* [Templates](#templates)
* [Crates](#crates)
  * [Component Libraries](#component-libraries)
  * [Components](#components)
  * [Hooks](#hooks)
  * [Utils](#utils)
  * [Wasm](#wasm)
* [Tooling](#tooling)
* [Articles](#articles)
* [Books](#books)
* [Alternatives](#alternatives)
* [Related lists](#related-lists)

## Official

* [Yew](https://github.com/yewstack/yew) ⭐ 32,399 | 🐛 153 | 🌐 Rust | 📅 2026-02-07 - Rust / WebAssembly framework for building client web apps.
* [Examples](https://github.com/yewstack/yew/tree/master/examples) ⭐ 32,399 | 🐛 153 | 🌐 Rust | 📅 2026-02-07 - Smaller examples included in official repo.
* [Live demo](https://yew-todomvc.netlify.com) - A todomvc demo.
* [API Docs](https://docs.rs/yew) - Docs on docs.rs.
* [Website](https://yew.rs/) - Official website.
* [Chatroom](https://discord.gg/VQck8X4) - It is pretty active and is a great place to ask questions.
* [Reddit](https://www.reddit.com/r/yew_web/) - Dedicated Sub Reddit.
* [Financial Contribute](https://opencollective.com/yew) - Become a financial contributor and help us sustain our community.
* [Playground](https://play.yew.rs) - Online playground for Yew.

## Projects

* [candle-wasm-examples](https://github.com/huggingface/candle) ⭐ 19,322 | 🐛 601 | 🌐 Rust | 📅 2026-02-06 - Candle is a minimalist ML framework for Rust with a focus on performance (including GPU support) and ease of use. Try our online demos: [whisper](https://huggingface.co/spaces/lmz/candle-whisper), [LLaMA2](https://huggingface.co/spaces/lmz/candle-llama2), [T5](https://huggingface.co/spaces/radames/Candle-T5-Generation-Wasm), [yolo](https://huggingface.co/spaces/lmz/candle-yolo), [Segment
  Anything](https://huggingface.co/spaces/radames/candle-segment-anything-wasm).
* [webapp.rs](https://github.com/saschagrunert/webapp.rs) ⭐ 2,240 | 🐛 23 | 🌐 Rust | 📅 2023-03-16 - A web application completely written in Rust, frontend is built with Yew.
* [zoom-rs](https://github.com/security-union/zoom-rs) ⭐ 1,698 | 🐛 56 | 🌐 Rust | 📅 2026-02-09 - Zoom clone written in rust for research purposes.
* [Rust-Full-Stack](https://github.com/steadylearner/Rust-Full-Stack) ⭐ 1,581 | 🐛 244 | 🌐 Rust | 📅 2023-05-10 - Easily testable and working Rust codes with blog posts to explain them.
* [Realworld example](https://github.com/jetli/rust-yew-realworld-example-app) ⭐ 890 | 🐛 6 | 🌐 Rust | 📅 2025-12-28 - Exemplary real world app built with Rust + Yew + WebAssembly. It utilizes Yew's latest `function components` and `hooks`. It also supports desktop application powered by [Tauri](https://github.com/tauri-apps/tauri) ⭐ 102,458 | 🐛 1,346 | 🌐 Rust | 📅 2026-02-08.
* [PinePods](https://github.com/madeofpendletonwool/PinePods) ⭐ 787 | 🐛 124 | 🌐 Rust | 📅 2026-02-05 - PinePods is a Rust based podcast management system that manages podcasts with multi-user support and relies on a central database with clients to connect to it.
* [Proxelar](https://github.com/emanuele-em/proxelar) ⭐ 447 | 🐛 13 | 🌐 Rust | 📅 2026-02-05 - Rust-based Man in the Middle proxy, an early-stage project aimed at providing visibility into network traffic.
* [Spaceman](https://github.com/eliaperantoni/spaceman) ⭐ 374 | 🐛 0 | 🌐 Rust | 📅 2023-04-23 - Spaceman is a cross-platform gRPC client designed to be pleasant to use and pretty to look at.
* [Sentry Relay](https://github.com/getsentry/relay) ⭐ 361 | 🐛 100 | 🌐 Rust | 📅 2026-02-08 - The Sentry Relay is a service that pushes some functionality from the Sentry SDKs as well as the Sentry server into a proxy process.
* [zzhack](https://github.com/zzhack-stack/zzhack) ⭐ 330 | 🐛 0 | 🌐 Rust | 📅 2026-01-14 - A personal blog, based on Rust & Yew, [Live Demo](https://www.zzhack.fun/).
* [Ubiquity](https://github.com/opensourcecheemsburgers/ubiquity) ⭐ 300 | 🐛 3 | 🌐 Rust | 📅 2023-08-01 - An open-source, cross-platform markdown editor; built with Yew, Tauri, Tailwind, and DaisyUI. [Web App](https://ubiquity.rs).
* [RustMart](https://github.com/sheshbabu/rustmart-yew-example) ⭐ 272 | 🐛 2 | 🌐 Rust | 📅 2020-08-31 - Single Page Application (SPA) written using Rust, Wasm and Yew.
* [tchatche.rs](https://github.com/nag763/tchatchers) ⚠️ Archived - A Websocket chat based application built in Yew and Axum.
* [Taxy](https://github.com/picoHz/taxy/tree/main) ⭐ 192 | 🐛 5 | 🌐 Rust | 📅 2025-04-06 - A reverse proxy server with built-in WebUI, supporting TCP/HTTP/TLS/WebSocket, written in Rust.
* [Crabtyper](https://github.com/brancobruyneel/crabtyper) ⭐ 187 | 🐛 9 | 🌐 Rust | 📅 2022-08-25 - A speedtyping web app written in Rust.
* [caniuse.rs](https://github.com/jplatte/caniuse.rs) ⭐ 183 | 🐛 8 | 🌐 Rust | 📅 2025-06-27 - Rust feature search.
* [karaoke-rs](https://github.com/tarkah/karaoke-rs) ⭐ 168 | 🐛 10 | 🌐 Rust | 📅 2022-06-08 - A simple, network enabled karaoke player in Rust.
* [yew-styles-page](https://github.com/spielrs/yew-styles-page) ⭐ 159 | 🐛 21 | 🌐 Rust | 📅 2023-01-20 - This is an initial project of a framework style for yew.
* [Kiomet](https://github.com/SoftbearStudios/kiomet) ⭐ 155 | 🐛 5 | 🌐 Rust | 📅 2025-09-10 - An online real-time strategy game in which you expand your territory by capturing towers.
* [wasm-2048](https://github.com/dev-family/wasm-2048) ⭐ 153 | 🐛 1 | 🌐 Rust | 📅 2020-12-30 - 2048 game implemented with Rust and Yew and compiled to Wasm.
* [diff.rs](https://github.com/xfbs/diff.rs) ⭐ 136 | 🐛 42 | 🌐 Rust | 📅 2025-07-05 - Web application to render a diff between Rust crate versions. Implemented in Yew, runs fully in the browser as WebAssembly, [Live Demo](https://diff.rs).
* [Yew-WebRTC-Chat](https://github.com/codec-abc/Yew-WebRTC-Chat) ⭐ 127 | 🐛 2 | 🌐 Rust | 📅 2023-08-17 - A simple WebRTC chat made with Yew.
* [Rust algorithms](https://github.com/Jondolf/rust-algorithms) ⭐ 126 | 🐛 1 | 🌐 Rust | 📅 2024-07-17 - A website with interactive implementations of various algorithms.
* [chipbox](https://github.com/chipnertkj/chipbox) ⭐ 123 | 🐛 10 | 🌐 Rust | 📅 2026-02-05 - chipbox is an open-source desktop DAW written in Rust.
* [CubeShuffle](https://github.com/philipborg/CubeShuffle) ⭐ 112 | 🐛 28 | 🌐 Rust | 📅 2023-02-24 - Card game shuffling utility built with Rust, Yew, Bulma and Tauri.
* [web-view todomvc desktop app](https://github.com/Extrawurst/rust-webview-todomvc-yew) ⭐ 108 | 🐛 15 | 🌐 Rust | 📅 2023-01-20 - Demo how to use yew for a todomvc that compiles to WebAssembly and is bundled as a lightweight(\~2mb) desktop app by [web-view](https://github.com/Boscop/web-view) ⭐ 1,950 | 🐛 117 | 🌐 JavaScript | 📅 2024-05-09, as an alternative to Electron, [web-view](https://github.com/Boscop/web-view) ⭐ 1,950 | 🐛 117 | 🌐 JavaScript | 📅 2024-05-09 also has a [demo](https://github.com/Boscop/web-view/tree/master/examples#todo-yew) ⭐ 1,950 | 🐛 117 | 🌐 JavaScript | 📅 2024-05-09.
* [Syre](https://github.com/syre-data/syre) ⭐ 108 | 🐛 3 | 🌐 Rust | 📅 2025-09-01 - Scientific data management and insights.
* [live-ask.com](https://github.com/liveask/liveask) ⭐ 104 | 🐛 9 | 🌐 Rust | 📅 2026-01-26 - Realtime Event/Meetup Q\&A Platform. [Live at live-ask.com](https://live-ask.com).
* [Fullstack-Rust](https://github.com/vascokk/fullstack-rust) ⭐ 96 | 🐛 1 | 🌐 Rust | 📅 2023-10-09 - A Full Stack Rust application (Connect5 game) with Actix-web, Yew, Bulma CSS and Diesel.
* [Macige](https://github.com/tramlinehq/macige) ⭐ 95 | 🐛 4 | 🌐 Rust | 📅 2023-06-07 - CI workflow generator for mobile app development, [Live Demo](https://macige.tramline.app).
* [RustedLessPass](https://github.com/RustedLessPass/RustedLessPass) ⭐ 77 | 🐛 2 | 🌐 Rust | 📅 2026-02-05 - A stateless password manager. [Web App](https://rustedlesspass.github.io/).
* [Mindsweeper](https://github.com/AlexBuz/mindsweeper) ⭐ 77 | 🐛 1 | 🌐 Rust | 📅 2023-12-30 - A principled take on minesweeper, [Live Demo](https://alexbuz.github.io/mindsweeper/).
* [simply-view-image-for-python-debugging](https://github.com/elazarcoh/simply-view-image-for-python-debugging?tab=readme-ov-file) ⭐ 71 | 🐛 17 | 🌐 Rust | 📅 2026-02-07 - Visual studio code extension simply view the image of the image variables when debugging python.
* [hurlurl](https://github.com/lucasmerlin/hurlurl) ⭐ 69 | 🐛 0 | 🌐 Rust | 📅 2025-07-25 - A randomizing link shortener, [Live Demo](https://hurlurl.com/).
* [yew-react-example](https://github.com/hobofan/yew-react-example) ⭐ 66 | 🐛 3 | 🌐 JavaScript | 📅 2020-11-17 - This project shows how to create a web app using a React component inside a Yew component.
* [SandCat](https://github.com/Xu-Mj/sandcat) ⭐ 63 | 🐛 0 | 🌐 Rust | 📅 2024-08-16 - The software has primarily implemented the basic functionalities of an IM application, which includes a fundamental friend system, one-on-one chat, group chat, and one-on-one audio/video calls. It also supports i18n and currently offers a switch between Chinese and English.
* [blog-rs](https://github.com/songday/blog-rs) ⭐ 61 | 🐛 0 | 🌐 Rust | 📅 2022-11-29 - A blog system in which frontend and backend are ALL written in Rust. Backend powered by Warp and frontend built on Yew (WASM).
* [Yew Fullstack Boilerplate](https://github.com/lukidoescode/yew-fullstack-boilerplate) ⭐ 58 | 🐛 22 | 🌐 Rust | 📅 2023-01-07 - Highly opinionated boilerplate for creating full stack applications with Rust.
* [website-wasm](https://github.com/kamiyaa/website-wasm) ⭐ 57 | 🐛 0 | 🌐 Rust | 📅 2022-03-03 - My personal website written in Rust via Yew/Wasm.
* [Flow.er](https://github.com/LighghtEeloo/flow.er) ⭐ 56 | 🐛 1 | 🌐 Rust | 📅 2023-05-24 - A notebook app integrated with todo lists utility. Developed with Rust, WebAssembly, Yew and Trunk.
* [Rust Audio](https://github.com/austintheriot/audio) ⭐ 55 | 🐛 3 | 🌐 Rust | 📅 2025-06-16 - Realtime audio processing / synthesis using Rust/WASM in the browser, [Live Demo](https://austintheriot.github.io/audio/).
* [surfer](https://github.com/zzy/surfer) ⭐ 52 | 🐛 0 | 🌐 Rust | 📅 2023-02-08 - A blog built on yew + graphql, with [live demo site](https://niqin.com). Backend for graphql services, and frontend for web application.
* [rust-async-wasm-demo](https://github.com/extraymond/rust-async-wasm-demo) ⭐ 47 | 🐛 13 | 🌐 Rust | 📅 2023-01-07 - Toy project to learn Rust and async that can be deployed to the web.
* [Kirk](https://github.com/stkevintan/Kirk) ⭐ 45 | 🐛 22 | 🌐 Rust | 📅 2022-12-11 - Just A Rust WebAssembly Blog.
* [tide-async-graphql-mongodb](https://github.com/zzy/tide-async-graphql-mongodb) ⭐ 45 | 🐛 2 | 🌐 Rust | 📅 2023-02-08 - Clean boilerplate for graphql services, with wasm/yew frontend.
* [Paudle](https://github.com/pmsanford/paudle) ⭐ 43 | 🐛 0 | 🌐 Rust | 📅 2022-10-11 - A reimplementation of the excellent word game Wordle by Josh Wardle.
* [DevAndDev](https://github.com/alepez/devand) ⭐ 41 | 🐛 58 | 🌐 Rust | 📅 2025-06-24 - A website where developers can find pair-programming partners. Written in Rust, Yew frontend.
* [Crypto-helper](https://github.com/TheBestTvarynka/crypto-helper) ⭐ 41 | 🐛 3 | 🌐 Rust | 📅 2025-12-23 - Web app that can hash, encrypt, and sign the data on the client side. Also includes a JWT debugger. [Website](https://crypto.qkation.com).
* [Minesweeper](https://github.com/jgpaiva/minesweeper) ⭐ 38 | 🐛 2 | 🌐 Rust | 📅 2023-02-04 - Minesweeper built with Rust, Yew and WebAssembly.
* [Pipe](https://github.com/pipe-fun/pipe) ⭐ 29 | 🐛 0 | 🌐 Rust | 📅 2020-09-21 - This is a Rust / Wasm client web app which is a task control center.
* [I Love Hue! (rs)](https://github.com/noc7c9/i-love-hue-rs) ⭐ 24 | 🐛 0 | 🌐 Rust | 📅 2020-02-10 - A clone of the mobile game I Love Hue in Yew (Rust).
* [yew-d3-example](https://github.com/ivanschuetz/yew-d3-example) ⭐ 24 | 🐛 0 | 🌐 Rust | 📅 2021-04-12 - Showing a d3 chart with Yew.
* [scap-rs](https://github.com/emo-crab/scap-rs) ⭐ 24 | 🐛 8 | 🌐 Rust | 📅 2026-02-03 - National Vulnerability Database (NVD) implemented by Rust, [Live Demo](https://scap.kali-team.cn/).
* [covplot](https://github.com/jbowens/covplot) ⭐ 21 | 🐛 14 | 🌐 Rust | 📅 2023-01-20 - Live graphs of worldwide CoVID-19 data.
* [Hikari](https://github.com/celestia-island/hikari) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-02-05 - The Frontend of Everything.
* [yew-octicons](https://github.com/io12/yew-octicons) ⭐ 19 | 🐛 3 | 🌐 Rust | 📅 2023-10-30 - An easy interface for using Octicons in Yew projects.
* [windows-terminal-theme-generator](https://github.com/LelouchFR/windows-terminal-theme-generator/) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2024-04-22 - Simplify your life to create a windows terminal theme. [Live Demo](https://windows-terminal-theme-generator.netlify.app/)
* [yew-ssr-actix-web](https://github.com/zzy/yew-ssr-actix-web) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2022-02-22 - The example demonstrates Yew server-side rendering with actix-web & reqwest, it needs the **development version** of Yew.
* [Rust electron yew demo](https://github.com/Extrawurst/rust-electron-demo) ⭐ 16 | 🐛 14 | 🌐 JavaScript | 📅 2022-12-10 - An example of building a Rust based web app (Yew) into a native app using electron.
* [Chord Quiz](https://github.com/Stigjb/chord-quiz) ⭐ 16 | 🐛 27 | 🌐 Rust | 📅 2023-01-20 - Practice recognizing chords in this Rust/Yew/WebAssembly app.
* [Oxfeed](https://github.com/sanpii/oxfeed) ⭐ 14 | 🐛 3 | 🌐 Rust | 📅 2026-01-26 - A feed reader written in Rust with a Yew frontend.
* [Portfolio website](https://github.com/simbleau/website) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2025-11-29 - A portfolio SPA with accessibility built-in by Spencer Imbleau.
* [0721](https://github.com/langyo/0721) ⭐ 12 | 🐛 1 | 🌐 Rust | 📅 2025-02-15 - The engine of image hosting written in Rust.
* [Sumi](https://github.com/vgwidt/sumi) ⭐ 11 | 🐛 24 | 🌐 Rust | 📅 2025-06-26 - Multi-user issue tracking and knowledge base app built with Yew & Actix.
* [KeyPress](https://github.com/rayylee/keypress) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2022-10-07 - A Rust WebAssembly Website example for practising english for chinese.
* [Puzzle Cube](https://github.com/wainwrightmark/puzzle_cube) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2022-06-22 - Rubix Cube solver using Rust and Yew, [Live Demo](https://wainwrightmark.github.io/puzzle_cube/).
* [ASCII-Hangman](https://github.com/getreu/ascii-hangman) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2021-10-31 - Configurable Hangman game for children with ASCII-art rewarding.
* [demo\_web\_zip\_wasm](https://github.com/MAE664128/demo_web_zip_wasm) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2024-05-23 - A simple example program for creating ZIP archives running in the browser using WebAssembly, [Live Demo](https://mae664128.github.io/demo_web_zip_wasm/).
* [Bucket Questions](https://github.com/hgzimmerman/BucketQuestions) ⭐ 5 | 🐛 17 | 🌐 Rust | 📅 2020-08-01 - A webapp written entirely in Rust for a dumb party game.
* [Freecell](https://github.com/Stigjb/freecell) ⭐ 5 | 🐛 15 | 🌐 Rust | 📅 2023-01-20 - A patience game written in Rust and Yew.
* [dotdotyew](https://github.com/shaunbennett/dotdotyew) ⭐ 4 | 🐛 6 | 🌐 Rust | 📅 2020-10-30 - [Dot-voting](https://en.wikipedia.org/wiki/Dot-voting) using Yew, with Rust powering the backend API.
* [yew-train-ticket](https://github.com/anthhub/yew-train-ticket) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2021-06-05 - A Rust WebAssembly [Webapp](http://118.190.37.169:8002) example basing Yew newest hooks and functional API, the code style is extremely like React Function Component.
* [note-to-yew](https://github.com/oovm/note-to-yew) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2020-10-19 - Convert your markups into Yew macro online, which is also made by Yew.
* [Rquote](https://github.com/Altair-Bueno/rquote) ⭐ 3 | 🐛 3 | 🌐 Rust | 📅 2023-08-11 - Rquote is a web application built using Rust and WebAssembly. It fetches Anime quotes from the Animechan API. [Live Demo](https://rquote.vercel.app/).
* [Sea\_battle](https://github.com/MAE664128/sea_battle) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2022-07-09 - A simple example of a sea battle game. Rust + Yew.
* [yew-ssr-tide](https://github.com/zzy/yew-ssr-tide) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2022-02-22 - The example demonstrates Yew server-side rendering with tide & surf, it needs the **development version** of Yew.
* [We-Come Monorepo](https://github.com/kabinetkmitb/wecome) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2022-04-08 - This is a monorepo for wecome KM ITB, [Live Demo](https://wecome-itb.com/).
* [theiskaa.com](https://github.com/theiskaa/theiskaa.com) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-01-24 - A real world implementation of Yew framework. [Live at theiskaa.com](https://theiskaa.com).
* [viz.rs](https://github.com/viz-rs/viz-rs.github.io) ⭐ 0 | 🐛 0 | 📅 2026-02-04 - A website for viz web framework, [Live Demo](https://viz.rs/).
* [qubit](https://abhimanyu003.github.io/qubit) - A handy calculator, based on Rust and WebAssembly, [Live Demo](https://abhimanyu003.github.io/qubit/).
* [Marc Portfolio](https://gitlab.com/marcempunkt/maeurerdev) - A software developer portfolio, [Live Demo](https://maeurer.dev/).
* [PixelGuesser](https://github.com/tdooms/pixelguesser) - PixelGuesser is a real life party gam where players try to guess the contents of an image as quickly as possible.
* [mb2](https://devctm.com) - A poker server with a Yew client. Click the `Demo` button and then `Start` to see the client.
* [konnektoren.help](https://github.com/Konnektoren/konnektoren-web-game) - An interactive web application for learning German grammar, featuring gamified challenges and a map-based interface. [Web App](https://konnektoren.help)
* [layout-viewer](https://prideout.net/layout-viewer) - Examine layouts of integrated circuits with zoom and pan controls.

## Templates

* [Create Yew App](https://github.com/jetli/create-yew-app) ⭐ 167 | 🐛 3 | 🌐 Rust | 📅 2024-10-12 - Set up a modern Yew web app by running one command, `npx create-yew-app my-app`.
* [rust-yew-axum-tauri-desktop](https://github.com/jetli/rust-yew-axum-tauri-desktop) ⭐ 161 | 🐛 0 | 🌐 Rust | 📅 2025-02-17 - Rust + Yew + Axum + Tauri, full-stack Rust development for Desktop apps.
* [axum-yew-setup](https://github.com/rksm/axum-yew-setup) ⭐ 143 | 🐛 1 | 🌐 Rust | 📅 2023-09-04 - A starter project that sets up Axum and Yew for full stack Rust web apps.
* [yew-wasm-pack-template](https://github.com/yewstack/yew-wasm-pack-template) ⭐ 119 | 🐛 11 | 🌐 Rust | 📅 2022-05-26 - A template for starting a Yew project to be used with wasm-pack.
* [yew-wasm-pack-minimal](https://github.com/yewstack/yew-wasm-pack-minimal) ⭐ 113 | 🐛 4 | 🌐 Rust | 📅 2023-10-19 - A minimal template for starting a Yew project using wasm-bindgen and wasm-pack.
* [yew-parcel-template](https://github.com/spielrs/yew-parcel-template) ⭐ 110 | 🐛 8 | 🌐 Rust | 📅 2023-01-07 - Awesome Yew with Yew-Router and Parcel application.
* [Yew PWA Minimal](https://github.com/fkohlgrueber/yew-pwa-minimal) ⭐ 61 | 🐛 2 | 🌐 Rust | 📅 2023-01-11 - A minimal Progressive Web App using Yew.
* [yew-template-for-github-io](https://github.com/Ja-sonYun/yew-template-for-github-io) ⭐ 25 | 🐛 0 | 🌐 HTML | 📅 2022-04-09 - Directly deployable Template of yew project for github.io, using tailwind and webpack for css, trunk for build and serve.
* [tailwindcss-yew-template](https://github.com/vvcaw/tailwindcss-yew-template) ⭐ 17 | 🐛 0 | 🌐 Rust | 📅 2022-04-10 - Simple layout for using Tailwindcss with Yew.
* [Yew HTTP Starter](https://github.com/LeTurt333/yew_http_starter) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2022-07-17 - Yew template with a simple HTTP message & useful helper comments.
* [Yew minimlistic template](https://github.com/averichev/yew-starter-template) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2023-12-22 - A minimalistic template for quickly starting a project on yew.

## Crates

### Component Libraries

* [Yewprint](https://github.com/yewprint/yewprint) ⚠️ Archived - Port of blueprintjs.com to Yew.
* [ybc](https://github.com/thedodd/ybc) ⭐ 256 | 🐛 21 | 🌐 Rust | 📅 2024-06-30 - A Yew component library based on the Bulma CSS framework.
* [material-yew](https://github.com/hamza1311/material-yew) ⭐ 238 | 🐛 15 | 🌐 Rust | 📅 2024-04-17 - Yew wrapper for Material Web Components.
* [patternfly-yew](https://github.com/ctron/patternfly-yew) ⭐ 166 | 🐛 28 | 🌐 Rust | 📅 2026-02-04 - Patternfly components for Yew.
* [tailwind-yew-builder](https://github.com/matiu2/tailwind-yew-builder) ⭐ 75 | 🐛 3 | 🌐 Dockerfile | 📅 2022-11-30 - Builds Tailwind CSS for Yew using docker-compose. Also supports Trunk.
* [yew-chart](https://github.com/titanclass/yew-chart) ⭐ 68 | 🐛 1 | 🌐 Rust | 📅 2024-09-27 - A Yew-based charting library that provides SVG based components for rendering charts.
* [yew-components](https://github.com/angular-rust/yew-components) ⭐ 63 | 🐛 5 | 🌐 Rust | 📅 2021-07-18 - Material Design Components for the Yew framework.
* [yew-mdc](https://github.com/dungeonfog/yew-mdc) ⭐ 61 | 🐛 4 | 🌐 Rust | 📅 2022-05-10 - Material Design Components for the Yew framework.
* [yew-bootstrap](https://github.com/isosphere/yew-bootstrap) ⭐ 44 | 🐛 11 | 🌐 Rust | 📅 2026-02-08 - A Yew wrapper for the Bootstrap 5 component library.
* [muicss-yew](https://github.com/AlephAlpha/muicss-yew) ⭐ 38 | 🐛 1 | 🌐 Rust | 📅 2021-04-10 - MUI-CSS Components for Yew framework.
* [yew-bulma](https://github.com/kellpossible/yew-bulma) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2021-05-19 - A Rust library providing components based on the bulma css library for projects using Yew.
* [yew-feather](https://github.com/pedrodesu/yew-feather) ⭐ 20 | 🐛 2 | 🌐 Rust | 📅 2023-11-09 - Feather Icons components for Yew.
* [tailyew](https://github.com/fuzzycloud/tailyew) ⭐ 18 | 🐛 0 | 🌐 Rust | 📅 2024-08-14 - Yew wrapper around DaisyUI (tailwindcss based) components.
* [Zu](https://github.com/RustVis/zu) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2025-02-21 - Yew web components, implementing Material Design.
* [yew-duskmoon-ui](https://github.com/gsmlg-dev/yew-duskmoon-ui) ⭐ 6 | 🐛 1 | 🌐 Rust | 📅 2023-02-08 - Duskmoon UI Component Library. This package use `stylist` to embbed css in components, so no extra CSS file is needed. [Live Demo](https://gsmlg-dev.github.io/yew-duskmoon-ui/).
* [yew-nav-link](https://github.com/RAprogramm/yew-nav-link) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-19 - A navigational link that is aware of its active state based on the current route in the application.
* [Rust Lucide](https://lucide.rustforweb.org) - Yew port of Lucide, a beautiful & consistent icon toolkit made by the community.
* [Rust Radix](https://radix.rustforweb.org) - Yew port of Radix, a library of components, icons, colors, and templates for building high-quality, accessible UI.
* [Rust shadcn/ui](https://shadcn-ui.rustforweb.org) - Yew port of shadcn/ui, a library of beautifully designed components that you can copy and paste into your apps.

### Components

* [Yew Form](https://github.com/jfbilodeau/yew_form) ⭐ 97 | 🐛 10 | 🌐 Rust | 📅 2022-03-23 - Components to simplify handling forms with Yew.
* [yew-oauth2](https://github.com/ctron/yew-oauth2/) ⭐ 48 | 🐛 9 | 🌐 Rust | 📅 2026-01-12 - A plain Yew OAuth2/OpenIDConnect component, not tied to any CSS framework.
* [yew-component-size](https://github.com/AircastDev/yew-component-size) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2020-12-19 - A Yew component that emits events when the parent component changes width/height.
* [yew-virtual-scroller](https://github.com/AircastDev/yew-virtual-scroller) ⭐ 4 | 🐛 1 | 🌐 Rust | 📅 2020-12-19 - A Yew component for virtual scrolling / scroll windowing.
* [yew-scroll-area](https://github.com/MatchaChoco010/yew-scroll-area) ⭐ 4 | 🐛 2 | 🌐 Rust | 📅 2022-06-08 - Custom scroll area for Yew.

### Hooks

* [yew-hooks](https://github.com/jetli/yew-hooks) ⭐ 177 | 🐛 7 | 🌐 Rust | 📅 2026-02-01 - Custom Hooks library for Yew, inspired by [streamich/react-use](https://github.com/streamich/react-use) ⭐ 43,929 | 🐛 650 | 🌐 TypeScript | 📅 2026-01-20 and [alibaba/hooks](https://github.com/alibaba/hooks) ⭐ 14,909 | 🐛 266 | 🌐 TypeScript | 📅 2026-02-02.
* [Bounce](https://github.com/bounce-rs/bounce) ⭐ 100 | 🐛 17 | 🌐 Rust | 📅 2024-01-22 - The uncomplicated state management library for Yew, inspired by [Redux](https://github.com/reduxjs/redux) ⭐ 61,451 | 🐛 43 | 🌐 TypeScript | 📅 2026-02-04 and [Recoil](https://github.com/facebookexperimental/Recoil) ⚠️ Archived.
* [yewv](https://github.com/yewv/yewv) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2022-04-20 - A lightning fast state management module for Yew built with performance and simplicity as a first priority.
* [yew-side-effect](https://github.com/futursolo/yew-side-effect) ⚠️ Archived - Reconcile Side Effects in Yew Applications, inspired by [react-side-effect](https://github.com/gaearon/react-side-effect) ⭐ 1,221 | 🐛 15 | 🌐 JavaScript | 📅 2023-03-04 and [react-helmet](https://github.com/nfl/react-helmet) ⭐ 17,490 | 🐛 221 | 🌐 JavaScript | 📅 2023-07-18.

### Javascript Library Ports

* [Plotly.rs](https://github.com/igiagkiozis/plotly) ⭐ 1,399 | 🐛 10 | 🌐 Rust | 📅 2026-02-09 - Rust bindings for the popular [Plotly](https://plotly.com/javascript/) charting library.
* [ag-grid-rs](https://github.com/mfreeborn/ag-grid-rs) ⭐ 15 | 🐛 4 | 🌐 Rust | 📅 2023-03-31 - Rust bindings for the [AG Grid](https://www.ag-grid.com/javascript-data-grid/) datatable library.
* [popper-rs](https://github.com/ctron/popper-rs/) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-01-13 - [Popper JS](https://popper.js.org/) bindings for Rust.

### Utils

* [stylist-rs](https://github.com/futursolo/stylist-rs) ⭐ 379 | 🐛 22 | 🌐 Rust | 📅 2024-08-14 - A CSS-in-Rust styling solution for WebAssembly Applications.
* [Yewdux](https://github.com/intendednull/yewdux) ⭐ 328 | 🐛 9 | 🌐 Rust | 📅 2025-11-04 - Redux-like state containers for Yew apps.
* [Tailwind RS](https://github.com/oovm/tailwind-rs) ⭐ 128 | 🐛 11 | 🌐 Rust | 📅 2025-08-26 - Tailwind style tracer in rust, JIT + AOT interpreter.
* [turf](https://github.com/myFavShrimp/turf) ⭐ 97 | 🐛 3 | 🌐 Rust | 📅 2025-05-02 - Macro based compile-time SCSS transpilation, CSS minification, and class name uniquification toolchain inspired by CSS modules.
* [reacty\_yew](https://github.com/hobofan/reacty_yew) ⭐ 54 | 🐛 6 | 🌐 JavaScript | 📅 2020-11-16 - Generate Yew components from React components via Typescript type definitions.
* [yew\_icons](https://github.com/finnbear/yew_icons) ⭐ 44 | 🐛 0 | 🌐 Rust | 📅 2025-12-26 - Easily include a variety of svg icons(Feather/Font Awesome/Octicons) into your Yew app.
* [Yew-Template](https://github.com/INSAgenda/yew-template) ⭐ 44 | 🐛 8 | 🌐 Rust | 📅 2023-08-26 - A crate for separating HTML and Rust code when using Yew.
* [Yew Interop](https://github.com/Madoshakalaka/yew-interop) ⭐ 43 | 🐛 6 | 🌐 Rust | 📅 2023-03-13 - Load JavaScript and CSS asynchronously in Yew.
* [styled-yew](https://github.com/IcyDefiance/styled-yew) ⭐ 35 | 🐛 17 | 🌐 Rust | 📅 2023-01-07 - CSS in Rust, similar to styled-components, but for Yew.
* [yew-style-in-rs](https://github.com/MatchaChoco010/yew-style-in-rs) ⭐ 23 | 🐛 1 | 🌐 Rust | 📅 2022-06-04 - Scoped CSS in Rust for Yew.
* [yew-nested-router](https://github.com/ctron/yew-nested-router) ⭐ 9 | 🐛 3 | 🌐 Rust | 📅 2025-12-16 - A router that supported nesting, with Yew 0.20.
* [browser-panic-hook](https://github.com/ctron/browser-panic-hook) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2023-06-02 - A panic handler for browser environments, allowing to fail in an end-user friendly way.
* [Rust Floating UI](https://floating-ui.rustforweb.org/) - Floating UI is a library that helps you create "floating" elements such as tooltips, popovers, dropdowns, and more.

### Wasm

* [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen) ⭐ 8,844 | 🐛 546 | 🌐 Rust | 📅 2026-02-09 - Facilitating high-level interactions between WebAssembly modules and JavaScript.
* [stdweb](https://github.com/koute/stdweb) ⭐ 3,460 | 🐛 135 | 🌐 Rust | 📅 2024-02-28 - Provides Rust bindings to the Web APIs and to allow a high degree of interoperability between Rust and JavaScript.
* [tauri-sys](https://github.com/JonasKruckenberg/tauri-sys) ⭐ 121 | 🐛 22 | 🌐 Rust | 📅 2025-12-10 - Raw bindings to the Tauri API for projects using wasm-bindgen.

### Frameworks

* [stackable](https://github.com/futursolo/stackable) ⭐ 23 | 🐛 16 | 🌐 Rust | 📅 2023-12-01 - A framework experience for Yew.

## Tooling

* [Tauri](https://github.com/tauri-apps/tauri) ⭐ 102,458 | 🐛 1,346 | 🌐 Rust | 📅 2026-02-08 - Tauri is a framework for building tiny, blazingly fast binaries for all major desktop platforms. Developers can integrate any front-end framework that compiles to HTML, JS and CSS for building their user interface. The backend of the application is a rust-sourced binary with an API that the front-end can interact with.
* [binaryen](https://github.com/WebAssembly/binaryen) ⭐ 8,328 | 🐛 510 | 🌐 WebAssembly | 📅 2026-02-08 - Compiler infrastructure and toolchain library for WebAssembly, for the `wasm-opt` tool to reduce .wasm file size.
* [wabt](https://github.com/WebAssembly/wabt) ⭐ 7,849 | 🐛 205 | 🌐 C++ | 📅 2026-01-21 - The WebAssembly Binary Toolkit, for the `wasm-strip` and `wasm-objdump` tools to reduce .wasm file size.
* [wasm-pack](https://github.com/rustwasm/wasm-pack) ⭐ 7,077 | 🐛 389 | 🌐 Rust | 📅 2026-02-05 - Your favorite Rust -> WebAssembly workflow tool.
* [Trunk](https://github.com/thedodd/trunk) ⭐ 4,149 | 🐛 129 | 🌐 Rust | 📅 2026-02-02 - Build, bundle & ship your Rust Wasm application to the web.
* [cargo-web](https://github.com/koute/cargo-web) ⭐ 1,114 | 🐛 107 | 🌐 Rust | 📅 2023-11-29 - A Cargo subcommand for the client-side Web.
* [wasm-pack-action](https://github.com/jetli/wasm-pack-action) ⭐ 56 | 🐛 19 | 🌐 TypeScript | 📅 2023-03-03 - Github action to install `wasm-pack` by downloading the executable to speed up CI/CD.
* [trunk-action](https://github.com/jetli/trunk-action) ⭐ 36 | 🐛 1 | 🌐 TypeScript | 📅 2025-07-18 - Github action to install `Trunk` by downloading the executable to speed up CI/CD.
* [yew-fmt](https://github.com/schvv31n/yew-fmt) ⭐ 27 | 🐛 2 | 🌐 Rust | 📅 2025-07-16 - A configurable extension to `rustfmt` for formatting Yew HTML.
* [wasm-bindgen-action](https://github.com/jetli/wasm-bindgen-action) ⭐ 12 | 🐛 23 | 🌐 TypeScript | 📅 2023-03-03 - Github action to install `wasm-bindgen` by downloading the executable to speed up CI/CD.

## Articles

* [How to use Rust Yew](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20Rust%20Yew.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to use a modal in Rust](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20a%20modal%20in%20Rust.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to use routers in Rust Frontend](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20routers%20in%20Rust%20Frontend.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to modulize your Rust Frontend](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20modulize%20your%20Rust%20Frontend.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to use NPM packages with Rust Frontend](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20NPM%20packages%20with%20Rust%20Frontend.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to use markdown with Rust Frontend](https://github.com/steadylearner/blog/blob/master/posts/Rust/How%20to%20use%20markdown%20with%20code%20snippets%20in%20Rust%20Frontend.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [Fullstack Rust with Yew](https://github.com/steadylearner/blog/tree/master/posts/Rust/Fullstack%20Rust%20with%20Yew.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to write Full Stack Rust code](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20write%20Full%20Stack%20Rust%20code.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to render a YouTube vlog with Rust Yew fetch API](https://github.com/steadylearner/blog/blob/master/posts/Rust/How%20to%20render%20a%20YouTube%20vlog%20with%20%20Rust%20Yew%20fetch%20API.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [How to render blog posts with Rust Yew mounted API](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20render%20blog%20posts%20with%20Rust%20Yew%20mounted%20API.md) ⭐ 4 | 🐛 1 | 📅 2021-05-19
* [Let's Build a Rust Frontend with Yew](https://dev.to/deciduously/lets-build-a-rust-frontend-with-yew---part-1-3k2o)
* [A Web Application completely in Rust](https://medium.com/@saschagrunert/a-web-application-completely-in-rust-6f6bdb6c4471)
* [Yew - Rust & WebAsse-frontend framework](https://sudonull.com/post/11627-Yew-Rust-WebAsse-frontend-framework)
* [Create a desktop app in Rust using Tauri and Yew](https://dev.to/stevepryde/create-a-desktop-app-in-rust-using-tauri-and-yew-2bhe)
* [A code walkthrough video of Yew with a real-world app with Christopher Hunt and Kiki Carter](https://www.youtube.com/watch?v=ilrGIJGdqRo)
* [Adding Tailwind to Yew](https://mikekrisher.com/writings/yew_and_tailwind)

## Courses

* [full-stack-todo-rust-course](https://github.com/brooks-builds/full-stack-todo-rust-course) ⭐ 259 | 🐛 6 | 🌐 Rust | 📅 2024-08-26 - Full stack rust course including course for Yew.

## Books

* [The WebAssembly Book](https://rustwasm.github.io/docs/book/) - Working with the web and producing .wasm files.
* [The wasm-bindgen Guide](https://rustwasm.github.io/docs/wasm-bindgen/) - How to bind Rust and JavaScript APIs.
* [The wasm-pack Guide](https://rustwasm.github.io/docs/wasm-pack/) - How to build and work with rust-generated WebAssembly.
* [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) - Includes a chapter `Advanced JavaScript Integration with Yew` on creating an app with Yew.
* [Creative Projects for Rust Programmers](https://www.oreilly.com/library/view/creative-projects-for/9781789346220/) - Chapter 5, `Creating a Client-Side WebAssembly App Using Yew`.
* [Server-Side WebAssembly](https://www.manning.com/books/server-side-webassembly) - How to use WebAssembly components and the WebAssembly System Interface (WASI) to build web back ends.

## Alternatives

Yew team love to share ideas with other projects and believe we can all help each other reach the full potential of this exciting new technology.

* [Dioxus](https://github.com/DioxusLabs/dioxus) ⭐ 34,613 | 🐛 638 | 🌐 Rust | 📅 2026-02-07 - Elegant React-like library for building user interfaces for desktop, web, mobile, SSR, liveview, and more.
* [Leptos](https://github.com/leptos-rs/leptos) ⭐ 19,941 | 🐛 138 | 🌐 Rust | 📅 2026-02-08 - Build fast web applications with Rust.
* [Seed](https://github.com/seed-rs/seed) ⭐ 3,839 | 🐛 55 | 🌐 Rust | 📅 2025-01-11 - A Rust framework for creating web apps.
* [Sycamore](https://github.com/sycamore-rs/sycamore) ⭐ 3,201 | 🐛 33 | 🌐 Rust | 📅 2025-12-02 - A reactive library for creating web apps in Rust and WebAssembly.
* [Percy](https://github.com/chinedufn/percy) ⭐ 2,307 | 🐛 43 | 🌐 Rust | 📅 2025-12-15 - A modular toolkit for building isomorphic web apps with Rust + WebAssembly.
* [Sauron](https://github.com/ivanceras/sauron) ⭐ 2,060 | 🐛 7 | 🌐 Rust | 📅 2025-01-27 - Sauron is an HTML web framework for building web-apps.
* [Smithy](https://github.com/rbalicki2/smithy) ⭐ 347 | 🐛 7 | 🌐 Rust | 📅 2020-02-20 - A framework for building WebAssembly apps in Rust.
* [Draco](https://github.com/utkarshkukreti/draco) ⭐ 304 | 🐛 16 | 🌐 Rust | 📅 2023-04-03 - A Rust library for building client side web applications with WebAssembly.

## Related lists

* [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) ⭐ 55,514 | 🐛 11 | 🌐 Rust | 📅 2026-02-08 - A curated list of Rust code and resources.
* [Awesome WebAssembly](https://github.com/mbasso/awesome-wasm) ⭐ 9,475 | 🐛 46 | 📅 2024-11-15 - Collection of awesome things regarding WebAssembly ecosystem.
* [Awesome Rust and WebAssembly](https://github.com/rustwasm/awesome-rust-and-webassembly) ⚠️ Archived - A list of awesome Rust and WebAssembly projects, libraries, tools, and resources.
