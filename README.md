# UsernameDB

A Plugin database for a BetterDiscord plugin.

PR your Discord Account ID in this format
```json
{
  "userId": {
    "fontId": 12,
    "effectId": 3,
    "colors": [16755404, 15961000]
  }
}
```

Only these currently exist
```ts
enum EffectID {
    SOLID = 1;
    GRADIENT = 2;
    NEON = 3
    TOON = 4;
    POP = 5;
}
enum FontIDs {
    BANGERS = 1,
    BIO_RHYME = 2,
    CHERRY_BOMB = 3,
    CHICLE = 4,
    COMPAGNON = 5,
    MUSEO_MODERNO = 6,
    NEO_CASTEL = 7,
    PIXELIFY = 8,
    RIBES = 9,
    SINISTRE = 10,
    DEFAULT = 11
}
```
