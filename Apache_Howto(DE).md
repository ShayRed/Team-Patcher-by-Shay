# 🧩 Apache Installation unter FreeBSD

Diese Anleitung erklärt, wie du Apache 2.4 unter FreeBSD installierst und einrichtest.

---

## 🧭 Schritt 1: Installiere Apache mit dem FreeBSD-Paketmanager:

pkg install apache24



## 🚀 Schritt 3: Apache beim Systemstart aktivieren


sysrc apache24_enable=YES



## ▶️ Schritt 4: Apache starten


service apache24 start


## Überprüfe den Status:

service apache24 status



Wichtig: Der Pfad befindet sich unter FreeBSD immer an dieser Stelle. Im Verzeichnis data werden auch die Ordner und Dateien für den Patcher abgelegt.

## Webverzeichnis	/usr/local/www/apache24/data