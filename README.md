# SASP-impulssi
### taputus ja muita tapoja mitata huoneen impulssivaste

Repo sisältää projektissa käytetyt koodit.
- [recording.mlx](recording.mlx) on audiosignaaleiden nauhoitukseen käytetty koodi
- [impulssivaste.mlx](impulssivaste.mlx) on impulssivasteiden piirtämisessä käytetty koodi
- [reverbation_time_original.mlx](reverbation_time_original.mlx) on jälkikaiunta-ajan laskemisessa ja piirtämisessä käytetty tiedosto
- [compareReverbandFrequency.mlx](compareReverbandFrequency.mlx) on "pääfunktio" taajuus-jälkikaiunta-aika-kuvaajien piirtämisessä. Se käyttää apunaan singleReverbTime-funktiota, joka löytyy saman nimisestä [tiedostosta](singleReverbTime.mlx).
> [!NOTE]
> Kolme viimeisintä koodia tarvitsevat audiosignaaleja toimiakseen. .wav-tiedostojen oletetaan löytyvän nauhoitukset-kansiosta.
> Kaikki muut paitsi alin koodi ajetaan Matlabissa painamalla _run_-nappia. _compareReverbandFrequency_-funktio ajetaan kutsumalla Matlabin komentorivillä funktiota ja antamalla sille analysoitavan wav-tiedoston nimi, esimerkiksi `>> compareReverbAndFrequency('u2_ilmapallo_02-Nov-2023_12_47_13_465.wav')`

- Demopäivän toteutus löytyy [demo](/demo)-kansion alta. Demon saa toimimaan avaamalla [Matlab App -tiedoston](/demo/SASPDemoApp.mlapp) Matlabissa ja painamalla _run_-nappulaa.
- Lisäksi [unused_code](/unused_code)-kansiossa on tekemiämme koodeja, jotka eivät kuitenkaan päätyneet lopulliseen projektiin mukaan. 
