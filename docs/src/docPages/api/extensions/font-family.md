# FontFamily
This extension enables you to set the font family in the editor. It uses the [`TextStyle`](/api/marks/text-style) mark, which renders a `<span>` tag. The font family is applied as inline style, for example `<span style="font-family: Arial">`.

## Installation
::: warning Use with TextStyle
This extension requires the [`TextStyle`](/api/marks/text-style) mark.
:::

```bash
# with npm
npm install @tiptap/extension-text-style @tiptap/extension-font-family

# with Yarn
yarn add @tiptap/extension-text-style @tiptap/extension-font-family
```

## Settings
| Option | Type    | Default         | Description                                                              |
| ------ | ------- | --------------- | ------------------------------------------------------------------------ |
| types  | `Array` | `['textStyle']` | A list of marks to which the font family attribute should be applied to. |

## Commands
| Command    | Parameters | Description                                   |
| ---------- | ---------- | --------------------------------------------- |
| fontFamily | fontFamily | Applies the given font family as inline style |

## Source code
[packages/extension-font-family/](https://github.com/ueberdosis/tiptap-next/blob/main/packages/extension-font-family/)

## Usage
<demo name="Extensions/FontFamily" highlight="" />