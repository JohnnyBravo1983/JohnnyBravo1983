# Hei, jeg er Johnny Strømø 👋

**Fullstack-utvikler og gründer av [CycleGraph](https://cyclegraph.app)**, en SaaS-plattform for syklister som er i produksjon med brukere i 22 land.

Jeg bygger produkter fra idé til drift: backend, frontend, betaling, integrasjoner og deploy. De siste to årene har jeg jobbet AI-assistert, med en strukturert arbeidsflyt der jeg selv eier arkitekturen, skriver oppgavespesifikasjoner, gjennomgår hver diff og verifiserer før noe går i produksjon. KI gjør meg raskere, men ansvaret for kvaliteten er mitt.

BSc i IT og ledelse fra USN, og 10 år som selvstendig næringsdrivende (vedfyr.no, over 2000 kunder). Jeg vet hva det vil si å drive noe som skal fungere for ekte kunder.

🌐 [cyclegraph.app](https://cyclegraph.app) · 💼 [LinkedIn](https://www.linkedin.com/in/johnny-str%C3%B8m%C3%B8-86b21881) · ✉️ jstromo83@gmail.com

---

## 🚴 CycleGraph: watt uten wattmåler

> *See your watts. No power meter.*

CycleGraph beregner effekt (watt) fra vanlige Strava-turer ved hjelp av fysikk, vær og terreng, slik at syklister uten wattmåler kan følge FTP og form over tid.

- **Validert:** ±17 W median avvik mot over 800 turer med ekte wattmåler (716 testpunkter)
- **Strava Approved Partner:** importerer inntil 200 tidligere turer med ett klikk
- **I produksjon:** brukere i 22 land, plattformen på norsk, engelsk, spansk og tagalog
- **Rider Pro:** abonnement med Stripe, FTP-utvikling, mål og formkurve
- **CycleGraph Coaching:** dashboard for trenere og klubber (Club, Coach Pro og Elite) med lagoversikt, mål for den enkelte rytter og støtte for innendørsturer

**Stack:** Rust-fysikkmotor via PyO3 · Python/FastAPI på Fly.io · React/TypeScript på Vercel · Strava API · Stripe · GDPR-samtykkeflyt · Meta Pixel

Kildekoden er privat fordi CycleGraph er et kommersielt produkt. Jeg viser gjerne kode og arkitektur i en gjennomgang. Design i samarbeid med Peter Conrad.

---

## 🎓 Bacheloroppgave: Rust-basert Datalog-evaluator

Utviklet i samarbeid med **Data Treehouse**. En Datalog-evaluator i Rust som parser regler til AST, oversetter til SPARQL og bruker statisk og delta-caching over RDF-data (100M+ tripler).

- 5 til 9 ganger raskere spørringer enn baseline
- Semi-naiv evaluering og golden testing
- Originalkoden er privat etter avtale; demo-repoet viser konseptene på syntetiske data

**Teknologi:** Rust · SPARQL · RDF · caching · golden testing

👉 [Se demo-repo](https://github.com/JohnnyBravo1983/Bachelor)

---

## 🧰 Teknologi

| Område | Verktøy |
|---|---|
| Backend | Python, FastAPI, Rust, PyO3, Java |
| Frontend | React, TypeScript, JavaScript |
| Drift | Fly.io, Vercel, GitHub Actions, Azure (AZ-900) |
| Integrasjoner | Strava API, Stripe, OAuth, webhooks |
| Data | Polars, SPARQL/RDF, SQL, R |
| Arbeidsform | AI-assistert utvikling med Claude Code, spesifikasjon → diff-review → verifisering |

---

## 📂 Andre prosjekter

| Prosjekt | Hva | Teknologi |
|---|---|---|
| [GitAction](https://github.com/JohnnyBravo1983/GitAction) | Rust-funksjoner eksponert til Python, med CI i GitHub Actions | Rust, PyO3, Polars, Pytest |
| [PizzaDise](https://github.com/JohnnyBravo1983/PizzaDise) | Fullstack bestillingsapp (studieprosjekt) | React, Node.js |
| [OAP2000](https://github.com/JohnnyBravo1983/OAP2000) | Desktop CRUD-app etter MVC med rapporter og innlogging (studieprosjekt) | Java, Swing, JDBC, JUnit 5 |
| [VIS3000V-1](https://github.com/JohnnyBravo1983/VIS3000V-1) | Analyse og visualisering av salgsdata (studieprosjekt) | R, dplyr, ggplot2 |

---

## Utenfor kode

Familiefar, landeveissyklist og glad i styrketrening. CycleGraph startet med mitt eget behov: Vätternrundan, Horten–Bergen og Hærvejsløbet 160 km, uten wattmåler.

**Åpen for roller innen fullstack, backend, produktutvikling og AI-assistert utvikling.** Ta gjerne kontakt.
