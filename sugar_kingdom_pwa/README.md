# Sugar Kingdom – Android-Projekt

## Voraussetzungen
- Windows / macOS / Linux
- Node.js (LTS)
- Android Studio mit Android SDK
- Java/JDK-Version passend zur installierten Android-Gradle-Version

## Projekt vorbereiten
1. ZIP entpacken.
2. Im Projektordner ein Terminal öffnen.
3. `npm install`
4. `npx cap add android`
5. `npx cap sync android`
6. `npx cap open android`

## APK bauen
In Android Studio: Build > Build Bundle(s) / APK(s) > Build APK(s).
Die Debug-APK liegt normalerweise unter `android/app/build/outputs/apk/debug/app-debug.apk`.

## Hinweise
- App-ID: `de.sugarkingdom.game`
- App-Name: Sugar Kingdom
- Der Spielstand wird lokal im WebView über localStorage gespeichert.
- Dies ist ein erster Entwicklungsstand. Missionen, Balancing, Animationen, Spezialsteine, Audio, Icons und gründliche Gerätetests müssen weiter ausgebaut werden.
