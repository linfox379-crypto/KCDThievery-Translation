# KCD Thievery — Turkish Translation

Community Turkish translation for the Bannerlord mod **KCD Thievery**.

- Main mod: KCD Thievery on Nexus Mods
- Template version: **v0.8.15.83**
- Target language: **Türkçe (TR)**

## What this is

A language-only module. It contains **no DLL and no assets**.
It must be enabled **together with** the main `KCDThievery` module.

## Install (players)

1. Put the `KCDThievery.TR` folder into `Modules/`.
2. Enable both `KCDThievery` and `KCD Thievery - Turkish Translation` in the launcher.
3. Set the game language to **Türkçe**.

## Translate

Edit `ModuleData/Languages/TR/kcdt_strings-tur.xml`.

- **Never change the `id` attribute.** It is how the game finds each string.
- Only replace the `text` attribute with Turkish.
- **329 strings contain placeholders** like `{0}`, `{1}`, `{2:0.0}`.
  Keep every placeholder, in the same order. Do not translate inside the braces.
- Escape XML characters: `&` → `&amp;`, `<` → `&lt;`, `>` → `&gt;`, `"` → `&quot;`.
- **Save as UTF-8 without BOM.** Windows Notepad may add a BOM — use VS Code or Notepad++.
- Do not add or remove `<string>` lines.

## Status

| Item | Progress |
|---|---|
| Strings translated | 0 / 1131 |
| Reviewed by a native speaker | no |

## Files

```
KCDThievery.TR/
  SubModule.xml
  ModuleData/Languages/TR/language_data.xml
  ModuleData/Languages/TR/kcdt_strings-tur.xml
```

## License

Translation files are licensed under CC BY 4.0. See `LICENSE`.
This repository contains no source code, DLL or animation assets from the mod.
