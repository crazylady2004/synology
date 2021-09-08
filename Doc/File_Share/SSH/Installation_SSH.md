# Installation de SSH 
## Clés SSH / NAS

- Créé un dossier .ssh
- Attribuer les droits 
    - sudo chmod 700 /var/services/homes/user/.ssh
    - sudo chmod 600 /var/services/homes/user/.ssh/*
    - sudo chown -R "user":users /var/services/homes/user/.ssh
- Créé un fichier authorized_keys
- Faire un VI et mettre les clés public dedans 
- On peux enregistrer toute les clés quand souhait
