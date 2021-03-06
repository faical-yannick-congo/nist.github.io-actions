# NIST Software Portal - Automatic Updates

This repository runs regular data updates for the [NIST Software Portal](https://software.nist.gov/).

These updates utilize scripts from the [faical-yannick-congo/nist.github.io](https://github.com/faical-yannick-congo/nist.github.io) repository.
The new data is pushed back to the same repository.

[![Current Schedule][schedule img]][schedule url]
[![Last Update][timestamp img]][timestamp url]

[schedule img]: https://img.shields.io/badge/schedule-daily%20%40%2008%3A05%20UTC-informational?style=for-the-badge
[schedule url]: https://github.com/faical-yannick-congo/nist.github.io-actions/blob/master/.github/workflows/main.yml "faical-yannick-congo/nist.github.io-actions/.github/workflows/main.yml"

[timestamp img]: https://img.shields.io/badge/dynamic/json?color=informational&label=last%20update&query=%24%5B0%5D.commit.author.date&url=https%3A%2F%2Fapi.github.com%2Frepos%2Ffaical-yannick-congo%2Fnist.github.io%2Fcommits%3Fpath%3D_explore%2FLAST_MASTER_UPDATE.txt%26per_page%3D1&style=for-the-badge
[timestamp url]: https://github.com/faical-yannick-congo/nist.github.io/blob/master/_explore/LAST_MASTER_UPDATE.txt "faical-yannick-congo/nist.github.io/.../LAST_MASTER_UPDATE.txt"
