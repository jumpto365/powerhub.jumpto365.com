# PowerHub

[MATT]: Intro

Ever wondered on how to share your power with your friends? Well, now you can! With PowerHub, you can share your power with your friends, and they can share their power with you! It's a win-win situation!

Use PowerHub for inspiration and governance of your Power* solutions.

By keeping an eye on new solutions as they get created you get a hook into the eco system of your company. Use the simple rate system for governance, e.g. apps that have been shared with anyone, or haven't been modified for a year scores low,  them based on if they are shared with a few or all. 


PowerHub is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

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
