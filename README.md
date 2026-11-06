# Week-end Manchester City–Chelsea

Page de préparation pour les 12 et 13 décembre 2026, au départ de Lyon. Public : adultes, adolescents et enfants. Aucun achat ni réservation.

La rubrique « Aéroport–hôtel » décrit le train vers Manchester Piccadilly, un arrêt de tram vers New Islington et la marche jusqu’au 2 Pollard Street. Alternatives : train puis marche, ou tram via Market Street. Durées estimées et sources officielles incluses ; horaires du 12 décembre et tarifs du groupe à vérifier.

Site : https://dev75008.github.io/mancity/

## Mise à jour des données

Le 6 novembre 2026, ajout de la capture originale fournie par l’organisateur pour le vol aller Jet2 LS946 du samedi 12 décembre : Lyon 10 h 45, Manchester 11 h 45, direct, 2 h, classe économique, statut « Programmé ». Aucun prix sur la capture ; l’ancien tarif de 93 € a été retiré de la fiche aller. Image : `assets/vol-aller-jet2-ls946.png`. Cette capture ne prouve pas une réservation.

Recherche du 30 octobre 2026. Les tarifs des vols sont des offres indexées, pas un devis garanti. Le retour direct du 13 décembre est contradictoire selon les sources ; cette incertitude figure sur la page. Les hôtels ont été recherchés via Booking.com pour deux adultes, une chambre, une nuit du 12 au 13 décembre 2026. Effectifs et âges exacts restent à préciser.

Sources principales :

- [Chelsea : horaire officiel du match](https://www.chelseafc.com/en/news/article/four-chelsea-december-fixtures-moved-for-tv)
- [Programme aller](https://zbordirect.com/en/tools/schedule?arrival_city=MAN&departure_city=LYS)
- [Programme retour](https://zbordirect.com/en/tools/schedule?arrival_city=LYS&departure_city=MAN)
- [Jet2 : offre Lyon–Manchester](https://www.jet2.com/en/flights/uk/manchester?lang=EN)
- [Trip.com : offres retour à confirmer](https://fr.trip.com/flights/manchester-to-lyon/airfares-man-lys/)
- Booking.com : liens datés propres à chaque hébergement sur la page.

## Développement

HTML et CSS statiques, sans dépendance ni collecte de données. Ouvrir `index.html` ou lancer `python -m http.server 8000`. GitHub Pages publie la racine de `main`.

## Limites de vérification

L’accès navigateur du poste n’était pas disponible lors de la création. Aucun contrôle visuel responsive réalisé. Les itinéraires piétons sont des estimations et les liens permettent de vérifier le trajet. Les tarifs adolescents, billets du match, chambres de groupe et conditions tarifaires restent à confirmer.
