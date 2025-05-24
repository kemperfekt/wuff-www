# Wuffchat / DogBot – Customer Journey (MVP)

Diese Customer Journey beschreibt die dialogbasierte Nutzerführung von Wuffchat (DogBot) im MVP-Status – mit Fokus auf:

- Empathische Nutzerbindung
- Relevante Datenerhebung
- Conversion zur kostenpflichtigen Beratung

---

## Übersicht der Journey

| Phase              | Nutzerinteraktion                                                                 | Ziel                                                    | Gesammelte Daten                                |
|--------------------|-----------------------------------------------------------------------------------|---------------------------------------------------------|--------------------------------------------------|
| **1. Symptomeingabe** | *„Was ist los? Was fühlst Du, wenn Dein Hund sich so verhält?“*                   | Einstieg durch Emotionalität & Problemorientierung      | Gefühl, Problembeschreibung                      |
| **2. Hundeperspektive** | *„Darf ich Dir sagen, wie ich mich dabei fühle, [Name Mensch]? Wie heiße ich?“* | Perspektivwechsel, Nähe, Identifikation mit dem Hund    | Name des Hundes, ggf. Name des Menschen          |
| **3. Kontextfrage**    | *„Darf ich Dich etwas besser kennenlernen?“*                                     | Personalisierte Diagnose, Vertrauen                    | Alter, Rasse, Geschlecht, Geburtsdatum des Hundes |
| **4. Diagnose**        | *„Bin ich kastriert? War ich schon immer bei Dir?“*                              | Erfassung erziehungsrelevanter Rahmenbedingungen        | Kastration, Herkunft (seit Welpe?)               |
| **5. Lernaufgabe**     | *„Möchtest Du unsere Lernaufgabe per E-Mail erhalten?“*                          | Mehrwert schaffen, Opt-in ermöglichen                   | E-Mail-Adresse, Opt-In für weitere Infos         |
| **6. CTA (Buchung)**   | *„Wenn Du Unterstützung brauchst: 60 Min Online-Beratung für 69 €.“*              | Conversion zur Beratung mit dem Menschen (Trainer)      | Buchung via Zoho Bookings + Checkout (Stripe)    |

---

## Technische Integrationen (MVP)

- **Zoho Bookings** für Terminvereinbarung
- **Zoho Checkout** (mit Stripe) für Zahlungsabwicklung
- **Zoho CRM / Flow** zur Speicherung von Kontaktdaten
- **E-Mail-Versand** (z. B. mit PDF oder Zusammenfassung) nach Opt-in