# Overview

- [How to build…](#how-to-build)
    + [... animations in React](#-animations-in-React)
    + [... code highlighting in React](#-code-highlighting-in-React)
    + [... desktop apps that needs access to native APIs](#-desktop-apps-that-needs-access-to-native-apis)

# How to build…

### ... animations in React

Spring physics are great for adding natural motion to your apps. 
- For granular control over animations and plug-and-play compatibility with [react-three-fiber](https://github.com/pmndrs/react-three-fiber), use [react-spring](https://react-spring.io).
- If you're aiming for advanced animations like Shared Element Transitions, have a look at [framer-motion](https://www.framer.com/motion/).
- Both libraries can be used for adding page transitions: 
    - [Page transitions with react-spring](https://codesandbox.io/s/react-spring-v9-page-transition-forked-k3kou) 
    - [Page transitions with framer-motion](https://dev.to/joserfelix/page-transitions-in-react-1c8g)

### ... code highlighting in React

[react-syntax-highlighter](https://github.com/react-syntax-highlighter/react-syntax-highlighter) is an easy way to add code highlighting to any React app. It uses [highlight.js](https://github.com/highlightjs/highlight.js) or [Prism](https://github.com/PrismJS/prism) under the hood, whichever you prefer. It doesn't require any global CSS but instead relies on JS-based styling.
If you're looking for more fine-grained control over the rendering, you can check out [prism-react-renderer](https://github.com/FormidableLabs/prism-react-renderer).

### ... desktop apps that needs access to native APIs

**Electron** bundles Node.js and Chrome into a native cross-platform app. The user interface can be developed using web technologies like React and native APIs can be used via Node.js. If you want to build apps with a smaller footprint, check out [Tauri](https://github.com/tauri-apps/tauri).

Quick Links for Electron:
- [GitHub - electron-react-boilerplate: A Foundation for Scalable Cross-Platform Apps](https://github.com/electron-react-boilerplate/electron-react-boilerplate)
- [GitHub - awesome-electron: Useful resources for creating apps with Electron](https://github.com/sindresorhus/awesome-electron)
- [GitHub - electron-builder: A complete solution to package and build a ready for distribution Electron app with “auto update” support out of the box](https://github.com/electron-userland/electron-builder)
- [Communication between the UI and Node.js process](https://www.electronjs.org/docs/api/ipc-main#ipcmain)
