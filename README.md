# DP-700_LAB04
# Microsoft Fabric - Gegevensinvoer met een Pipeline

Dit project demonstreert hoe je gegevens uit een externe bron kunt extraheren, transformeren en laden (ETL) in een **Lakehouse** binnen **Microsoft Fabric**. Het proces is ontworpen om een herbruikbare en schaalbare gegevensinvoerlijn te creëren met behulp van een combinatie van een **Data Pipeline** en **Apache Spark Notebooks**.

## 🔍 Overzicht

Met Microsoft Fabric kunnen data engineers eenvoudig complexe gegevensinvoerprocessen implementeren door:

- Het opzetten van een **Lakehouse** als centrale opslag.
- Het gebruik van een **Pipeline** om gegevens automatisch te kopiëren vanuit een externe HTTP-bron.
- Het toepassen van transformaties met **Spark-notebooks**.
- Het laden van de getransformeerde gegevens in Delta-tabellen binnen de Lakehouse-structuur.

## 📋 Wat je hebt gebouwd

Tijdens deze oefening heb je:

1. Een nieuwe **workspace** aangemaakt met Fabric-capaciteit.
2. Een lege **Lakehouse** aangemaakt met een submap voor nieuwe gegevens.
3. Een **pipeline** opgezet met:
   - Een activiteit om oude bestanden te verwijderen.
   - Een **Copy Data**-activiteit om een CSV-bestand van een publieke URL te laden.
   - Een **Notebook**-activiteit die gegevens transformeert (o.a. filtering, splitsing van namen, toevoegen van jaar en maand) en deze opslaat als een Delta-tabel.
4. De volledige workflow geautomatiseerd, zodat deze herhaald kan worden zonder handmatige tussenkomst.

## 🧠 Leerdoelen

- Werken met het Microsoft Fabric Lakehouse-concept.
- Gebruik van pipelines om gegevensinvoer te automatiseren.
- Gebruik van Apache Spark-notebooks voor transformaties.
- Tabellen creëren en beheren met Delta-formaat binnen OneLake.

## 📁 Gebruikte gegevensbron

Publieke CSV-bron:  
[https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/sales.csv](https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/sales.csv)

## 🧹 Opruimen

Na afloop kun je de volledige workspace verwijderen om middelen vrij te maken. Dit voorkomt ook onnodige kosten of opslaggebruik.

## 📌 Vereisten

- Een Microsoft Fabric-account met proeflicentie of toegang tot Fabric Premium.
- Basiskennis van Spark en data engineering-processen.

---



![Schermafbeelding 2025-04-30 064634](https://github.com/user-attachments/assets/b2dad854-0446-455f-ae4c-8e1acd496dd1)


![Schermafbeelding 2025-04-30 065336](https://github.com/user-attachments/assets/653b1045-6630-49e6-87e8-e91b0ab1578c)



![Schermafbeelding 2025-04-30 065734](https://github.com/user-attachments/assets/13de84f3-f263-45f2-ab26-0ed1a4c93c0c)


![Schermafbeelding 2025-04-30 065857](https://github.com/user-attachments/assets/4af64923-6c03-42e0-bfaf-f25fc16ce074)



![Schermafbeelding 2025-04-30 070223](https://github.com/user-attachments/assets/1fabad05-a040-4dfd-bc8a-94a7e0ffbbc4)



![Schermafbeelding 2025-04-30 070252](https://github.com/user-attachments/assets/40308997-b203-4708-9840-811810f38f98)




![Schermafbeelding 2025-04-30 071157](https://github.com/user-attachments/assets/3889609e-e463-460e-b53c-fb2b55718681)


![Schermafbeelding 2025-04-30 071329](https://github.com/user-attachments/assets/afb97e7d-e6b5-45bd-a852-ed5e94fe5323)



![Schermafbeelding 2025-04-30 072129](https://github.com/user-attachments/assets/7b6ef588-5168-4871-bb52-4ff55d86f674)



![Schermafbeelding 2025-04-30 072704](https://github.com/user-attachments/assets/061742ee-5941-4208-bb4e-ed4e128eb7a6)


![Schermafbeelding 2025-04-30 074725](https://github.com/user-attachments/assets/02783da8-c91b-4cd4-9c31-e5c7ee63e5be)


![Schermafbeelding 2025-04-30 075053](https://github.com/user-attachments/assets/0d632666-ef80-4487-b436-2e5d449433cc)


![Schermafbeelding 2025-04-30 075217](https://github.com/user-attachments/assets/400efef6-bd1a-455c-beef-a81da9d1c2d2)



Bedankt voor het bekijken van dit project!  
Voor vragen of suggesties, voel je vrij om een issue aan te maken of een pull request in te dienen.

