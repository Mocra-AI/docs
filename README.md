# Mocra documentation

This repository contains the source for [Mocra](https://mocra.io) product documentation: quickstart, API reference, and development setup. The site is built and hosted with [Mintlify](https://mintlify.com).

## Previewing locally

1. Install the Mintlify CLI: `npm i -g mint`
2. Clone this repo and from its root (where `docs.json` is), run: `mint dev`
3. Open `http://localhost:3000` to view the docs.

Changes to `.mdx` and OpenAPI files will hot-reload.

## Publishing

The live site is updated automatically when changes are pushed to the default branch. The Mintlify GitHub app must be installed for the organization/repo; configure it in the [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app).

## Troubleshooting

- **Local preview won’t start or looks wrong:** Run `mint update` to use the latest CLI.
- **404s on every page:** Ensure you’re in the repo root that contains `docs.json`.

## More

- For the full Development guide (custom ports, link checking, editing tips), open the docs locally or on the published site and go to **Development**.
- [Mintlify docs](https://mintlify.com/docs) for the platform itself.
