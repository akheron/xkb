# My XKB config

My keyboard layout is basically [Colemak] with [Mod-DH], keeping most
of the local Finnish symbols from the `fi` keymap in place.

I've moved many AltGr bindings to a more comfortable location, and
added an "extend" layer (inspired by [DreymaR's Big Bag of Keyboard
Tricks]), which is activated by pressing Caps Lock, left Alt, or both,
and has e.g. arrows, Backspace, Delete and many Emacs specific keys.
Right Win key, Menu key and Print Screen key act as Super (Mod4).

This is the base layout. By pressing AltGr, you get the symbols in the lower right.
```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│ ~   │ !   │ "   │ #   │ $   │ %   │ &   │ /   │ (   │ )   │ =   │ ?   │ ^   ┃         ┃
│ `   │ 1   │ 2 @ │ 3   │ 4 € │ 5   │ 6   │ 7   │ 8   │ 9   │ 0   │ + \ │ ^   ┃Backspace┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃ Q   │ W   │ F   │ P   │ B   │ J   │ L   │ U   │ Y   │ Ö   │ Å   │     ┃       ┃
┃ Tab   ┃ q < │ w > │ f = │ p   │ b   │ j   │ l   │ u   │ y   │ ö   │ å   │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃ A   │ R   │ S   │ T   │ G   │ K   │ N   │ E   │ I   │ O   │ Ä   │ *   ┃      ┃
┃ Ctrl   ┃ a _ │ r - │ s / │ t ? │ g   │ k   │ n   │ e   │ i   │ o   │ ä   │ '   ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃ Z   │ X   │ C   │ D   │ V   │Caps │ M   │ H   │ ;   │ :   │ _   ┃              ┃
┃Shift ┃ z | │ x   │ c : │ d ; │ v   │ Lock│ m   │ h   │ ,   │ .   │ -   ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃       ┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Alt   ┃  Alt  ┃                Space              ┃ AltGr ┃ Super ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

Caps Lock acts mostly as Control, except for the following keys which
have a different meaning when Caps Lock is pressed. You can still
press left Control to get their original control key:

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃Backspace┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃ Tab   ┃     │     │     │     │     │     │  ⌫  │  ↑  │  ⌦  │     │     │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃Pressed!┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃ Ctrl!  ┃     │     │     │     │     │ C-x │  ←  │  ↓  │  →  │     │     │     ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃     │     │     │     │     │Caps │Shift│     │     │     │     ┃              ┃
┃Shift ┃     │     │     │     │     │ Lock│ Ins │     │     │     │     ┃     Shift    ┃
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
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃Backspace┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃ Tab   ┃     │     │     │     │     │     │ C-w │     │ M-d │     │     │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃ Ctrl   ┃     │     │     │     │     │     │ M-b │     │ M-f │     │     │     ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃     │     │     │     │     │Caps │     │     │     │     │     ┃              ┃
┃Shift ┃     │     │     │     │     │ Lock│ M-y │     │     │     │     ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃Pressed┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Alt   ┃  Alt! ┃                Space              ┃ AltGr ┃ Super ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

When both Caps Lock and Left Alt are pressed:

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃Backspace┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃ Tab   ┃     │     │     │     │     │     │     │ PgUp│ C-k │     │     │     ┃ Enter ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃Pressed ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃ Ctrl!  ┃     │     │     │     │     │     │ Home│ PgDn│ End │     │     │     ┃      ┃
┣━━━━━━┳━┹───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┬─┴───┲━┷━━━━━┻━━━━━━┫
┃      ┃     │     │     │     │     │Caps │     │     │     │     │     ┃              ┃
┃Shift ┃     │     │     │     │     │ Lock│     │     │     │     │     ┃     Shift    ┃
┣━━━━━━┻┳━━━━┷━━┳━━┷━━━━┱┴─────┴─────┴─────┴─────┴─────┴────┲┷━━━━━┷┳━━━━┻━━┳━━━━━━━┳━━━┛
┃       ┃       ┃Pressed┃                                   ┃       ┃       ┃       ┃
┃ Ctrl  ┃ Meta  ┃  Alt! ┃                Space              ┃ AltGr ┃ Super ┃ Ctrl  ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
```

## Usage

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

[DreymaR's Big Bag of Keyboard Tricks]: https://github.com/DreymaR/BigBagKbdTrixXKB
[Colemak]: https://colemak.com
[Mod-DH]: https://colemakmods.github.io/mod-dh/
