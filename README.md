# Codetext

**Text mit einem Passwort verschlüsseln und wieder entschlüsseln – direkt im Browser.**

Du schreibst einen Text, wählst ein Passwort und bekommst einen verschlüsselten Code. Nur wer das Passwort kennt, kann den Text wieder lesen.

## So funktioniert's

1. `index.html` im Browser öffnen
2. **Verschlüsseln:** Text eingeben, Passwort wählen, auf *Verschlüsseln* klicken
3. Den Code kopieren und verschicken
4. **Entschlüsseln:** Code einfügen, gleiches Passwort eingeben – fertig

## Sicherheit

- AES-256-GCM, Schlüssel aus dem Passwort mit PBKDF2 (200 000 Runden)
- Läuft komplett im Browser über die Web Crypto API
- Kein Server, keine Speicherung, kein Tracking

> ⚠️ **Passwort weg = Text weg.** Es gibt keine Möglichkeit, den Text ohne Passwort zurückzuholen.

## Lizenz

[GPL-3.0](LICENSE)
