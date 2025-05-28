# Käyttö tapaukset

Kaaviossa on kuusi eri käyttötapausta.

Ne ovat

1. Selaa Äänestyksiä
2. Valitse Äänestys
3. Äänestäminen
4. Näytä Äänestystilanne
5. Poista Äänestys
6. Uusi Äänestys


1: Selaa Äänestyksiä
Käyttäjät: Käyttäjä
Laukaisija: Käyttäjä haluaa tutustua olemassa oleviin äänestyksiin
Esiehto: Käyttäjä on kirjautunut sovellukseen
Jälkiehto: Näytetään lista saatavilla olevista äänestyksistä

2: Valitse Äänestys

Käyttäjät: Käyttäjä
Laukaisija: Käyttäjä haluaa valita äänestyksen osallistuakseen siihen
Esiehto: Käyttäjä on selannut äänestyksiä
Jälkiehto: Valittu äänestys on aktiivisena käyttäjän istunnossa

3: Äänestäminen

Käyttäjät: Käyttäjä
Laukaisija: Käyttäjä haluaa antaa äänen valitussa äänestyksessä
Esiehto: Käyttäjä on valinnut äänestyksen
Jälkiehto: Ääni on tallennettu

4: Näytä Äänestystilanne

Käyttäjät: Käyttäjä, Ylläpitäjä
Laukaisija: Käyttäjä tai ylläpitäjä haluaa tarkastella äänestyksen tilannetta
Esiehto: Äänestys on valittu
Jälkiehto: Äänestystilanne on näytetty

5: Poista Äänestys

Käyttäjät: Ylläpitäjä
Laukaisija: Ylläpitäjä haluaa poistaa äänestyksen järjestelmästä
Esiehto: Ylläpitäjä on kirjautunut sisään
Jälkiehto: Äänestys on poistettu järjestelmästä

6: Uusi Äänestys

Käyttäjät: Ylläpitäjä
Laukaisija: Ylläpitäjä haluaa luoda uuden äänestyksen
Esiehto: Ylläpitäjä on kirjautunut sisään
Jälkiehto: Uusi äänestys on lisätty järjestelmään