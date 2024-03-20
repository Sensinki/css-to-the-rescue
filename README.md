# CSS TO THE RESCUE 

Voor het vak CSS to the Rescue moeten wij een opdracht maken waar alleen css mag gebruikt worden. We kregen de keuze uit verschillende opdrachten, ik heb uiteindelijk gekozen voor de opdracht 'controle panel' te maken.

## WEEK 1 
In de eerste week moesten we na het kiezen van een case een idee genereren. Daarna moesten we een begin maken met het idee dat we hadden gekozen. Je kunt hieronder volgen wat ik heb gedaan :) 

## 🎨 Het Idee

Mijn idee is om een oude retro TV te maken met behulp van een control panel. Ik heb twee verschillende versies bedacht om deze retro tv te maken. Ofwel bedien ik de tv met de afstandsbediening van de tv, ofwel plaats ik de bedieningsknoppen op de rechterkant van de tv. Ik heb genoeg voorbeelden van beide versies gevonden in de oude tv's die ik heb geanalyseerd.

### Oudste tv
<img src="/assets/images/wiki/idee1-d.png" alt="retro oudste desktop" height="400px"> <img src="/assets/images/wiki/idee1-m.png" alt="retro oudste phone" height="400px">

### Oude tv
<img src="/assets/images/wiki/idee2-d.png" alt="retro oude desktop" height="400px"> <img src="/assets/images/wiki/idee2-m.png" alt="retro oude phone" height="400px">

### Nieuwe tv
<img src="/assets/images/wiki/idee3-d.png" alt="retro nieuwe desktop" height="300px"> <img src="/assets/images/wiki/idee3-m.png" alt="retro nieuwe phone" height="300px">

## Voortganggesprek 1

Na het voortganggesprek heb ik veel idee en inspiratie gekregen. Ik had drie verschillinde idee om te maken maar na het gesprek bepaal ik alles bijelkaar te houden. Dus ik ga alle drie gebruiken in verschillende media query's. Dus mijn nieuwe idee is als volgt;

### Phone 
<img src="/assets/images/wiki/n-mobile.png" alt="retro oudste phone" height="400px">
Dit is de oudste tv style die ik ga gebruiken als mijn kleinste scherm. 

### Tablet
<img src="/assets/images/wiki/n-tablet.png" alt="retro oude tablet" height="400px">
Dit is de middel grootte scherm die ik ga gebruiken. 

### Desktop
<img src="/assets/images/wiki/n-desktop.png" alt="retro nieuwe desktop" height="400px">
Dit is de nieuwe tv style die ik ga gebruiken als mijn grootste scherm. Omdat het groot is, zijn er veel ruimte en gebruiker moet afstandsbediening gebruiken.

## WEEK 2
Deze week ben ik bezig geweest met semantiek van html en styling van css. Ik probeer verschillende versies van mijn retro tv na te maken. Het is nog steeds niet perfect responsive wat ik tot nu toe heb maar ik heb de uitlijnen om het te bereiken.

### Hoe ziet mijn html eruit?

```

<body>
    <main>
        <!-- display hidden -->
        <h1>Retro TV</h1>
        <!-- TV -->
        <article>
            <!-- tv channels -->
            <section>
                <!-- don't forget to add 'autoplay' -->
                <video autoplay controls muted loop
                    src="./assets/videos/Rick Astley - Never Gonna Give You Up (Official Music Video).mp4">
                    <source src="/assets/videos/Rick Astley - Never Gonna Give You Up (Official Music Video).mp4"
                        type="video/mp4">
                    Your browser does not support the video tag.
                </video>
            </section>

            <!-- remote -->
            <section>
                <!-- on/off button -->
                <section>
                    <label for="onoff">ON/OFF</label>
                    <input type="checkbox">
                </section>

                <!-- channel numbers -->
                <section>
                    <ul>
                        <!-- p WEG -->
                        <li>
                            <input type="radio" name="channel">1
                        </li>
                        <li>
                            <input type="radio" name="channel">2
                        </li>
                        <li>
                            <input type="radio" name="channel">3
                        </li>
                        <li>
                            <input type="radio" name="channel">4
                        </li>
                        <li>
                            <input type="radio" name="channel">5
                        </li>
                        <li>
                            <input type="radio" name="channel">6
                        </li>
                        <li>
                            <input type="radio" name="channel">7
                        </li>
                        <li>
                            <input type="radio" name="channel">8
                        </li>
                        <li>
                            <input type="radio" name="channel">9
                        </li>
                    </ul>
                </section>

                <!-- volume -->
                <section>  
                    <label for="volume">VOLUME</label>
                    <input type="range">
                </section>
            </section>
        </article>
        <!-- TV foots -->
        <span></span>
        <span></span>
    </main>
    <!-- table? -->
    <footer></footer>
</body>

```

