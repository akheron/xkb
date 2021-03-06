# My keyboard layout

My keyboard layout is basically [Colemak] with [Mod-DHk], keeping most
of the local Finnish symbols from the `fi` keymap in place.

I've moved many AltGr bindings to a more comfortable location, and
added an "extend" layer (inspired by [DreymaR's Big Bag of Keyboard
Tricks]), which is activated by pressing Caps Lock, left Alt, or both,
and has e.g. arrows, Backspace, Delete and many Emacs specific keys.
Caps Lock (locked) and Super (latched) have been moved to better locations as
well.

This is the base layout. By pressing AltGr, you get the symbols in the lower right.
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
┃ Tab   ┃ q < │ w > │ f = │ p   │ b   │ j   │ l   │ u [ │ y ] │ ö   │ Esc │ ^   ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃ A   │ R   │ S   │ T   │ G   │ K   │ N   │ E   │ I   │ O   │ Ä   │ *   ┃      ┃
┃ Ctrl   ┃ a _ │ r - │ s / │ t ? │ g   │ k   │ n { │ e ( │ i ) │ o } │ ä   │ '   ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃ Z   │ X   │ C   │ D   │ V   │     | M   │ H   │ ;   │ :   │ _   ┃              ┃
┃Shift ┃ z | │ x   │ c : │ d ; │ v   │Super│ m   │ h   │ ,   │ .   │ -   ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃       ┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Alt   ┃  Alt  ┃                Space              ┃ AltGr ┃       ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

Caps Lock acts mostly as Control, except for the following keys which
have a different meaning when Caps Lock is pressed. You can still
press left Control to get their original control key:

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃    ⌫    ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃ Tab   ┃     │     │     │     │     │     │  ⌫  │  ↑  │  ⌦  │     │ Esc │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃Pressed!┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃ Ctrl!  ┃     │     │     │     │     │ C-x │  ←  │  ↓  │  →  │     │     │     ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃     │     │     │     │     │     │Shift│     │     │     │     ┃              ┃
┃Shift ┃     │     │     │     │     │Super│ Ins │     │     │     │     ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃       ┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Alt   ┃  Alt  ┃                Space              ┃ AltGr ┃       ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

Left Alt acts mostly as Alt (Meta1), except for the following keys.
The left Win key acts as an unmodified Alt (Meta1).

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃    ⌫    ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃ Tab   ┃     │     │     │     │     │     │ C-⌫ │     │ C-⌦ │     │ Esc │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃ Ctrl   ┃     │     │     │     │     │     │ C-← │     │ C-→ │     │     │     ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃     │     │     │     │     │     │     │     │     │     │     ┃              ┃
┃Shift ┃     │     │     │     │     │Super│ M-y │     │     │     │     ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃Pressed┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Alt   ┃  Alt! ┃                Space              ┃ AltGr ┃       ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

When both Caps Lock and Left Alt are pressed:

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃    ⌫    ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃ Tab   ┃     │     │     │     │     │     │     │ PgUp│ C-k │     │ Esc │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃Pressed ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃ Ctrl!  ┃     │     │     │     │     │     │ Home│ PgDn│ End │     │     │     ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃     │     │     │     │     │     │     │     │     │     │     ┃              ┃
┃Shift ┃     │     │     │     │     │Super│     │     │     │     │     ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃Pressed┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Meta  ┃  Alt! ┃                Space              ┃ AltGr ┃ Super ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

## Usage

### X11

Copy the file `akheron` to `/usr/share/X11/xkb/symbols`.

Activate the layout: `setxkbmap -rules evdev -model pc105 -layout
akheron -variant '' -option ''`

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

[DreymaR's Big Bag of Keyboard Tricks]: https://github.com/DreymaR/BigBagKbdTrixXKB
[Colemak]: https://colemak.com
[Mod-DHk]: https://colemakmods.github.io/mod-dh/
