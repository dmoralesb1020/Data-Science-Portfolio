# The recovery of foreign visits to Colombia
## Introduction

For my capstone project in Google’s Data Analytics Professional Certificate Program, I undertook an analysis titled "The Recovery of Foreign Visits to Colombia". As a native Colombian, I wanted to apply my new skills to analyze data from my country. The aim of this project was to explore the trends in international tourism to Colombia, particularly focusing on the recovery trajectory following the disruption caused by COVID-19. I was also interested in examining the country of origin of our international visitors, providing a clearer understanding of tourism dynamics.

In this project I used Microsoft Excel, MySQL Workbench, and Tableau.

## Questions for analysis
* Has Colombia experienced a year after 2019 with more international visitors than in 2019? This would help determine if the country successfully recovered from the tourism disruptions caused by COVID-19.
* Medellín has experienced a significant growth in tourism on the last 5 years. Has Medellín succeeded in becoming the second most visited city in Colombia by foreigners, surpassing Cartagena?
* What are the countries of origin for Colombia's international visitors?
* Which month does Colombia receive the highest number of international visitors?

## Dataset

**Name:** non-resident visitors

**Latest update:** June 7th, 2024

**Source:** Colombia’s National Platform of Open Data - https://www.datos.gov.co/Comercio-Industria-y-Turismo/Visitantes-No-Residentes/bkar-zsub/data_preview

**Data provided by:** Ministry of Commerce, Industry and Tourism

**Description:** Data on non-resident visitors entering the country through various immigration points. This data is collected monthly and is broken down at the municipal level. Information is reported from the January 2015 until June 2024. All data is in Spanish.

## Project workflow
**Microsoft Excel**
* Imported the CSV file in Microsoft Excel.
* Performed an initial inspection of the data. I found that the words that include the letter “ñ” or vowels with accents, have errors. For example, “Perú” is shown in the file as “PerÃº”.
* Applied the corrections for special characters such as: á, é, í, ó, ú, ñ, ü. More than 300,000 corrections were made.

**MySQL**
* Imported the updated CSV file into MySQL
* Checked for blank cells. None was found.
* Identified cells containing the value “Sin Especificar” (meaning “Unspecified”). Since I could not determine the corresponding * destination city or country of origin for these entries, I removed those rows.
* There were some cells with the value “Sin Especificar”, this means “Unspecified”. Since I had no way to find out the city or country for those cells, I removed those rows.
* Checked for duplicate records and removed 13 rows.

**Tableau**
* Created a line chart to visualize the number of foreign non-resident visitors over time.
* Created a pie chart to visualize the 5 most visited cities.
* Created a bar chart to display the number of foreign visitors by country of origin.
* Created a bar chart to display the number of visitors by month.

* ## Conclusions
* My analysis sought to determine whether Colombia experienced a year after 2019 with more international visitors than in 2019, as a measure of recovery from the tourism disruptions caused by COVID-19. The data reveals that in both 2022 and 2023, Colombia registered more foreign visitors than in 2019, indicating that the country successfully recovered from the pandemic's impact on tourism by 2022. 
* Over the entire period from 2015 to 2023, Cartagena maintained its position as the second most visited city, attracting 18.45% of foreign visitors, while Medellín ranked third with 17.19%. However, when focusing on the period from 2019 to 2023, Medellín emerged as the second most popular destination, with 19.77% of foreign visitors compared to Cartagena's 19.08%. Medellín surpassed Cartagena in both 2022 and 2023, demonstrating its successful ascent to the second most visited city in Colombia by foreigners during this period.  
* The top 5 countries of origin between 2015 and 2023 were United States, Mexico, Ecuador, Perú and Brazil. Notably, the number of visitors from the United States is remarkably higher, exceeding the number of visitors from Mexico, the second-highest country of origin, by more than 350%. 
* December is the month in which Colombia receives more foreign visitors.




