# OutfitDiary

## Sovelluksen toiminnot

* Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen.
* Käyttäjä pystyy lisäämään sovellukseen, muokkaamaan ja poistamaan asukokonaisuuksia (otsikko, kuvaus, kuvat).
* Käyttäjä näkee sekä itse lisäämänsä että muiden käyttäjien lisäämät asut.
* Käyttäjä pystyy etsimään asuja hakusanalla (esim. koulu, toimisto. juhlat).
* Sovelluksessa on käyttäjäsivut, jotka näyttävät jokaisesta käyttäjästä tilastoja ja käyttäjän lisäämät asukokonaisuudet.
* Käyttäjä pystyy valitsemaan asulle yhden tai useamman luokittelun (esim. mihin asun voisi pukea). Mahdolliset luokat ovat tietokannassa.
* Käyttäjä pystyy kommentoimaan muiden käyttäjien lisäämiä sekä omia asukokonaisuuksia.

## Sovelluksen asennus

Asenna `flask`-kirjasto:

```
$ pip install flask
```

Luo tietokannan taulut ja lisää alkutiedot:

```
$ sqlite3 database.db < schema.sql
$ sqlite3 database.db < init.sql
```

Voit käynnistää sovelluksen näin:

```
$ flask run
```
