# Font file names

The launcher and game scan this folder at startup. Use these exact names:

```text
<Family Name>-Regular.ttf   required
<Family Name>-Bold.ttf      optional
```

`<Family Name>` must exactly match the family name stored inside the TTF file,
including spaces and capital letters. A bold face without a regular face is ignored.
Files with another name are ignored.

Examples:

```text
DejaVu Sans-Regular.ttf
DejaVu Sans-Bold.ttf
Cascadia Mono-Regular.ttf
```

Restart the launcher and game after changing fonts. Keep each font's license file
in this folder.
