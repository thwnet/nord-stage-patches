# Nord Stage Patches

Freie Programme für den Nord Stage 3 und den Nord Stage 4.

Seite: https://thwnet.github.io/nord-stage-patches/

## Einen Patch dazulegen

1. Die Datei nach `patches/` legen.
2. In `patches.json` einen Eintrag anfügen.

```json
{
  "name": "Name",
  "model": "stage4",
  "file": "patches/datei.ns4p",
  "audio": "audio/datei.mp3",
  "note": {
    "de": "Kurz",
    "en": "Short",
    "it": "Breve",
    "es": "Breve"
  }
}
```

`model` ist `stage3` oder `stage4`. `file` beginnt mit `patches/` und enthält kein `..`. `audio` ist optional, beginnt mit `audio/` und ist eine `.mp3`, `.m4a` oder `.wav`.
