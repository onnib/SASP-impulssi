# SASP-impulssi
### taputus ja muita tapoja mitata huoneen impulssivaste

Repo sisältää projektissa käytetyt koodit.
- [recording.mlx](recording.mlx) on audiosignaaleiden nauhoitukseen käytetty koodi
- [impulssivaste.mlx](impulssivaste.mlx) on impulssivasteiden piirtämisessä käytetty koodi
- [reverbation_time_original.mlx](reverbation_time_original.mlx) on jälkikaiunta-ajan laskemisessa ja piirtämisessä käytetty tiedosto
- [compareReverbandFrequency.mlx](compareReverbandFrequency.mlx) on "pääfunktio" taajuus-jälkikaiunta-aika-kuvaajien piirtämisessä. Se käyttää apunaan singleReverbTime-funktiota, joka löytyy saman nimisestä [tiedostosta](singleReverbTime.mlx).
> [!NOTE]
> Kolme viimeisintä koodia tarvitsevat audiosignaaleja toimiakseen. .wav-tiedostojen oletetaan löytyvän nauhoitukset-kansiosta.

- demopäivän toteutus löytyy
