# templar-arena-bin

AUR package for [Templar Arena](https://magic-squirrel-games.itch.io/templar-arena-pre-release-v01) — a 90s-inspired free-to-play multiplayer arena shooter set in a dark fantasy world, made by [Magic Squirrel Games](https://magic-squirrel-games.itch.io/).

> ⚠️ This is an unofficial AUR package. The game itself is developed and owned by Magic Squirrel Games.

---

## Installation

### Via AUR helper (recommended)
```bash
yay -S templar-arena-bin
```

### Manually
```bash
git clone https://aur.archlinux.org/templar-arena-bin.git
cd templar-arena-bin
makepkg -si
```

---

## Running

After installation, launch from your application menu or run:
```bash
templar-arena
```

---

## Package Details

| Field       | Value                        |
|-------------|------------------------------|
| Package     | `templar-arena-bin`          |
| Version     | `0.1.2`                      |
| Arch        | `x86_64`                     |
| Install dir | `/opt/templar-arena/`        |
| AUR page    | https://aur.archlinux.org/packages/templar-arena-bin |

---

## About the Game

Templar Arena is currently in early development (started March 2026). Features so far:

- 3 weapons, 2 maps
- Unity Relay-based multiplayer (host & share join code)
- Bunny hopping & strafe mechanics
- Dark fantasy setting

Follow development updates on the [itch.io page](https://magic-squirrel-games.itch.io/templar-arena-pre-release-v01) or on the developer's [YouTube channel](https://www.youtube.com/@magicsquirrelgames).

---

## Updating

When a new version is released:

1. Update the zip in the GitHub release
2. Bump `pkgver` in `PKGBUILD`
3. Regenerate `.SRCINFO`:
   ```bash
   makepkg --printsrcinfo > .SRCINFO
   ```
4. Commit and push:
   ```bash
   git add .
   git commit -m "update to vX.X.X"
   git push
   ```

---

## Maintainer

- **taxin** — [AUR profile](https://aur.archlinux.org/account/taxin)
