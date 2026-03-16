# Cambridge Battlecode — Docs

Documentation for the [Cambridge Battlecode](https://battlecode.cam) programming competition.

Built with [Mintlify](https://mintlify.com) and deployed to [docs.battlecode.cam](https://docs.battlecode.cam).

## Structure

```
getting-started/   Installation, first bot, running matches, submitting
spec/              Full game rules — units, buildings, turrets, resources
api/               Controller methods, types/enums, game constants
```

## Development

```bash
npm i -g mint
mint dev
```

Preview at `http://localhost:3000`.

## Deployment

Pushes to `main` auto-deploy via the Mintlify GitHub app.
