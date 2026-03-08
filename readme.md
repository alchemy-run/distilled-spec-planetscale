# distilled-spec-planetscale

A git mirror of PlanetScale's [OpenAPI spec](https://api.planetscale.com/v1/openapi-spec). The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Usage as a submodule

```sh
git submodule add https://github.com/alchemy-run/distilled-spec-planetscale.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
