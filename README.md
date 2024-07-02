# sourcegit-theme

Custom Themes for SourceGit

## How to make & use your theme

1. Create a new json file, and provide your favorite colors with follow keys:

* Basic Colors

| Key | Description |
| --- | --- |
| Window | Window background color |
| WindowBorder | Window border color. Only used on Linux. |
| TitleBar | Title bar background color |
| ToolBar | Tool bar background color |
| Popup | Popup panel background color |
| Contents | Background color used in inputs, data grids, file content viewer, change lists, text diff viewer, etc. |
| Badge | Badge background color |
| BadgeFG | Badge foreground color |
| Conflict | Conflict panel background color |
| ConflictForeground | Conflict panel foreground color |
| DecoratorIconBG | Background color for commit ref icon |
| DecoratorIcon | Foreground color for commit ref icon |
| DecoratorBranch | Background color for commit branch ref name |
| DecoratorTag | Background color for commit tag ref name |
| DecoratorFG | Foreground color for commit ref name |
| Border0 | Border color used in some controls, like Window, Tab, Toolbar, etc. |
| Border1 | Border color used in inputs, like TextBox, ComboBox, etc. |
| Border2 | Border color used in visual lines, like seperators, Rectange, etc. |
| FlatButton.Background | Flat button background color, like `Cancel`, `Commit & Push` button |
| FlatButton.BackgroundHovered | Flat button background color when hovered, like `Cancel` button |
| FG1 | Primary foreground color for all text elements |
| FG2 | Secondary foreground color for all text elements |
| Diff.EmptyBG | Background color used in empty lines in diff viewer |
| Diff.AddedBG | Background color used in added lines in diff viewer |
| Diff.DeletedBG | Background color used in deleted lines in diff viewer |
| Diff.AddedHighlight | Background color used for changed words in added lines in diff viewer |
| Diff.DeletedHighlight | Background color used for changed words in deleted lines in diff viewer |
| SystemAccentColor | Accent color for selected items |

* Colors used in commit graph. 

Array of colors used to draw commit graph. Optional. At least one color is needed.

For example:

```json
{
  "Basic": {
    "Window": "#FFFF6059"
  },
  "Graph": [
    "Red",
    "Yellow",
    "Green",
    "#FF00FF",
  ]
}
```

2. Open `Preference` -> `Appearance`, choose the json file you just created in `Custom Color Schema`.

> **NOTE**: The `Custom Color Schema` will override the colors with same keys in current active theme.

## Screenshots

[JetBrainsDark](./themes/JetBrainsDark.json) from [@MelonHell](https://gist.github.com/MelonHell)

![JetBrainsDark](screenshots/JetBrainsDark.png)

[JetBrainsDark DiffHighContrast](./themes/JetBrainsDark_DiffHighContrast.json) based on `JetBrainsDark` with higher contrast in diff view.

![JetBrainsDark DiffHighContras](screenshots/JetBrainsDark_DiffHighContrast.png)