Ik dacht dat ik dit html-formulier niet ga veranderen. Maar aan het eind van de week realiseerde ik me dat het onmogelijk is om de volumefunctie zonder js te doen. Een paar jaar geleden was dit mogelijk in chrome en chromium gebaseerde browsers, maar nu is het niet meer mogelijk. Dus ik zal een ander idee bedenken om die functie te vervangen. 

Ik kan wel wat leuke ideeën bedenken, maar misschien een beetje ver van realisme. Bijvoorbeeld, de omgeving verandert volledig na het klikken op een knop, of dag- en nachtmode, of de antennes van de TV bewegen. Ik heb hier nog niet over nagedacht, maar het zal een van de dingen zijn waar ik volgende week over na zal denken. 

### Waar had ik moeite mee deze week?

Eigenlijk was ik aan het begin van de week in de war over hoe ik precies moest beginnen, maar het duurde niet lang en ik ging aan de slag. Dit waren de problemen waar ik mee worstelde en hoe ik ze heb opgelost:
- Ten eerste, omdat ik voor elke tv-stijl een ander ontwerp moest maken, controleerde ik de html-elementen bij elke stap terwijl ik ze maakte. Om deze kleine moeilijkheid op te lossen, gebruikte ik de commentaarfunctie van html, zodat ik gemakkelijk kon zien welke stap van de structuur ik aan het doen was.
- Ten tweede, duurde het even voordat ik me realiseerde dat het niet mogelijk is om het volume van de video alleen met css te verhogen of verlagen. Met hulp van Sanne, ontdekte ik dat het niet meer mogelijk is maar vroeger wel. Helaas heb ik dit probleem nog niet opgelost. Ik ben nog steeds op zoek naar nieuwe ideeën.

## Voortganggesprek 2
In eerste instantie plaatste ik een ```<p>``` element in de ```<li>``` om te schetsen. Dankzij de feedback die ik kreeg, realiseerde ik me dat het beter zou zijn om in plaats daarvan het ```<input type="radio">``` element te gebruiken en de kanalen op deze manier te wijzigen.
Verder kreeg ik inspiratie van mijn vrienden. Het was een nuttig gesprek om het project in mijn hoofd te realiseren.

### Wat ben ik van plan volgende week te doen?

- Helemaal responsief
- Styling van de afstandsbediening
- Kanalen werkend krijgen
- Nieuwe idee vinden in plaats van volume

## WEEK 3
Deze week ben ik bezig geweest met css. Ik heb paar animaties toegevoegd en tv aan/uit effect werkend gekregen. Ik heb een nieuwe idee gevonden en die uitgewerkt. Het glitch idee nog niet helemaal af maar ik ben hiermee bezig. Het tv heeft nu perfect responsiveness. 

### Waar had ik moeite mee deze week?
- Ik had moeite mee met glitch effect te creeren. Maar uiteindelijk lukt het wel en ik heb twee verschillende (voor titel en tv) glitch effect gemaakt. 

## Voortganggesprek 3

### Wat ben ik van plan volgende week te doen?
- em en px veranderen naar rem
- Styling van de afstandsbediening
- Glitch effect verbeteren
- Knop stylingen
- Passende titel maken
- Kanalen werkend krijgen
- Alles in de @layers zetten volgens prioriteit  

## WEEK 4

Deze week is de deadlineweek. Vorige week heb ik alle taken afgerond die nog ontbraken en voor de deadline afgerond moesten worden. Wat ik moeilijk vond, was eigenlijk het nesten. Het was erg moeilijk om alle code die ik eerder had geschreven te verbeteren. De volgende keer zou het beter zijn als ik alles vanaf het begin doe met nesting. 

## REFLECTIE

Dankzij deze cursus heb ik geleerd dat je zoveel dingen kunt doen met css. Ik had nooit gedacht dat ik zoveel dingen kan doen met css. Vooral Julia Miocene, die onze klas kwam bezoeken, heeft me hier erg over verbaasd. 

Dankzij dit project heb ik het gebruik van ```:has``` en ```:not``` geleerd en ik weet zeker dat ik ze in de toekomst zal gebruiken. Aan de andere kant heeft dit project me geholpen om de moeite die ik meestal heb met kleurverlopen (gradients) en animaties te verminderen en om praktischer te worden.




