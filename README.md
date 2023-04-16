# :oncoming_automobile: Road route

Repository *will* contain Cloudflare Worker written in Rust to get route and related to the route data needed for a car trip.

## Use-case

::: mermaid
graph LR;
    User --> id1["Cloudflare"] --> Worker --> id2[(D1)] & RapidApi?;
:::

## Usage

This template starts you off with a `src/lib.rs` file, acting as an entrypoint for requests hitting your Worker. Feel free to add more code in this file, or create Rust modules anywhere else for this project to use.

With `wrangler`, you can build, test, and deploy your Worker with the following commands:

```sh
# run your Worker in an ideal development workflow (with a local server, file watcher & more)
$ npm run dev

# deploy your Worker globally to the Cloudflare network (update your wrangler.toml file for configuration)
$ npm run deploy
```

Read the latest `worker` crate documentation here: https://docs.rs/worker

