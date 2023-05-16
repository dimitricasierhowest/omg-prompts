# Zinsontleding

## Nederlandstalige zinnen ontleden

- //chat.openai.com

### prompt:
``` 
Je voer taal is Nederlands. Je neemt de rol op zich van expert in de Nederlandse taal. Uit de tekst tussen ===, extract je voor elke zin:
- het onderwerp
- de persoonsvorm
- lijdend voorwerp
- meewerkend voorwerp

Indien er geen van deze elementen aanwezig is, toon je "-". Je leest eerst elke zin voor dat je antwoordt.

Je toont de uitvoer volgens de structuur tussen ''' en in markdown

'''
## {zin}
- **het onderwerp:** {onderwerp}
- **persoonsvorm:** {persoonsvorm}
- **lijdend voorwerp:** {lijdend voorwerp}
- **meewerkend voorwerp:** {meewerkend voorwerp}
'''
===
Matthias en Hannelore wilden dolgraag aan boord gaan, maar er was één probleem. Meester Dirk, hun strenge leerkracht, stond aan de rand van de boot en keek hen streng aan. "Jullie mogen hier niet zomaar op!", riep hij.

Matthias en Hannelore keken elkaar aan en besloten om een plan te bedenken. Ze keken om zich heen en zagen dat er een mysterieus personage op de kade stond. Het was een oude man met een lange baard en een hoed op. Hij had een briefje in zijn handen en fluisterde iets in het oor van Meester Dirk.

Meester Dirk knikte en liet Matthias en Hannelore aan boord. Ze konden hun geluk niet op en bestelden meteen een grote portie frietjes. Maar terwijl ze aan het eten waren, merkten ze dat er iets vreemds aan de hand was. De frietjes waren heel anders dan ze gewend waren. Ze smaakten niet alleen lekker, maar ook een beetje vreemd.

Matthias en Hannelore besloten om op onderzoek uit te gaan en kwamen erachter dat er iets geheimzinnigs aan de hand was op de boot. Maar voordat ze meer konden ontdekken, klonk er plotseling een luide knal en begon de boot te wiebelen. 
===
```
