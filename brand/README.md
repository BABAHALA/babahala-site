# Brand assets

Generated from the site's own design system, so they match the website and the
client deliverables rather than approximating them.

| File | Size | Use |
|---|---|---|
| `linkedin-logo.png` | 400×400 | LinkedIn company page logo, ink ground |
| `linkedin-logo-light.png` | 400×400 | The same on paper, if the ink reads too heavy |
| `linkedin-cover.png` | 4200×700 | LinkedIn company page cover |

The logo carries its own background on purpose. LinkedIn shows a page logo on
both light and dark surfaces, and a transparent mark would disappear on one of
them. The mark sits well inside the square, so it survives a circular crop.

The cover keeps its bottom left corner empty, because LinkedIn overlaps the
logo there.

Regenerate them the same way the favicon is regenerated: render the mark at the
required size with the row gap at 0.07 of a cell and the column gap at 0.15.
