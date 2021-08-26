# Documents d’installation 
## Synology
### Connection & Création

#### Connection au NAS Synology

	⁃	Trouvé son adresse IP (128.178.11.108)
	⁃	Aller sur un Browser 
	⁃	Taper dans la barre de recherche l’IP
	⁃	Il vous demandera un nom, un mot de passe & un utilisateur (SYNO-IDEVFSD, Epfl@2021 & admini)
	⁃	Et une adresse mail (syno-idevfsd@groupes.epfl.ch)

#### Création des RAID

	⁃	Aller dans Storage Manager
	⁃	Cliquer sur Storage à gauche
	⁃	Créé une nouveau Storage Pool 
	⁃	Ensuite deux possibilité est possible la facile en choisis Rapide ou Personalise j’ai choisi personnalisé
	⁃	Choissiser BTRFS 
	⁃	Sélectionnée les disks 
	⁃	Définir quelle RAID en veux (personnellement j’ai choisi Raid 1 & Raid 5 pour deux volume différent)
	⁃	Oui pour la vérification des disks

#### Création d’un user

	⁃	Aller dans le Control Panel
	⁃	Puis User & Groupe
	⁃	Cliquer sur User dans la barre de navigation
	⁃	Create
	⁃	Ensuite il vous demande un nom et un mot de passe
	⁃	Si vous voulez donner les droits d’écrire et de lire un fichier particulier 
	⁃	Mettre une limite dans un fichier
	⁃	Puis Done

#### Création d’un Groupe

	⁃	Aller dans le Control Panel
	⁃	Puis User & Groupe
	⁃	Cliquer sur le deuxième dans la barre de navigation
	⁃	Create
	⁃	Donner un nom
	⁃	Ajouter les utilisateurs (User)
	⁃	Permission des Folder
	⁃	Limitation de Byte dans un fichier
	⁃	Puis Next jusqu’à Done
