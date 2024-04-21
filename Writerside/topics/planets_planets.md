# Planets

## dictionary
This json contains a dictionary of key: value pairs, with the keys representing the planet's planet_index, and the 
values being a dictionary containing planet attributes.

```json
{
  "0": {
    "name": "Super Earth", // <- Default Planet Name; en-US
    "sector": "Sol",
    "biome": "unknown", // <- String for planet biome type.
    "environmentals": [ //<-  Array[String] for each environmental hazard this planet has
      "none"
    ],
    "names": { // <- Localization options for all supported languages.
      "en-US": "SUPER EARTH",
      "en-GB": "SUPER EARTH",
      "pt-BR": "SUPERTERRA",
      "de-DE": "ÜBER-ERDE",
      "es-ES": "SUPERTIERRA",
      "fr-FR": "SUPER-TERRE",
      "it-IT": "SUPER TERRA",
      "ja-JP": "スーパーアース",
      "ko-KO": "슈퍼지구",
      "ms-MY": "SUPERTIERRA",
      "pl-PL": "SUPER ZIEMIA",
      "pt-PT": "SUPER TERRA",
      "ru-RU": "СУПЕР-ЗЕМЛЯ",
      "zh-Hans": "超级地球",
      "zh-Hant": "超級地球"
    }
  }
}
```