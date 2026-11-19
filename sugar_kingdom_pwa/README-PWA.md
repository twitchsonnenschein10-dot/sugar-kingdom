# Sugar Kingdom – PWA-Vorbereitung

Dieses Paket enthält die bisherige Sugar-Kingdom-Spielversion, ergänzt um die Grundlagen einer installierbaren Progressive Web App (PWA):

- Web-App-Manifest mit Name, Farben und Symbolen
- Service Worker für Offline-Caching
- App-Symbole in 192 × 192 und 512 × 512
- Start im eigenständigen App-Fenster

## Wichtig
Das ist noch keine veröffentlichte Website und keine fertige APK. Für PWABuilder muss diese Website zuerst über eine HTTPS-Adresse erreichbar sein. Danach kann die Adresse bei https://www.pwabuilder.com/ eingegeben werden.

## Lokal testen
Die Dateien müssen über einen lokalen Webserver oder HTTPS ausgeliefert werden. Das direkte Öffnen von `index.html` per Doppelklick aktiviert den Service Worker nicht.

## Spielstände
Der aktuelle Prototyp speichert den Fortschritt lokal im Browser/auf dem jeweiligen Gerät. Wenn zwei Geräte denselben Link nutzen, haben sie deshalb getrennte Spielstände. Es gibt noch keine Cloud-Synchronisierung.

## Nächster Schritt
Die Website kostenlos hosten (z. B. mit Netlify oder GitHub Pages) und anschließend die veröffentlichte HTTPS-Adresse in PWABuilder eingeben.
