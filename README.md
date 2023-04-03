# Seriium

## Aplikacija za vođenje evidencije serija

Mobilna aplikacija Seriium je nastala na faksu kao projekt za konstrukcijske vježbe za predmet **Programiranje mobilnih aplikacija**.

Aplikacija služi za vođenje evidencije serija kako bi si korisnik mogao pratiti gdje je stao sa gledanjem.

Tu su dakle _prijava i registracija_ koji rade putem Firebase-a za koje postoji opcija potvrde profila mail adresom.

---

Kada se prijavi u aplikaciju, korisnik može:

- vidjeti svoju listu serija
- pretražiti serije
- pogledati detalje pojedine serije
- dodavati i micati serije iz svoje liste
- označavati i odznačavati pogledane sezone i epizode

Uz to se nalazi i detaljna statistika gdje korisnik može vidjeti koliko je sveukupno vremena potrošio gledajući serije, ukupan broj pogledanih serija, sezona i epizoda, te najgledanija dva žanra.

Korisnik ima i uvid u svoj profil na kojemu može mjenjati sve podatke.

---

Projekt je rađen u Android Studiu, a za programski jezik izabrana je **Java** uz **Firebase** bazu podataka. Primjenjena su znanja korištenja: activitya, adaptera, fragmenta, listenera, izrade modela i služenja network-om.
\
\
[![My Skills](https://skills.thijs.gg/icons?i=androidstudio,java,firebase)](https://skills.thijs.gg)

Za izlistavanje serija, sezona i epizoda korišten je **RecyclerView**, a za dohvaćanje podataka o serijama koristi se **Retrofit** koji se spaja na [EPISODATE API](https://www.episodate.com/api) radi dohvaćanja podataka o serijama.
