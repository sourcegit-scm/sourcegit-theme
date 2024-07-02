# sourcegit-theme

Custom Themes for SourceGit

## How to make & use your theme

1. Create a new json file, and provide your favorite colors with follow keys:

| Key | Description |
| --- | --- |
| Color.Window | Window background color |
| Color.WindowBorder | Window border color. Only used on Linux. |
| Color.TitleBar | Title bar background color |
| Color.ToolBar | Tool bar background color |
| Color.Popup | Popup panel background color |
| Color.Contents | Background color used in inputs, data grids, file content viewer, change lists, text diff viewer, etc. |
| Color.Badge | Badge background color |
| Color.BadgeFG | Badge foreground color |
| Color.Conflict | Conflict panel background color |
| Color.ConflictForeground | Conflict panel foreground color |
| Color.DecoratorIconBG | Background color for commit ref icon |
| Color.DecoratorIcon | Foreground color for commit ref icon |
| Color.DecoratorBranch | Background color for commit branch ref name |
| Color.DecoratorTag | Background color for commit tag ref name |
| Color.DecoratorFG | Foreground color for commit ref name |
| Color.Border0 | Border color used in some controls, like Window, Tab, Toolbar, etc. |
| Color.Border1 | Border color used in inputs, like TextBox, ComboBox, etc. |
| Color.Border2 | Border color used in visual lines, like seperators, Rectange, etc. |
| Color.FlatButton.Background | Flat button background color, like `Cancel`, `Commit & Push` button |
| Color.FlatButton.BackgroundHovered | Flat button background color when hovered, like `Cancel` button |
| Color.FG1 | Primary foreground color for all text elements |
| Color.FG2 | Secondary foreground color for all text elements |
| Color.Diff.EmptyBG | Background color used in empty lines in diff viewer |
| Color.Diff.AddedBG | Background color used in added lines in diff viewer |
| Color.Diff.DeletedBG | Background color used in deleted lines in diff viewer |
| Color.Diff.AddedHighlight | Background color used for changed words in added lines in diff viewer |
| Color.Diff.DeletedHighlight | Background color used for changed words in deleted lines in diff viewer |

For example:

```json
{
  "Color.Window": "#FFFF6059"
}
```

2. Open `Preference` -> `Appearance`, choose the json file you just created in `Custom Color Schema`.

> **NOTE**: The `Custom Color Schema` will override the colors with same keys in current active theme.

## Screenshots

[JetBrainsDark](./themes/JetBrainsDark.json) from [@MelonHell](https://gist.github.com/MelonHell)

![JetBrainsDark](screenshots/JetBrainsDark.png)

[JetBrainsDark DiffHighContrast](./themes/JetBrainsDark_DiffHighContrast.json) based on `JetBrainsDark` with higher contrast in diff view.

![JetBrainsDark DiffHighContras](screenshots/JetBrainsDark_DiffHighContrast.png)