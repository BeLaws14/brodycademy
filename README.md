# brodycademy

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator, and are deployed onto GitHub Pages.

:::hint[Tip]
It has a ton of cool features like support for [rendering math equations](https://docusaurus.io/docs/markdown-features/math-equations) using just markdown, which would make for some really convenient math notes.
:::

### Installation

```
$ npm i
```

### Local Development

```
$ npm run start
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
