# Full stack template for your your projects

> Quickly bootstrap a new project with this template.

This template contains all the tools you need to build a modern web app with TypeScript, React, Vite, Storybook and Express.

You can use it to quickly bootstrap your project.

ESLint, stylelint, prettier, husky and lintstaged are configured to give you a solid development environment.

## Installing / Developing

First, create a repository from this template.

Now you are ready to go:

```shell
npm install
```

This will install the dependencies required to run the template.

```shell
npm run dev
```

These scripts run your server, client and storybook in development mode.

The default PORTS are:

- `3001` for the server
- `3000` for the client
- `6006` for the storybook

If you don't like to call all scripts at once, you can also run:

```shell
npm run server:dev
npm run client:dev
npm run storybook
```

## Building

To build the project, run:

```shell
npm run build
```

This will build the client, server and storybook.

```shell
npm start
```

In production, you have a single server serving everything.

`/api/*` is the API endpoint.  
`/storybook` is the Storybook.  
`/*` is the client.

## Tests

A test runner is not installed (right now). But TypeScript, linter and prettier are checked on commit and push thanks to husky and lintstaged.

## Licensing

MIT
