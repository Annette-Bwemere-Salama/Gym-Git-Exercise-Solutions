# Gym-Git-Exercise-Solutions

## Bundle 1

### Exercise 1


 ```bash
     anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git init
Dépôt Git existant réinitialisé dans /home/anette-bwemere/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions/.git/
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git add .
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git commit -m"make change"
[main 0e3340d] make change
 1 file changed, 1 insertion(+), 1 deletion(-)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push origin main
Énumération des objets: 5, fait.
Décompte des objets: 100% (5/5), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (1/1), fait.
Écriture des objets: 100% (3/3), 274 octets | 274.00 Kio/s, fait.
Total 3 (delta 0), réutilisés 0 (delta 0)
To https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions.git
   ed16253..0e3340d  main -> main
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout -b dev
Basculement sur la nouvelle branche 'dev'
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git branch test
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git branch -d test
Branche test supprimée (précédemment 0e3340d).
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git pull
Mise à jour c2e4f4e..fe9a9ae
Fast-forward
 home.html | 3 +++
 1 file changed, 3 insertions(+)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git remote add git-copy https://github.com/Annette-Bwemere-Salama/gym-exercice-copy.git
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git add .
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git commit -m"git coppy change home page"
[main 06f6b7f] git coppy change home page
 1 file changed, 13 insertions(+)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push origin main
Énumération des objets: 5, fait.
Décompte des objets: 100% (5/5), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (3/3), fait.
Écriture des objets: 100% (3/3), 1.01 Kio | 258.00 Kio/s, fait.
Total 3 (delta 1), réutilisés 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: Bypassed rule violations for refs/heads/main:
remote: 
remote: - At least 1 approving review is required by reviewers with write access.
remote: 
To https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions.git
   fe9a9ae..06f6b7f  main -> main
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push git-copy m
ain
Énumération des objets: 70, fait.
Décompte des objets: 100% (70/70), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (66/66), fait.
Écriture des objets: 100% (70/70), 12.45 Kio | 579.00 Kio/s, fait.
Total 70 (delta 29), réutilisés 0 (delta 0)
remote: Resolving deltas: 100% (29/29), done.
To https://github.com/Annette-Bwemere-Salama/gym-exercice-copy.git
 * [new branch]      main -> main
```