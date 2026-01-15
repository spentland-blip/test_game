# Godot Web Project Template

A GitHub template for creating Godot games that deploy to the web.

## Getting Started

1. Click **<a href="https://github.com/acodeninja/godot-web-project/generate" target="_blank">Use this template</a>** to create a new repository from this template.
2. Go to "Settings" > "Pages" - Set "Source" to "GitHub Actions"
3. Edit the `config.yml` file to set your game's name, Godot version, and website template.
4. Export a ZIP file from the Godot online engine.
5. Upload the ZIP file to the `game/` directory.
6. Wait for your game to build and publish.

## Project Structure

### `game/`

Upload the zip file produced by the Godot web export here. This is where your playable game lives.

### `docs/`

Markdown files for your game's website. Edit these to describe your game—GitHub Pages will turn them into a site automatically.

### `.github/workflows/`

Contains GitHub Actions workflows for automated builds and deployment. **Do not edit this unless you know what you are doing.**

## License

MIT
