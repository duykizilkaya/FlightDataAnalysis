# FlightDataAnalysis

** German Below 

This project focuses on processing and analyzing a large dataset with flight information. The main goals are to clean the data, analyze it, and visualize the findings to uncover various correlations.

Project Overview

_Goals:_

* Data Cleaning: Ensure the dataset is free of inconsistencies and errors to improve analysis accuracy.
* Data Analysis: Perform statistical analysis to discover patterns and relationships within the flight data.
* Data Visualization: Create visual representations of the findings to facilitate understanding and communication of results.

_Achievements:_

* Processed a dataset with approximately 3 million flight records.
* Handled missing values, corrected data types, and removed duplicates.
* Identified key correlations and patterns in the data.
* Applied various statistical tests to find significant correlations (ANOVA, Chi-square)
* Developed several visualizations to illustrate findings clearly.
  
_Results:_

* Proportion of cancelled Flights:

![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/3e37ff0a-dd2a-4d70-af94-78be89b398b0)

* Proportion of cancelled Flights by Airlines:

![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/91d8b9cc-f202-4a00-8464-f19aff4abb43)

* Proportion of cancelled Flights by Airports:

![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/1e7f03c6-7872-4a70-9fb1-4b57b762d6e5)

* Number of Cancellations by Year and Airline in the Top Three Cancelled Airline:
![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/36f95847-8e75-402d-8171-ed5791757fbb)

* ANOVA:
   * Anova Between Delay Times and Airlines
    Results:
    F-statistic = 1182.5929791586866, p-value: 0.0021
    Interpretation: There is a statiscally significant difference in flight delays across different airlines.

* Chi-Square Test
    * Chi Square test between Airlines and the Cancellation Rate.
    * Results:
      * Chi-square statistic: 6235.42531094938 P-value: 0.0 Degrees of freedom: 17
      * Interpretation: There is a statiscally significant difference in flight cancellation across different airlines.     
    
    * Chi Square test between Airport and the Cancellation Rate.
    * Results:
      * Chi-square statistic: 6970.551315709208 P-value: 0.0 Degrees of freedom: 379
      * Interpretation: There is a statiscally significant difference in flight cancellation across different airports.

    * Chi Square test between Airlines with the top 3 Cancellation Rate and Year
    * Results
      * Chi-square statistic: 0.006960290029202889 P-value: 0.9999999999939051 Degrees of freedom: 8
      * Interpretation: There is no statiscally significant difference between arlines with the top 3 cancellation rate and year .

_Conclusion:_

* This project demonstrates the process of cleaning, analyzing, and visualizing a large flight dataset to uncover valuable insights. The findings can be used to improve flight operations and passenger experience.


# German version - Flugdatenanalyse

Dieses Projekt konzentriert sich auf die Verarbeitung und Analyse eines großen Datensatzes mit Fluginformationen. Die Hauptziele sind die Bereinigung der Daten, deren Analyse und die Visualisierung der Ergebnisse, um verschiedene Korrelationen aufzudecken.

Projektübersicht

_Ziele:_
* Datenbereinigung: Sicherstellen, dass der Datensatz frei von Unstimmigkeiten und Fehlern ist, um die Genauigkeit der Analyse zu verbessern.
* Datenanalyse: Durchführung statistischer Analysen, um Muster und Beziehungen in den Flugdaten zu entdecken.
* Datenvisualisierung: Erstellung visueller Darstellungen der Ergebnisse, um das Verständnis und die Kommunikation der Ergebnisse zu erleichtern.

_Erfolge:_

* Verarbeitung eines Datensatzes mit etwa 3 Millionen Flugaufzeichnungen.
* Umgang mit fehlenden Werten, Korrektur der Datentypen und Entfernung von Duplikaten.
* Identifizierung wichtiger Korrelationen und Muster in den Daten.
* Anwendung verschiedener statistischer Tests zur Findung signifikanter Korrelationen (ANOVA, Chi-Square).
* Entwicklung mehrerer Visualisierungen zur klaren Darstellung der Ergebnisse.

_Ergebnisse:_

* Anteil der annullierten Flüge:

![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/3e37ff0a-dd2a-4d70-af94-78be89b398b0)

* Anteil der annullierten Flüge nach Fluggesellschaften:

![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/91d8b9cc-f202-4a00-8464-f19aff4abb43)

* Anteil der annullierten Flüge nach Flughäfen:

![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/1e7f03c6-7872-4a70-9fb1-4b57b762d6e5)

* Anzahl der Annullierungen nach Jahr und Fluggesellschaft bei den Top-Drei annullierten Fluggesellschaften:
* 
![download](https://github.com/duykizilkaya/FlightDataAnalysis/assets/169436713/36f95847-8e75-402d-8171-ed5791757fbb)

* ANOVA:
   * Anova zwischen Verspätungszeiten und Fluggesellschaften
    Ergebnisse:
    F-statistic = 1182.5929791586866, p-value: 0.0021
    Interpretation: Es gibt einen statistisch signifikanten Unterschied bei Flugverspätungen zwischen verschiedenen Fluggesellschaften.

* Chi-Square Test
    * Chi-Square Test zwischen Fluggesellschaften und der Annullierungsrate.
    * Ergebnisse:
      * Chi-square statistic: 6260.8239987525485 P-value: 0.0 Degrees of freedom: 17
      * Interpretation: Es gibt einen statistisch signifikanten Unterschied bei Flugannullierungen zwischen verschiedenen Fluggesellschaften.    
    
    * Chi-Square test zwischen Flughafen und der Annullierungsrate.
    * Ergebnisse:
      * Chi-square statistic: 6972.479475542252 P-value: 0.0 Degrees of freedom: 379
      * Interpretation:Es gibt einen statistisch signifikanten Unterschied bei Flugannullierungen zwischen verschiedenen Flughäfen.

    * Chi-Square Test zwischen den Fluggesellschaften mit den drei höchsten Stornierungsraten und dem Jahr
    * Ergebnisse
      * Chi-square statistic: 0.006960290029202889 P-value: 0.9999999999939051 Degrees of freedom: 8
      * Interpretation: Es gibt keinen statistisch signifikanten Unterschied zwischen den Fluggesellschaften mit den drei höchsten Stornierungsraten und dem Jahr.

_Fazit:_

* Dieses Projekt demonstriert den Prozess der Bereinigung, Analyse und Visualisierung eines großen Flugdatenbestands, um wertvolle Erkenntnisse zu gewinnen. Die Ergebnisse können zur Verbesserung des Flugbetriebs und der Passagiererfahrung genutzt werden.


** This data set was retrieved via Kaggle: https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023
** Dieser Datensatz wurde über Kaggle abgerufen: https://www.kaggle.com/datasets/patrickzel/flight-delay-and-cancellation-dataset-2019-2023

