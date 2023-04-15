# Seriium

## Mobilna aplikacija za vođenje evidencije serija

Mobilna aplikacija Seriium je nastala na faksu kao projekt za konstrukcijske vježbe za predmet **Programiranje mobilnih aplikacija**.

Aplikacija služi za vođenje evidencije serija kako bi si korisnik mogao pratiti gdje je stao sa gledanjem.

Projekt je rađen u Android Studiu, a za programski jezik izabrana je **Java** uz **Firebase** bazu podataka. Primjenjena su znanja korištenja: activitya, adaptera, fragmenta, listenera, izrade modela i služenja network-om.

[![My Skills](https://skills.thijs.gg/icons?i=androidstudio,java,firebase)](https://skills.thijs.gg)

Za izlistavanje serija, sezona i epizoda korišten je **RecyclerView**, a za dohvaćanje podataka o serijama koristi se **Retrofit** koji se spaja na [EPISODATE API](https://www.episodate.com/api).

Tu su _prijava i registracija_ koje rade putem Firebase-a i za koje postoji potvrda profila mail adresom.

---

### Kada se prijavi u aplikaciju, korisnik može:

- vidjeti svoju listu serija
- pretražiti serije
- pogledati detalje pojedine serije
- dodavati i micati serije iz svoje liste
- označavati i odznačavati pogledane sezone i epizode
- ima uvid u bogatu statistiku
- ima uvid u svoj profil
- izmjeniti korisničke podatke za svoj profil

---

### Pokretanje projekta

Za pokretanje projekta potrebno je kreirati vlastitu Firebase bazu, potom dobivene podatke za spajanje zalijepiti u `app/build/generated/res/google-services/debug/values.xml`.
