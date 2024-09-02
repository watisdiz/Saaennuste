# Sääennustesivusto

Responsiivinen sääennustesivusto, joka on rakennettu Bootstrap 5 -pohjalla. Sivusto mahdollistaa reaaliaikaisen säätiedon hakemisen eri kaupungeista käyttäen OpenWeatherMap API:a.

## Yleiskuvaus

Sääennustesivusto tarjoaa käyttäjille mahdollisuuden hakea ajankohtaista säätietoa syöttämällä haluamansa kaupungin nimen. Sivusto on suunniteltu responsiiviseksi, joten se toimii hyvin sekä mobiililaitteilla että pöytäkoneilla. Sivustolla on selkeä ja helppokäyttöinen käyttöliittymä.

## Ominaisuudet

- **Reaaliaikainen sääennustehaku:** Käyttäjä voi hakea säätiedot syöttämällä kaupungin nimen hakukenttään.
- **Säätietojen esitys:** Näyttää lämpötilan, kosteuden, tuulen nopeuden ja säätilan kuvauksen.
- **Hakuhistoria:** Aiemmat haut tallennetaan sivustolle, jolloin käyttäjä voi helposti tarkastella niitä uudelleen.
- **Responsiivinen design:** Sivusto mukautuu eri näyttökokoihin ja toimii hyvin sekä mobiililaitteilla että pöytäkoneilla.
- **Bootstrap 5 -tyylit:** Sivusto käyttää Bootstrap 5 -kirjastoa tyylittelyyn, mikä takaa modernin ja yhtenäisen ulkoasun.

## Teknologiat

- **HTML5 & CSS3**
- **Bootstrap 5**
- **JavaScript**
- **OpenWeatherMap API**

## Käyttöohjeet

- **API-avain:** Hanki API-avain OpenWeatherMapista ja lisää se index.html tiedostossa olevaan JavaScript-koodiin kohdassa const apiKey = 'YOUR_API_KEY';.
- **Sivuston käyttö:** Syötä kaupungin nimi hakukenttään ja paina "Get Weather" -painiketta. Sivusto hakee säätiedot ja näyttää ne käyttöliittymässä.
