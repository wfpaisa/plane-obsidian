# Obsidian Plane Theme

fork of: https://github.com/birneee/obsidian-adwaita-theme. tanks.

## Installation

### Obsidian Community Theme Store

1. In Obsidian go to `Settings >  Options > Appearance > Themes > Manage` search for `Plane`
2. Click `Install and use`
3. Optionally install the [Obsidian Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings) for customization. Adjust under `Settings > Community Plugins > Style Settings > Plane`

### Automatic

1. Install [just](https://github.com/casey/just)
2. Set `export OBSIDIAN_HOME="/home/../.."` environment variable to your vault path
3. run `just install`
4. In Obsidian go to `Settings > Options > Appearance > Themes` and select the `Plane` theme
5. Optionally install the [Obsidian Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings) for customization. Adjust under `Settings > Community Plugins > Style Settings > Plane`

### Manual

1. create a `.obsidian/themes/Plane` directory in your Obsidian vault
2. Copy `theme.css` and `manifest.json` to the created `Plane` folder
3. In Obsidian go to `Settings > Options > Appearance > Themes` and select the `Plane` theme
4. Optionally install the [Obsidian Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings) for customization. Adjust under `Settings > Community Plugins > Style Settings > Plane`

## Build

- Install [just](https://github.com/casey/just) and [sassc](https://github.com/sass/sassc), watchexec
- Run `just watchexec` or `just css` or `just install`

## Style Settings

Requires the [Obsidian Style Settings Plugin](https://github.com/mgmeyers/obsidian-style-settings).
Adjust under `Settings > Community Plugins > Style Settings > Plane`.

![](src/preview/style-settings.png)

## Contribution

Feel free to create Issues and Pull Requests.
