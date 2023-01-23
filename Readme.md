# Apprentissage-automatique-Regression
Ce référentiel contient 2 notebook détaillés: Nettoyage-Exploration et Prédiction
## Checklist

Depuis 2001, **l’ADEME** acquiert tous les ans ces données auprès de **l’Union Technique de l’Automobile du motocycle et du Cycle UTAC** (en charge de l’homologation des véhicules avant leur mise en vente) en accord avec le ministère du développement durable.
Pour chaque véhicule les données d’origine (transmises par l’Utac) sont les suivantes :

* **Les consommations de carburant**

* **Les émissions de dioxyde de carbone (CO2)**

* **Les émissions des polluants de l’air** (réglementés dans le cadre de la norme Euro)

* **L’ensemble des caractéristiques techniques des véhicules** (gammes, marques, modèles, n° de CNIT, type d’énergie ...)



# L'inventaire des varaibles pertinentes:

Les données comprenent des variables pertinentes suivantes:

* **lib_mrq_utac**: La marque, il y'a 12.

* **cod_cbr**: Le type de carburant, il y a 5.

* **hybride**: Information permettant d’identifier les véhicules hybrides (O/N)

* **puiss_max** : Puissance maximale

* **typ_boite_nb_rapp**: Type boite de vitesse et le nombre de rapport.

* **conso_urb**: Consommation urbaine de carburant (en l/100km),

* **conso_exurb**: consommation extra urbaine de carburant (en l/100km),

* **conso_mixte**: Consommation mixte de carburant (en l/100km),

* **co2**: Emission de CO2 (en g/km),

* **masse_ordma_min**: Masse en ordre de marche mini

* **masse_ordma_max**: Masse en ordre de marche max
 
* **Carrosserie**: Carrosserie

* **gamme**: Gamme du véhicule



# Objectif

Notre objectif majeur comprend:

#  Notebokk1: 
**1** Nettoyage feature engineering 
**2** Exploration  

Prédire les emisisions de **CO2** des vehicules en fonction de certaines informations (Variables explicatives)

* En utilisant 4 à 5 modéles différents

* En comparant  les scores
    
* En choissisant le meilleur modèle


# Description des données

Lien vers les données: https://www.data.gouv.fr/fr/datasets/emissions-de-co2-et-de-polluants-des-vehicules-commercialises-en-france/
