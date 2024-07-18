The documentation is generated in a `_build_docs` directory. To view, open `index.html`.


For Self-Hosters
================

Adventurer's Codex is fully open source, and can be self-hosted by anyone. If you're looking to start up your own Adventurer's Codex setup, then follow the instructions below.

## Installation

The first thing you'll need to do to get started with Adventurer's Codex is install it on a server, or run it locally. To do this, you'll need to clone the repo.

```bash
$ git clone https://github.com/adventurerscodex/charactersheet.git
$ cd charactersheet
$ npm install
```

## Hosting

If you're hosting Adventurer's Codex locally, then you can serve the charactersheet folder like so:

```bash
$ npm run start
```

If you're hosting Adventurer's Codex on a server, then you can serve the charactersheet folder like so:

```bash
$ npm run build
```

Since Adventurer's Codex is an entirely client-side application, there's no need for anything more complicated than static file hosting. Simply extract the `charactersheet` directory to your `static/` files directory in Apache, Nginx, S3, etc and load up the page!
