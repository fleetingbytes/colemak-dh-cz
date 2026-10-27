# Colemak Layout for Czech

This repository provides the layout definition file for the [X Window System][x].

In the following I present the standard `us(colemak_dh)` layout provided with X and then my modification of it, `cz(colemak_dh_cz)`, which makes all the Czech characters easier to type.

The ASCII diagrams below show the basic keyboard keys with their four layers of mappings for each key like this:

```
┌─────┐
│bd···│
│ac···│
└─────┘
```

Here `a`, `b`, `c`, `d` represent the characters mapped to layer 1 through layer 4:

- `a`: layer 1 (unshifted)
- `b`: layer 2 (shifted)
- `c`: layer 3 (AltGr)
- `d`: layer 4 (AltGr, shifted)


## Standard Colemak DH (US layout, variant colemak_dh)

With the standard Colemak-DH variant of the US layout it is possible to type Czech characters but they are not readily accessible. Heavy use of dead keys and layer 3, layer 4 is necessary. It looks like this:

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬───────────┐
│~~   │!¹   │@²   │#³   │$£   │%¥   │^Ħ   │&Ð   │*Þ   │(“   │)”   │_—   │+÷   │           │
│`~   │1¡   │2º   │3ª   │4¢   │5€   │6ħ   │7ð   │8þ   │9‘   │0’   │-–   │=×   │ backspace │
├─────┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬────────┤
│        │QÄ   │WÅ   │FÃ   │PØ   │B~   │JĐ   │LŁ   │UÚ   │YÜ   │:Ö   │{‹   │}›   │        │
│ tab    │qä   │wå   │fã   │pø   │b˘   │jđ   │lł   │uú   │yü   │;ö   │[«   │]»   │  enter │
├────────┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┐      │
│          │AÁ   │R~   │Sẞ   │T˝   │G~   │M~   │NÑ   │EÉ   │IÍ   │OÓ   │"Õ   │|~   │      │
│ caps lk  │aá   │r`   │sß   │t´   │g˛   │m¯   │nñ   │eé   │ií   │oó   │'õ   │\~   │      │
├───────┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴─────┴──────┤
│       │ZÆ   │X~   │CÇ   │D~   │VŒ   │ZÆ   │K~   │H~   │<~   │>~   │?~   │               │
│ shift │zæ   │x^   │cç   │d¨   │vœ   │zæ   │k°   │hˇ   │,¸   │.˙   │/¿   │         shift │
├───────┼─────┴┬────┴──┬──┴─────┴─────┴─────┴─────┴─────┴───┬─┴─────┼─────┴┬──────┬───────┤
│       │      │       │                                    │       │      │      │       │
│ ctrl  │ supr │ alt   │              space                 │ altgr │ supr │ fn   │  ctrl │
└───────┴──────┴───────┴────────────────────────────────────┴───────┴──────┴──────┴───────┘
```

## Colemak DH CZ (This Layout)

I propose the following modified Colemak layout to write Czech more easily:

```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬───────────┐
│~~   │!‘   │@’   │#€   │$£   │%¥   │^¢   │&§   │*‰   │(“   │)”   │_—   │+÷   │           │
│`~   │ď1   │ť2   │ů3   │é4   │á5   │ň6   │ú7   │ý8   │ě9   │í0   │-–   │=×   │ backspace │
├─────┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬────────┤
│        │ČQ   │ŽW   │ŘF   │PØ   │B‽   │JĐ   │LŁ   │UX   │YÜ   │:Ö   │{‹   │}›   │        │
│ tab    │čq   │žw   │řf   │pø   │b˘   │jđ   │lł   │ux   │yü   │;ö   │[«   │]»   │  enter │
├────────┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┐      │
│          │AÁ   │R²   │Sẞ   │T˝   │Gº   │Mª   │NÑ   │EÉ   │IÍ   │OÓ   │"Õ   │|Þ   │      │
│ caps lk  │aá   │r`   │sß   │t´   │g˛   │m¯   │nñ   │eé   │ií   │oó   │'õ   │\þ   │      │
├───────┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴──┬──┴─────┴──────┤
│       │ZÆ   │Š¹   │CÇ   │D³   │VŒ   │ZÆ   │KĦ   │Hħ   │<ð   │>Ð   │?¡   │               │
│ shift │zæ   │š^   │cç   │d¨   │vœ   │zæ   │k°   │hˇ   │,¸   │.˙   │/¿   │         shift │
├───────┼─────┴┬────┴──┬──┴─────┴─────┴─────┴─────┴─────┴───┬─┴─────┼─────┴┬──────┬───────┤
│       │      │       │                                    │       │      │      │       │
│ ctrl  │ supr │ alt   │              space                 │ altgr │ supr │ fn   │  ctrl │
└───────┴──────┴───────┴────────────────────────────────────┴───────┴──────┴──────┴───────┘
```

### Motivation

- Every Czech letter should be typable in one to three keystrokes (including dead keys and layer shifts)
- Most frequent Czech letters shall be preferred to easily accessible numbers on the top row
- Frequent Czech letters shall be preferred to `Q`, `W`, `X`, `F` which are rare in Czech texts.
- Preserve the location of frequent special characters, i. e. `~!@#$%^&*()-_=+;:[]{}'"\|<>/?`
- Preserve the location of dead keys of the US colemak layout
- Prefer to move rarely used special characters to some of the `asciitilde` places, rather than to lose them entirely
- Add a few rare special characters in favor of yet another extra way to type `asciitilde`


