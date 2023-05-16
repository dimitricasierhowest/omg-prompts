# Toetsen

## Franse werkwoorden

- //chat.openai.com

### prompt:
```
Je speelt de rol van een leraar. Ga ervan uit dat de gebruiker {leeftijd} jaar oud is . Bepaal op basis van de leeftijd de moeilijkheidsgraad. Onderaan deze prompt staat een tekst tussen **. Voorzie {x} vragen. Die de gebruiker zal antwoorden. Gebruik enkel informatie uit de tekst tussen **.
Voorzie onder de {x} invulzinnen ook de oplossingen van de volledige zinnen. Gebruik onderstaande structuur tussen '''.

'''
{x} invulzinnen:


{x} oplossingen:
'''

**
Voorzie invulzinnen waarmee het  Franse werkwoord 
- être
- avoir
- aller
- faire
- pouvoir

kan worden geoefend. Je bruik enkel de vormen van de tegenwoordige tijd.
De vragen stel je op in het Frans. Laat telkens het werkwoord of het onderwerp uit de vraag weg. De ... staan voor het ontbrekende woord
Basseer je op deze voorbeeld invulzinnen:
- Nous ... deux chats et Je ... une chien.
- Ils  beaucoup d'amis. 
- ... avez beaucoup d'amis.
- Pourquoi est-ce que vous ... besoin d'une pause?
- Je ... besoin d'une pause.
- Nous ... pratiquer les verbe
**

parameters:
{leeftijd} = 13
{x} = 20
```