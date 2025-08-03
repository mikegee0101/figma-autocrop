# Figma plugin: Autocrop

A Figma plugin that automatically crops the extra space surrounding images in your designs.

## Installation

1. Clone this repository
2. Run `npm install` to install dependencies
3. Run `npm run build` to compile TypeScript
4. In Figma, go to Plugins → Development → Import plugin from manifest
5. Select the `manifest.json` file

## Development

1. Run `npm run dev` to automatically compile changes with watch mode
2. Run `npm run build` for production builds
3. Reload the plugin in Figma after making changes

## Usage

1. Select one or more rectangle layers with image fills
2. Run the Autocrop plugin from the Plugins menu
3. The plugin will automatically crop excess space around each image
4. If errors occur, an error dialog will display with specific layer information

## License

© 2025 Mike Gowen

MIT License
