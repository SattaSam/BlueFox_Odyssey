BLUEFOX ODYSSEY V0.13.2 — CONTRÔLE 3D ET PASSAGES DE MAPS

Lancement :
1. Décompresser entièrement l'archive.
2. Double-cliquer sur index.html.
3. Utiliser Chrome, Edge ou Firefox avec WebGL activé.

Cette version contient localement le moteur, le modèle BlueFox V0.13 et les
images nécessaires. Elle ne télécharge aucune dépendance au lancement.

Fonctions présentes :
- monde 3D à deux biomes ;
- modèle BlueFox animé ;
- autonomie, déplacements et contournement des obstacles ;
- caméra libre avec recentrage progressif ;
- collecte, inventaire, énergie et repos ;
- missions, recherche, journal et personnalité ;
- boussole d'influence et système Planète ;
- sauvegarde locale et simulation des absences.

Correctifs conservés de la V0.13.1 :
- orientation du modèle corrigée : BlueFox regarde désormais dans le sens de
  son déplacement ;
- jointure entre les deux zones recouverte par une transition texturée
  irrégulière mélangeant progressivement les deux sols ;
- pierres du chemin conservées au-dessus de la transition.

Nouveautés V0.13.2 :
- contrôleur 3D refondu avec accélération, freinage, orientation progressive
  et animation déterminée par la vitesse réelle ;
- évitement d'obstacles intégré au mouvement sans téléportation ;
- passage Nord clairement indiqué sur la Plaine des Cristaux ;
- passage Sud de retour indiqué dans les Ruines d'Émeraude ;
- transition masquée pendant le chargement logique d'une nouvelle map ;
- BlueFox peut retourner seul sur les maps déjà visitées ;
- aucune première exploration ni action lourde pendant une absence ;
- Journal compact tenant dans la fenêtre, portrait mieux cadré et liste des
  actions scrollable indépendamment ;
- convention future des scènes « 1nomdelimage » et des trames « 01 », « 02 ».

Si le navigateur bloque WebGL, l'interface reste accessible sur le décor
illustré mais le personnage 3D ne peut pas être affiché.
