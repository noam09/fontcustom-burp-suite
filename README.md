# fontcustom-burp-suite

[Burp Suite icon font](https://noam09.github.io/fontcustom-burp-suite/Burp-preview.html) for use with status bars, created with [FontCustom](https://github.com/FontCustom/fontcustom).

* Burp Suite icons by [Icons8](https://icons8.com)

![Preview](https://i.imgur.com/b4N5yOS.png)

## Usage

Make the font file available to your system. One possibility is to copy it to the `/usr/share/fonts` directory:

```console
cp Burp_1f883ee54015e9dfd40a1f9c7276edf2.ttf /usr/share/fonts/TTF/.
```

Add the reference to your status bar configuration, it should come before other font files so its glyph will take precedence:

```ini
font-1 = "Burp:size=10;3"
font-2 = "MaterialIcons:size=10;6"
```

Use the glyph for workspaces, etc.

```
set $ws5 "5:"
```
