# Povprečne mesečne plače po občinah

## Opis problema

Izbran problem (oziroma zbirka podatkov) je Povprečne mesečne plače po občinah, Slovenija, letno.

Problem zajema povprečne bruto in neto plače po občinah v Sloveniji, z dodatnimi podatki kot so opravljene (oz. plačane) nadure, število oseb, ki so opravljale nadure na mesec, število oseb, ki so prejele zaostala izplačila itd.

Vse vrednosti so povprečne mesečne vrednosti, ki so razdeljena na leta (npr. povp. neto plača na mesec v letu 2015 itd.)

Ti podatki podajo več zanimivih vprašanj, kot npr.:
  * V katerij regijah Slovenije so plače višje/nižje?
  * Kako izgleda rast/upad plač skozi leta (posledice recesije?)?
  * Kje je opravljenih največ nadur, in kje so te najbolje plačane?
  * Kakšne so vrednosti, če upoštevano/primerjmo inflacijo?
  
Cilj je seveda analiza, pregled in vizualizacija teh podatkov, ter njihova razdelitev po regijah. Zanima nas tudi razporeditev plač po Sloveniji.

## Podatki

V podatkovni datoteki so podane sledeče vrednosti:
 * Povprečna mesečna bruto plača
 * Povprečna mesečna neto plača
 * Indeks povprečne mesečne bruto plače
 * Indeks povprečne mesečne neto plače
 * Povprečna plača za plačano naduro
 * Povprečna mesečna bruto plača za plačano uro
 * Povprečna mesečna neto plača za plačano uro
 * Indeks povprečne mesečne bruto plače za plačano uro
 * Indeks povprečne mesečne neto plače za plačano uro
 * Zaposlene osebe, ki so prejele zaostala izplačila
 * Zaposlene osebe z izplačanimi nadurami
 
Vrednosti so za leta od 2005 do 2019, in so povprečja celotnega leta za posamezne občine v Sloveniji (katerih je 211).

Iz podatkov sva odstranila vnose za občine Ankaran in Mirna, saj so tem občinam manjkali podatki za vrsto let (tako je skupaj 209 občin). Odstranila sva tudi leto 2005 za indeks povprečne mesečne plače za plačano uro, saj je to leto bilo popolnoma prazno.

Za potrebe analize sva uporabljala samo neto vrednosti (namesto bruto), saj ponujajo boljšo predstavitev dejanskega denarnega prihodka za posamezno občino.

## Predstavitev podatkov

### Največja povprečna neto plača

Pri vseh letih je največja plača v občini **Cerklje na Gorenjskem**. Sledeče vrednosti so največje 3 neto plače, v vsakem stolpcu urejene po barvi kjer **bold == največja plača**, *italics == druga največja plača*.

|                       |   2005 |    2006 |    2007 |    2008 |    2009 |    2010 |    2011 |    2012 |    2013 |    2014 |    2015 |    2016 |    2017 |    2018 |    2019 |
|:----------------------|-------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|--------:|
| Cerklje na Gorenjskem | **994.07** | **1028.63** | **1065.88** | **1179.98** | **1147.61** | **1173.7**  | **1182.71** | **1187.71** | **1378.65** | **1393.08** | **1431.88** | **1404.53** | **1438.7**  | **1445.17** | **1433.9**  |
| Kobilje               | *857*    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |
| Ljubljana             | 848.09 |  *889.75* |  *963.6*  | 1042.35 | *1081.27* | *1106.95* | *1125.64* | *1124.97* | *1125.61* | 1130.74 | *1140.33* | *1159.83* | *1197.56* | *1231.47* | 1281.66 |
| Sveta Ana             |   0    |  886.28 |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |
| Dol pri Ljubljani     |   0    |    0    |  955.73 | *1066.81* |    0    | 1066.37 | 1119.9  | 1120.9  |    0    |    0    |    0    |    0    |    0    |    0    |    0    |
| Sveti Tomaž           |   0    |    0    |    0    |    0    | 1052.42 |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    |
| Novo mesto            |   0    |    0    |    0    |    0    |    0    |    0    |    0    |    0    | 1116.34 | *1145.87* | 1138.56 | 1149.06 | 1173.36 | 1217.78 | *1286.19* |
