# Changelog

## Unreleased

## v0.2.0

- BREAKING CHANGE: bump python version requirement to 3.10.
- Add map list parsing.
- Add py.typed.
- BREAKING CHANGE: move all command for click into their own files.
  Move public API functions to `__init__.py`.

## v0.1.1

- Show percentage of winrate changed instead of the amount when `compare` command
  is used.
- Add `focus` command that shows only win rate related to the bot of interest.
- Add `focus-compare` command that is similar to the `focus` command but also
  allow comparision between two map folders.

## v0.1.0

- Shorten the bot's name in the column as well when `--full` is not supplied.
- Rename the repository to a shorter name.
- Add `format` option with choices of `github` or `latex`.
- Add `view` command.
- Add `compare` command.

## v0.0.1

- Initial version.