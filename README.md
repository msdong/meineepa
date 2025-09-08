## Datenschutzerklärung für "Meine ePA"
Stand: 08. September 2025

Mit dieser Datenschutzerklärung informieren wir Sie darüber, welche Daten unsere mobile App "Meine ePA" (nachfolgend "App") verarbeitet, wie sie dies tut und welche Rechte Sie haben.

## 1. Verantwortlicher
Andreas Stammer
Behringstr. 12
76646 Bruchsal
E-Mail: support@dumango.com

## 2. Grundprinzip: Lokale Datenverarbeitung ("Local First")
Ihre Privatsphäre ist das Kernstück dieser App. Alle Ihre persönlichen Gesundheitsdaten (Dokumente, Vitalwerte, Termine, Medikamente, Notfalldaten) werden ausschließlich lokal auf Ihrem Gerät gespeichert. Wir als Anbieter haben zu keinem Zeitpunkt Zugriff auf diese Daten.

## 3. Art und Zweck der verarbeiteten Daten
Die App verarbeitet verschiedene Daten, um Ihnen die volle Funktionalität zu bieten:

Profildaten: Ihr Name und Ihre E-Mail-Adresse werden lokal gespeichert, um die App zu personalisieren (z.B. für das Wasserzeichen beim Teilen). Ihr Profilbild wird ebenfalls nur lokal und verschlüsselt abgelegt.

Gesundheitsdaten: Alle von Ihnen eingegebenen oder gescannten Daten wie Diagnosen, Blutwerte, Vitalwerte, Medikamentenpläne, Termine und Notfalldaten werden direkt auf Ihrem Gerät gespeichert.

Nutzungsdaten: Wir erfassen keine Nutzungsdaten zu Analyse- oder Werbezwecken. Ein lokales Aktivitätenprotokoll speichert zur Transparenz lediglich wichtige Aktionen (z.B. "Dokument gelöscht"), die Sie selbst in der App durchführen. Dieses Protokoll verlässt Ihr Gerät nicht.

## 4. Datensicherheit und Verschlüsselung 🔑
Der Schutz Ihrer Daten hat höchste Priorität.

Lokale Verschlüsselung: Alle von Ihnen gespeicherten Dateien (Dokumente, Notfalldaten etc.) werden auf Ihrem Gerät mit dem von Google empfohlenen Industriestandard AES256-GCM verschlüsselt (über die AndroidX Security Bibliothek). Dies stellt sicher, dass die Daten auch bei einem Verlust Ihres Geräts für Unbefugte unlesbar sind.

App-Sperre: Sie können den Zugriff auf die App zusätzlich durch eine PIN oder biometrische Merkmale (Fingerabdruck/Gesichtserkennung) schützen.

## 5. Erforderliche Berechtigungen
Die App fragt nur nach Berechtigungen, die für Kernfunktionen zwingend notwendig sind:

Kamera (CAMERA): Wird ausschließlich für die Funktion "Dokumente scannen" benötigt. Die Bildverarbeitung zur Texterkennung (OCR) findet direkt auf Ihrem Gerät statt.

Benachrichtigungen (POST_NOTIFICATIONS): Erforderlich, um Sie an bevorstehende Termine zu erinnern.

Biometrie (USE_BIOMETRIC): Wird für die optionale App-Sperre per Fingerabdruck oder Gesichtserkennung benötigt.

Exakte Alarme (SCHEDULE_EXACT_ALARM): Notwendig, damit Terminerinnerungen zuverlässig und pünktlich angezeigt werden können.

## 6. Sicheres Teilen von Dokumenten (Firebase)
Sie haben die optionale Möglichkeit, einzelne Dokumente über einen sicheren Link zu teilen. Nur wenn Sie diese Funktion aktiv nutzen, werden Daten an externe Server gesendet.

Prozess: Wenn Sie ein Dokument teilen, wird dieses mit einem neuen, zufälligen Schlüssel Ende-zu-Ende-verschlüsselt und in den sicheren Firebase Storage (Anbieter: Google Ireland Ltd.) hochgeladen. Metadaten zum Link (z.B. das Ablaufdatum und eine anonyme Nutzer-ID) werden in der Firebase Firestore-Datenbank gespeichert.

Keine Lesbarkeit: Weder wir als Anbieter noch Google können die von Ihnen hochgeladenen, verschlüsselten Dokumente entschlüsseln oder einsehen.

Anonyme Authentifizierung: Um geteilte Links Ihrem Konto zuordnen zu können, ohne Ihre Identität zu kennen, verwendet die App Firebase Authentication zur Erstellung einer anonymen Nutzer-ID.

Gültigkeit: Geteilte Links sind nur für eine von Ihnen festgelegte Dauer gültig und können jederzeit von Ihnen widerrufen werden.

Die Datenschutzerklärung von Google finden Sie unter: https://policies.google.com/privacy.

## 7. Ihre Rechte und die Datenlöschung
Da alle primären Daten lokal gespeichert werden, haben Sie die volle Kontrolle.

Rechte: Ihnen stehen die gesetzlichen Rechte auf Auskunft, Berichtigung, Löschung und Einschränkung der Verarbeitung Ihrer Daten zu.

Löschung: Sie können Ihre Daten jederzeit selbst in der App löschen. Eine vollständige Löschung aller Daten erfolgt durch die Nutzung der "Konto löschen"-Funktion in den Einstellungen oder durch die Deinstallation der App von Ihrem Gerät.

## 8. Kontakt und Änderungen
Bei Fragen zum Datenschutz erreichen Sie uns unter der E-Mail-Adresse: support@dumango.com.

Wir behalten uns vor, diese Datenschutzerklärung anzupassen, damit sie stets den aktuellen rechtlichen Anforderungen entspricht oder um Änderungen unserer Leistungen umzusetzen.
