# Matte 4C (TMA4432) – eksamensøving

Teorihefter, øvingssett og prøveeksamener med løsningsforslag til **TMA4432 Matematikk 4C, høst 2026** (eksamen 24.11.2026, hjelpemiddel D + formelark), sortert etter tema i pensum.
Hvert sett har to filer: `oppgaver.pdf` og `losningsforslag.pdf`. I tillegg ligger de originale eksamenene som settene er hentet fra.

**Start med [`ovingssett/0-oversikt.pdf`](ovingssett/0-oversikt.pdf)**: den forklarer hvordan materialet brukes, har innholdstabeller, sier hva som står på formelarket, og gir en plan for ukene før eksamen.

## Struktur

```
ovingssett/
├── 0-oversikt.pdf                       bruk, innhold, formelark, plan
├── 1-teori/                             12 teorihefter (engelsk), ett per tema
│   ├── T01-SVD-and-Moore-Penrose.pdf
│   ├── …
│   └── T12-Least-squares.pdf
├── 2-temasett/                          12 sett, eksamensoppgaver + egenlagde der eksamensoppgaver mangler
│   ├── 01-SVD-og-Moore-Penrose/         TMA4145 2016–2025
│   ├── 02-Tensorer/
│   ├── 03-Kurver-og-flater/
│   ├── 04-Jacobi-og-Newton/
│   ├── 05-Kjerneregel-gradient-og-optimering/
│   ├── 06-Newton-og-optimering-4N/
│   ├── 07-Fourierrekker/
│   ├── 08-Fouriertransform-og-DFT/
│   ├── 09-PDE-og-numerikk/
│   ├── 10-Splines-og-Bezier/
│   ├── 11-Minste-kvadraters/
│   ├── 12-Ronny-eksamener-blandet/      Matte 4N 2022–2025 (samme faglærer), alt innenfor 4C-pensum
│   └── 06-12-tatt-med-og-ekskludert.pdf
└── 3-proveeksamener/                    4 prøveeksamener i TMA4432-format
    ├── proveeksamen-1/                  11 oppgaver (10 temaer + minste kvadraters), 108–113 poeng
    ├── …                                LF fra originalene, med poeng per trinn der de finnes
    └── proveeksamen-4/
originale-eksamener/
├── Matte4C-proveeksamen/                prøveeksamen Matte 4C + formelarket (formula-sheet-26h.pdf)
├── TMA4145-Lineaere-metoder/            2016–2025, eksamen + løsning
├── Matte4N-Ronny/                       TMA4125 Matte 4N 2022–2025
└── Matte4N-eldre/                       Matte 4N 2016–2024
```

## Slik er det laget

- **Teoriheftene** (engelsk, som eksamen og formelark) har oppskrifter, teoremer med presise hypoteser, typiske poengtap og en tydelig deling mellom det som står på formelarket og det du må kunne utenat. De er merket ★★★ / ★★☆ / ★☆☆ etter hvor ofte temaet kommer på eksamen. Alle tall og eksempler er kontrollregnet med sympy/numpy, og heftene er gjennomgått av en uavhengig reviewer.
- **Temasettene** er eksakte utklipp av gamle eksamensoppgaver (TMA4145, Matte 4N) og årets øvinger, med de originale løsningsforslagene i en egen PDF. Bare oppgaver som ligger helt innenfor 4C-pensum er tatt med. Polynominterpolasjon og fikspunktiterasjon er utelatt.
- **Egenlagde oppgaver** er brukt der det finnes få eller ingen eksamensoppgaver (tensorer, kurver og flater, optimering, splines, minste kvadraters). De er merket som egenlagde, og løsningene er numerisk kontrollert, men kan inneholde feil – åpne gjerne en issue hvis du finner noe.
- **Prøveeksamenene** har én oppgave per tema, satt sammen av oppgaver fra temasettene (ekte eksamensoppgaver der de finnes). Ingen oppgave går igjen mellom prøveeksamenene, og ingen er hentet fra den offisielle prøveeksamenen. Alle oppgavene står også i temasettene – ta prøveeksamenene først hvis du vil ha dem blinde.

## DFT-konvensjon

Formelarket, slides 07, prøveeksamenen og løsningsforslagene fra 2024–25 bruker faktoren 1/N i den forlengs DFT-en. Oppsummeringen og noen eldre løsningsforslag (2022–23) bruker den uten 1/N. Oppgavene der dette betyr noe, er merket i prøveeksamenene, og T07 forklarer forskjellen.

## Kilder og opphav

Eksamensoppgavene, øvingene, formelarket og de offisielle løsningsforslagene tilhører NTNU / faglærerne i de respektive emnene (TMA4432 Matematikk 4C, TMA4145 Lineære metoder, TMA4125/TMA4130 Matematikk 4N), og er hentet fra de offentlige emnesidene på wiki.math.ntnu.no. De er samlet her kun som studiehjelp. Teorihefter, egenlagde oppgaver og løsninger kan brukes fritt.

Se også [Matte 1 – eksamensøving](https://github.com/akselwe/matte1-eksamensovinger).

Lykke til på eksamen!
