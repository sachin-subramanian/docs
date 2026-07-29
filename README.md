# Sweetspot Documentation

Source for the Sweetspot user documentation, published at [docs.sweetspotgov.com](https://docs.sweetspotgov.com) via Mintlify.

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview changes locally:

```
npm i -g mint
```

Run the following command at the root of the repo (where `docs.json` is):

```
mint dev
```

### Publishing Changes

Changes merged to `main` deploy to production automatically through the Mintlify GitHub app.

#### Troubleshooting

- `mint dev` isn't running: run `mint update` to get the latest CLI version.
- Page loads as a 404: make sure you are running in the folder with `docs.json`.
