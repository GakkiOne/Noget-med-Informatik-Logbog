# Informatik-Logbog
Logbog for informatik

## Indholdsfortegnelse
* [Makeraktiviteter](#Makeraktiviteter)
* [Systemdesign](#Systemdesign)
* [Programmering](#Programmering)
* [Dronecontroller](#Dronecontroller)
* [Sikkerhed Privathed](#Sikkerhed-Privathed)
* [Reklamespil / Undervisningsspil](#Reklamespil-Undervisningsspil)
* [Computer / Netværk](#Computer-Netværk)


## Makeraktiviteter
  * __Hvad vi gjorde:__ 
  Vi brugte Fusion 360 til at lave en 3 figur, som skulle have et rumfang på 10cm^3, og have vores initial ingravet i figuren. Jeg valgte at lave en kugle, cylinder og firkant     og have bogstavet M ingravet. Vi gik 3 sammen om at udprint vores figure i makerspace. 24 timer senere var Figurene færdige, og de endte med at se rigtig gode ud. 
 
  * __Hvad lærte vi:__ 
  Vi lærte at bruge Fusion 360 som et 3D redskab, og CURE til at formatere vores figur til kode(kordinater), som 3D printeren så kunne bruge til at lave vores figur.
 
  ![Cylinder](/images/Cylinder.png)
  
  ![Firkant](/images/Firkant.png)
  
  ![Kugle](/images/Kugle.png)
  

## Systemdesign
  * __Hvad vi gjorde:__ 
  Vi lavede en analyse af hvordan Tello Dronen fungerede, og hvordan dens systemer var opbygget og hængte sammen. Vi lavede blandt andet en 3-lagsmodel over hvordan vi troede     Tello dronens systemer snakkede sammen med hinanden. Efter lavede jeg et blokdiagram som visualiserede hvad systemets 3-lag indeholdte og hvordan de snakkede sammen.
  * __Hvad lærte vi:__
  Vi lærte hvordan vi kunne tænke og forstå hvordan for eksempel en drones komponenter snakker sammen, og visualisere det ved hjælp af 3-lagsmodellen, bolkdiagram og flowcharts.
  
  ![blokdiagram](/images/blokdiagram.png)
  Blokdiagram
  ![trelagsmodel](/images/trelagsmodel.jpg)
  3-lagsmodel
  
## Programmering
   * __Hvad vi gjorde:__
   Under Programmerings forlåbet gik vi igang med at lege med arduinoer. Vi satte en sensor til arduionoen og satte derefter arduiono til vores computere, så vi kunne måle          sensorens data.
   
   * __Hvad lærte vi:__
   Vi fik et godt indtryk af hvordan man betjener en arduino. Dette bestod af at skrive noget kode til arduinoen, som så kan opfange data fra en sensor og give dataen videre til    os i python, hvor vi der kan skrive et program der udnytter denne data.
   
   
## Dronecontroller
  * __Hvad vi gjorde:__ 
  Under vores forlåb med Dronecontroller har vi både lavet en iteration 0, 1, brugerundersøgelse og en rapport. Vores iteration 0 gik ud på at brainstorme en ide til hvad vores   controller skulle indholde, så dronen kunne udføre en opgave. Vi lavede blandt andet et flowchart over hvordan controlleren skulle virke og hvilke knapper den skulle have. Vi   lavede også et blokdiagram der viste hvordan controlleren og dronen skulle hængde sammen.
 
 ![blokdiagramdrone](/images/blokdiagramdrone.png)
 ![flowchartdrone](/images/flowchartdrone.png)
 
 Vores iteration 1 indeholdede koden til arduinoen som fik vores joystick og knap til at måle data og sende det til arduinoen. Vi havde også begyndelsen på vores python kode til   både joysticket og vores knap.
 
  I vores rapport fik vi opdateres vores flowchart så det passede bedre til det vores controller kunne i slutningen af forlåbet. Vi fikl skrevet vores kode færdig så vi kunne     modtage data fra controlleren og bruge det i python til at lave beregninger.
  
  ![arduino](/images/arduino.png)
  Arduinokode
  ![python](/images/python.png)
  Pythonkode

  * __Hvad lærte vi:__
  Gennem vores Dronecontroller projekt har vi lært meget omkring hvordan vi bruger vores forskellige redskaber som brainstorm, blokdiagramer, opgavelister, tidsplan og flowcharts til at få opsat en god iteration 0, som vi så kan gå videre med til den næste iteration osv. På den måde har vi fået skabt et arbejdsmiljø hvor vi kan have styr på   alt der blivet lavet.
  Derudover lavede vi også en brugerundersøgelse hvor vi brugte gestaltlovene til at klargøre hvad det var vi ville undersøge og forbedre ved vores controller.
  
  
## Sikkerhed Privathed
  * __Hvad vi gjorde:__ Indtil videre har vi haft kigget på, hvordan vi som bruger på internettet bliver overvåget, og hvad man kan gøre for at beskytte sig selv, mod Hackers og    Scams på nettet. Vi har set filmen Snowden som handlede om ham der offentlig gjorde at FBI og NSA overvåger folk på deres Mails og bærbare kameraer.
  
| Datatype          | Følsomhed |   |   |   |
|-------------------|-----------|---|---|---|
| Etnisk oprindelse | Følsom    |   |   |   |
| Religion          | Følsom    |   |   |   |
| Adresse           | Normal    |   |   |   |
| Race              | Følsom    |   |   |   |
| Økonomi           | Følsom    |   |   |   |
| Fødselsdato       | Normal    |   |   |   |
| Navn              | Normal    |   |   |   |
| Biometriske data  | Følsom    |   |   |   |
| Gæld              | Følsom    |   |   |   |
| Seksuelle forhold | Følsom    |   |   |   |
| Arbejdsområde     | Normal    |   |   |   |
|                   |           |   |   |   |


  Vi har kigget på hvor følsomme persondata det er vi deler med forskellige private og offentlige virksomheder
  
  * __Hvad lærte vi:__ 


## Reklamespil Undervisningsspil
  
  #### Hvad vi gjorde 
 
  * __Målgruppeværktøjer:__ Vi har gjordt brug af Minerva modellen, AIDA modellen, forskellige spillertyper og til sidst Persona. Vi har skulle bruge dette til at lære hvordan man er mere målgruppe oriterenret når man laver et spil eller en reklame. Dette er vigtigt, da hvis målgruppen ikke er tænkt på kan en reklame eller psil mislykkes meget nemt.


  * __Designværktøjer:__ Vi har brugt AIDA modellen til at kigge på hvordan man ombygger en reklame og et spil, og kigget på spilmekanismer vores reklamespil kunne indeholde, så der ville være flere muligheder for brugerinteraktion.

  * __Vores projekt:__ Gennem forløbet har vi gjotdt brug af disse modeller til at vi som slutning skulle lavet et spil som skulle have implementeret en form for reklame. Vi har gjordt brug af disse modeller til at komme frem til målgrupper og reklamer ideer og herefter videre arbejdet på dem, for at tænke ideer til hvordan man kunne implementere dem i vores spil.

## Computer Netværk
  
  #### Hvad vi gjorde 
 
  * __OSI Model:__ 

![OSI](/images/OSI.jpeg)
  OSI Model

  * __Designværktøjer:__ Vi har brugt AIDA modellen til at kigge på hvordan man ombygger en reklame og et spil, og kigget på spilmekanismer vores reklamespil kunne indeholde, så der ville være flere muligheder for brugerinteraktion.

  * __Vores projekt:__ Gennem forløbet har vi gjotdt brug af disse modeller til at vi som slutning skulle lavet et spil som skulle have implementeret en form for reklame. Vi har gjordt brug af disse modeller til at komme frem til målgrupper og reklamer ideer og herefter videre arbejdet på dem, for at tænke ideer til hvordan man kunne implementere dem i vores spil.
