# dotfiles

### Configurations
- [kitty](https://sw.kovidgoyal.net/kitty/)
- [waybar](https://github.com/Alexays/Waybar)
- [oh-my-posh](https://ohmyposh.dev/)

### Base theme
[Catppuccin](https://catppuccin.com/)

### Keyboard layout

Create file `/usr/share/X11/xkb/symbols/us-italtgr`

```shell
// Custom US layout with Italian-style AltGr accents
xkb_symbols "us_italtgr" {

    include "us(altgr-intl)"
    name[Group1]= "US (AltGr Intl + Italian accents)";

    // --- Accenti gravi (AltGr + lettera) ---
    key <AC01> { [ a, A, agrave, Agrave ] }; // AltGr+a → à / À
    key <AD03> { [ e, E, egrave, Egrave ] }; // AltGr+e → è / È
    key <AD08> { [ i, I, igrave, Igrave ] }; // AltGr+i → ì / Ì
    key <AD09> { [ o, O, ograve, Ograve ] }; // AltGr+o → ò / Ò
    key <AD07> { [ u, U, ugrave, Ugrave ] }; // AltGr+u → ù / Ù
};
```
