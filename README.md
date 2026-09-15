# discord-addons

Public stable releases of Discord plugins, themes, and other add-ons for supported mobile and desktop clients.

## Repository roles

| Repository | Visibility | Purpose |
| --- | --- | --- |
| [discord-addons](https://github.com/ItsTripleSix/discord-addons) | Public | Stable releases for supported Discord clients |
| [discord-addons-staging](https://github.com/ItsTripleSix/discord-addons-staging) | Public | Testing, release candidates, and publicly fetchable builds |
| discord-addons-workbench | Private | Development source, experiments, tests, and migration work |
| [ShiggyCord](https://github.com/ItsTripleSix/ShiggyCord) | Public | The ShiggyCord client fork |

## Layout and current installs

Client-specific copies live under clients/. Existing plugin and theme paths remain available for installed clients. [Migration and compatibility notes](docs/repository-migration.md) explain the paths, maintenance command, and known pre-existing packaging issues.

These repositories can hold add-ons for supported mobile or desktop Discord clients; check each add-on's actual client requirements. No ShiggyCord build is promoted to stable by this reorganization.

## Revenge Classic plugins

The current stable collection targets Revenge Classic. Three pre-existing manifest entry points need repair; see the migration notes before a new installation.


### Account Switcher

Restores Discord's native mobile multi-account switcher and uses Discord's own saved-account state. It does not store, export, or handle account tokens itself.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/account-switcher/
```

### Silent Typing

Adds a configurable silent-typing toggle to the message composer so you can type without sending Discord's typing event.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/silent-typing/
```

### Composer Cleaner

Lets you hide selected native composer buttons such as attachments, gifts, emoji, voice messages, apps/commands, and new-thread controls.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/composer-cleaner/
```

### Purge Tools

Bulk cleanup for your messages and your own reactions across selected DMs, channels, and servers, with per-target filters, preview/discovery, checkpoints, resume support, and rate-limit-aware pacing.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/purge-tools/
```

### Hidden Channels

Shows channel metadata for channels Discord still sends to the client even when your account lacks `VIEW_CHANNEL`, while blocking message loading for inaccessible channels.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/hidden-channels/
```

### Quick Mock

Adds fast alternating-case mock text through long-press and `/mock` workflows.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/quick-mock/
```

### Theme Toolkit

Current stable release: **v2.2.1**. Create, edit, save, switch, preview, export, and share themes with additional color, icon, folder, mention, and avatar controls.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/plugins/theme-toolkit/
```

## Themes

### AMOLED Monochrome

Pure-black OLED theme with white and gray UI accents.

```text
https://raw.githubusercontent.com/ItsTripleSix/discord-addons/main/themes/amoled-monochrome.json
```

## Compatibility

These plugins and themes target Revenge Classic's Vendetta-compatible loader. Discord updates can change internal modules and occasionally require fixes.

## License

MIT
