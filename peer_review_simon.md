# Peer Review P-uppgift Simon
Peer review av Simon Stoll, skrivet av Tyra Areskoug.
## Klasser
Simon har använt sex stycken klasser för att bygga upp sitt minesweeper-spel, varav alla har en init-metod. T.ex. har han en som hanterar tkinter-GUI:n, och en som hanterar minfältet, vilka båda är centrala funktioner i spelet.

## Struktur
Spelet är strukturerat helt utifrån de sex klasserna, dvs. det finns inga fristående funktioner utan allt sker genom klassernas metoder. Detta ger en tydlig logik i strukturen. Vidare finns inga globala variabler, och det enda globala anropet är det till main.

## Storlek på funktioner, klasser och metoder
Jag tycker att Simon gjort ett bra jobb med att göra sina klasser lagom stora. Den största klassen är den för GUI:n, vilket är rimligt med tanke på att den hanterar den största delen av tkinter-interfacet. 

## Dokumentation (Kommentarer)
Varje metod och klass har en tillhörande kommentar som förklarar dess funktion. Gillar även att han ibland lägger till hur metoden är relaterad till andra metoder/klasser i programmet, vilket gör det lättare att läsa programmet uppifrån och ned - det kan ju vara en utmaning eftersom anropen mellan metoder inte sker linjärt nedåt. Han har även kommenterat på utvalda ställen i koden där ett förtydligande behövs, ett bra komplement till de i sig förklarande variabelnamnen.

## Undvik globala variabler
Simon använder inga globala variabler.

## Undvik onödig kodupprepning
Koden är väluppbyggd och radeffektiv med metoder som återanvänds. Tex. används ett dictionary för alla tiles i minefieldet, vilket är ett mycket effektivt sätt att lagra och möjliggöra uppdatering av minefieldet.

## Undvik hårdkodning
Programmet är uppbyggt så att spelaren i början både får välja storlek på fönster, rutnät, antal bomber samt skriva in sitt namn. Detta visar att koden är uppbyggd på ett "generellt" sätt, utan att hardcoda endast vissa scenarion.

## Utskrifterna
Tkinter-GUI:t är simpelt och lätt att navigera runt. Har spelat flertalet gånger med olika inställningar och aldrig stött på några felmeddelanden eller problem. Väldigt bra gjort!

## Namn på variabler
Variabelnamnen är beskrivande och det är lätt att läsa koden utan övriga kommentarer eller förklaringar. Simon använder snake_case, men har några få ställen där detta inte följs. Detta åtgärdade han dock direkt när jag gav honom feedbacken. 
