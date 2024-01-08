# Blue Heart Industries website

https://blueheartindustries.ddns.net

Welcome!

If you wish to contribute to the website's content, all the pages are located in the ["docs" directory](./docs)

If you're not sure how to use github, that's fine! Just copy-paste some of the content you'd like to see edited and reach out to Nofed Moped / inbouto on discord.





This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

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
