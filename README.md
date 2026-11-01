# ShitBoxTV – Release-Kanal

Öffentlicher Verteilkanal der **ShitBoxTV**-App für Android TV / Google TV.
Hier liegen **nur** die fertigen APKs (als GitHub-Releases) und die Versions-Metadaten
(`stable/version.json`). **Kein Quellcode** – der bleibt privat.

Die App prüft `stable/version.json`, vergleicht den `versionCode` mit der installierten
Version und lädt bei Bedarf die zugehörige APK aus dem passenden Release.

## Format von `stable/version.json`
```json
{
  "versionCode": 2,
  "versionName": "0.1.1",
  "apkUrl": "https://github.com/djtugamuc-tech/ShitBoxTV-Releases/releases/download/v0.1.1/shitbox-tv-0.1.1.apk",
  "changelog": "Kurzbeschreibung der Änderungen.",
  "mandatory": false,
  "minSdk": 26
}
```
