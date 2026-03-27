```
 ██╗   ██╗  ██████╗   ██████╗ ██╗  ██╗ ██████╗
 ██║   ██║ ██╔═══██╗ ██╔════╝ ██║ ██╔╝██╔═══██╗
 ██║   ██║ ██║   ██║ ██║      █████╔╝ ██║   ██║
 ██║   ██║ ██║   ██║ ██║      ██╔═██╗ ██║   ██║
 ╚██████╔╝ ╚██████╔╝ ╚██████╗ ██║  ██╗╚██████╔╝
  ╚═════╝   ╚═════╝   ╚═════╝ ╚═╝  ╚═╝ ╚═════╝  .cz
```
> ⚒ &nbsp;Oficiální skripty pro Razor Community Edition&nbsp; ⚒

**[UOčko.cz](https://uocko.cz/)** — český Ultima Online server

---

## Co je to za repozitář?

Veřejný repozitář automatizačních skriptů pro český Ultima Online server **UOčko.cz**.
Skripty jsou psané pro **Razor Community Edition** v jazyce **UOS (Ultima Online Script)**.

Stačí stáhnout soubory a nakopírovat je do složky Razor CE:

```
Data/Plugins/Assistant/Scripts/
```

---

## Skripty

### `Mining.razor` — Automatické těžení rudy

Skript pro kontinuální těžení rudy v dole. Hráč se pohybuje v jednom směru a skript automaticky kope všechna okolní políčka, vysypává rudu na zem a táhne ji sebou.

**Jak to funguje:**

1. **Kopání** — Na každé pozici vykope 5 políček v řadě kolmo na směr chůze (2 vlevo, střed, 2 vpravo). Používá shovel z batohu, nebo pickaxe z ruky jako záložní nástroj.
2. **Vysypání batohu** — Rudu z batohu hodí na zem před sebe. Pokud je tam zeď, zkusí ostatní strany.
3. **Pohyb** — Postoupí o jedno políčko ve zvoleném směru.
4. **Tahání rudy** — Vezme rudu ze země a hodí ji o políčko dál ve směru chůze, aby se postupně hromadila na konci dolu.
5. Opakuje od kroku 1.

**Nastavení:**

Na začátku skriptu změň směr chůze:
```
pushlist 'smer' 'N'   # N = North, S = South, E = East, W = West
```

**Podporované typy rudy:** Iron (6583), Dull Copper (6584), Shadow (6585), Copper (6586)

> Skript se sám zastaví, pokud postava zemře nebo nemá žádný nástroj.

---

## Razor Community Edition

Razor CE je zdarma ke stažení na [github.com/markdwags/Razor](https://github.com/markdwags/Razor).
Dokumentace UOS skriptovacího jazyka: [razorenhanced.net/dokuwiki](https://razorenhanced.net/dokuwiki/)

---

*UOčko.cz — hraj, těž, přežij.*
