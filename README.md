# ChatDeathRoll

Provides roll buttons in chat for death rolling and display results.

This is a fork of the original [ChatDeathRoll](https://github.com/anya-hichu/ChatDeathRoll) plugin.

Install it by adding this custom repository URL to Dalamud:

`https://raw.githubusercontent.com/NeoGriever/ChatDeathRoll2/master/repo.json`

## Changes

The collapsed **Settings** section adds an optional replacement exclusion for active plugin windows whose titles match a regular expression.

- **Enabled** turns the exclusion check on or off.
- **Window title regular expression** matches titles of currently active IMGui plugin windows. Empty values and expressions shorter than three characters disable detection. The default is `^SimpleBlackjack \d+.*$`.
- **/random** selects whether matching windows suppress `/random` replacements. Disabled by default.
- **/dice** selects whether matching windows suppress `/dice` replacements. Enabled by default.

## Commands

- `/chatdeathroll config`
- `/chatdeathroll enable`
- `/chatdeathroll disable`
