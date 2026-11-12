# Refleksjon: Grunnleggende JavaScript

Svar når du er ferdig med oppgavene i `oppg1_grunnleggende.js`. Skriv med egne ord, og ikke se i koden mens du svarer på del A. Korte svar er helt greit.

---

## A. Forklar med egne ord

**1. Hva er forskjellen på `let` og `const`? Når bruker du hvilken?**

> let er variabel som kan endres og const er variabel som kan ikke endres  

**2. Hvorfor ble `"5" + 5` til `55`, mens `5 + 5` ble `10`?**

> let x = 5 + 5; //normalt svar let y = "5" + 5; //"5" compileres som tekst og +5 liges til den tekst som tall. let z = Number("5") + 5; // funksjon Number converteter til tall og videre liges til 5 

**3. Hva gjør `%`? Gi et eksempel fra oppgavene der du brukte den.**
 
> dette er divisjon med modul

**4. Hva er forskjellen på `=` og `===`?**

> _ = er setter vedrien og === skjeker om verdier er like  

**5. Forklar de tre delene i denne linja:** `for (let i = 1; i <= 5; i++)`

> Vi setter verdien for indeksvariabelen til 1. Deretter gjør programmet indeksverdien mindre enn eller lik 5. Deretter legger det til 1 til indeksen.

**6. Når er en `while`-løkke bedre enn en `for`-løkke? Hva kan gå galt med en `while`-løkke?**

> 

**7. Hvorfor er den første byen i lista `byer[0]` og ikke `byer[1]`?**

> fordi liste starter med 0

---

## B. Bruk det du har lært

**8. Hva skrives ut her? Svar før du tester.**

```js
const temp = -3;
if (temp < -5) {
  console.log("Veldig kaldt");
} else if (temp < 0) {
  console.log("Kaldt");
} else {
  console.log("Mildt");
}
```

> kaldt

**9. Hva skrives ut her? Svar før du tester.**

```js
const lag = ["Titans", "Ulvene", "Polarnatt"];
lag.push("Nordlys");
console.log(lag.length);
console.log(lag[1]);
```

> 4 Ulvene

**10. Denne koden skal skrive ut 1, 2 og 3, men gjør det ikke. Hva er feil?**

```js
for (let i = 1; i < 3; i++) {
  console.log(i);
}
```

> det skal være 1 2 og ikke 3 pga det står i < 3 i sted av i <= 3

---

## C. Om din egen læring

**11. Hvilken oppgave var vanskeligst, og hvordan løste du den?**

> Jeg håppet over oppgaven 19 fordi denne oppgaven var vanskelig. 

**12. Hvilken feilmelding fikk du oftest? Hva betydde den?**

> Jeg fikk feil på grunn av feil syntaks fordi jeg glemte å skrive ";"

**13. Hva gjorde du når du sto fast? Hva vil du gjøre annerledes neste gang?**

> Jeg forvrengte veiledningene og prøvde å finne en forklaring eller lignende kode der.

**14. Hvor langt kom du?**

| Nivå | Kryss av |
|---|---|
| Grunnleggende | x |
| Middels | x |
| Avansert | x |

**15. Kryss av for det du kan nå.**

| Jeg kan... | Ja | Litt | Nei |
|---|---|---|---|
| lage variabler med `let` og `const` | x |  |  |
| bruke tekst og tall, og sette dem sammen med `${}` | x |  |  |
| ta valg med `if`, `else if` og `else` |  | x |  |
| skrive en `for`-løkke |  | x |  |
| hente, legge til og gå gjennom verdier i en array |  | x |  |
| lese en feilmelding og finne riktig linje |  |  | x |

**16. Hva vil du øve mer på før vi går videre til funksjoner?**

> Jeg vil øve mer på løkker, arrays og if-setninger. Jeg vil også bli bedre til å forstå feilmeldinger og finne feil i koden.