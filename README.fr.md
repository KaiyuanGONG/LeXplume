<p align="center">
  <img src="assets/logo-512.png" alt="Logo Semantic Fold de LeXplume" width="96">
</p>

# LeXplume

## Des mots rencontrés aux mots retenus.

Capturez les mots de vos articles, rapports et diapositives, ou du français de tous les jours. Obtenez une explication adaptée à votre domaine, des suggestions tirées de votre propre bibliothèque et des révisions programmées par FSRS.

[简体中文](README.md) · [English](README.en.md)

[Aperçu en ligne](https://lexplume.com) · [Logique produit](PRODUCT.md) · [FAQ](FAQ.md) · [Assistance](mailto:support@lexplume.com) · [Confidentialité](https://lexplume.com/privacy)

> `lexplume.com` présente actuellement LeXplume 1.0.0. Une version gratuite sur invitation, réservée aux adultes de 18 ans et plus qui apprennent à titre personnel, est en préparation ; l'inscription publique, le paiement et une version publique sur Google Play ne sont pas encore disponibles.

![LeXplume sélectionnant aligned et embeddings dans un texte technique tout en conservant leurs phrases d'origine](assets/readme/01-capture-real-material.webp)

_Capture de l'interface en ligne LeXplume 1.0.0 avec des données fictives._

## Capturer depuis vos contenus, pas depuis une liste générique

LeXplume commence par ce que vous lisez déjà. Saisissez un mot, collez une phrase ou un paragraphe et sélectionnez plusieurs cibles, ou extrayez le texte d'une image par OCR. Chaque mot peut conserver sa phrase, sa source, ses étiquettes et sa date de capture : le vocabulaire reste ainsi lié au contexte qui l'a rendu utile.

Ce flux convient aux articles scientifiques, rapports techniques, supports de cours et expressions françaises rencontrées dans la vie quotidienne.

## Des explications adaptées à votre domaine

Un même mot peut désigner des concepts très différents selon le domaine. Indiquez votre domaine dans les Réglages (par exemple « bio-informatique ») : LeXplume ajoute alors une explication adaptée à ce domaine, à côté de la définition du dictionnaire.

Prenons `alignment` :

- Dans l'usage général, le mot peut désigner un alignement ou un accord.
- En bio-informatique, il correspond généralement à l'**alignement de séquences** d'ADN, d'ARN ou de protéines.
- En apprentissage automatique, `model alignment` concerne l'adéquation du comportement d'un modèle avec les intentions, normes ou objectifs humains.

Le sens court, la définition de base et l'explication détaillée par domaine restent distincts. L'explication spécialisée est mise en cache après sa génération.

![LeXplume comparant la définition générale d'alignment avec ses sens en bio-informatique et en apprentissage automatique](assets/readme/02-domain-explanation.webp)

## Des suggestions qui suivent votre bibliothèque

LeXplume combine la langue étudiée, votre domaine, un niveau choisi manuellement, les captures récentes, les étiquettes thématiques et les mots fragiles selon FSRS afin de proposer :

- des concepts voisins qui prolongent les thèmes déjà étudiés ;
- des collocations, dérivés et familles de mots utiles ;
- un renforcement ciblé des zones où le rappel reste faible.

Les mots déjà présents dans la bibliothèque de la langue active sont exclus. Les propositions restent temporaires jusqu'à ce que vous décidiez de les ajouter par le flux de capture normal. Avec une bibliothèque vide, le système revient au domaine et au niveau de difficulté.

## Anglais et français, chacun avec son propre rythme

L'anglais et le français partagent un même modèle de données local et un même format de sauvegarde, tout en conservant des vues de bibliothèque, des recommandations et des files de révision séparées. Le français adopte une ambiance bleue avec des repères `FR` ; l'anglais garde l'ambiance ambre et n'affiche pas de repère.

Une session de révision ne couvre qu'une langue, afin d'éviter de mélanger les cartes. Désactiver l'étude du français masque les entrées françaises sans les supprimer.

![Comparaison de la bibliothèque anglaise ambre et de la bibliothèque française bleue de LeXplume avec repères FR](assets/readme/03-english-french.webp)

_Montage côte à côte de deux états réels de l'interface, avec des données fictives._

## Réviser avec FSRS

LeXplume utilise FSRS pour programmer la prochaine révision de chaque mot selon votre évaluation, avec quatre modes : cartes, orthographe, dictée et phrases à compléter. Le tableau de bord affiche les mots à réviser, la rétention, les séries, l'activité et la répartition des mots par état.

| Capacité | Traitement dans LeXplume |
| --- | --- |
| Capture | Mots, phrases, paragraphes et image/OCR ; plusieurs cibles en une fois |
| Compréhension | Prononciation, définition, sens chinois concis, explication spécialisée mise en cache et questions par mot |
| Recommandation | Nouveaux mots choisis selon langue, domaine, difficulté, vocabulaire récent et zones fragiles |
| Révision | Planification FSRS avec cartes, orthographe, dictée et phrases à compléter |
| Anglais / français | Bibliothèques, recommandations et révisions séparées ; ambiance bleue et repères `FR` en français |
| Données | Stockage local dans le navigateur, cœur utilisable hors connexion et import/export JSON |
| Cloud | Synchronisation facultative et IA cloud avec limite quotidienne ; l'application travaille toujours sur la copie de l'appareil |

## Données locales et clés API

- **Local par défaut.** Le vocabulaire actif et les révisions vivent dans le navigateur ; la capture et la révision essentielles fonctionnent hors connexion.
- **Sauvegarde portable.** Les données peuvent être exportées et restaurées en JSON.
- **BYOK en connexion directe.** Vous choisissez un fournisseur et un modèle IA et fournissez votre propre clé. Elle reste sur l'appareil et n'entre ni dans l'export JSON ni dans la synchronisation.
- **Synchronisation facultative.** Elle garde une copie dans le cloud pour vos autres appareils ; l'application continue de travailler sur la copie locale.
- **IA cloud facultative.** Réservée aux comptes invités, avec une limite quotidienne ; LeXplume fonctionne sans elle.

Consultez la [politique de confidentialité](https://lexplume.com/privacy) avant d'activer l'IA. Seul le contenu nécessaire à l'opération demandée est transmis au fournisseur.

## Disponibilité actuelle

- L'application officielle est le Web/PWA sur [lexplume.com](https://lexplume.com), actuellement en version 1.0.0.
- Les comptes et l'IA cloud sont encore en test avant lancement et restent réservés aux comptes invités.
- Limite connue : pour les mots français, l'enrichissement IA remplit la catégorie grammaticale, la définition française et un sens chinois court, mais pas encore la transcription phonétique (API).
- L'inscription publique, le paiement et la distribution publique sur Google Play ne sont pas disponibles. Voir [ROADMAP.md](ROADMAP.md) et [RELEASE_NOTES.md](RELEASE_NOTES.md).
- LeXplume n'est actuellement ni promu ni pris en charge en Chine continentale.

## Point de vue design

Le style de l'interface s'appelle **Paper** : fond blanc cassé, titres en serif, peu de décoration et beaucoup d'espace, pour garder l'attention sur le mot et sa phrase. Le logo **Semantic Fold** est une forme continue autour d'un espace vide ; il évoque la langue capturée, comprise et retenue, et reste lisible en une couleur et à petite taille.

Voir la [logique produit et design complète](PRODUCT.md).

## Retours et portée du dépôt

Utilisez le formulaire d'issue pour les suggestions sans données personnelles. Les demandes liées à un compte vont à [support@lexplume.com](mailto:support@lexplume.com), et les vulnérabilités suivent [SECURITY.md](SECURITY.md).

Ce dépôt public d'information produit contient les notes de version, l'assistance, la direction publique et les médias de marque approuvés. Il ne contient pas le code source de l'application, qui reste privé. Sa publication n'accorde aucune licence sur l'application, le nom, l'identité visuelle ou le code privé LeXplume.
