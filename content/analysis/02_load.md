---
Title: Load
Description: This is our analysis page about load.
Template: analysis
---

# Load
I denna uppgift ska jag analysera prestanda och laddningstider för tre olika webbplatser och kolla efter möjliga förbättringar. Genom att titta närmare på olika laddningstider sidorna presterar kommer jag att få en bättre förståelse och peka på bättrings områden för en bättre upplevelse. 

# Urval
Sidorna jag har valt att undersöka är Nike.se, svt.se och sonymusic.com. Jag har valt ut dessa webbplatser på grund av popularitet samt att det är olika typer av webbplatser. E-handel, nyheter och musikindustri. Sidorna är välbesökta vilket gör dom intressanta att analysera och titta närmare på just prestandan. I och med att sidorna representerar olika branscher och syften får vi flera synvinklar för analysen.

# Metod
För att kunna ta fram dessa mätvärdena använde jag mig av två verktyg.

- Google Pagespeed Insights, för att mäta prestanda för både dator och mobila enheter på alla tre webbplatser. Resultaten jag fick visade statistik för First Contentful Paint, Largest Contentful Paint, Total Blocking Time, och Cumulative Layout Shift.

- Google Chrome DevTools, Jag använde detta för att beräkna sidans laddningstid. För varje sida gjorde jag tre mätningar och tog snittet av värdena för att visa resultat.

Jag dokumenterade mätvärdena i ett Google Kalkylark.


# Resultat
## Nike
![Nike](../assets/img/nike.png){.screenshot-image}

## SVT
![SVT](../assets/img/svt.png){.screenshot-image}

## SonyMusic
![Sony](../assets/img/sony.png){.screenshot-image}

### Mätvärden
<div class="responsive-iframe-container">
  <iframe 
    class="responsive-iframe" 
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ6O4UUXlJ-tH29kgF5kY_YLo1Y-8pHY55B886C6sR4aYyKHZYHffLO6y9YwinQABVuwknlYkWeySFU/pubhtml?widget=true&amp;headers=false" 
    title="Landing Page Analysis">
  </iframe>
</div>



# Analys

## Nike.se
Nike sidan har bra prestanda på datorn med FCP på 1,2 sekunder och LCP på 3,4 sekunder vilket är hållbara siffror för en webbshop.  Mobilsidan har däremot problem med sin prestanda… FCP på 5,1 sekunder och LCP på 16,5 sekunder. Mobilversionen underpresterar och har tider långt över vad som är rekommenderat. TBT på 15 450 ms visar att mobilsidan har mycket blockerad javascript vilket resulterar långsamhet. Att hitta bättre sätt att hantera bilder samt videos kan vara möjliga förbättringsåtgärder. Nike har däremot en mobilapp som de kanske fokuserar mer på för mobilanvändare.

## SVT.se
Prestandan för svt.se var bra både dator och mobil. Dataversionen hade mycket bra siffror, en FCP som låg på 0,8 sekunder och en LCP på 1,1 sekunder. Mobilversionen hade en FCP som låg på 3,6 sekunder och LCP på 5,5 sekunder. Här fanns det förbättringspotential men siffrorna är fortfarande acceptabla och fungerande. Genom att minska skript som blockeras och optimera hur resurser laddas kan användarupplevelsen förbättras.

## SonyMusic.com
Prestandan på datorversionen hos Sony Music är bra. Den har en FCP på 0,6 sekunder och LCP på 2,2 sekunder. Mobilasidan har FCP på 2,7 sekunder och LCP 11.1 sekunder. Godkänt men även denna sida kan bli bättre för mobilenheter. Genom att minska storleken på stora resurser och bilder kan sidan förbättras. CLS är på 0,057 vilket är bra men kan förbättras för att slippa att sidan ändrar layout vid laddning.

### Förbättringsområden
* Hantera bilder och stora filer för att snabbare laddningstider, främst på mobil.
* Minska bildstorleken utan att tappa kvalitet.
* Förbättra CLS för att göra så att sidan inte förändras när den laddas, vilket ger en bättre användarupplevelse.

### Rangordning
1.	SVT.se presterar stabilt både på dator och mobil.
2.	SonyMusic.com är bra på dator men kan förbättras på mobil.
3.	Nike.se har stora prestandaproblem på mobil och bör förbättras

Jag anser att en webbsida är snabb om den laddar på max 3 sekunder på en dator och skulle nog säga 4 sekunder på en mobilenhet. På så sätt uppfattar jag svt och sony som sidor som presterar bra medans jag tycker att nike underpresterar… sen som jag nämnde innan tror jag att de prioriterar upplevelsen på deras mobilapplikation.


# Referenser
* Google Pagespeed Insights
* Google Chrome DevTools

# Övrigt
Utförd av: Joel Berhane