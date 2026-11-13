# MarioPartyDS-private

Private Dateien zu [MarioPartyDS-native](https://github.com/Erzoy38/MarioPartyDS-native). **Nicht öffentlich machen:** Die Releases enthalten übersetzten Spielcode und den Android-Signierschlüssel.

| Release | Inhalt |
|---|---|
| `data` | `mpds-laptop-data.zip` (native/third_party, native/assets, native/generated, Analyse-Tabellen) und `mpds-release.jks` (Schlüssel; die Passwörter sind nicht hier) |
| `v0.4.x` | Android-Builds: APK zum Installieren, AAB |

## iOS bauen

Actions → **iOS** → *Run workflow*. Ein macOS-Rechner von GitHub baut aus dem Quellcode von MarioPartyDS-native und dem Release `data` eine unsignierte `.ipa` (Artefakt `MarioPartyDS-unsigned-ipa`, 14 Tage). Auf iPhone oder iPad kommt sie mit Sideloadly, das sie mit der eigenen Apple-ID signiert (kostenlose Apple-ID: 7 Tage gültig).