# My keyboard layout

My keyboard layout is basically [Colemak] with [Mod-DHk], keeping most
of the local Finnish symbols from the `fi` keymap in place.

I've moved many AltGr bindings to a more comfortable location. Caps Lock
(locked) and Super (latched) have been moved to better locations as well.

By pressing AltGr, you get the symbols in the lower right of each key.
```
┌─────┐
│Caps │
│ Lock│
└─────┘
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│ ~   │ !   │ "   │ #   │ $   │ %   │ &   │ /   │ (   │ )   │ =   │ ?   │ Å   ┃         ┃
│ `   │ 1   │ 2 @ │ 3 £ │ 4 € │ 5   | 6   │ 7   │ 8   │ 9   │ 0   │ + \ │ å   ┃    ⌫    ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃ Q   │ W   │ F   │ P   │ B   │ J   │ L   │ U   │ Y   │ Ö   │     │ ^   ┃       ┃
┃ Tab   ┃ q < │ w > │ f = │ p ← │ b → │ j   │ l   │ u [ │ y ] │ ö   │ Esc │ ^   ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃ A   │ R   │ S   │ T   │ G   │ K   │ N   │ E   │ I   │ O   │ Ä   │ *   ┃      ┃
┃ Ctrl   ┃ a _ │ r - │ s / │ t ? │ g ↑ │ k   │ n { │ e ( │ i ) │ o } │ ä   │ '   ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃ Z   │ X   │ C   │ D   │ V   │     | M   │ H   │ ;   │ :   │ _   ┃              ┃
┃Shift ┃ z | │ x   │ c : │ d ; │ v ↓ │Super│ m   │ h   │ ,   │ .   │ -   ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃       ┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Alt   ┃  Alt  ┃                Space              ┃ AltGr ┃       ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

## Usage

### X11

Copy the file `akheron` to `/usr/share/X11/xkb/symbols`.

Activate the layout: `setxkbmap -rules evdev -model pc105 -layout
akheron -variant '' -option ''`, or just `setxkbmap akheron`.

To make the changes persistent, add the following to
`/etc/X11/xorg.conf`, or `/etc/X11/xorg.conf.d/00-keyboard.conf`

```
Section "InputClass"
    Identifier "akheron"
    MatchIsKeyboard "on"
    Option  "XkbRules"         "evdev"
    Option  "XkbModel"         "pc105"
    Option  "XkbLayout"        "akheron"
    Option  "XkbVariant"       ""
    Option  "XkbOptions"       ""
EndSection
```

### macOS

Open the `akheron.bundle` folder in Keyboard Installer, install for the current
user. Open Settings -> Keyboard -> Input methods and find select the `Colemak -
akheron` layout under the the Finnish language.

[Colemak]: https://colemak.com
[Mod-DHk]: https://colemakmods.github.io/mod-dh/
