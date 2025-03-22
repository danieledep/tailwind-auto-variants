# Tailwind Auto Variants

A VS Code extension that provides smart snippets for breakpoint variants and other common modifiers. This extension automatically picks up the last utility class before the cursor so that you only need to write the changing value.

`bg-red-500` -> `md:bg-red-`

`flex-col` -> `md:flex-`

`border-tr-[2px]` -> `md:border-tr-[px]`


![alt text](tvs.jpeg)

## Features

- Support for responsive, state, and modifier variants
- Support for custom values inside square brackets
- Support for tailwind v4 custom property. Eg: `bg-(--color-primary)`

## Installation

1. Open VS Code
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X)
3. Search for "Tailwind Auto Variants"
4. Click Install

## Usage

Type the snippet prefix, such as `md:` or `hover:`, and the snippets will appear in the suggestion list as you type.

## Recommended VS Code Settings

To get the best experience with these snippets, we recommend adding the following settings to your VS Code settings.json:

```json
{
  "editor.suggest.showSnippets": true,
  "editor.snippetSuggestions": "top",
  "editor.suggestOnTriggerCharacters": true,
  "editor.quickSuggestions": {
    "other": true,
    "comments": true,
    "strings": true
  }
}
```

These settings will:
- Always show snippets in the suggestion list
- Prioritize snippets at the top of the suggestion list
- Show suggestions when typing trigger characters
- Enable quick suggestions in various contexts

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.