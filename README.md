# BooksByToon – Drupal Webshop Project

Dit project is een Drupal 11 webshop die werd ontwikkeld als onderdeel van een studentenproject aan **HOGENT**.  
De webshop focust op het verkopen en beheren van boeken, met aandacht voor contentbeheer, gebruikersrollen en e-commerce functionaliteit.

---

##  Rollenoverzicht

### Administrator
**Doel:** Volledig beheer van de website

**Rechten:**
- Volledige toegang tot Drupal administratie
- Beheren van contenttypes, views, blocks en taxonomie
- Beheren van gebruikers en rollen
- Beheren van producten, productvariaties en prijzen
- Site-configuratie en modules beheren

**Gebruik:**
- Enkel voor sitebeheer en ontwikkeling

---

### Moderator
**Doel:** Inhoud beheren zonder technische toegang

**Rechten:**
- Boeken (content) aanmaken, bewerken en verwijderen
- Producten koppelen aan content
- Alles van commerce beheren
- Afbeeldingen en categorieën beheren
- Pagina's beheren
- Geen toegang tot systeeminstellingen of gebruikersbeheer
- URL's beheren

**Gebruik:**
- Voor een algemene bewerker van paginas die acties kan opzetten en tonen

---

### Content Manager
**Doel:** Inhoud beheren zonder technische toegang

**Rechten:**
- Boeken (content) aanmaken, bewerken en verwijderen
- Producten koppelen aan content
- Afbeeldingen en categorieën beheren
- Geen toegang tot systeeminstellingen of gebruikersbeheer

**Gebruik:**
- Voor redacteurs of beheerders van het boekenaanbod

---

### Authenticated User (Geregistreerde gebruiker)
**Doel:** Klanten die een account hebben

**Rechten:**
- Registreren, wachtwoord veranderen en inloggen
- Boeken bekijken
- Producten toevoegen aan winkelmandje
- Bestellingen plaatsen
- Lezen van about us
- Contactformulier gebruiken

**Gebruik:**
- Standaard webshopgebruikers

---

### Anonymous User (Bezoeker)
**Doel:** Niet-ingelogde bezoekers

**Rechten:**
- Publieke pagina’s bekijken (homepage, boekenoverzicht, detailpagina’s)
- Contactpagina bekijken
- Lezen van about us
- Geen aankopen zonder account 

---

## Voorbeeldgebruikers

| Gebruiker | Wachtwoord | Rol | Beschrijving |
|---------|----|----|-------------|
| admin | "drupal" | Administrator | Sitebeheer en ontwikkeling |
| mod_toon | "drupal" | Moderator | Beheer van boeken en content |
| content_toon | "drupal" | Content Manager | Beheer van boeken en content |
| user_toon | "drupal" | Authenticated User | Klant die aankopen kan doen |

---

## Auteur

**Naam:** Toon Vanpoucke  
**E-mail:** toon.vanpoucke@student.hogent.be  
**Opleiding:** Toegepaste Informatice HoGent – CMS

---
