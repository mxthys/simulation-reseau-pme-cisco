# simulation-reseau-pme-cisco

Ce projet est une simulation d'une infrastructure réseau de PME réalisée 
sur Cisco Packet Tracer dans le cadre de ma préparation au BTS SIO option SISR.
Le réseau est composé de deux sous-réseaux interconnectés via un routeur,
avec des services DHCP, DNS et Web.

Équipement        | Adresse IP      | Rôle
------------------|-----------------|------------------
Serveur0          | 192.168.0.1     | Serveur de fichiers
PC0               | 192.168.0.2     | Poste utilisateur
Laptop0           | 192.168.0.3     | Poste utilisateur
Switch0           | -               | Commutateur réseau 1
Router0           | 192.168.0.254   | Passerelle réseau 1
Router0           | 192.168.100.254 | Passerelle réseau 2
Switch1           | -               | Commutateur réseau 2
PC1               | 192.168.100.1   | Poste utilisateur
PC2               | 192.168.100.2   | Poste utilisateur
Laptop1           | Attribution DHCP| Poste utilisateur
Laptop2           | Attribution DHCP| Poste utilisateur
Serveur DHCP      | 192.168.100.250 | Attribution automatique des IP + résolution des noms
Serveur web       | 192.168.100.249 | Hébergement site interne


1 Shéma du réseau complet
<img width="1280" height="565" alt="01-schema-reseau-complet" src="https://github.com/user-attachments/assets/ec27bcf1-2c75-4fe3-af81-543d5914df6f" />

2 Ping test d'un réseau à un autre
<img width="1277" height="567" alt="02-ping-test-reussi" src="https://github.com/user-attachments/assets/0dc7583e-3a82-4329-917c-b701fafc6881" />

3 Configuration ip d'un poste
<img width="521" height="528" alt="03-configuration-ip-poste png 2" src="https://github.com/user-attachments/assets/30a4fbf0-ecba-4d51-96d8-0c081e9447d6" />
<img width="524" height="532" alt="03-configuration-ip-poste png 1" src="https://github.com/user-attachments/assets/495e4157-c3aa-426d-a8cc-cac360b7f497" />


