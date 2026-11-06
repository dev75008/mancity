# Week-end Manchester City–Chelsea

Page de préparation pour les 12 et 13 décembre 2026, au départ de Lyon. Public : adultes, adolescents et enfants. Aucun achat ni réservation.

La rubrique « Aéroport–hôtel » décrit le train vers Manchester Piccadilly, un arrêt de tram vers New Islington et la marche jusqu’au 2 Pollard Street. Alternatives : train puis marche, ou tram via Market Street. Durées estimées et sources officielles incluses ; horaires du 12 décembre et tarifs du groupe à vérifier.

Site : https://dev75008.github.io/mancity/

## Mise à jour des données

Le 6 novembre 2026, ajout de la capture originale fournie par l’organisateur pour le vol aller Jet2 LS946 du samedi 12 décembre : Lyon 10 h 45, Manchester 11 h 45, direct, 2 h, classe économique, statut « Programmé ». Aucun prix sur la capture ; l’ancien tarif de 93 € a été retiré de la fiche aller. Image : `assets/vol-aller-jet2-ls946.png`. Cette capture ne prouve pas une réservation.

Le 6 novembre 2026, remplacement du retour provisoire easyJet par la capture fournie pour Brussels Airlines le dimanche 13 décembre 2026 : SN2178, Manchester (MAN) terminal 2 à 17 h 25, Bruxelles (BRU) à 19 h 50 ; correspondance avec changement d’avion de 1 h 15 ; SN3593, Bruxelles à 21 h 05, Lyon (LYS) terminal 1 à 22 h 30. Durée totale : 4 h 05, classe économique. Statut affiché « Traitement », aucun prix ni confirmation de réservation. Image : `assets/vol-retour-brussels-airlines.png`. Programme du dimanche mis à jour en conséquence.

Les hôtels ont été recherchés le 30 octobre 2026 via Booking.com pour deux adultes, une chambre, une nuit du 12 au 13 décembre 2026. Effectifs et âges exacts restent à préciser.

Sources principales :

- [Chelsea : horaire officiel du match](https://www.chelseafc.com/en/news/article/four-chelsea-december-fixtures-moved-for-tv)
- [Programme aller](https://zbordirect.com/en/tools/schedule?arrival_city=MAN&departure_city=LYS)
- Captures originales de l’aller Jet2 et du retour Brussels Airlines fournies par l’organisateur le 6 novembre 2026, dans `assets/`.
- Booking.com : liens datés propres à chaque hébergement sur la page.

## Développement

HTML et CSS statiques, sans dépendance ni collecte de données. Ouvrir `index.html` ou lancer `python -m http.server 8000`. GitHub Pages publie la racine de `main`.

## Limites de vérification

L’accès navigateur du poste n’était pas disponible lors de la création. Aucun contrôle visuel responsive réalisé. Les itinéraires piétons sont des estimations et les liens permettent de vérifier le trajet. Les tarifs adolescents, billets du match, chambres de groupe et conditions tarifaires restent à confirmer.
