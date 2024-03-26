---
marp: true
theme: gaia
class:
  
  - invert
paginate: true voeg pagina nummers toe
header: SSL informatie
footer:  '![image width:47px height:1.2cm](<md oefeningen ssl/footer.png>)'

---

![bg brightness:.8 sepia:50%](<md oefeningen ssl/ssl-certificate-feature.jpg>)
<!-- _color: white -->


# Wat is ssl?


---
<style scoped>
    * {
        font-size: 36px;
    }
</style>

# De afkorting en definitie:

## waar staat de afkorting voor?
De afkorting staat voor Secure Sockets Layer.
### Definitie

Je kunt SSL zien als een veiligheidslaag voor het internet-verkeer tussen de website-server en de bezoekers van die website. SSL zorgt ervoor dat dit verkeer versleuteld wordt. Alleen de bezoeker en de server kunnen dit verkeer weer ontsleutelen.Die beveiliging bestaat uit het versleutelen van de gegevens die worden verzonden tussen een website en een browser, of tussen twee servers.
_ _ _
![width:500px height:5cm](<md oefeningen ssl/md oefeningen ssl/ssl_veilig.png>) <!-- Setting both lengths -->
<style scoped>
    * {
        font-size: 30px;
    }
</style>
### veligheid
* Een SSL-certificaat beveiligt de verbinding tussen jouw website en je bezoekers. De gegevens die verzonden worden via het beveiligde gedeelte van jouw website zijn afgeschermd en kunnen niet zomaar worden ingezien. SSL maakt het internet veiliger.

* Deze versleuteling voorkomt dat hackers de verzonden informatie, waaronder mogelijk persoonlijke of financiële gegevens, kunnen bekijken of stelen.

_ _ _
<style scoped>
    * {
        font-size: 30px;
    }
</style>
* Hoe vergemakkelijkt het WWW de uitwisseling van informatie op het internet?

Een SSL verbinding houdt in dat de verbindingen, bijvoorbeeld voor betalingstransacties en het verzenden van gegevens bij formulieren zoals naam, email etc. vanuit een website veilig zijn. Dit gebeurt door een SSL certificaat te koppelen aan de website. Hiermee kan de privacy worden gewaarborgd van de bezoekers van de website. Wanneer de website gekoppeld is met een SSL certificaat is deze herkenbaar doordat er HTTPS voor de URL staat. Een niet beveiligde verbinding is HTTP zonder de “s”, deze “s” staat voor secure (veilig). Omdat op een mobiel http en https niet wordt weergegeven is er ook nog een slotje toegevoegd voor de URL om de beveiliging beter zichtbaar te maken.
_ _ _ 
![bg right](ssl.jpg)

# Enkele situaties waarin het implementeren van SSL van cruciaal belang is:
_ _ _
<style scoped>
    * {
        font-size: 30px;
    }
</style>
 # Het implementeren van SSL  is cruciaal in situaties waar:

1. Gevoelige informatie wordt uitgewisseld, zoals in e-commerce websites tijdens het verwerken van betalingen.
2. Inloggegevens en persoonlijke gegevens worden verzonden, bijvoorbeeld op inlogpagina's van websites of bij het invullen van formulieren.
3. Vertrouwelijke communicatie plaatsvindt tussen een webserver en een webbrowser, zoals bij online bankieren of het versturen van medische gegevens.
4. Bescherming tegen gegevensmanipulatie en afluisteren nodig is, vooral op openbare wifi-netwerken.
5. Om de integriteit en authenticiteit van een website te verifiëren, waardoor gebruikers weten dat ze met de juiste server communiceren.
   