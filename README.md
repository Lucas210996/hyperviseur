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




History des commandes passées sur : Ansible machine (192.168.114.138)


 1  ssh-keygen
    2  ssh-copy-id root@192.168.114.132
    3  ssh-copy-id root@192.168.114.133
    4  ssh-copy-id root@192.168.114.134
    5  ssh 192.168.114.132
    6  exit
    7  mkdir projetinfra
    8  ls
    9  cd projetinfra/
   10  nano hosts.yaml
   11  nano deploy.yaml
   12  ls
   13  ls -l
   14  vi hosts.yaml
   15  ls
   16  cd /
   17  cd /etc/ansible
   18  vi hosts
   19  cd /etc/ansible
   20  ls
   21  cd /home/lucas/projetinfra/
   22  ls
   23  nano hosts.yaml
   24  git log
   25  git init
   26  git log
   27  git status
   28  git add hosts.yaml
   29  git status
   30  git commit -m "l'inventaire gère un cluster de 3 serveurs"
   31  git log
   32  git status
   33  nano hosts.yaml
   34  git status
   35  git dif
   36  git diff
   37  git add -p
   38  git status
   39  git commit -m
   40  git commit -m "L'inventaire est au format yaml"
   41  git log
   42  git checkout
   43  git checkout b35ef156884b7a4a088a80438bdf184776ed6fc3
   44  ls
   45  nano hosts.yaml
   46  git log
   47  git checkout master
   48  history
   49  nano hosts.yaml
   50  git status
   51  cd /
   52  git log
   53  cd /home/lucas
   54  git log
   55  git status
   56  git log
   57  history
   58  cd .git
   59  ls
   60  cd projetinfra/
   61  ls
   62  cd .git
   63  git lo
   64  git log
   65  git status
   66  cd /etc/ansible/hosts
   67  nano /etc/ansible/hosts
   68  reboot
   69  ls
   70  cd projetinfra/
   71  nano hosts.yaml
   72  ansible all -m ping
   73  cd /etc/ansible/hosts
   74  ls
   75  nano /etc/ansible/hosts
   76  ansible all -m ping
   77  nano hosts.yaml
   78  pip install proxmoxer
   79  cd /
   80  pip install proxmoxer
   81  apt install python-pip
   82  pip install proxmoxer
   83  cd /home/lucas
   84  ls
   85  nano deployvm.yaml
   86  ansible-playbook -i hosts.yaml -u root deployvm.yaml
   87  nano deployvm.yaml
   88  ansible-playbook -i hosts.yaml -u root deployvm.yaml
   89  nano deployvm.yaml
   90  ansible-playbook -i hosts.yaml -u root deployvm.yaml
   91  nano deployvm.yaml
   92  ansible-playbook -i hosts.yaml -u root deployvm.yaml
   93  nano deployvm.yaml
   94  ansible-playbook -i hosts.yaml -u root deployvm.yaml
   95  nano deployvm.yaml
   96  ansible-playbook -i hosts.yaml -u root deployvm.yaml
   97  ls
   98  cd projetinfra/
   99  nano hosts.yaml
  100  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  101  cp /home/lucas/deployvm.yaml /home/lucas/projetinfra/
  102  ls
  103  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  104  nano hosts.yaml
  105  nano deployvm.yaml
  106  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  107  nano deployvm.yaml
  108  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  109  exit
  110  nano deployvm.yaml
  111  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  112  nano deployvm.yaml
  113  reboot
  114  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  115  nano /home/lucas/deployvm.yaml
  116  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  117  nano /home/lucas/deployvm.yaml
  118  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  119  ping 192.168.114.132
  120  nano /home/lucas/deployvm.yaml
  121  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  122  nano /etc/ansible
  123  nano /home/lucas/deployvm.yaml
  124  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  125  nano /home/lucas/deployvm.yaml
  126  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  127  nano /home/lucas/deployvm.yaml
  128  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  129  nano /home/lucas/deployvm.yaml
  130  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  131  ls
  132  cd projetinfra/
  133  ls
  134  nano hosts.yaml
  135  nano deployvm.yaml
  136  rm /home/lucas/deployvm.yaml
  137  cd /home/lucas/
  138  ls
  139  cd projetinfra/
  140  ls
  141  nano deployvm.yaml
  142  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  143  nano deployvm.yaml
  144  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  145  nano deployvm.yaml
  146  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  147  nano deployvm.yaml
  148  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  149  nano deployvm.yaml
  150  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  151  nano deployvm.yaml
  152  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  153  nano deployvm.yaml
  154  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  155  nano deployvm.yaml
  156  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  157  nano deployvm.yaml
  158  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  159  nano deployvm.yaml
  160  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  161  nano deployvm.yaml
  162  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  163  nano deployvm.yaml
  164  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  165  nano deployvm.yaml
  166  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  167  nano deployvm.yaml
  168  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  169  nano deployvm.yaml
  170  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  171  nano deployvm.yaml
  172  git status
  173  git add deployvm.yaml
  174  git commit -m "Fichier conf deploy"
  175  git status
  176  git log
  177  reboot
  178  vi sshgen.yaml
  179  ls
  180  vi sshgen.yaml
  181  vi iptables.yaml
  182  vi sshgen.yaml
  183  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  184  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  185  vi sshgen.yaml
  186  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  187  vi sshgen.yaml
  188  git status
  189  git add adduser.yaml
  190  git commit -m "Adduserfolder"
  191  git add iptables.yaml
  192  git commit -m "Iptablefolder"
  193  git add sshgen.yaml
  194  git commit -m "Sshgenfolder"
  195  git log
  196  git push --set-upstream origin master
  197  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  198  ls
  199  vi hosts.yaml
  200  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  201  ssh root@192.168.114.132root@192.168.114.132
  202  ssh root@192.168.114.132
  203  ls -l
  204  ansible-playbook -i hosts.yaml -u root sshgen.yaml -k
  205  ssh root@192.168.114.132
  206  ssh-copy-id root@192.168.114.132
  207  ansible-playbook -i hosts.yaml -u root sshgen.yaml -k
  208  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  209  vi hosts.yaml
  210  ls
  211  vi sshgen.yaml
  212  cat ~/.ssh/id_rsa.pub
  213  vi sshgen.yaml
  214  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  215  ansible all -m ping
  216  ansible-playbook -i hosts.yaml -u root sshgen.yaml
  217  ansible-playbook -i hosts.yaml -u root adduser.yaml
  218  vi hosts.yaml
  219  ansible-playbook -i hosts.yaml -u root iptables.yaml
  220  ansible-playbook -i hosts.yaml -u root adduser.yaml
  221  vi adduser.yaml
  222  vi addusersanspassword.yaml
  223  git status
  224  vi addusersanspassword.yaml
  225  git status
  226  git add addusersanspassword.yaml
  227  git commit -m"addusersanspasswordfolder"
  228  git commit -m "addusersanspasswordfolder"
  229  git push --set-upstream origin master
  230  nano hosts.yaml
  231  cd /
  232  cd /root/.ssh/
  233  ls
  234  cd /homz/lucas
  235  cd /home/lucas/projetinfra/
  236  nano deployvm.yaml
  237  nano sshgen.yaml
  238  nano deployvm.yaml
  239  ansible-playbook -i hosts.yaml -u root deployvm.yaml
  240  git push --set-upstream origin master
  241  git add deployvm.yaml

