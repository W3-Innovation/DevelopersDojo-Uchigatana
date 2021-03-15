<br>

# **README FILE NOTES**

<br>
<br>

---

1. Suggested Work-Space Configuration:
    + **Tab & Git-Decoration Settings**
      - "workbench.editor.decorations.colors": true,
      - "workbench.editor.decorations.badges": true,
      - "workbench.editor.highlightModifiedTabs": false,
      - "workbench.editor.tabSizing": "fit",
      - "workbench.editor.pinnedTabSizing": "normal",
    + "workbench.tree.renderIndentGuides": "onHover",
    + "editor.overviewRulerBorder": false,
    + "editor.rulers": [40, 50, 60, 70, 80, 80, 80],
    + ""
    + ""

<br>

2. The process behind creating a Color Scheme/Profile for a theme could be defined as condensing a whole lot of properties (250+) down to a few that can be read, and understood with relative ease.

<br>

3. I highlight UNTRACKED as SafteyOrange (#FF7600) becuase I don't leave files untracked, I either ignore them, or add them to a repository, however; many other themes, and including vscodes defualt themes, highlight untracked much more subtly, often in a grey.  If you wish to change the untracked decoration so that it is not so prominant, the setting you configure is listed below.

<br>

4. A border can be set to be used between the ruler and minimap, however; I perfer to not use the border

<br>

5. The ruler is dim so you can set the opaqueness to your likeing. Bellow shows how to make the ruler more or less transparent.

<br>

6. The few settings I highly recommend not changing are the Background colors of the editors workspace, and the background color of the editor. I make this suggestion becuase throughout the theme, including syntax highlighting, some colors have there colors set to be ever so slightly transparent, and changing backgrounds will change the color of borders and forgrounds that you dont intend to change. I plan on making adjustments in the future so that the bg-colors can be reconfigured without consequence, but untill I release that update, I suggest using the BG-colors provided with the Uchigatana theme, however; if you do decide to change it you will certainly want to change the property that is responsable for highlighting the editors current-line in focus, the property is written in the code-block below.
  
<br>

```
{
  /* The color that you see the property set to is the color that is considered
  defualt for the Uchigatana Theme. */

  "colors": {
    "editor.lineHighlightBackground": "#1040FF24"
  }
}
```

<br>
  
<br>

7. I dont know much about notebooks and therefore have not appropriatly styled theme.

<br>

8.

<br>

<br>

---
---

<br>
<br>
<br>
<br>
