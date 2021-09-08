# Installation Backup sur USB
## Création d'une tache de démarage 
Bute

    Créer un backup sur une clé USB en une tache

Création

    - Tout d’abord on vas faire des liens virtuelles entre les fichiers de notre choix avec un mount 
    - Il faudrat aller dans  /usr/ local/etc/rc.d qui est le chemin absolu 
    - Ensuite en fait un VI scriptmount.sh pour le script
    - Et en met le cript dedans
    - Maintenant si en fair un "mount" il devrait les afficher 
    
Script 
```{r}
#!/bin/bash
mount --bind /volume2/famille-Dorer/emilie /volume2/backup2USB/photo_emilie
mount --bind /volume1/doc_travail /volume2/backup2USB/homes
```
