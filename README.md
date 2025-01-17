# VillagerRefresh Plugin

## Overview
VillagerRefresh is a lightweight Minecraft plugin that solves the issue with villager trade refreshing when the `doDaylightCycle` gamerule is disabled. It periodically refreshes villager trades regardless of the day/night cycle, allowing players to continue trading and leveling up villagers normally.

## Features

- Automatically refreshes all villager trades at configurable intervals;
- Works with disabled `doDaylightCycle` gamerule;
- Preserves all trade properties (experience rewards, villager experience, price multipliers);
- Minimal performance impact;
- Simple configuration.

## Requirements

- Minecraft Server version 1.21+
- Java 17 or higher
- Purpur, Paper, or Spigot server software

## Installation

Download the latest release, place it in your server's plugins folder and restart the server or use the `/reload` command.
The plugin will generate a default configuration file at `plugins/villager-refresh/config.yml`.

## Configuration

The plugin uses a simple configuration file (config.yml):
```
# Time interval between trade refreshes (in minutes)
refresh-interval-minutes: 20
```

## Permissions

The plugin doesn't require any special permissions to function.

## Commands

Currently, the plugin doesn't include any commands. All functionality is automatic.

## Support

If you encounter any issues or need assistance:

- Check if the server meets the requirements;
- Verify the configuration file is correctly formatted;
- Check server logs for any error messages.

## License

This plugin is open source and available under the MIT License.