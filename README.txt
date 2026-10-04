V8 - correction historique Présence

Correction importante :
Le nom JavaScript `history` entrait en conflit avec l'objet natif window.history
du navigateur. Le récapitulatif et le camembert s'affichaient, mais pas la liste
Historique. La V8 cible explicitement l'élément HTML #history.

Conséquence :
- historique visible
- boutons Modifier / Supprimer visibles
- clic sur le nom du joueur dans l'historique fonctionnel
- détails individuels accessibles
- camembert conservé
- favicon Blagnac conservé

Après mise en ligne sur GitHub Pages, faire un rechargement forcé du navigateur.
La page doit afficher « Version Présence V8 ».
