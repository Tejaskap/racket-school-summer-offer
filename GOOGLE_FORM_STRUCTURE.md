# Google Form Setup — Padel Sommer Kurs 2026

Build this as a **Google Form** with 4 pages (use "Page Break" to separate sections).

---

## **PAGE 1 — Intro & Personal Details**

**Form Title:** Racket School – Padel Sommer Kurs 2026

**Form Description:**
```
Anmeldeformular für die Padel Sommer Blöcke 2026
Wir freuen uns auf deine Anmeldung! Bitte fülle dieses Formular vollständig aus.

Start Block 1: 02. Mai 2026
```

**Fields:**

1. **Vor- und Nachname** *(Short answer)*
   - Required: Yes

2. **E-Mail-Adresse** *(Email)*
   - Required: Yes

3. **WhatsApp-Nummer** *(Short answer)*
   - Description: "Alle Kursinformationen laufen über WhatsApp"
   - Required: Yes

4. **Geburtsdatum** *(Date)*
   - Required: Yes

5. **Wohnort / Stadt** *(Short answer)*
   - Required: Yes

---

## **PAGE 2 — Course Selection**

**Fields:**

6. **Welches Level passt zu dir?** *(Multiple choice)*
   - Required: Yes
   - Options:
     - Anfänger (START RALLY, 12:30–14:00) — Ich habe ein paar Mal gespielt, aber noch keine richtige Technik
     - Amateure (COURT CLUB, 14:00–15:30) — Ich spiele regelmäßig und möchte mich gezielt verbessern
     - Fortgeschrittene (PERFORMANCE CLUB, 15:30–17:00) — Ich spiele Matches und will auf höherem Niveau trainieren
     - Mittwoch START RALLY (17:00–18:30) — Anfänger, unterschiedlicher Tag
     - Mittwoch COURT CLUB (18:30–20:00) — Amateure, unterschiedlicher Tag
     - Donnerstag START RALLY (18:00–19:30) — Anfänger, unterschiedlicher Tag
     - Donnerstag PERFORMANCE CLUB (19:30–21:00) — Fortgeschrittene, unterschiedlicher Tag
     - Ich bin unsicher — bitte empfehlt mir ein Level

7. **Hast du bereits Padel-Erfahrung?** *(Multiple choice)*
   - Required: Yes
   - Options:
     - Nein, absoluter Anfänger
     - Ja, gelegentlich gespielt (weniger als 6 Monate)
     - Ja, regelmäßig (6 Monate – 2 Jahre)
     - Ja, seit mehr als 2 Jahren

8. **Wenn ja — bitte kurz beschreiben: Wo spielst du normalerweise, wie oft pro Woche?** *(Paragraph text)*
   - Required: No

9. **Hast du Interesse an der Schnupperstunde (15 Min, kostenpflichtig) um dein Level zu bestimmen?** *(Multiple choice)*
   - Required: No
   - Options:
     - Ja, bitte kontaktiert mich
     - Nein, ich weiß bereits welches Level passt

---

## **PAGE 3 — Health & Emergency**

**Fields:**

10. **Hast du gesundheitliche Einschränkungen, die für das Training relevant sind?** *(Multiple choice)*
    - Required: Yes
    - Options:
      - Nein
      - Ja — bitte unten angeben

11. **Falls ja, bitte beschreiben:** *(Paragraph text)*
    - Required: No

12. **Name & Telefonnummer einer Notfallkontaktperson** *(Short answer)*
    - Required: Yes

13. **Hast du eine Krankenversicherung?** *(Multiple choice)*
    - Required: Yes
    - Options:
      - Ja
      - Nein

---

## **PAGE 4 — Payment & T&C**

**Section Header (use Text field for this):**
```
Zahlungsinformationen

Der Kursbeitrag beträgt:
• €266 (Anfänger / Amateure) für 7 Sessions
• €350 (Fortgeschrittene) für 7 Sessions

Die Zahlung erfolgt vor der ersten Session.
Der Betrag ist nicht erstattungsfähig.
```

**Fields:**

14. **Zahlungsart** *(Multiple choice)*
    - Required: Yes
    - Options:
      - Ich zahle per Überweisung
      - Ich zahle per PayPal
      - Ich zahle bar vor Ort

15. **Wie hast du von uns erfahren?** *(Multiple choice)*
    - Required: No
    - Options:
      - Instagram (@racket_school)
      - Empfehlung / Freunde
      - Nice Racket Club
      - Sonstiges

16. **Bemerkungen oder Fragen an uns** *(Paragraph text)*
    - Required: No

17. **AGB & Haftungsausschluss** *(Checkbox)*
    - Required: Yes
    - Options:
      ```
      ☐ Ich habe die AGB gelesen und akzeptiere sie.

      Ich bestätige:
      • Die Kursgebühr (€266 oder €350) ist nicht erstattungsfähig
      • Ich verpflichte mich zu allen 7 Sessions in meiner Gruppe
      • Session-Tausche organisiere ich selbst über WhatsApp
      • Ich übernehme die volle Verantwortung für meine körperliche Fitness und Sicherheit
      • Ich bin versichert (Krankenversicherung)
      • Ich werde der WhatsApp-Gruppe hinzugefügt und lese alle Nachrichten dort
      ```

---

## **Form Settings**

**Confirmation Message:**
```
Vielen Dank für deine Anmeldung!

Wir bestätigen dir per WhatsApp:
• Dein Level & Trainingszeit
• Deine erste Session (Datum & Uhrzeit)
• Zahlungsinformationen
• WhatsApp-Gruppen-Link

Fragen? Schreib uns: https://wa.me/4915255191566

Bis bald auf dem Platz! 🎾
```

**Notifications:**
- Enable: Email notifications to your email when form is submitted
- Set response destination: Google Sheets (auto-create or link to existing sheet)

---

## **Setup Checklist**

- [ ] Create Google Form with title "Racket School – Padel Sommer Kurs 2026"
- [ ] Add all 17 fields across 4 pages
- [ ] Mark required fields
- [ ] Set confirmation message
- [ ] Enable response collection (Google Sheet)
- [ ] Get shareable link
- [ ] Add form link to website (embed or link)
- [ ] Test form end-to-end
- [ ] Share link via Instagram, WhatsApp
