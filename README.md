# BB to FMBE Command Converter

A static HTML utility for converting Blockbench-exported Minecraft Bedrock Edition model JSON into FMBE-compatible command blocks.

## Features

- Convert Bedrock model bones and cubes into FMBE command text
- Supports version selection for different FMBE command variants
- Handles block rotation, pivot, and bone hierarchy
- Optional dynamic bone conversion for models with parented bones
- Supports custom prefix/suffix output wrappers with block numbering
- File upload support for `.json` model files

## Usage

1. Open `index.html` in a web browser.
2. Set the scale conversion factor `k` (default `1`).
3. Choose the desired version button.
4. Paste the Bedrock model JSON exported from Blockbench into the input box, or upload a `.json` file.
5. Optionally enter a custom prefix or suffix. Use `<>` inside prefix/suffix to insert the cube number.
6. Click `Convert`.
7. Copy generated output commands using the individual copy buttons or the `Copy All` button.

## Notes

- If the model contains bone hierarchy, the app will prompt whether to enable dynamic bone conversion.
- The converter is designed for Blockbench-exported Minecraft Bedrock model JSON and may not work for unsupported formats.
- Custom prefix/suffix placeholders are sanitized for safe insertion.

## Files

- `index.html` — main static web interface and conversion logic.
- `LICENSE` — MIT License.

## License

This project is released under the MIT License.See `LICENSE` for details. 
