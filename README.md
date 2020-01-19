# BI_smart_home_dataset

| Listes des appareils | Conditions méteo | Liste des lieux|
| --------- | --------- | -----:|
| Solar | Temperature_far | Barn |
| Dishwasher  | Temperature_cel | Well |
| Furnace1  | Humidity | Living Room |
| Furnace2  | Visibility |
| Home Office  | Summary |
| Fridge  | ApparentTemperature_far |
| Wine cellar  | ApparentTemperature_cel |
| Garage Door  | Pressure |
| kitchen 12  | WindSpeed |
| Kitchen 14  | CloudCover |
| Kitchen 38  | WindBearing |
| MicroWave  | PrecipIntensity |
|   | PrecipProbability |
|   | DewPoint |


- [x] Nettoyer les données
  - [x] Suppression de la colonnes  House overall » et calcul de la colonne « real use »
  - [x] Suppression de la colonne « gen » qui est la meme donnée que celle de l'appareil «Solar»
  
- [x] Normaliser les chiffres à virgules
    - [x] Pour les données météos
    - [x] Pour les conso des appareils
    
- [ ] Créer un diagramme 
    - [x] Séparer par différentes feuilles les données
    - [x] Etablier les liens entre les feuilles
    - [ ] Valider le schéma
    
- [ ] Etablir des mesures
    - [ ] Mesurer le consommer a un temps X
    - [ ] Mesurer le générer à un temps X
    
  ![](diagram.png)


### Comment procéder :
1. Faite un clone du repo et mettez le à la racine du "C:\" tres important ! Sinon conflit avec Power BI
2. Allez sur https://drive.google.com/open?id=19RK99wd1I-AnZ9ABpW6mgQDoPVoS3jzL
3. Téléchargez les fichiers et mettez les dans le dossier "BI_smart_home_dataset"
4. Unzip, et laissez les fichiers les fichier excel dans le dossier DataSheet et le fichier BI à la racine

Votre arborescence doit ressembler à ca :
+ Data Sheet
    + smart_home_scan_sheet
    + smart_home_things_sheet
    + smart_home_weather_sheet
+ Dataset_bi.pbix
+ diagram.png
+ README.md
+ smart_home_dataset_original.csv

