# À quoi correspondent 10 kg de CO₂e ?

Certains chercheurs estiment qu'une requête à un LLM émet 1g de CO₂e *. Est-ce beaucoup ? Faut-il se restreindre sur l'utilisation des LLM ? Ou vaut-il vaut mieux renoncer à un steak de bœuf, à un vol d'avion ou à 10'000 requêtes à chatGPT ?

Pour répondre à ces questions, cette page recense quelques gestes qui "coûtent" 10 kg de CO₂e.

Il me semble qu'il y a un véritable avantage à présenter ces ordres de grandeur : faire des efforts partout, tout le temps est très difficile mais si on sait quels gestes ont le plus d'impact, on peut cibler nos efforts. Faire attention à regarder une vidéo en qualité réduite sera complétement négligeable par rapport à éviter un trajet en voiture.

Attention, il ne s'agit pas de conclure de ces  comparaisons que le numérique ne pollue pas : il représente 1,5 à 4% des émissions mondiales de gaz à effet de serre (1).
Mais dans une vidéo "climat et numérique" (2), le Réveilleur remarque que :
1) Le numérique est utilisé tous les jours par une immense partie de la population mondiale pour travailler, s'informer, communiquer et se divertir (contrairement à l'aviation, auquel il est souvent comparé, qui n'est utile qu'à une minorité de la population).
2) Il est beaucoup plus facile de décarboner l'électricité du numérique que les énergies de l'aviation
3) Exagérer le poids du numérique risque de focaliser nos efforts vers de "petits gestes" peu efficaces.

Toutes les sources, les hypothèses sont explicitées et les calculs sont détaillés. Et comme je suis l'auteure de cette page, n'hésitez pas à m'écrire si vous avez des suggestions !

*CO₂e signifie « équivalent CO₂ » et permet de regrouper différents gaz à effet de serre selon leur effet climatique.

Sources :
(1) Digital technologies and the environment: OECD Digital Economy Outlook 2024 (Volume 2). (2024, November 19). OECD. https://www.oecd.org/en/publications/oecd-digital-economy-outlook-2024-volume-2_3adf705b-en/full-report/digital-technologies-and-the-environment_c0701b0b.html?utm_source=openai

(2) Le Réveilleur. (2025, July 8). Faut-il vraiment culpabiliser en regardant YouTube en 4K ?@ApresLaBiere@labiologiefaitdesvideos [Video]. YouTube. https://www.youtube.com/watch?v=ln5iQtd7XZI


## Contenu

Onze cartes, chacune dépliable (« Hypothèses et sources ») :

| Thème | Cartes |
|---|---|
| Alimentation | bœuf, poulet |
| Logement | chauffage à 1 °C de moins |
| Transports | voiture à essence, avion, train |
| Numérique et IA | questions à un chatbot, « vibecoding » avec des agents IA, vidéos générées par IA, streaming vidéo, smartphone neuf |

## Sources

Quand c'est possible, la source principale est [Our World in Data](https://ourworldindata.org/) (OWID). Les autres sources sont citées carte par carte : ADEME / Impact CO₂, Agribalyse, CFF, KBOB, AIE, Ember, ainsi que des études et analyses publiées sur l'énergie de l'IA (Hausfather, Couch, Delavande et al., MIT Technology Review).

Les valeurs sont des **ordres de grandeur**. Plusieurs reposent sur des hypothèses de calcul propres à ce projet, signalées dans le texte (par exemple le facteur ×1,5 pour le matériel, ou le mix électrique UE ou États-Unis choisi pour l'IA). Les données sur l'IA sont de qualité limitée : les fournisseurs publient peu de mesures.

## Utilisation

La page est un unique fichier HTML statique, sans compilation ni dépendance à installer : il suffit d'ouvrir [index.html](index.html) dans un navigateur.

Une connexion internet est nécessaire pour charger les polices (Google Fonts : Atkinson Hyperlegible et Bricolage Grotesque) et les icônes (Tabler Icons, via jsDelivr). Sans connexion, le contenu s'affiche avec les polices et les icônes par défaut.

## Fichiers

- `index.html` : la page.

## Modifier ou corriger un chiffre

Chaque carte est un bloc `<article class="card">` écrit directement dans `index.html`. Pour corriger un chiffre, modifiez à la fois le résultat affiché en haut de la carte et le calcul détaillé dans « Hypothèses et sources », puis mettez à jour la date de compilation dans le pied de page.

Les corrections et les sources supplémentaires sont les bienvenues, en particulier pour les cartes sur l'IA, où les estimations sont les plus fragiles.

## Licence

Aucune licence n'est définie pour l'instant. À ajouter avant publication si vous souhaitez autoriser la réutilisation (par exemple CC BY 4.0 pour le contenu et MIT pour le code).

## Contact

Je suis enseignante de mathématiques, sans lien avec les secteurs cités. Je ne suis pas spécialiste du climat : signalez-moi toute erreur via github.
