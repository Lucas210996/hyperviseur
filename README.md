# hyperviseur
hyperviseur

M2I Res ITESCIA 
Groupe TP composé de :
Beaumont Lucas & Goulain Clément

Création d'un repository Git nommé :"hyperviseur"
Récupération de la clé  id_rsa.pub dans /.ssh/ sur le serveur ansible
Ajout de la clé dans interface Git pour la communication entre Ansible et Git
Création des fichiers adduser.yaml - iptables.yaml - sshgen.yaml
Vérification du statut Git
Git add adduser.yaml - iptables.yaml - sshgen.yam
Git commit -m "Message correspondant au commit"
Git push --set-upstream origin master
Vérification de la remontée des fichiers dans repertoire Git : OK
test des différents playbook avec la commande suivante :
ansible-playbook -i hosts.yaml -u root foldername.yaml

Password de l'utilisateur itesciadmin : itescia
Le password a été chiffré avec du SHA-512


