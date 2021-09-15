# Installation & configuration du VPN
## VPN
### Instalation
    - Aller sur PAckage center 
    - Rechercher VPN Server
    - Installer & Open
### configuration
    - Une fois que l'application ouverte 
    - Aller sur OpenVPN
    - Cocher Enable OpneVPN server
    - Changer :
        - l'IP (128.178.11.108)
        - Connection number (15)
        - Connection account (4)
        - Protocol (UDP)
        - Cocher case Allow client to acces server's...
        - Apply
        - Ensuite Export Configuration
        - Déziper le fichier 
        - Ouvrir le fichier Openvpn.vpn
        - Modifier le document en mettant votre DDNS que vous avez comfiguré (voir document DDNS)
    - Ensuite de le Console Pannel 
    - Aller dans Securité
    - Firewall
    - Edit Rules
    - Create 
    - Dans la partie Port il faut selectioné Select from a list... 
    - Select
    - Choisir VPN serveurs OpenVPN 
    - OK
