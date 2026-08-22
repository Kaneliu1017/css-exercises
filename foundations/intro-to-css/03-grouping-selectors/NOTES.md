# CSS Learning Notes

Personal notes and takeaways as I work through The Odin Project's CSS exercises.

---

## 01-css-methods
**Date:** Aug 21, 2026

- Practiced all three ways to add CSS to HTML: external, internal, and inline.
- External CSS (separate `.css` file + `<link>`) is the standard, most maintainable approach.
- Internal CSS (`<style>` in `<head>`) is fine for single-page, unique styles.
- Inline CSS (`style="..."` on an element) overrides the other two — useful only for one-off, single-element tweaks.

---

## 02-class-id-selectors
**Date:** Aug 22, 2026

- Practiced applying class (`.classname`) and ID (`#idname`) selectors.
- Classes are reusable across multiple elements; IDs must be unique per page.
- **Key takeaway (from comparing my solution to the official one):**
  When two elements share a declaration — even if they're otherwise styled differently — it's better to extract that shared style into its own reusable class, rather than repeating the same property-value pair inside separate ID/type selectors.

  Example:
  ```css
  /* Less optimal — duplicated across two ID rules */
  #third { font-size: 24px; }
  #fourth { font-size: 24px; background-color: lightgreen; }

  /* Better — shared style pulled into a class */
  .adjust-font-size { font-size: 24px; }
  ```
  This follows the DRY principle (Don't Repeat Yourself) — if the shared value ever needs to change, you only edit it in one place.


---

## [03-grouping-selectors]
**Date:** Aug 22, 2026

- What I practiced: applied grouping classes.
- Anything that confused me: the "," to connect two classes, and how to style them properily. 
- Key takeaway / what I'd do differently: maybe come out a better names and be aware of space to make code visually appealing. 


---
## Template for future entries

## [exercise-folder-name]
**Date:**

- What I practiced:
- Anything that confused me:
- Key takeaway / what I'd do differently: