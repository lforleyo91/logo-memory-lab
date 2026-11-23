# Logo Memory Lab — The Designer's Edition

A live QR-join Mandela Effect icebreaker for designers.

## Included
- 15 rounds covering Figma, DBS, POSB, Old Chang Kee, SMRT, Apple, Claude, Pikachu, Monopoly, Starbucks, KFC, Looney Tunes, KitKat, Fruit of the Loom and Froot Loops.
- Host/projector screen with QR join code and live vote counts.
- Player phone view; display name only, no account required.
- Host-controlled answer reveal, explanations, scoring and leaderboard.

## Run locally
Requires Node.js 18 or newer.

```sh
npm install
npm start
```

Open http://localhost:3000. Players join at `/?mode=play&room=LAB26`.

## Deploy on Render
Create a Node Web Service connected to this repository. Build command: `npm install`; start command: `npm start`. A free instance may spin down while idle. Open the host page early before the event. Room state and scores are held in memory, so keep the service running during play.

## Quiz artwork
The options use simplified symbolic illustrations rather than full official logo artwork, to avoid giving away the answers with background logo collages. Some rounds are well-known Mandela Effect examples; others test logo-detail recognition.