### Result

- Czech letters are easily accessible, most of them in one key stroke.
- `Q`, `W`, `X`, `F` and numbers are only acessible through AltGr, which breaks some keyboard shortcuts.
- Every character typable on Colemak-DH is also typable on Colemak-DH-CZ, although some of them moved to other places or layers.


### Changes with regards to Colemak-DH

In the following overview the target key locations are named after their standard Colemak location. Thus, when I say something like _`X` moved to layer 3 of `U`_ this means that the character `X` moved to layer 3 of that key where the Colemak-DH layout has `U`, not where the US QWERTY layout has `U`.

#### Regular Characters

- numbers stayed on their keys but moved to layer 3
- `Q` now types `Č`
- `W` now types `Ž`
- `F` now types `Ř`
- `X` now types `Š`
- original Colemak `Q`, `W`, `F` stayed on their keys but moved to layer 3
- original Colemak `X` moved to layer 3 of `U`
- original Colemak `1234567890` now type `ďťůéáňúýěí`
- Czech `ĎŤŮÉÁŇÚÝĚÍ` have to be typed through the dead keys or layer 3

#### Special characters

- `¡` moved to `AltGr-Shift-/`
- `¹` moved to `AltGr-Shift-x`
- `º` moved to `AltGr-Shift-g`
- `²` moved to `AltGr-Shift-r`
- `ª` moved to `AltGr-Shift-m`
- `³` moved to `AltGr-Shift-d`
- `¢` moved to `AltGr-Shift-6`
- `€` moved to `AltGr-Shift-3`
- `ħ` moved to `AltGr-Shift-h`
- `Ħ` moved to `AltGr-Shift-k`
- `ð` moved to `AltGr-Shift-,`
- `Ð` moved to `AltGr-Shift-.`
- `þ` moved to `AltGr-\`
- `Þ` moved to `AltGr-Shift-\`
- `‘` moved to `AltGr-Shift-1`
- `’` moved to `AltGr-Shift-2`
- `äÄåÅãÃ` must be written with the help of the corresponding dead key
- `‽` added at `AltGr-Shift-b`
- `§` added at `AltGr-Shift-7`
- `‰` added at `AltGr-Shift-8`

## Installation

To install the keyboard layout, just link the file in `xkb/symbols/cz` in your local xkb directory (or copy it there), e.g.:

```bash
ln -fs $HOME/src/colemak-dh-iso-cz/symbols/cz $XDG_CONFIG_HOME/xkb/symbols/cz
```

Load it like this:
```bash
setxkbmap -I "$XDG_CONFIG_HOME/xkb" -model pc105 -layout cz -variant colemak_dh_cz -print | \
xkbcomp -w0 -I "$XDG_CONFIG_HOME/xkb" - "$DISPLAY"
```

Although, you are probably going to use it in alternation with your other layout, e.g. with the standard `us(colemak_dh)`:

```bash
setxkbmap -I "$XDG_CONFIG_HOME/xkb" \
          -model pc105 \
          -layout us,cz \
          -variant colemak_dh,colemak_dh_cz \
          -option caps:escape_shifted_capslock \
          -option grp:alt_shift_toggle \
          -print | \
xkbcomp -w0 -I "$XDG_CONFIG_HOME/xkb" - "$DISPLAY"
```

The above command is also ready to be added to your `~/.xinitrc` or `~/.xsession` (before the `exec`) to load these keyboard layouts when X starts.


## References:

- Jan Králík: [Grapheme Frequencies][kralik]
- Stefan Trost: [Buchstabenhäufigkeit Tschechisch][trost]

[x]: https://grokipedia.com/page/X%20Window%20System
[kralik]: http://www.czech-language.cz/alphabet/alph-prehled.html
[trost]: https://www.sttmedia.de/buchstabenhaeufigkeit-tschechisch
