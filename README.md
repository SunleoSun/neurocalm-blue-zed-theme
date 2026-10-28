# NeuroCalm Blue Theme

NeuroCalm Blue Theme is a low-stimulation theme family for Zed built around muted blue-gray surfaces with blue, teal, violet, and restrained warm accents.

The design goal is a calmer, comfortable coding environment for long sessions; it is not a medical or health claim.

## Variants

### NeuroCalm Blue Dark

The original deep-navy variant with bright but controlled syntax accents.

- Editor background: `#020614`
- Main UI background: `#060D24`
- Variables: `#96E8FF`
- Functions: `#D9B3FF`
- Types: `#4AD99E`

### NeuroCalm Blue Medium

A medium-light desaturated blue-gray variant with dark syntax for higher text clarity while keeping the same color semantics.

- Editor background: `#D5DEE5`
- Main UI background: `#C8D3DB`
- Main text: `#101820`
- Variables: `#18384D`
- Functions: `#633873`
- Types: `#006047`

### NeuroCalm Blue Light

A brighter blue-gray variant with stronger syntax color separation, based on the post-Medium contrast and saturation refinements.

- Editor background: `#E4EBEF`
- Main UI background: `#D8E2E8`
- Main text: `#101820`
- Variables: `#17465F`
- Functions: `#734083`
- Types: `#00785C`

All three variants use teal for added changes, violet for deleted changes, blue for modified changes, and restrained warm accents for strings and numbers.

## Local development

1. Clone this repository.
2. In Zed, open the command palette.
3. Run `zed: install dev extension`.
4. Select the repository root.
5. Open the theme selector with `Ctrl+K Ctrl+T` and choose **NeuroCalm Blue Dark**, **NeuroCalm Blue Medium**, or **NeuroCalm Blue Light**.

After editing the theme, use `zed: rebuild dev extension` if Zed does not pick up the change automatically.

## Publishing

The extension manifest is ready for the Zed extension registry. Before publishing a new release, bump the version in `extension.toml`, then submit or update the extension entry in the official `zed-industries/extensions` repository.

## Attribution

NeuroCalm Blue Theme started as a customized override of the Zed **VSCode Dark Modern** theme. Some fallback theme tokens remain based on the VSCode Dark Modern Zed theme by kcamcam:

https://github.com/kevcamel/vscode_dark_modern.zed

The NeuroCalm palette, syntax choices, UI colors, and Git diff colors are customized for this theme.

## License

NeuroCalm Blue Theme is released under the MIT License. See [LICENSE](LICENSE).