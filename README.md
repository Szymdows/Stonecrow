# Stonecrow

An independent chess engine with its own playable interface, made by Szymdows.

Stonecrow is a chess engine: a program that looks at a position and decides which move to play. It comes with a desktop interface, so you can play against it straight away, watch it play itself, or test it against Stockfish. It runs entirely on your computer and does not need an internet connection.

Stonecrow started as a passion project. I wanted to learn how chess engines actually work, and I wanted to build one myself, partly for the challenge and partly just for fun. The longer-term goal is to see how far I can take it and end up with a genuinely strong engine.

## Features

- Drag and drop moves
- Hints that show your legal moves
- A picker for promotions
- A move list in standard algebraic notation (SAN)
- A panel showing captured pieces
- Games saved locally in a PGN-style format

## Game modes

- **Human vs Stonecrow:** you play against the engine.
- **Stonecrow vs Stonecrow:** let it play itself and watch.
- **Stonecrow vs Stockfish:** test it against Stockfish. This mode is optional and needs Stockfish installed.

## Getting started

1. Download the Windows zip from the [Stonecrow page](https://szymdows.com/stonecrow.html#download) or directly from github releases.
2. Extract the zip.
3. Launch Stonecrow and pick a game mode.

Stonecrow runs without Stockfish. You only need it for the Stonecrow vs Stockfish mode, and you can get it from [stockfishchess.org](https://stockfishchess.org/download/).

## Saved games

Your games are saved locally in the `data\games\` folder, in a PGN-style format. Stonecrow does not have built-in game review yet, so to go over a game, open it in Lichess, chess.com or a desktop chess program.

## Help improve Stonecrow

- **Submit your games.** Games from the `data\games\` folder can be used to train Stonecrow so that it keeps getting better over time: [submit games](https://docs.google.com/forms/d/e/1FAIpQLSeYguzAa6EgOWi05odENTyRVz19yGC4bnDxAW0HGZoOGwVadw/viewform?usp=publish-editor)
- **Send feedback.** Bug reports, ideas and things that felt wrong are all useful: [submit feedback](https://docs.google.com/forms/d/e/1FAIpQLSffq8KGssHZuPJVFegXlj18GZLJP0mhb8HlPreWfA4FbiL4ng/viewform?usp=publish-editor)

## Planned

- Game review inside the app
- More training tools over time
- A stronger engine

## About

Stonecrow is its own engine. It is not a wrapper around Stockfish or any other engine. It is not open source.

Made by [Szymdows](https://szymdows.com).
