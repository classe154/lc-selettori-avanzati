# lc-selettori-avanzati

Raccolta di esercizi interattivi sui selettori CSS avanzati. Ogni cartella è una demo autonoma con un `index.html` da aprire nel browser.

---

## Cartelle

### `selector-hierarchy`
Demo sulla gerarchia e le relazioni tra selettori CSS. Copre:
- Selettore discendente (spazio) vs figlio diretto (`>`)
- Confronto diretto dei due comportamenti
- Gerarchia "interrotta": quando un selettore non attraversa livelli
- Fratello adiacente (`+`) e fratello generale (`~`)
- Selettore concatenato (`div.card`) vs discendente (`div .card`)
- Catene miste con `>` e spazio combinate

### `lc-html-css-selector`
Demo sui selettori CSS fondamentali. Copre:
- Selettore di classe combinata (`p.importante`, `.highlight.speciale`)
- Selettore universale discendente (`div *`)
- Selettore discendente (`div p`)
- Selettore figlio diretto (`div > p`)
- Selettore fratello adiacente (`div + p`)
- Selettore fratello generale (`div ~ p`)

### `lc-html-css-attribute-selectors`
Demo sui selettori di attributo CSS. Copre:
- Presenza di attributo (`tag[attr]`)
- Valore esatto (`[attr="value"]`)
- Inizia con (`[attr^="value"]`)
- Finisce con (`[attr$="value"]`)
- Contiene substring (`[attr*="value"]`)
- Contiene parola intera (`[attr~="value"]`)
- Test combinati con più selettori

### `lc-html-css-pseudo-class`
Demo sulle pseudo-classi CSS. Copre:
- `:first-child` e `:last-child`
- `:hover`, `:visited`, `:active`, `:focus`
- Combinazioni di pseudo-classi
- Area di test completa con suggerimenti

### `lc-html-css-pseudo-elements`
Demo sugli pseudo-elementi CSS. Copre:
- `::before` e `::after` applicati a una task list
- Posizionamento e comportamento degli pseudo-elementi
- Lista numerata custom con `::before`
- Regole fondamentali per l'utilizzo degli pseudo-elementi
