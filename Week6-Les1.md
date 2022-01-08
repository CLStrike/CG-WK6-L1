__gemaakt door Dennis & Coen __  
# Week 6, Lesson 1: Governance Frameworks

## Framework: ISAE 3402  
In dit document zullen we ingaan op het ISAE 3402 Framework en hoe dit wordt toegepast in het Cloudlandschap.

We Hebben twee korte videos die uitleggen wat ISAE 3402 inhoudt en op welke manier de Audit plaastvindt om te bewijzen of je voldoet aan de ISAE 3402.  
Videos below  
- [CyberGuard Compliance ISAE 3402 Audit Overview](https://www.youtube.com/watch?v=CGQUCbDtCwI&ab_channel=CyberGuardCompliance%2CLLP)  
- [SOC 1 and SOC 2 Audits vs Type I and Type II Audits](https://www.youtube.com/watch?v=PHOjErF7yis&ab_channel=CyberGuardCompliance%2CLLP)


## Wat is het ISAE 3402 Framework

---
De norm staat voor International Standard for Assurance Engagements. Het is een audit standaard voor rapportage over beheersing van processen die zijn uitbesteed. Een ISAE-verklaring is gericht op organisaties die in aanmerking komen voor een onderzoek naar de geïmplementeerde beheersmaatregelen om de kritische processen van een klant te beveiligen.

<br>

Het ISAE-Framework bestaat uit vier verschillende onderdelen die samen het gehele ISAE-framework opbouwen.  
Om verwarring te voorkommen zullen we beschrijven wat de onderdelen inhouden en wat het primairy doel is van het gehele ISAE 3402-framework.

<br>

## SOC 1 & 2
Het ISAE-framework process beheer kan worden onderverdeeld in twee delen SOC 1 en SOC 2.   
beiden variant kijken naar een ander gedeelte van de organisatie en controlleren andere aspecten van de organisatie.

**SOC 1** heeft als doel de interne financieele processen van een organisatie na te lopen, Echter kijkt SOC 1 ook naar hoe een organisatie hun financieele gegevens deelt en verwerkt bbinnen de organisatie. We kunnen concluderen dat SOC 1 Voornamelijk is gemaakt voor bedrijven die financieele gegevens verwerkt voor en van klanten. SOC 1 is niet direct bedoeld voor het Cloudlandschap.

**SOC 2** is gemaakt voor het Cloudlandschap en kijkt naar de volgende aspecten van de cloudomgeving: Security, availability, process integrity, confidentiality en privacy hierin wordt onderzocht of de benoemde aspecten voldoen aan de gestelde eisen van de klant en aan de eisen van de wetgeving zoals het verwerken van persoonsgegevens. Elk aspect wordt nagelopen en er wordt nagekeken of de omgeving voldoet aan de gestelde eisen van het AICPA. 

Zowel SOC 1 & 2 moeten worden gecontroleerd of ze daadwerkelijk worden gebruik binnen een organisatie. Hiervoor heeft ISAE twee opties beschikbaar gesteld Type 1 en Type 2 we zullen kort ingaan wat de types precies inhouden.

<br>

---

## Type 1 & Type 2

het verschil tussen Type 1 en 2 zit voornamelijk op de manier hoe wordt gecontroleerd of je voldoet aan de ISAE 3402 en hebben beiden ook een andere sterkte van controle. 

Bij Type 1 wordt er onderzocht of er een beleid en proces is beschreven omtrent de maatregelen die binnen de scope vallen. De auditor bekijkt of de beschrijving van het ISAE-rapport overeenkomt met de daadwerkelijke situatie. Hierbij wordt alleen gekeken of wat op papier staat ook aanwezig is maar niet de effectiviteit van de aanwezigen processen of systemen.

Bij Type 2 verzamelt De organisatie informatie over een proces of tool gedurende zes maanden  met daarbij, behorende risico's en maatregelen. De auditor bekijkt de manier waarop maatregelen hebben gewerkt om de beheer doelstellingen die zijn vastgesteld te behalen. Type 2 kijkt dus daadwerkelijk of het systeem en processen over een lange periode effectief zijn en worden gebruikt door een organisatie.

<br>

---

## Hoe draagt het ISAE 3402 bij aan Cloud Governance en is het compleet?

<br>

SOC 2 van het ISAE 3402 framework heeft specifiek als doel om het Cloud Governance framework die is geimplementeerd bij een klant te controleren.  Zoals eerder beschreven defineert SOC 2 meerdere criteria's voor het beheren van klant data in cloud omgevingen. In dit hoofdstuk zal eerst kort de hoofd componenten van Cloud Governance worden besproken en SOC 2 worden vergeleken met het Cloud Governance framework, vervolgens word er gekeken welke raakvlakken er precies zijn en tot slot zal hierdoor zichtbaar worden hoe ISAE3402 bijdraagt aan Cloud Governance.

## CloudGovernance in a nutshell.
 
![CloudGovernance primary components](images/Group-15663.png "'primary components of a cloud governance framework.' ~ imperva.com")  

<details open>
<summary>Cloud Financial Management  </summary>
&nbsp;&nbsp;&nbsp;&nbsp;Cloud kosten kunnen snel oplopen. Het is van belang om binnen de Cloud maatregelen te nemen. Binnen het financieel management zijn er drie aspecten die nagestreven moeten worden: 
<br><ul>
  <li>Financiele policies</li>
      Via deze policies kan een organisatie bepalen hoe financieel gezien de Cloud gebruikt mag worden.
      Zo kan men policies maken die eisen stellen aan het uitrollen van cloud diensten, denk hierbij aan cost management checklists of conditionele voorwaarden voor het kiezen van bepaalde producten.
  <li>budgettering</li>
      Via budgettering kan een organisatie bepaalde limieten opgeven betrekkend tot verschillende afdelingen en/of cloud service catagorieën.
  <li>kosten rapportages</li>
      Doormiddel van kost rapportages kan een organisatie inzicht krijgen in de kosten en eventueel bezuinigen.
</ul> 
</details>
<details open>
<summary>Cloud Operations Management  </summary>
&nbsp;&nbsp;&nbsp;&nbsp;Cloud Operations Management draait om het defineren van de processen voor het uitrollen van diensten. De volgende punten moeten in de processen aanwezig zijn:
<br><ul>
  <li>Service-level agreements (SLAs) om de verwachte prestaties te defineren</li>
  <li>monitoring van de diensten en producten om de SLA te waarborgen</li>
  <li>Een helder overzicht van resources die in de loop van de tijd aan de dienst zijn toegewezen</li>
  <li>Een process en bijhorende checklist voor het uitrollen van code naar productie</li>
  <li>toegangscontrole vereisten</li>
</ul> 
</details>
<details open>
<summary>Cloud Data Management  </summary>
&nbsp;&nbsp;&nbsp;&nbsp;De cloud maakt het gemakkelijk om enorme hoeveelheden data te verzamelen en te analyseren, echter zal hierdoor het beheer van deze data een stuk ingewikkelder worden. <br>
&nbsp;&nbsp;&nbsp;&nbsp;Vanuit de principes van Cloud Governance zal een bedrijf moeten specificeren hoe de data lifecycle moet worden beheerd. Het gaat hierbij om de volgende principes:
<br><ul>
  <li>Het uitwerken en opzetten van een data classificatie schema en het instellen van policies van data op verschilende niveaus van confidentiality.</li>
  <li>Ervoor zorgen dat alle gegevens worden versleuteld, Hierbij geldt het voor "at rest" en "in transit"</li>
  <li>Passende toegangscontroles instellen voor elk type gegevens</li>
  <li>Gegevensmaskering gebruiken om het risico van gevoelige gegevens te verkleinen wanneer deze worden gebruikt voor scenario's zoals ontwikkeling, testen of training</li>
  <li>Een gelaagdheidsstrategie ontwikkelen, gegevens in de loop van de tijd verplaatsen van dure snelle toegangssystemen naar goedkopere archiveringssystemen</li>
  <li>Ervoor zorgen dat het beheer van de levenscyclus van gegevens wordt geautomatiseerd - dit is van cruciaal belang om beleid toe te passen bij grootschalige cloudimplementaties</li>
</ul> 
</details>
<details open>
<summary>Cloud Security and Compliance Management  </summary>
&nbsp;&nbsp;&nbsp;&nbsp;Cloud governance neemt de verantwoordelijkheid voor alle belangrijke onderwerpen van bedrijfsbeveiliging. Het bepaalt wat de beveiligings- en nalevingsvereisten van de organisatie zijn en zorgt ervoor dat deze worden gehandhaafd in de cloudomgeving. Denk hierbij aan:
<br><ul>
  <li>Risico management</li>
  <li>Identity & Access Management (IAM)</li>
  <li>Opslag beheer & versleuteling</li>
  <li>Applicatie beveiliging</li>
  <li>Disaster Recovery</li>
</ul> 
</details>  
<br>

## SOC 2 & Cloud Governance  
Nu de Cloud Governance haar kern componenten beschreven zijn, kunnen we vaststellen dat het ISAE3407 framework en het Cloud Governance framework een directe koppeling met elkaar hebben. Beide frameworks benoemen namelijk de volgende punten.
- Security  
- availability  
- process integrity  
- confidentiality  
- privacy

Hieruit kunnen we dus concluderen dat de frameworks samen gebruikt kunnen worden om het cloud landschap van een organisatie te controleren.  

---

## Wat zijn de sterke punten en wat is minder goed?

## The bad

Het framework van ISAE geeft een organisatie de mogelijkheid hun Cloudomgeving en het Cloud-framework te controleren en na te gaan of ze aan alle eisen voldoen. Echter zijn er wel een aantal punten die benoemt moeten worden die wat minder goed zijn is het ISAE-framework. 

De Type 1 controle biedt de organisatie de mogelijk snel te voldoen aan een ISAE onderdeel. Echter controleert Type 1 alleen maar of er een process, systeem of oplossing aanwezig is. Het contrleert niet of het systeem daadwerkelijk werkt. Hiervoor is een Type 2 audit nodig. Hierdoor kan er snel verwarring onstaan als een organisatie aangeeft dat ze compliant zijn volgens de ISAE standaard. 

Daarbij Heeft de ISAE geen certificiering die wordt uitgereikt. Een organisatie die een audit heeft behaalt krijgt, alleen een rapportage als bewijs dat ze aan de ISAE eisen voldoen. Dit kan Fraude gevoelig zijn en lastig voor een klant zijn om te controlleren of een leverancier echt voldoet aan de eisen van het ISEA-framework.

<br>

## The good

ISEA stelt een organisatie in staat een leverancier te vinden dat voldoet aan een bepaalde manier van werken. Waardoor de organisatie weet dat hun systemen en Data veilig worden verwerkt. Daarbij kan een Organisatie die een Type 2 audit heeft behaald ook daadwerkelijk aantonen dat ze werken volgens het ISAE-framework en ze voldoen aan een Internationaal erkent standaard.  

---

## Wat doen de grote public cloud providers eigenlijk met deze standaard/framework?

En bekende Cloud Providers zoals Microsoft, AWS en Google maken ook gebruik van het ISAE framnework om aan te tonen dat hun services, gegevensverwerking  en systemen voldoen aan de eisen van het standaard we zullen kort benoemen hoe Azure, AWS en Google omgaan met het ISAE-Framework. 

<br>

### Microsoft

Maakt gebruik van meerdere frameworks om aan te tonen dat ze voldoen aan het beveiligen van hun data en omgeveing hiervoor hebben ze een [website](https://docs.microsoft.com/nl-NL/compliance/regulatory/offering-home?view=o365-worldwide) waar alle framework zichtbaar zijn waar ze aan voldoen. Hierin verwijzen ze ook naar [SOC 1](https://docs.microsoft.com/nl-NL/compliance/regulatory/offering-soc-1) en [SOC 2](https://docs.microsoft.com/nl-NL/compliance/regulatory/offering-soc-2) hierin wordt beschreven welke componenten van hun cloudiensten in de scope vallen van de Audit en waar ze specieifek op getest zijn. Daarnaast is het mogelijk het rapport gratis te downlouden hierdoor kunnen geintresserden nakijken wat er precies is geaudit. 

<br>

### AWS 

biedt net zoals Microsoft de modgelijkheid om in te zien op een website aan Welke ISAE standaarden ze voldoen en welke typen ze hebben gehaald op de volgende [website](https://aws.amazon.com/compliance/soc-faqs/ "SOC Frequently Asked Questions") Hierin is ook zichtbaar welke onderdelen in de scope vallen en is de rapportage te downlouden voor het publiek.


<br>

### Google  

Google biedt net als Microsoft en AWS de mogelijkheid om via de website te zien aan welke ISAE standaarden ze voldoen en welke types ze gehaald hebben. [website](https://cloud.google.com/security/compliance/offerings#/ "Google Cloud Compliance page") 
Net zoals de andere bekende publieke cloud providers biedt Google ook de mogelijkheid om rapportages in te zien op de website.  

---

<br><br>

---
Bronnen

https://www.imperva.com/learn/data-security/cloud-governance/  
https://www.imperva.com/learn/data-security/soc-2-compliance/  
https://www.youtube.com/watch?v=CGQUCbDtCwI&ab_channel=CyberGuardCompliance%2CLLP  
https://www.youtube.com/watch?v=PHOjErF7yis&ab_channel=CyberGuardCompliance%2CLLP  
https://isae3402.nl/wat-is-isae3402  
https://www.abab.nl/services/audit-assurance/isae3402-verklaring
https://certificeringsadvies.nl/wat-is-isae-3402/
https://docs.microsoft.com/nl-NL/compliance/regulatory/offering-soc-2
https://docs.microsoft.com/nl-NL/compliance/regulatory/offering-soc-1
https://docs.microsoft.com/nl-NL/compliance/regulatory/offering-home?view=o365-worldwide
https://aws.amazon.com/compliance/soc-faqs/

