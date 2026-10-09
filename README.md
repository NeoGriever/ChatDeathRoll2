# ChatDeathRoll

Provides roll buttons in chat for death rolling and display results.

Installable using my custom repository (instructions here: https://github.com/anya-hichu/DalamudPluginRepo) or from compiled archives.

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
