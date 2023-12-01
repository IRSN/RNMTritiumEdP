# RNMTritiumEdP

## Description

Total tritium measurements in rainwater in France extracted from the RNM (https://mesure-radioactivite.fr)

## Content

- /Data folder contains a csv file for tritium measurement data in rainwater
- ExportRnm_2023-11-30-10-02-30.csv dile contains around 20,000 rows and 14 columns

## Source

All the data are extracted from National Network for Environmental Radioactivity Measurements  (https://mesure-radioactivite.fr)

## data format
All data are in csv format

| Nom de la Colonne | Format de la donnée | Description |
|-----------|-----------|-----------|
| Date de début de prélèvement | DD/MM/YYYY  |   |
| Date de fin de prélèvement  | DD/MM/YYYY  |   |
| Résultat | string  | Valeur mesurée si dépassant le seuil de significativité, sinon seuil de significativité  |
| Incertitude | float  | Valeur vide si le résultat est inférireur au seuil de significativité précisé dans la colonne résultat |
| Unité  | string  | Valeur constante (becquerel par litre)  |
| Organisme  | string  | Nom de l'organisme aynant réalisé le relevé (10 valeurs distinctes)  |
| Commune | string  | Nom de la commune dans laquelle le prélèvement a été réalisé |
| Point de prélèvement  | string  |   |
| Espèce | string  | Valeur constante (especes.eauplui)  |
| Nature  | string  | Valeur constante (especes.eauplui)  |
| Radion | string  | Valeur constante (Tritium total)  |
| Laboratoire  | string  | Nom du laboratoire  39 valeurs distinctes|
| Sites surveillés | string  | 35 valeurs distinctes (avec des valeurs vides)  |
| Commentaires  | string  | Type de prélèvement (3 valeurs distinctes) |



## Overview

You will find below an extract of the dataset /

| Date de début de prélèvement | Date de fin de prélèvement | Résultat | Incertitude absolue | Unité                     | Organisme                       | Commune       | Point de prélèvement                | Espèce        | Nature                                               | Radion       | Laboratoire       | Sites surveillés | Commentaire          |
|------------------------------|----------------------------|----------|----------------------|---------------------------|---------------------------------|---------------|-------------------------------------|---------------|------------------------------------------------------|--------------|-------------------|-------------------|-----------------------|
| 01/12/2009                   | 01/01/2010                 | <6.4     |                      | becquerel par litre       | EDF - Electricité de France     | BRENNILIS     | station météo Brennilis            | especes.eaupl  | Eaux douces (eau de pluie, eau de nappe, eau de surface ...) | Tritium total | MSIS Laboratoire  | CNPE Brennilis    |                       |
| 01/12/2010                   | 01/01/2011                 | <6.2     |                      | becquerel par litre       | EDF - Electricité de France     | BRENNILIS     | station météo Brennilis            | especes.eaupl  | Eaux douces (eau de pluie, eau de nappe, eau de surface ...) | Tritium total | MSIS Laboratoire  | CNPE Brennilis    |                       |
| 01/02/2010                   | 01/02/2010                 | <6.6     |                      | becquerel par litre       | EDF - Electricité de France     | LOQUEFFRET    | fosse d'exhaure IDT aire TFA       | especes.eaupl  | Eaux douces (eau de pluie, eau de nappe, eau de surface ...) | Tritium total | MSIS Laboratoire  | CNPE Brennilis    |                       |

## Licence

La licence sous lquelle ce jeu données est publié est Open Data Commons Open Database License v1.0

## Thanks

We would like to thank Miriam Basso and the IRSN/PSE-ENV/SIRSE/BMDE department for their contributions in providing access to these data.

