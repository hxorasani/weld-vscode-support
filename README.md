# Weld Syntax

Weld Syntax adds support for two custom file types in VS Code:

- **Weld CSS** (`.css.w`)  
- **Weld HTM** (`.htm.w`)

## Features

- **Syntax Highlighting**  
  Provides a TextMate grammar for `.css.w` and `.htm.w` files.  
  Weld CSS is a tab-aligned, property-first flavor of CSS.  
  Weld HTM follows similar ideas, but for HTML.

- **File Icons**  
  Weld CSS files show the same icon as regular CSS.  
  Weld HTM files show the same icon as regular HTML.

- **Language Associations**  
  Files ending in `.css.w` are recognized as Weld CSS, and files ending in `.htm.w` are recognized as Weld HTM.  
  This means they’ll benefit from word suggestions, folding, and theming just like their standard counterparts.

## Why Weld?

Weld formats are designed to be more human-readable by enforcing consistent indentation and alignment.  
For example, in Weld CSS you can write:

```css
.task_item li
	list-style		none
	position		relative
	padding-left	20px
```

Instead of juggling braces and semicolons, properties are aligned using tabs for clarity.

## Installation

1. Open VS Code.
2. Go to **Extensions → Install from VSIX...** (or search `Weld Syntax` if published).
3. Select the `.vsix` file you built.

## Usage

* Open a `.css.w` file → you’ll see Weld CSS highlighting and CSS icon.
* Open a `.htm.w` file → you’ll see Weld HTM highlighting and HTML icon.

## Notes

* This extension reuses existing CSS/HTML icon assets from the default VS Code theme.
* Syntax highlighting is custom, so themes will still color your properties, values, variables, etc.

---

💡 Weld CSS and Weld HTM are experimental formats. Use them if you prefer a lighter syntax with clean indentation, but still want full editor support in VS Code.
You'd need the Weld bundler installed to make use of these formats for your PWAs

