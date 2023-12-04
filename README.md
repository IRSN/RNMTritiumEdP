# RNMTritiumEdP

## Description

Total tritium measurements in rainwater in France extracted from the RNM (https://mesure-radioactivite.fr)

## Content

- /Data folder contains a csv file for tritium measurement data in rainwater
- ExportRnm_2023-11-30-10-02-30.csv dile contains around 20,000 rows and 14 columns

## Source

All the data are extracted from National Network for Environmental Radioactivity Measurements  (https://mesure-radioactivite.fr)

## Data format
All data are in csv format

| Nom de la Colonne | Format de la donnée | Description |
|-----------|-----------|-----------|
| Date de début de prélèvement | DD/MM/YYYY  |   |
| Date de fin de prélèvement  | DD/MM/YYYY  |   |
| Résultat | string  | Measured value if above significance level, otherwise significance level  |
| Incertitude | float  | Empty value if the "resultat" is less than the significance threshold specified in the "resultat" column. |
| Unité  | string  | Constant value (becquerel par litre)  |
| Organisme  | string  | Name of the organisation that carried out the measure (10 separate values)  |
| Commune | string  | Name of the commune in which the sample was taken  |
| Point de prélèvement  | string  |   |
| Espèce | string  | Constant value (especes.eauplui)  |
| Nature  | string  | Constant value (Eaux douces (eau de pluie, eau de nappe, eau de surface ...))  |
| Radion | string  | Constant value (Tritium total)  |
| Laboratoire  | string  | Laboratory name (39 distinct values) |
| Sites surveillés | string  | 35 distinct values (with empty values)  |
| Commentaires  | string  | Type of sampling (3 distinct values) |



## Overview

You will find below an extract of the dataset /

| Date de début de prélèvement | Date de fin de prélèvement | Résultat | Incertitude absolue | Unité                     | Organisme                       | Commune       | Point de prélèvement                | Espèce        | Nature                                               | Radion       | Laboratoire       | Sites surveillés | Commentaire          |
|------------------------------|----------------------------|----------|----------------------|---------------------------|---------------------------------|---------------|-------------------------------------|---------------|------------------------------------------------------|--------------|-------------------|-------------------|-----------------------|
| 01/12/2009                   | 01/01/2010                 | <6.4     |                      | becquerel par litre       | EDF - Electricité de France     | BRENNILIS     | station météo Brennilis            | especes.eaupl  | Eaux douces (eau de pluie, eau de nappe, eau de surface ...) | Tritium total | MSIS Laboratoire  | CNPE Brennilis    |                       |
| 01/12/2010                   | 01/01/2011                 | <6.2     |                      | becquerel par litre       | EDF - Electricité de France     | BRENNILIS     | station météo Brennilis            | especes.eaupl  | Eaux douces (eau de pluie, eau de nappe, eau de surface ...) | Tritium total | MSIS Laboratoire  | CNPE Brennilis    |                       |
| 01/02/2010                   | 01/02/2010                 | <6.6     |                      | becquerel par litre       | EDF - Electricité de France     | LOQUEFFRET    | fosse d'exhaure IDT aire TFA       | especes.eaupl  | Eaux douces (eau de pluie, eau de nappe, eau de surface ...) | Tritium total | MSIS Laboratoire  | CNPE Brennilis    |                       |

## License

The license under which this dataset is published is Open Data Commons Open Database License v1.0.

## Thanks

We would like to thank Miriam Basso and the IRSN/PSE-ENV/SIRSE/BMDE department for their contributions in providing access to these data.

