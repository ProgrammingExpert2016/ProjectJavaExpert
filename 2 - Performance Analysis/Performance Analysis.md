1) Zoek op wat er precies met "performance analysis" bedoelt/verstaan wordt.
2) Welke tools zijn er voorhanden om deze analyse uit te voeren/ worden er gebruikt. (Java tools)

Bovenstaande puntje moeten verwerkt worden in een bibliografie/tekstuele beschrijving.

# Wat is performance analyse?

### Inleiding

Indien we opzoek gaan naar wat "performance analysis" betekent, waarvoor het gebruikt wordt en het nut ervan, stellen we vast dat dit concept gekend is en gebruikt wordt in talrijke domeinen:

    - Software & algoritmes
    - Sport
    - Economie
    - Human resource management
    - Verkoop
    - Marketing
    - ...

In deze analyse gaan we ons echter focussen op het domein van software en algoritmes.

### Beschrijving

Performance analysis is eigenlijk een discipline waarbij systematische observaties worden gedaan om prestaties en besluitvorming te verbeteren.
Hierbij wordt alle informatie hoofdzakelijk verstrekt door middel van objectieve statistische (Data Analysis) en visuele feedback (Video Analysis).

In het performance analysis proces onderschiedt men 3 verschillende stappen:

    ###### 1. Verzamelen van gegevens

    Het verzamelen van gegevens is het proces waarbij data, over de prestaties van programma's, worden verkregen uit een uitvoerend programma.
    Om dit te kunnen realiseren worden er observatietools gebruikt die gegevens kunnen meten, registreren en visueel voorstellen.

    Dit proces heeft een zeer uiteenlopende tijdsduur en is vrijwel afhankelijk van de software samen met welke doeleinden men voor ogen heeft.
    Doorgaans is dit een langdurig en intensief gebeuren.

    ###### 2. Gegevens transformeren

    Om data goed te kunnen bestuderen is het nodig dat de gegevens zodanig in een vorm worden omgezet die het mogelijk maken antwoorden te bieden.
    Nieuwe verzamelde gevegens voldoen zelden aan deze eisen en is het dus noodzakelijk om een transformatie te verwezenlijken.

    Vaak wordt het volume van gegevens verminderd en gestructureerd tot een bestudeerbare hoeveelheid.

    ###### 3. Gegevens visualiseren

    Nadat de data een transformatie heeft ondergaan, zou het een enorme bijdrage zijn voor de analyse dat alle data visueel voorgesteld zou kunnen worden.
    Gegevens visualiseren kan vele vormen aannemen. Een van de meest voorkomende vormen zijn: grafieken, diagrammen en statistieken.
    Het is dus belangrijk dat er goed wordt nagedacht dient te worden over welke visualisatie technieken er gebruikt zullen worden in het analyse proces. 

    Visualisatie bevorderd dus het inzicht in de gegevens waardoor er sneller observaties kunnen worden gedaan en het nemen van beslissingen bekrachtigt.


### Waarom performance anylyse?

Er zijn vele redenen waarom performance analyse uitgevoerd wordt. (Efficientie, ...)

### Verschillende tools

Om prestaties echter te kunnen verbeteren moeten we het eerst in meetbare termen kunnen beschrijven. Dit wordt vaak aan de hand van interviews, surveys, grafieken, diagrammen,... gemeten.
In het software & algoritme domein wordt er voornamenlijk gebruikt gemaakt van observatietools die de prestaties van lopende software kunnen gaan meten en visueel weergeven.


"As we shall see, a wide variety of data collection, transformation, and visualization tools are available. When selecting a tool for a particular task, the following issues should be considered:  

Accuracy. In general, performance data obtained using sampling techniques are less accurate than data obtained by using counters or timers. In the case of timers, the accuracy of the clock must be taken into account.
Simplicity. The best tools in many circumstances are those that collect data automatically, with little or no programmer intervention, and that provide convenient analysis capabilities.
Flexibility. A flexible tool can be extended easily to collect additional performance data or to provide different views of the same data. Flexibility and simplicity are often opposing requirements.
Intrusiveness. Unless a computer provides hardware support, performance data collection inevitably introduces some overhead. We need to be aware of this overhead and account for it when analyzing data.
Abstraction. A good performance tool allows data to be examined at a level of abstraction appropriate for the programming model of the parallel program. For example, when analyzing an execution trace from a message-passing program, we probably wish to see individual messages, particularly if they can be related to send and receive statements in the source program. However, this presentation is probably not appropriate when studying a data-parallel program, even if compilation generates a message-passing program. Instead, we would like to see communication costs related to data-parallel program statements."