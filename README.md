# xdP Wiki

[![Crowdin](https://badges.crowdin.net/cca-wiki/localized.svg)](https://crowdin.com/project/cca-wiki)

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ npm install
```

### Local Development

```
§ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true npm run deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.


### OpenSource

xdP Wiki was built using Jetbrain's WebStorm IDEA. I am thanful that Jetbrains gave us an [open source license](https://www.jetbrains.com/community/opensource/#support) (Click on that to learn more)