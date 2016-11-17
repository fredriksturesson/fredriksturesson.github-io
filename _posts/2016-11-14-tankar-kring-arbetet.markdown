---
layout: post
title:  "Mina tankar och svar på frågorna."
date:   2016-11-17 12:00:00
categories: jekyll update
---


#### What do you think of pre-compiling your CSS?

Att arbeta med scss var en ny och spännande teknik för min del. Jag har arbetat en del med html och css innan jag påbörjade denna utbildning men aldrig använt mig av denna teknik. Från början när jag hörde talas om det på föreläsningen kändes det som att det skulle kännas ganska så enkelt att ställa om sig till ett nytt arbetssätt, men efter att fått igång Vagrant efter mycket strul så va jag inte längre så säker med att det skulle bli ”enkelt”.

Om man jämför scss och css så är det inte svårt att förstå att med hjälp av scss så kan man spara både tid och energi då man inte alltid behöver upprepa sig utav koden, man behöver inte skriva lika mycket och man behöver inte söka efter flera olika css attribut när man vill ändra t ex färgen på texten eller på rutorna på hemsidan, det räcker att ändra på ett ställe och då uppdateras allt som berörs av attributet på hemsidan.
Med scss måste man ha något som omvandlar koden (generator) som gör kodenvi skrivit till ren html / css. Vilket kräver mer program men gör det också enklare för det funkar på allas datorer oavsett operativsystem.

När jag började arbeta med uppgiften och scss försökte jag förstå mig på hur allt fungerade först med alla filer som fanns från början. Jag ändrade text färg, och lite bakgrundsfärger och liknande och försökte hitta vad allt gjorde.

Jag kan inte säga att resultatet av uppgiften blev vad jag hoppats på, men det beror på att jag hade en helt annan bild i huvudet av hur det funkade. Helst hade jag hade velat jobba mer med hemsidan men med tiden vi hade(vilket va lång tid) och tiden det tog för mig att sätta mig i detta så blev detta va jag fick ihop och det är jag ändå nöjd över, men jag tänker experimentera vidare med detta och förhoppningsvis bli bra på det i framtiden.

Min slutssatts är att det är en väldigt kraftfullt verktyg som kan förenkla mycket om man jobbar både ensam men framförallt om man jobbar flera på ett projekt för att förenklar för alla.

<br>

#### What do you think of static site generators?

Precis som med scss va Markdown ett nytt och spännande arbetssätt. Det var ett väldigt skönt sätt att skriva kod på. Det gjorde så att det blev bra struktur och enkelt att läsa.

Däremot tycker jag att det blev jobbigt när man ville föra in html kod i det, jag ville t ex ha två divar för att ha en del innehåll till höger, och en del till vänster, Detta hitta jag inget sätt att göra med hjälp av Markdown utan fick lägga in html kod i dokumentet ändå.

Markdown eller andra ”static site generator” verktyg skulle jag säga passar sig perfekt till t ex bloggar när man skriver mycket. Det är ett väldigt ”cleant” verktyg som gör det enkelt att skriva och hålla ordning på text i ett dokument. Det skulle också kunna användas till anteckningar och liknande då det skapas struktur och ordning utan några större kodning.

<br>

#### What is robots.txt and how have you configure it for your site?

Robots.txt används för att skydda filer på hemsidan, ibland vill man inte att användare skall kunna komma åt visa filer och med hjälp utav robots.txt kan man skydda sig lite från detta. Det är dock inte rekommenderat att man sparar lösenord eller annan känsligdata i en fil på servern ändå och tro att den skulle vara helt skyddad av robots.txt.

Jag har valt att lägga till Disallow: i robots.txt för att till låta "spindlar/botar" överallt på sidan.

<br>

#### What is humans.txt and how have you configure it for your site?

Humans.txt används för användaren som går in på en hemsida skall kunna se vem som ligger bakom sidan och också hitta information vart man lånat någon bild eller liknande ifrån då kan man ge ”credit” till den personen eller företaget som bidragit till sidan.

Jag har valt att på min humans.txt att börja med att skriva att jag är skaparen av sidan och lite kontaktinformation till mig. Efter det har jag satt upp ett tack till Linnéuniversitetet för att visa att ni stått bakom mig och stöttat mig med kunskap och hjälp. Det sista på sidan är information om vilka verktyg som använts och när den senast uppdaterades

<br>

#### How did you implements comments to blog posts

Jag använde mig utav disqus för att kunna kommentera på blogginläggen. Det är ett verktyg som vi fick rekommenderat i kursen och det visade sig att det passade mig väldigt bra, det va enkelt att arbeta med och ett kraftfullt verktyg. För att använda sig av disqus så registerar man sig på deras hemsida och sedan följer man enkla och tydliga instruktioner. Det finns olika verktyg man som man kan välja mellan beroende på vad man jobbar med, t ex Wordpress och Jekyll.

Det tog mig ca 3 – 5 minuter att få det inlagt på blogginläggen, man får en ”universal code” som skall läggas in under ”posts.html” i Jekyll och sedan en liten modifiering i config-filen.


<br>

#### What is Open Graph and how do you make use of it?

Open graph används för att göra det enklare för användare att dela saker från sidan. Med open graph blir det en förhandsvisning av innehållet när man delar sidan så användere som ser ”delningen” vet vad det är den går in på för sida och att det faktiskt är relevant för den personen och inte bara se en länk.

Själv la jag open graph taggarna i head.html och ställde in dom så det passa min sida!
