---
marp: true
author: Jos van Reenen
size: 16:9
theme: gaia
paginate: true
footer: :copyright: Hogeschool Utrecht 2024
---

<style>
  :root {
    --color-background: #fff;
    --color-foreground: #000;
    --color-highlight: #f96;
    --color-dimmed: #888;
  }
  
  :root h1 {
    color: #00A1E1;
    }
    </style>

# Welkom bij de SD Rampup Kick-off
Vandaag op het programma: 
* :wave: Kennismaken met Jos
* :exclamation: Waarom de Rampup bestaat
* :question: Wat houdt de Rampup in
* :calendar: Hoe zien de komende weken er uit?
* :pencil: Het project!

--- 

# Jos van Reenen
* :briefcase: Information Engineering :arrow_right: :briefcase: Master of Informatics (Information Systems Architecture) 
* Trainee :arrow_right: Onderzoeker :arrow_right: Docent :arrow_right: Hogeschooldocent I
* Studieadviseur SD Duaal
* Coördinator SD Duaal jaar 1 & 2
* Curriculumcommissie SD
* :man: :ring: :woman: & :boy: :girl: :boy: :boy: :girl:
* :netherlands: :us: :de: (:fr: :es:)

---

# Waarom bestaat de Rampup
Up to speed komen met:

* Programmeren in teamverband
* Samenwerken op (de)centrale wijze
* Versiebeheer van software
* Interacteren met stakeholders
* Documenteren & Presenteren

---

# Wat houdt de Rampup in
* Aftrap (nu) :arrow_left:
* Figma, Django & Python introductie
* User Story management & definitie
* Git & GitHub workshop 
* Oplevering & feedback half-way
* HTML, CSS & JS
* Persistentie met python & SQL
* Oplevering & afronding Rampup

---

# Hoe zien de komende weken er uit?

* Maandags: check-in 15 min / team & Check-out 15 min / team
* Dinsdags: check-in 15 min / team & Check-out 15 min / team
* Woensdag: Rampup workshops @HU
* Donderdag: Hybride lesdag - Huiswerk & Workshops mogelijk
* Vrijdag: Lesdag - BoK vak & SB / SLB programma

* Volgende week dus de 1e workshop

---

# Het project, waar gáát dit over?
* In teamverband dmv Python & Frontend technieken een applicatie in elkaar draaien rondom 1 centraal thema. 
* Onderdeel van je beroepstaak voor BT1, naast de onboarding.
* Praat je met de opdrachtgever (c'est moi :)) en bepaal je de scope
* Werk in Python en op het Django Framework, gebruik een database maak er iets moois van.
* Het doel is dat je daadwerkelijk leert samenwerken op HBO niveau en leert meedraaien in een team.

---

# De casus
Ontwikkel een Twitter/X/Reddit lookalike (web) applicatie waarin gebruikers berichten kunnen plaatsen en daar commentaar op kunnen geven.

_Grafisch design is geen beoordelingscriterium_

--- 

# User stories (1/2)
* Registratie van nieuwe users, met password
* Een user kent de volgende authorisatieniveaus : read-only, read-write, administrator
* Nieuwe users krijgen standaard de status : read-only
* Users met de status administrator kunnen het authorisatieniveau van users wijzigen
* Users kunnen na registratie inloggen en uitloggen
* if(ingelogd): toon de meest recente berichten (xx/pagina & optie tot doorklikken naar volgende pagina / continuous scrolling)

---

# User stories (2/2)
* Er kunnen berichten worden gepost
* Er kan commentaar op de berichten worden gepost
* Een user met het authorisatieniveau read-only mag alleen maar berichten en commentaar op berichten lezen
* Een user met het authorisatieniveau read-write of administrator mag berichten én commentaar op berichten lezen én schrijven
* Bij het bericht of bij het commentaar wordt getoond door wie het bericht is geplaatst en wanneer

---

# User stories (3/2)
* Berichten kunnen groeperen per onderwerp, bijvoorbeeld “Gaming”, “AI”, “Climate”, “Zaterdagavond”, “Voetbal”
* Een functionaliteit voor “Likes” van berichten en van commentaar
* Een administrator kan berichten modereren, als in zorgen dat deze voor andere users niet meer leesbaar zijn, bijvoorbeeld wanneer sprake is van hate-speech, spam, of andere vormen van abuse
* Notificatie mechanisme, bijv. e-mail of pushbericht wanneer er een nieuw bericht wordt geplaatst onder een bericht dat je hebt ge-like-t en/of waar je commentaar op hebt gegeven.

---

# Wat gaan we nu doen?
We gaan: 
* Groepjes formuleren - teamnaam!
* Python werkomgeving installeren
* Teamafspraken maken
* GitHub Classroom opdracht accepteren
* (Plan maken voor komende weken)

---

# Groepjes formuleren
* Zit je in dezelfde klas?
* Wie kan er maandags/dinsdags doorwerken?
* Wie werkt bij hetzelfde bedrijf

---

# Python werkomgeving installeren
* Registreer je bij jetbrains als student
* Download Pycharm Pro
* Installeer Python @ latest
* Check Django installatie

---

# Teamafspraken maken
* Wat is je teamnaam?
* Don't be that guy, be this guy
* Wat is jullie ambitie?
* Hoe bereik je die?

---

# GitHub Classroom opdracht accepteren
* Github Educational Benefits
* Classroom-repo's bevatten eventueel boilerplate code
  * Staan onder beheer van je docent

---

# Plan maken voor de komende weken
Optioneel