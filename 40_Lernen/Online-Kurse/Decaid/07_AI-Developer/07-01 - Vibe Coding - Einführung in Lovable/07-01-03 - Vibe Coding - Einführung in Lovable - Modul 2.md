---
typ: Kurs
plattform:
  - Decaid
instruktor: Philipp Hoffmann
status:
  - 🔴 Nicht gestartet / 🟡 In Arbeit / 🟢 Abgeschlossen
kurs_link: https://app.decaid.academy/path-player?courseid=vibe-coding-einfuhrung-in-lovable&unit=68babbd400490371310dcbf8Unit
tags:
  - lernen
  - weiterbildung
  - ai
  - developer
  - loveable
  - ki
  - decaid
erstellt: 2026-03-13
---
# 🎓 Kurs: 07-01-01 - Vibe Coding - Einführung in Lovable - Modul 2

> [!abstract] Kurs-Beschreibung
> 

# 📂 Kurs-Materialien


##  Superbase Datenbank 02:43

##  Datenbank 03:23

##  Datenbank-Theorie 04:46

##  Superbase Einrichtung 03:52

##  Benutzer-Authentifizierung 04:03

##  Tabellen in Supabase 02:34

##  Table Supabase

![[07-01-03_01_Table.pdf]]

### Praktische Übung

### Erste Tabelle ändern

1. Geben Sie in Lovable folgenden Prompt ein: „Füge in meiner `profiles`-Tabelle in Supabase Felder für Vorname (`first_name`) und Nachname (`last_name`) hinzu und entferne das Feld `full_name`.“    
2. Lovable wird daraufhin erneut SQL-Code generieren. Sie müssen diesen bestätigen, um Ihre Datenbank zu ändern.    
3. Sobald dies abgeschlossen ist, gehen Sie in Supabase zu **Database > Schema Visualizer** und überprüfen Sie, ob die Änderungen erfolgreich angewendet wurden.
    

**Struktur der `profiles`-Tabelle (Beispiel):**

- `id` (uuid)    
- `user_id` (text / auth.users.id)    
- `username` (text)    
- `avatar_url` (text)    
- `created_at` (timestamptz)    
- `updated_at` (timestamptz)    
- `vorname` (text)    
- `nachname` (text)
##  Integration von Supabase 06:25

##  Supabase Prompt

![[07-01-03_02_Supbase.pdf]]

### Praktische Übung

### Supabase Auth integrieren

1. Wechseln Sie zu Ihrem Projekt (z. B. dem Garten-Projekt, bei dem bisher nur eine Landingpage existiert).
    
2. Geben Sie in Lovable folgenden Prompt ein: „Ich möchte eine Benutzerregistrierung und einen Login erstellen, damit sich Benutzer mit E-Mail/Passwort registrieren und anmelden können und danach auf ein persönliches Dashboard zugreifen können.“.
    
3. Lovable wird daraufhin wahrscheinlich einen längeren SQL-Befehl schreiben, um die notwendigen Datenbankstrukturen vorzubereiten (z. B. einen Trigger, der automatisch ein Profil erstellt, wenn sich ein Benutzer registriert).
    
4. Klicken Sie auf **„Apply Changes“**: Lovable erstellt nun im Hintergrund die Tabellen sowie die `/auth`-Seite und das `/dashboard`.
    
5. Testen Sie anschließend die Registrierung und den Login, um zu sehen, ob Sie nach der Anmeldung erfolgreich auf das Dashboard zugreifen können.
##  Supabase Authentifizierung & Profil Setup 04:21

##  Row Level Security 07:15

##  Row Level Security Prompt 

![[07-01-03_03_RLS.pdf]]

### Praktische Übung

### RLS implementieren und prüfen

1. Geben Sie in Lovable folgenden Prompt ein: „Ist meine App mit RLS gegen unbefugten Zugriff gesichert?“    
2. Das Ergebnis in Lovable könnte wie folgt aussehen:    
    - Aktuelle Sicherheit: RLS ist auf der Tabelle `profiles` aktiviert.        
    - Benutzer können nur ihre eigenen Profile einsehen oder bearbeiten.        
    - Die Authentifizierung ist erfolgreich implementiert.
        
3. Gehen Sie in Supabase zu **Authentication > Policies**, um Ihre RLS-Richtlinien (Policies) einzusehen:    
    - Dort sollten Einträge stehen wie: „Users can insert their own profile“, „Users can update their own profile“ oder „Users can view their own profile“.        
4. Falls keine RLS-Richtlinien vorhanden sind, bitten Sie Lovable einfach darum, entsprechende Richtlinien zu erstellen.
## Modulabschluss 01:50

---
*Zuletzt bearbeitet: 2026-03-13*