# User manual voor Microsoft Cloud Adoption Framework for Azure 
## inhoudsopgave
* [Inleiding](#inleiding) 
* [Wat voor soort framework is dit](#wat-voor-soort-framework-is-dit)
* [De 6 fases](#de-6-fases)
* [Nuttige tools voor Cloud governance framework](#Nuttige-tools-voor-Cloud-governance-framework)
* [Wat zijn de sterke punten en zwakke punten van Microsoft Cloud Adoption Framework voor Azure](#Wat-zijn-de-sterke-punten-en-zwakte-punten-van-Microsoft-Cloud-Adoption-Framework-voor-Azure)
* [Wat is de vergelijking met AWS Cloud Adoption Framework](#Wat-is-de-vergelijking-met-AWS-Cloud-Adoption-Framework)

# Inleiding 
Microsoft Cloud Adoption Framework for Azure is een framework die gemaakt is door Microsoft. Dit framework is onderverdeeld in 6 fases zoals u hieronder ziet. De reden dat het onderverdeeld is in verschillende fases is zodat elk bedrijf dit framework kan gebruiken onafhankelijk van hoe volwassen hun Cloudomgeving is om beter governance te krijgen. Als u voor het eerst een omgeving maakt in Azure kunt u beginnen bij het begin met define strategy of als u al voor jaren een Cloud omgeving hebt bij Azure maar het beheren van uw omgeving wilt verbeteren kunt u kijken naar govern of manage gedeelte van het framework. 

![image of the azureframwork](https://docs.microsoft.com/nl-nl/azure/cloud-adoption-framework/_images/caf-overview-new.png)

# wat voor soort framework is dit
Dit framework is vooral gemaakt voor het migreren naar de Azure Cloud omgeving. Ook al dekt het een groot deel van de aspecten van Cloud governance af wordt er weinig gezegd over security, het is de bedoeling dat uw zelf de applicatie veilig maakt terwijl de security van de omgeving door Azure zelf wordt geregeld. 
# De 6 fases 
De 6 fases zijn samen te vatten in een zin “define your strategy, make a plan, ready your organization, adopt the cloud, and govern and manage your digital estate.”

**Define strategy:**

U wilt uw motivatie begrijpen, de reden dat u naar de Cloud migreert is heel belangrijk om een Cloud strategie te ontwerpen.
Wat zijn uw business business outcomes, het is belangrijk dat uw stakeholders weten op welke uitkomsten u moet focusen. 
Maak een business case en financial model om de impact te meten van de adoptie strategie.  

**Plan:**

Heb een duidelijk overzicht van al jouw IT assets en evalueer ze zodat u de beste manier vindt om ze te hosten in de Cloud. 
Maak een adoptie plan op basis van business impact en complexiteit. 
Maak een skills readiness plan zodat u weet hoe werknemers rollen veranderd moeten worden of bijgeschoold moeten worden door de verandering naar de Cloud  
 
**Ready:**

Dit gaat vooral om een omgeving te maken en het te migreren naar Cloud. 
Gebruik landing zones om voor te bereiden op het migreren naar Azure. Landing zones zijn een soort blauwdruk waarmee gestroomlijnd een migratie kan doen naar een Cloudomgeving. 

u kunt hiervoor ook een blueprint kunnen gebruiken, met een blueprint laat u Azure automatisch een omgeving bouwen. Dit is nuttig voor als u een omgeving wilt hebben die aan iso standaarden voldoet maar u wilt niet zelf de omgeving bouwen. U kan ook de blueprint aanpassen om beter bij uw bedrijf te passen. 


**Adopt:**

Waarom gaat u naar de Cloud, er zijn twee motivaties:

**Migratie**
: Uw bedrijf gaat uw bestaande applicaties naar de Cloud migreren. u begint met een paar applicaties en gaat daarna de rest doen met de ervaring die u gekregen hebt. 
Innovation: U wilt focussen op een moderne omgeving en product innovatie en u wilt Cloud daarvoor gebruiken 

**Govern:** 
Gebruik de governance benchmark tool om te kijken waar de gaten zitten in uw governance.
Het is ook belangrijk dat risicos geidentificeerd worden en dat u een risico beleid maakt

**Manage:**
Dit gaat vooral over het beheren van de omgeving. De 3 belangrijkste delen hiervan zijn monitoring, management en resiliency
•	Staat monitoring aan, worden alerts gegenereerd, wordt data verzameld en wordt er een sla gemaakt.
•	Wordt managment goed geregeld, identificeer kritische operations voor de business operations, welke services zijn afhankelijk van elkaar, 
•	Is het platform resilient, heb een juiste balans van hoeveel u betaald voor resilience en hoeveel u ervoor krijgt, kunt u herstellen van failures met minimale downtime en data verlies en als laatste moet u evolueren naar een highly available platform. 

# Nuttige tools voor Cloud governance framework
Het kan redelijk intimideerend zijn om een Framework toe te passen, zeker als u al een azure omgeving hebt. Daarom heeft azure verschillende tools gemaakt om u te helpen met het implementeren van het framework.

**Journey tracker**
Dit is een van de eerste tools die u kan gebruiken. U vult meerdere multiple choice vragen in over uw omgeving en daarna krijgt u een overzicht met hoe goed uw bedrijf de 6 fases heeft uitgevoerd. De tracker geeft ook begeleiding hoe iets verbeterd moet worden als het nodig is en verwijst naar het nuttige materiaal zodat u dit kan toepassen. 

![journeytracker](https://azurecomcdn.azureedge.net/cvt-2881b2a529b708c1f6ca6ce54d3368d6a0b5536105a12d7c023e5ab6fef6e4e5/images/page/cloud-adoption-framework/value-prop-1.png)

**Governance benchmark tool**
Dit is een iets meer in-depth vragenlijst die er vooral is om de zwaktes te vinden in de governance van jouw omgeving. Journey focused op alle 6 fases en is redelijk oppervlakig en Governance benchmark tool is vooral gefocused op governance. 
Het resultaat wordt weergegeven in current state en desired state en laat ook zien hoe hoog de industrie standaar scoort. 

![benchmark tool](https://azurecomcdn.azureedge.net/cvt-2881b2a529b708c1f6ca6ce54d3368d6a0b5536105a12d7c023e5ab6fef6e4e5/images/page/cloud-adoption-framework/value-prop-3.png)

# Wat zijn de sterke punten en zwakte punten van Microsoft Cloud Adoption Framework voor Azure

Een van de sterkste punten van dit framework is dat het direct geïntegreerd is met Azure want het makkelijker maakt om te implementeren. Bij de Journeytracker krijgt u direct advies hoe u dit moet implementeren, Azure heeft blueprints die het versimpelen om een omgeving te maken die voldoet aan ISO standaarden en Azure heeft meerdere functies in het portal die u kunnen helpen zoals Quickstart. 

Het nadeel van dit framework is dat het geen onafhankelijke standaard is, het is gemaakt door Microsoft en ze willen dat u Microsoft producten gaat gebruiken, een gevolg hiervan is dat u makkelijk vendor lock-in krijgt. 

# Wat is de vergelijking met AWS Cloud Adoption Framework 

Als u geen fan bent van Azure kan uw AWS Cloud Adoption Framework gebruiken (AWS CAF). AWS CAF is verdeeld in 6 termen en deze 6 termen lijken veel op de termen die Azure gebruikt maar dan met een andere naam. In plaats van define strategy heef AWS business perspective, deze focussen allebei op het idee dat de eerste stap van de cloud migratie is dat u moet nadenken over business interest en financiele modelen voordat u door gaat naar de volgende stap. Maar AWS CAF heeft wel een aparte stap voor security wat ze niet bespreken bij Azure. Voor mij lijkt de Azure het betere framework aangezien hij meer volwassen is en meer integratie heeft met zijn platform. 