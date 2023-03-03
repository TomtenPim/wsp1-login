# Titel

Simon Mikael Ågren | 2023-03-03

## Inledning

Här beskriver du kortfattat arbetets syfte/mål, arbetssätt, genomförande.

Målet med denna uppgift var att, i grupp, skapa en fungerande login, register och profile som skulle vara kopplad till Skolans databas för att hålla reda på dess andvändare och lössenord. För säkerhet skulle vi använda sessions för att garantera att man hade loggat in. För detta använde vi följande paket:

- bcrypt: För att kryptera lösenorden 
- express: För att använda en index.js fil där vi skapade 
- express-session: För att kolla om man har loggat in
- mysql2: För att sammankoppla Det som sker på hemsidan till vår databas
- nunjucks: För att skapa Views som i sin tur bygger upp HTML-strukturen på sidorna

## Bakgrund

Redovisa arbetets olika delar. Så att läsaren förstår vad du gjort och hur.

nej tack :)

## Positiva erfarenheter

kodandet gick bra och vi han klart med alla tester på den allokerade tiden vi fick. Vi höll ett bra fokus och tog oss fram för varje lektion. Detta fokus skulle vara bra om jag kunde ta med mig i frmatida projekt.

Diskution mellan gruppen gick väl och ledde oftast till snabba lösningar på de problem som uppstod under kodandets gång. Diskussion är ofta en vettig lössning då problem uppstår vilket visades i denna övning. (vår dåliga syn visades också) 

## Negativa erfarenheter

Grupparbetet hade kunant utföras bättre. Poängen var att alla skulle tala och alal skulle koda men det blev mestadels en som kodade däremot var alla med och diskuterade steg frammot och lösningar på problem. För att inte upprepa att det bara blir en som sitter och kodar skulle jag implementera något klock- eller passsystem där man antingen byter vem som skriver utifrån en timer elelr att man designerar en person per pass att vara den som kodar.

Det problem som tog mest tid för oss att lösa var en req.parse... som hade råkat skrivas res.parse... Hur detta kan motverkas då at det inte tar 30 min sammanlagd tid skulle vara att, i framtida felsökning, läsa koden lite noggrannare 

## Sammanfattning

Detta projekt har visat fördelarna med att arbeta i grupp för denna sorters arbeten. Att lätt ha tillgång till folka att analysera och diskutera problem hjälper mycket med att producera en färdig produkt. Produkten i fråga hade fungerande login, registrering och en profilhemsida med fungerande säkerhet. 

Om man skulle göra uppgiften igen skulle jag iplementera något system som uppmanr mer till att rotera den akriva kodaren.