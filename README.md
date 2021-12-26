# **CHANGELOG**
## **Version 1.1**

### **Ajouts**
- Annonce du nombre de vies restantes à la mort de chaque joueur
- Effets sonores lors des divers annonces
- Ajout d'un cooldown de 3 secondes entre chaque intéraction avec l'œuf du dragon
- Lorsque les piliers sont dévoilés, tous les joueurs dans un rayon de 50 blocs autour des tueurs du Dragon qui sont proches d'autres joueurs (rayon de 20 blocs) possèdent des effets négatifs :
    - 3 joueurs ou plus : weakness 1
    - 5 joueurs ou plus : weakness 2
    - 7 joueurs ou plus : weakness 2 + slowness 2
    - Les joueurs de sa propre équipe et les tueurs du Dragon ne comptent pas parmis les joueurs proches
    - Les tueurs du Dragon ne sont pas impactés

### **Ajustements**
- Lorsqu'une équipe tue le Dragon, trois piliers apparaissent au lieu d'un seul
- Les coordonnées des piliers sont désormais dévoilées une fois que l'équipe qui a tué le Dragon franchit le portail de l'end
- Lorsqu'une équipe pose l'œuf de Dragon ou que ce dernier est téléporté, ses coordonnées sont dévoilées
- Un message affichant l'équipe ayant récupéré l'œuf après que ce dernier ait été posé est systématiquement annoncé (même si la même équipe possédait l'œuf juste avant)
- Les pseudos des joueurs prennent désormais la couleur de leur équipe au-dessus de leur tête
- Les joueurs sont triés par équipe dans le scoreboard

### **Correction de bugs**
- Lorsque que le scénarios Cat Eyes est activé, les joueurs conservent l'effet night vision s'ils meurent
- Les joueurs qui ont tué le Dragon conservent l'effet résistance s'ils meurent
- Un message est affiché lorsque la boussole est utilisée alors que personne ne possède l'œuf dans son inventaire
- La position de la boussole est réinitialisée lorsque personne ne possède l'œuf
- La vie du joueur ne monte plus à 15 cœurs s'il est sur sa dernière vie et que le pacte "pas de seconde chance" est activé

Lien du doc : https://docs.google.com/document/d/1LfmjdChM0G3Qg1IiypbSJzmsgZu8wXpV5CSX_m1btcY/
