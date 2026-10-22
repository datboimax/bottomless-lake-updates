# Bottomless Lake

## Download (Windows)

**[Download the installer: Bottomless-Lake-Setup.exe](https://github.com/datboimax/bottomless-lake-updates/raw/download/Bottomless-Lake-Setup.exe)**

Double-click it and follow the steps. If Windows says "Windows protected your PC", click
**More info**, then **Run anyway** (the game isn't signed yet). Your save comes along, and
from then on the game keeps itself up to date.

## How updates work

- **0.34 and newer:** the game reads `update.json` on the
  [`folder`](https://github.com/datboimax/bottomless-lake-updates/tree/folder) branch, downloads
  the signed game zip, checks its signature and plays it.
- **Up to 0.33:** the older app reads `latest.json` here and plays that single game file.

Only built game files live here (no source code).
