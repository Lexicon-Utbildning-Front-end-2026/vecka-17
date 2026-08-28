# Schema Vecka 17: AI-arbetsflöde, idé och projektstart

Under första veckan går vi från AI-grunder och idéarbete till en första tydlig projektplan och den första implementationen. Målet är inte perfekta dokument, utan en tillräckligt tydlig riktning för att kunna börja bygga.

---

## Måndag: AI-grunder och mini-PRD (kort produktplan)

Vi introducerar projektuppgiften, pratar om AI-assisterad utveckling och använder AI som stöd för att utveckla och avgränsa en projektidé.

### Kort om projektet

Du ska bygga ett mindre portfolio-projekt i Next.js, med eller utan stöd av AI.

Projektet ska ha en tydlig målgrupp, lösa ett konkret problem eller behov och innehålla ett fungerande kärnflöde som går att demonstrera. Ni får gärna ta sånt vi gått igenom för att repetera det, eller om ni hellre vill, något nytt som auth eller liknande.

AI kan användas för idéarbete, planering, kod, felsökning och review, men du ansvarar själv för att förstå, kontrollera och kunna förklara det du gjort.

### Mål för dagen

- Förstå uppgiften
- Välja en idé
- Börja avgränsa MVP (minsta användbara versionen)
- Skapa ett första mini-PRD (kort produktplan)
- Göra en enkel skiss, mood board (visuell känsla) eller user flow (användarflöde)

### Förmiddag: Lite teori och presentation av uppgift

- Projektuppgift, mål och grundkrav
- Grundläggande mental modell för AI-assisterad utveckling
- Prompting och hur man kan använda AI för att utveckla en idé
- Första steget mot mini-PRD, prototypval och avgränsning

### Eftermiddag: Eget arbete med planering och projektidé

- Brainstorma och välj projektidé
- Beskriv produktens kärna i en mening
- Skriv 3-5 möjliga user stories
- Gör en första MVP-avgränsning
- Identifiera största risken eller osäkerheten
- Använd AI som kritisk samtalspartner (t ex genom grill-with-docs), inte som ensam beslutsfattare

---

## Tisdag: AI-arbetsflöde, PRD och tickets (små uppgifter)

Vi fortsätter från idé till mer konkret planering. Fokus ligger på att göra projektet genomförbart, skapa små vertikala tickets och få tidig feedback.

### Mål för dagen

- Förstå vertikala tickets
- Göra PRD:t mer användbart - PRD -> Specs
- Från PRD -> Tickets

### Förmiddag: Gemensam genomgång

- Genomgång av vertikal och horisontell uppdelning
- Demo av hur ett kort PRD kan bli små demonstrerbara tickets
- Exempel på hur man väljer en första genomförbar feature (blocking)

### Förmiddag: Elevdemo AI-flöde

- Demo av ett verkligt AI-arbetsflöde
- Fokus på hur AI kan användas med kontroll, inte bara på slutresultatet
- Kort tid för frågor och gemensamma reflektioner

### Eftermiddag: Presentation och godkännande av idé

Vi avtalar tid med varje grupp under eftermiddagen. Varje deltagare visar och förklarar:

- För vem byggs produkten?
- Vilket problem eller behov möter den?
- Vilket är det centrala användarflödet?
- Vad ingår i MVP?
- Vad har valts bort tills vidare?
- Vilken är projektets största risk eller osäkerhet?
- Inspiration och eventuella skisser/protyper

Presentationerna är ett tidigt avstämningstillfälle. Den viktigaste återkopplingen handlar om scope (omfattning). Planen godkänns av lärare eller så får ni tänka vidare och återkomma tills ni har fått godkänt.

---

## Onsdag: Färdigställ planering

Vi färdigställer de viktigaste planeringsdelarna och gör projektet redo för implementation.

### Mål för dagen

- Färdigställa PRD och enkel skiss
- Bestämma teknikval
- Strukturera backlog (lista med kommande uppgifter)
- Välja första vertikala ticket (en liten uppgift som ger synligt värde)
- Skapa repo och GitHub Project

### Förmiddag: Implementation

Innan elevdemon har vi en lärarledd genomgång av implementation:

- Välj en första vertikal ticket och bestäm hur den ska kontrolleras
- Låt agenten genomföra en liten del och kör TypeScript eller relevant test tidigt
- Öva på att stoppa, korrigera och ge konkret feedback till agenten

### Förmiddag: Elevdemo - LM Studio

- Demo av LM Studio tillsammans med Continue och VS Code
- Fokus på ett fungerande end-to-end-flöde
- Kort om möjligheter och begränsningar med lokal modell

### Studentens eget arbete

Deltagare vars plan är godkänd av lärare kan börja implementera och fortsätta utvecklingen.

---

## Torsdag: Implementation

Vi går från planering till kod. Fokus ligger på att välja en liten uppgift, implementera kontrollerat och kunna verifiera att den fungerar.

### Mål för dagen

- Kontrollera scope
- Börja implementera första ticket
- Testa att ge tydlig AI-feedback

### Studentens eget arbete

- Välj en godkänd ticket
- Implementera en liten del
- Kör relevanta kontroller tidigt
- Läs diffen (ändringarna i koden) innan commit (sparad ändring i Git)

---

## Fredag: Fortsatt arbete

Vi fortsätter implementationen. Stäm gärna av lite med gruppen hur arbetet gått hittills och om ert scope känns rimligt. Dela erfarenheter och stötta varandra. Dema gärna för varandra vad ni gjort.

### Mål för dagen

- Se till att göra klart åtminstone en första ticket/issue
- Stäm av arbetet hittills, kommer det hålla eller inte?
- Justera backlog inför vecka 2
