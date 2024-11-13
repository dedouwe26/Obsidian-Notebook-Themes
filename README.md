# Obsidian-Notebook-Themes v2.3.0
## A Series of Notebook Theme CSS Snippets for Obsidian.
These a few CSS classes that mimic a few of my real-world notebook pages and pen colors.
Go ahead and try it out! You can change or add new color variables or entire new
classes and combinations. 
Check out the full video going over the process [here](https://youtu.be/9T9VL8_i1Tg)!

*Image Effects generated with https://angel-rs.github.io/css-color-filter-generator.*

### CSS Classes

Inside Obsidian, apply a page class with an optional pen color class to see the effects.

**Page themes**:
- White | `page-white`
- Manila | `page-manila`
- Blueprint | `page-blueprint`

**Pen Colors**:
- Black | `pen-black`
- Gray | `pen-gray`
- Red | `pen-red`
- Green | `pen-green`
- Blue | `pen-blue`
- Purple | `pen-purple`
- White | `pen-white`

**Miscellaneous**:
- Add a grid on the page background. | `page-grid`
- Recolor image to the current pen color. | `recolor-images`
- Adds the page color to the background of the images. | `embed`

- Can be used to set up the configuration for external pages or pens. | `.use-config`

### How to Install and use the CSS Snippet

1. Download `Notebook Backgrounds.css` from this repo.
2. Open the settings panel in Obsidian and click the Appearance tab.
3. Scroll to "CSS snippets" and click the folder icon.
4. Drop `Notebook Backgrounds.css` into the folder that appears.
5. Now back in Obsidian, next to "CSS snippets", click the "Reload snippets" button.
6. You should now see `Notebook Backgrounds` in the list. Toggle it on and you're ready to go!

### CSS Variables

Descibes waht each variable created by this stylesheet does.

**Constants** (above in the root):
- `pen-...` : The text color of the pen / page.
- `page-...` : The primary (background) color of the page.
- `page-...-secondary` : The secondary color of the page.
- `page-...-grid` : The grid color of the page.
- `grid-size` : The size of the grid (if enabled).

**Variables** (used by pages, pens, etc):
- `line-thickness`: The thickness of the line under a letter that is underlined, the thickness of the box around the attributes, etc.
- `text-weight`: The default weight (thickness) of text.
- `bold-weight`: The weight (thickness) of bold text, the title and a header 1.
- `text-color`: The default text color of most things.
- `text-weight`: The default weight (thickness) of text.
- `primary-color`: The primary (background) color.
- `secondary-color`: The secondary color used by the quote background and the box around the attributes, etc.
- `link-color`: The color of a link.
- `color-theme`: The theme of the page. Can be light, dark, etc.


