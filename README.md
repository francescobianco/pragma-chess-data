<p align="center">
  <a href="https://yafb.net/pragma-chess/">
    <img src="https://yafb.net/pragma-chess/assets/logo.png" alt="Pragma Chess" width="96">
  </a>
</p>

<h1 align="center">pragma-chess-data</h1>

<p align="center">
  <em>My chess, kept in step across every computer I play on.</em>
</p>

This repository is my personal **Pragma folder**: the games, databases,
projects and opening books I work with in
[Pragma Chess](https://yafb.net/pragma-chess/), the open source chess
database for studying, training and playing.

I don't edit these files by hand. Pragma Chess writes them, and its
**folder sync** keeps this repository and every computer I use the same:
games added on the laptop are on the desktop at the next sync, and an
opening book tuned at home is there at the club. Each commit is one real
change, named after the files it touches
(`Update Databases/allenamento.pdb; update Projects/scacchi1.pch`).

## What's inside

| Path | What it is |
| --- | --- |
| `Databases/*.pdb` | Databases of games: SQLite files with every game, its moves, variations and annotations. Some fill themselves from lichess.org, chess.com or tournament sites. |
| `Projects/*.pch` | Projects (YAML): the database, game, position, engine and panel layout I was looking at, so a study opens again exactly as I left it. |
| `Books/*.bin` | Opening books in the Polyglot format, with my repertoire and the weights I gave the moves. |
| `Books/Opening Names/` | The names of the openings, in English and Italian. |
| `.pragma-chess.conf` | Who I am (YAML): the name that goes on my side of new games. |
| `.pragma-chess.sync` | The sync manifest: each file with its hash, the device that changed it last, and what was merged or deleted. |

A database changed on two computers at once is never overwritten: Pragma
Chess merges the two copies game by game, so nothing played anywhere is
lost.

## Keep your own chess like this

Every game you play, study or import, in one place, on every computer you
own — and a Git history of it, if you like.

1. **[Download Pragma Chess](https://yafb.net/pragma-chess/)**: free, MIT
   licensed, for Windows, macOS and Linux.
2. Create an empty repository (it can be private).
3. In Pragma Chess, open **Options ▸ Sync Settings…**, set **Service** to
   **Git repository**, paste its address in **Repository** and press
   **Sync Now**.

FTP and WebDAV servers work too.

<p align="center">
  <a href="https://yafb.net/pragma-chess/">
    <img src="https://yafb.net/pragma-chess/assets/screenshots/hero.png" alt="Pragma Chess explaining why 14.Rd1 wins Morphy's Opera game" width="720">
  </a>
</p>

<h3 align="center">
  <a href="https://yafb.net/pragma-chess/">♞ Get Pragma Chess →</a>
</h3>

<p align="center">
  <a href="https://yafb.net/pragma-chess/">Website</a> ·
  <a href="https://github.com/francescobianco/pragma-chess">Source code</a> ·
  <a href="https://github.com/francescobianco/pragma-chess/releases/latest">Latest release</a>
</p>
