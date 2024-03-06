display: grid;

grid-tempelate-colums: mettere in orizontale linie

grid-tempelate-rows: mettere in verticale colone

column-gap: spazio tra le colone

row-gap: spazio tra linie

gap: spazio tra colone e linie

grid-auto-rows: altezza di tutte colone

grid-auto-flow: mettre elemento in linea

1fr: distribuisce tutto spazio di colone

repeat(5, 100px): 5 colone di 100px

grid-column-start: da quale colona inizia elemento

grid-column-end: quando finisce eloemento

grid-colum: 1 / 5: uguale

minmax(): responsive

grid-template-areas: marcatura
grid-template-areas:
"h h h h"
"m m . s"
"f f f f";

grid-area: realizazuine di marcatura

justify-content: Questa proprietà controlla l'allineamento degli elementi lungo l'asse principale della griglia (orizzontale per grid e verticale per inline-grid). Può assumere valori come start, end, center, space-between, space-around, e space-evenly, che determinano come gli elementi vengono distribuiti lungo l'asse principale.

justify-items: Questa proprietà controlla l'allineamento degli elementi lungo l'asse delle righe della griglia. Può essere utilizzato per specificare come gli elementi devono essere allineati all'interno dei loro spazi assegnati lungo l'asse delle colonne. I valori comuni includono start, end, center, e stretch.

align-content: Questa proprietà controlla l'allineamento degli elementi lungo l'asse trasversale della griglia (verticale per grid e orizzontale per inline-grid). Può assumere valori come start, end, center, stretch, space-between, space-around, e space-evenly, determinando come gli elementi vengono distribuiti lungo l'asse trasversale.

align-items: Questa proprietà controlla l'allineamento degli elementi lungo l'asse delle colonne della griglia. Può essere utilizzato per specificare come gli elementi devono essere allineati all'interno dei loro spazi assegnati lungo l'asse delle righe. I valori comuni includono start, end, center, stretch, e baseline.

justify-self: Questa proprietà specifica l'allineamento orizzontale di un singolo elemento all'interno di una cella della griglia. Può assumere valori come start, end, center, stretch, e auto, determinando come l'elemento deve essere allineato lungo l'asse delle colonne della cella della griglia.

align-self: Questa proprietà specifica l'allineamento verticale di un singolo elemento all'interno di una cella della griglia. Può assumere valori come start, end, center, stretch, e auto, determinando come l'elemento deve essere allineato lungo l'asse delle righe della cella della griglia.
