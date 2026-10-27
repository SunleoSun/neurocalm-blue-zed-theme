# NeuroCalm Blue Theme

NeuroCalm Blue Theme is a dark theme for [Zed](https://zed.dev/) built around deep navy surfaces with blue, teal, and violet accents.

The palette is intentionally low-stimulation: large surfaces stay dark and cool, while brighter colors are reserved for syntax, focus states, diagnostics, and version-control meaning. The design goal is a calmer, comfortable coding environment for long sessions; it is not a medical or health claim.

## Palette

- Editor background: `#020614`
- Main UI background: `#060D24`
- Panel/surface background: `#071027`
- Variables: `#96E8FF`
- Functions: `#D9B3FF`
- Types: `#4AD99E`
- Added diff emphasis: teal
- Deleted diff emphasis: violet
- Strings and numbers: restrained warm accents

## Local development

1. Clone this repository.
2. In Zed, open the command palette.
3. Run `zed: install dev extension`.
4. Select the repository root.
5. Open the theme selector with `Ctrl+K Ctrl+T` and choose **NeuroCalm Blue Theme**.

After editing the theme, use `zed: rebuild dev extension` if Zed does not pick up the change automatically.

## Publishing

The extension manifest is ready for the Zed extension registry. Before publishing a new release, bump the version in `extension.toml`, then submit or update the extension entry in the official `zed-industries/extensions` repository.

## Attribution

NeuroCalm Blue Theme started as a customized override of the Zed **VSCode Dark Modern** theme. Some fallback theme tokens remain based on the VSCode Dark Modern Zed theme by kcamcam:

https://github.com/kevcamel/vscode_dark_modern.zed

The NeuroCalm palette, syntax choices, UI colors, and Git diff colors are customized for this theme.

## License

NeuroCalm Blue Theme is released under the MIT License. See [LICENSE](LICENSE).