# RésiTerre

**Outil de préparation des territoires aux risques majeurs, conçu et développé par Mahel Chéour.**

Ouvrir l'outil : https://mahel-chr.github.io/resiterre/

Version précédente, conservée : https://mahel-chr.github.io/resiterre/version-precedente/

RésiTerre interroge en direct les sources publiques officielles sur les risques et les croise à l'échelle de chaque bâtiment et de chaque rue. Au-delà des cartes d'aléa, il montre les conséquences indirectes d'une crue : routes coupées, quartiers restés au sec mais isolés, établissements que les secours ne peuvent plus rejoindre. Chaque information garde les termes, les classes et le lien de sa source ; aucune note synthétique ne vient s'y substituer, et l'outil signale quand une donnée manque ou ne couvre pas le territoire.

## Trois outils sur une même analyse

- **Diagnostic** : que disent toutes les sources officielles sur ce quartier ?
- **Inondation** : quand la rivière monte, qui est touché, et qui se retrouve coupé ?
- **Feu de forêt** : quels quartiers touchent la forêt, et par où en sortir ?

Chaque outil a son onglet « Comprendre », qui part des résultats de la zone analysée.

## Ce que l'on peut faire

- **Anticiper** : faire monter l'eau scénario par scénario (cartes des TRI, niveaux des cartes Vigicrues), voir les voies qui passent sous l'eau, les bâtiments hors d'eau mais coupés, les établissements sensibles touchés, l'ordre dans lequel tout cela arrive, et le comparer au niveau mesuré en direct à la station (Hub'eau).
- **Se mettre à l'abri** : pour chaque bâtiment exposé, le trajet par la route jusqu'au point hors de la surface inondée le plus proche.
- **Feu de forêt** : repérer les secteurs desservis par une seule voie, en lisière des massifs boisés.
- **Prioriser** : classer les carreaux de 200 m où se cumulent huit facteurs de vulnérabilité, tous tirés des sources officielles.
- **Préparer** : éditer une fiche de crise par établissement d'enseignement, de santé, de secours ou camping.
- **Jumeau numérique 3D** : relief du sol (RGE ALTI), plan ou photographie aérienne, bâtiments à leur hauteur, eau du scénario à la hauteur publiée, routes coupées.
- Cadrer une zone de 16 km² au plus et lancer l'analyse, que l'on peut interrompre à tout moment.
- Ouvrir la fiche d'un bâtiment, en 2D ou en 3D : plans de prévention et zone réglementaire, scénarios d'inondation et hauteurs d'eau, cartes Vigicrues, cours d'eau le plus proche, altitude du sol, argiles, cavités, débroussaillement, sols pollués, canalisations, plan particulier d'intervention nucléaire, zone du PLU, habitants du carreau INSEE. Chaque ligne renvoie à la fiche de sa source.
- Colorer les bâtiments selon dix-sept lectures, chacune accompagnée de sa légende et d'un texte qui explique comment l'interpréter.
- Découvrir les lectures croisées : logements de plain-pied en zone inondable, établissements sensibles exposés, zones à urbaniser recoupant un aléa, habitants âgés des carreaux concernés.
- Consulter la commune : risques recensés, plans de prévention et leurs dates, arrêtés de catastrophe naturelle, DICRIM, TRI, PAPI, sismicité, radon, installations classées et Seveso, références climatiques officielles.
- Lire, pour chaque source, comment la donnée est produite, ce qu'elle permet de dire et ses limites, et télécharger les données de la zone au format GeoJSON.
- Créer un rapport à imprimer ou à enregistrer en PDF, pour la zone ou pour un bâtiment, avec tous les liens.
- Télécharger la carte affichée, en 2D ou en 3D, sous forme d'image PNG avec sa légende complète, son échelle, ses sources et sa date.
- Apprendre, dans un espace séparé de l'outil : vocabulaire, lecture des cartes de risque, réglementation, bons réflexes, effet domino, méthode et limites de chaque calcul.

## Sources

IGN (BD TOPO : bâtiments, réseau routier, établissements, végétation, hydrographie ; altimétrie RGE ALTI ; Géoplateforme ; zonage des obligations légales de débroussaillement), Géoportail de l'urbanisme (servitudes PM1 et PM3, zonage des PLU, documents d'urbanisme), Géorisques et base GASPAR (procédures, catastrophes naturelles, TRI, PAPI, DICRIM, sismicité, radon, installations classées, installations nucléaires, sites et sols pollués, canalisations), BRGM (argiles, cavités, mouvements de terrain), Vigicrues (zones d'inondation) et Hub'eau (hauteurs mesurées en temps réel), zonages réglementaires au standard CNIG publiés par les services de l'État, INSEE (données carroyées à 200 m), Référentiel national des bâtiments, Base adresse nationale, data.gouv.fr.

## Auteure

**Mahel Chéour**, géographe des risques et SIG, Master 2 Dynamiques des Milieux et des Risques, Université Paris 1 Panthéon-Sorbonne. Contact : mahelchr@gmail.com

Licence MIT.
