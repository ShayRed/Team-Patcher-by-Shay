# Informationen

**Wichtig:**  
Dieses Tool dient ausschließlich als **Team-Patcher**, **nicht** als Live-Patcher.  
Es soll die Zusammenarbeit und den Austausch von Dateien zwischen Teammitgliedern vereinfachen.

---

# Anleitung

## Schritt 1

1. Lade die drei Ordner auf deinen Server hoch, die im Paket enthalten sind:  
   - `Client`  
   - `Client_SRC`  
   - `Proto`  

2. Nachdem du die Ordner erfolgreich hochgeladen hast, kannst du sie von deinem Desktop oder lokalen Speicher löschen.

---

## Schritt 2

1. Klicke im Tool auf **Patchliste** und wähle dort die Ordner aus, die du als Patch vorbereiten möchtest.  
2. Erklärung:  
   - Dateien aus dem **Client_SRC** gehören in den Ordner `Client_SRC` auf dem Server.  
   - Dateien aus dem **Client** kommen in den Ordner `Client`.  
3. Die Datei **patchlist.txt** wird immer in dem Ordner gespeichert, den du für das Patchen vorbereitet hast (z. B. `Client_SRC`).

---

## Schritt 3

In den **Update-Optionen** kannst du anschließend auswählen, für welchen Bereich ein Patch vorbereitet wurde.

---

# Hinweise

- Unter **Server-IP-Adresse** trägst du die IP deines (Apache-)Servers ein.  
- Der Patcher erstellt automatisch eine Datei **config.txt**, in der die IP gespeichert ist.  
  Diese kann jederzeit manuell geändert werden.
