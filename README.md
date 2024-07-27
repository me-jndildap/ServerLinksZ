![banner](https://cdn.modrinth.com/data/cached_images/b1a659a750a37515bf4c4c767ccdfe9a7c3fe038.png)

![paper](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact/supported/paper_vector.svg)
![purpur](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact/supported/purpur_vector.svg)
[![github](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact/available/github_vector.svg)](https://github.com/KartoffelChipss/ServerLinksZ)
[![modrinth](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact/available/modrinth_vector.svg)](https://modrinth.com/plugin/serverlinksz)
[![discord-plural](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact/social/discord-plural_vector.svg)](https://strassburger.org/discord)

ServerLinksZ is a simple plugin, that allows you to add Links to the "Server Links" page in the pause menu. ServerLinksZ also adds a command for users to quickly look up links like /discord.

## Features
- ✅ Custom links
- ✅ Colored link Names
- ✅ HEX Colors
- ✅ Link commands (e.g. `/dsicord`, `/website`)
- ✅ Highly customizable
- ✅ Easy setup
- ✅ Multiple languages

## Permissions

- **serverlinksz.manage** - Allows a user to manage links (default: op)
- **serverlinksz.admin** - Allows a user to do admin tasks (default: op)

## Config

Here is an example of the configuration file:
<details>
<summary>Click me!</summary>

```yml
#     _____                            _      _       _          ______
#    / ____|                          | |    (_)     | |        |___  /
#   | (___   ___ _ ____   _____ _ __  | |     _ _ __ | | _____     / /
#   \___ \ / _ \ '__\ \ / / _ \ '__| | |    | | '_ \| |/ / __|   / /
#   ____) |  __/ |   \ V /  __/ |    | |____| | | | |   <\__ \  / /__
#  |_____/ \___|_|    \_/ \___|_|    |______|_|_| |_|_|\_\___/ /_____|


# === COLOR CODES ===

# This plugin supports old color codes like: &c, &l, &o, etc.
# It also supports MiniMessage, a more advanced way to format messages:
# https://docs.advntr.dev/minimessage/format.html
# With MiniMessage, you can add HEX colors, gradients, hover and click events, etc.


# === GENERAL SETTINGS ===

# Set the language to any code found in the "lang" folder (don't add the .yml extension)
# You can add your own language files. Use https://github.com/KartoffelChipss/ServerLinksZ/tree/main/src/main/resources/lang/en-US.yml as a template
#  | en-US | de-DE |
lang: "en-US"

# Wether to show hints when using commands
hints: true

# Add a /link command to view the links
linkCommand: true


# === LINKS ===

links:
  # You can add as many links as you want with the following schema
  discord:
    # The name of the link
    name: "<#7289da>&lDiscord"
    # The URL of the link
    url: "https://strassburger.org/discord"
    # Wether people should be able to see the link in /link
    allowCommand: true
  website:
    name: "<#7cd770>&lWebsite"
    url: "https://modrinth.com"
    allowCommand: false
```
</details>

## Support

If you need help with the setup of the plugin, you can join my Discord:

[![discord-plural](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/compact/social/discord-plural_vector.svg)](https://strassburger.org/discord)