# COVID-19 in SPAIN

Official Data Source: https://www.mscbs.gob.es/

Official Data in pdf (2020-03-03 to 2020-03-27): covid_spa_pdfs

Official Data in .csv (2020-03-03 to 2020-03-27):

    1) COVID19_SPA.csv the data correspond to the whole of the Spanish State. 
    2) COVID19_SPA_AC.csv the data has been classified by Autonomous Communities (Regions).

## Dataset Info

Each dataset contains 9 columns: 

* **Region**
* **Date**
* <sup>1</sup> **Total** : Total Confirmed Cases. 
* <sup>2</sup> **AI(14d)** : Accumulated Incidence in the last 14 days.
* <sup>3 </sup><sup>4</sup> **Hospitalized**
* <sup>4</sup> **ICU**
* <sup>3</sup> **Deads** 
* <sup>3</sup> **Recovered** 
* **New** : New Confirmed Cases

<sup>1</sup> The Total Confirmed Cases do not come from the sum of Hospitalized, Recovered and Dead patients, since they are not exclusive.

<sup>2</sup> AI: Accumulated incidence (cases accumulated per 100,000 inhabitants).

<sup>3</sup> Dead and Recovered patients may have been hospitalized and therefore compute in both
groups. 

<sup>4</sup> Patients who have required ICU also compute in patients who have been hospitalized.
