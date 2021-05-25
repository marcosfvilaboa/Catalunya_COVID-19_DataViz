# Incidència de la COVID-19 a Catalunya

Aquest treball pretén mostrar el procés d'elaboració d'una visualització de dades a partir del dataset "[Incidència de la COVID-19 a Catalunya](https://analisi.transparenciacatalunya.cat/Salut/Incid-ncia-de-la-COVID-19-a-Catalunya/623z-r97q/data)" proporcionada pel portal de dades obertes de la Generalitat de Catalunya.

## Visualització de dades

La visualització es pot consultar a [Flourish Studio - Public Website](https://public.flourish.studio/visualisation/6245825/). 

El seu objectiu és representar de manera interactiva l'evolució de la COVID-19 a Catalunya en funció del temps. 


[![Visualization](./img/Incidencia_Covid-19_Cat.png)](https://public.flourish.studio/visualisation/6245825/)

## Dades

Les dades utilitzades formen part del conjunt de dades obertes de la [Generlitat de Catalunya](http://governobert.gencat.cat/ca/dades_obertes/).

- [data](./data): fitxers CSV utilitzats per a la construcció de la visualització.
  - Dades originals: [Incid_ncia_de_la_COVID-19_a_Catalunya.csv](./data/Incid_ncia_de_la_COVID-19_a_Catalunya.csv)
  - Dades modificades: [COVID-19_Catalunya_setmanal.csv](./data/COVID-19_Catalunya_setmanal.csv)
- [docs](./docs): document PDF amb l'informe. 
  - [FernandezVilaboaMarcos_VD_PAC3.pdf](./docs/FernandezVilaboaMarcos_VD_PAC2.pdf)
- [img](./img): captures de la visualització
  - [Incidència de la Covid-19 Catalunya.jpeg](./img/Incidencia_Covid-19_Cat.png)
- [src](./src): fitxers amb el codi per a la neteja i transformació de les dades.
  - [transformation.ipynb](./src/transformation.ipynb)


----
