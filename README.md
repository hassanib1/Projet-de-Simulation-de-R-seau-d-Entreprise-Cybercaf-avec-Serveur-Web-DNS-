Objectifs

Mettre en place un réseau local pour le cybercafé.
Configurer un routeur principal (CAFE) pour distribuer les adresses IP via DHCP.
Connecter le réseau local au réseau FAI simulant l'accès à Internet.
Configurer un serveur DNS et un serveur Web pour les clients.
Appliquer des ACL pour sécuriser le réseau.

Topologie du Réseau
![apercus du contenu](cybercafe.pkt)


Configuration des Équipements

1. Routeur FAI

Configuration NAT pour permettre l'accès à Internet.
Attribuer une IP publique (par exemple : 20.20.20.2).

2. Routeur d'accès

DHCP activé pour la distribution d'adresses IP aux clients.
Configuration des interfaces LAN/WLAN avec des sous-réseaux spécifiques.

3. Serveur Web

Adresse IP statique : 192.168.1.2
Configuration du service HTTP (activé)
Création d'une page d'accueil par défaut (index.html)

4. Serveur DNS

Adresse IP statique : 192.168.1.2
Configuration des entrées DNS pour les domaines utilisés (par exemple : www.google.com).

5.Tests de Communication
Vérifier l'accès web en tapant l'IP du serveur (http://20.20.20.2) et le nom de domaine (http://www.google.com).

6.Tester la résolution DNS avec la commande :
nslookup www.google.com



