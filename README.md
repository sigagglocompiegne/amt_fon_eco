![picto](https://github.com/sigagglocompiegne/orga_gest_igeo/blob/master/doc/img/geocompiegnois_2020_reduit_v2.png)

# Urbanisation des données aménagements / foncières (cessions/acquisitions) / activités économiques

[ ] à rédiger [x] en cours de rédaction [ ] finaliser

Ensemble des éléments constituant la mise en oeuvre de la base de données urbanisées sur les thématiques d'aménagement, de foncier et d'activités économiques ainsi que l'exploitation de ces données dans les différentes applications :

- [Lire la documentation du standard](gabarit/livrables.md)
- Script d'initialisation de la base de données (hors [Suivi du marché de l'immobilier d'entreprises](https://github.com/sigagglocompiegne/marcheimmo))
  * [Suivi des modifications](bdd/afe_00_trace.sql)
  * [Création  de la structure initiale](bdd/afe_10_squelette.sql)
  * [Création des vues de gestion](bdd/afe_20_vues_gestion.sql)
  * [Création des vues applicatives](bdd/afe_21_vues_xapps.sql)
  * [Création des vues applicatives gd public](bdd/afe_22_vues_xapps_public.sql)
  * [Création des vues open data](bdd/afe_23_vues_xopendata.sql)
  * [Création des privilèges](bdd/afe_99_grant.sql)  
- [Documentation d'administration de la base](bdd/doc_admin_bd_amt_fon_eco.md) (hors Suivi du marché de l'immobilier d'entreprises
- [Documentation d'administration de l'application FONCIER](app/doc_admin_app_fon.md)
- [Documentation d'administration de l'application ACTIVITE ECONOMIQUE](app/doc_admin_app_eco.md)
- [Documentation d'administration de l'application AMENAGEMENT](app/doc_admin_app_amt.md)

## Contexte

L’ARC est engagée dans un plan de modernisation numérique pour l’exercice de ses missions de services publics. L’objectif poursuivi vise à permettre à la collectivité de se doter d’outil d’aide à la décision et d’optimiser l’organisation de ses services. Ces objectifs se déclinent avec la mise en place d’outils informatiques adaptés au quotidien des services et le nécessaire retour auprès de la collectivité, des informations (données) produites et gérées par ses prestataires. 

L’ARC privilégie donc une organisation dans laquelle l’Interface Homme Machine (IHM) du métier assure l’alimentation d’un entrepôt de données territoriales. Cette stratégie « agile » permet de répondre au plus près des besoins des services dans une trajectoire soutenable assurant à la fois une bonne maitrise des flux d’information et un temps d’acculturation au sein de l’organisation.

## Voir aussi

- [Standard régional d'échange des données sur l'activité économique (V2 2015)](https://geo.compiegnois.fr/documents/metiers/eco/modele_groupe_activite_economique_version2_2015.pdf)
- [Documentation d'administration de la base du marché de l'immobilier d'entreprises](https://github.com/sigagglocompiegne/marcheimmoent/blob/master/doc/doc_admin_bd_immo.md)

## Jeu de données consolidé

Vous pouvez retrouver plusieurs jeux de données à l'échelle de l'Agglomération de la Région de Compiègne :
 * [Les pôles d'activités](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/8db8e6ee-0f87-4926-a559-4769c01ddb28)
 * [Les sites d'activités](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/8653f903-ccf8-42a9-a298-90f24d7ee0e0)
 * [Les lots à vocation économique](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/b62edffb-14bb-4460-8f4e-3c1dc2bcd368)
 * [Les lots à vocation habitat](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/289f9a02-fd1e-4df1-9710-188e17758082)
 * [Les lots à vocation mixte](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/f2336765-c302-49ae-9c82-ad02227fd52d)
 * [Les lots à vocation d'équipement](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/b54beae3-822d-4bc7-867c-84b8c26c596e)
 * [Les cessions foncières](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/e35607f5-ff9b-4d34-a4f5-7d1d87671f41)
 * [Les établissements](https://geo.compiegnois.fr/geonetwork/srv/fre/catalog.search#/metadata/b1344995-4703-41ac-8867-ac2a398666b1)
