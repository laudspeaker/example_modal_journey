# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.


### Using Laudspeaker

To use this app with laudspeaker you will need to update the app with your laudspeaker api key.

Go to `index.js` under `src/components/HomepageFeatures/` and update the api key there

Then go to the journey builder in Laudspeaker and create the journey you want. After starting the webapp and the journey the modal should appear.
