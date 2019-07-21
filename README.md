# Keittiökirja

## Kansiorakenne

Tämä README-tiedosto sijaitsee korkeimmalla hierarkiatasolla. Tältä tasolta 
löytyy `keittiokirja.tex`-tiedosto, joka kokoaa kaikki muut tiedostot yhteen.

Kansiossa `pic` sijaitsee kaikki kuvat sekavana nippuna. Pitänee mahdollisesti 
kansioida niitä joskus vähän siistimmin.

Kansiossa `tex` sijaitsee lukukohtaisesti yksi tiedosto per luku. Siellä on 
myös yksi alikansio nimeltä `reseptit`, johon säilötään jokainen yksittäinen 
resepti omaksi tiedostokseen.

## Riippuvuudet

Ainakin `subfile` ja `xcookybooky`-paketit pitää olla käytössä. Windows-koneella 
käytä `MikTeX Console`-ohjelmaa pakettien asentamiseen ja päivittämiseen.