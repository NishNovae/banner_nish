# banner_nish
```
    _   ___      __
   / | / (_)____/ /_
  /  |/ / / ___/ __ \
 / /|  / (__  ) / / /
/_/ |_/_/____/_/ /_/
```
## Introduction
Current latest release: v1.1.0 (2024. 07. 16)

Nothing special; a practice on publishing python packages.

## Installation
```
$ pip install banner-nish
```
Make sure you have the minimum python version to run it, which is `3.9`.

## Usages
As of `v1.3.0`, banner_nish has three functionalities which can be executed directly from the command line.

- The `nish-banner` command prints out a slanted ASCII-based banner that says my nickname, Nish. This functionality is implemented via its dependency `pyfiglet`.

- The `show-pic` command prints out a pre-selected ASCII art image of a tiger.

- The `nish-lottery` is a random number generator of six numbers, in the range between 1 and 46.

An example execution looks like this:
```
$ nish-banner

    _   ___      __
   / | / (_)____/ /_
  /  |/ / / ___/ __ \
 / /|  / (__  ) / / /
/_/ |_/_/____/_/ /_/

```

```
$ show-pic

```

```
$ nish-lottery

```
