# 🔐 Cryptalk

**Cryptalk** ist ein sicherer Messenger mit End-to-End-Verschlüsselung (RSA + AES), einfacher grafischer Benutzeroberfläche (Tkinter) und Client-Server-Kommunikation über TCP-Sockets.

---

## 📦 Features

- ✅ Ende-zu-Ende-Verschlüsselung (RSA + AES)
- ✅ GUI mit Tkinter
- ✅ Client-Server-Architektur
- ✅ Mehrere Clients gleichzeitig möglich
- 🔜 Gruppenchat, Key-Verifikation, Signaturen

---

## 🖥️ Voraussetzungen

Installiere die benötigten Python-Pakete mit:

```bash
pip install cryptography
```

Tkinter ist bei den meisten Python-Installationen bereits enthalten. Falls nicht:

```bash
sudo apt install python3-tk  # Für Linux
```

---

## 🚀 Starten

### 1. Server starten

```bash
python server.py
```

### 2. Clients starten

In separaten Terminals:

```bash
python client.py
```

### 3. Chatten 🔐

Gib Nachrichten in die GUI ein – sie werden automatisch verschlüsselt, übertragen und entschlüsselt.

---

## 🔐 Sicherheit

- Nachrichten werden mit einem zufälligen AES-Schlüssel verschlüsselt.
- Der AES-Schlüssel wird mit dem RSA-Public-Key des Empfängers verschlüsselt.
- Nur der Empfänger kann mit seinem Private Key die Nachricht entschlüsseln.

---

---

## 📌 To-Do

- [ ] Public-Key-Management
- [ ] Nutzer-Authentifizierung
- [ ] Gruppenchat
- [ ] Nachrichtenverlauf (lokal gespeichert & verschlüsselt)

---

## 🛠️ Lizenz

MIT License – Feel free to use, modify, and contribute!

---

## 💬 Kontakt

Projekt von [Nico]  

