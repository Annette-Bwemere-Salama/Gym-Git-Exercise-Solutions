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
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout ft/faq-page
Basculement sur la branche 'ft/faq-page'
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout -b ft/home-page-redesign
Basculement sur la nouvelle branche 'ft/home-page-redesign'
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout main
Basculement sur la branche 'main'
Votre branche est en retard sur 'origin/main' de 9 commits, et peut être mise à jour en avance rapide.
  (utilisez "git pull" pour mettre à jour votre branche locale)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git add .
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git commit -m"pull request"
```
```bash
[main 3765325] pull request
 1 file changed, 3 insertions(+), 1 deletion(-)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push origin main
To https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: impossible de pousser des références vers 'https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions.git'
astuce: Les mises à jour ont été rejetées car la pointe de la branche courante est derrière
astuce: son homologue distant. Intégrez les changements distants (par exemple 'git pull ...')
astuce: avant de pousser à nouveau.
astuce: Voir la 'Note à propos des avances rapides' dans 'git push --help' pour plus d'information.
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git pull
Merge made by the 'recursive' strategy.
 contact.html | 15 +++++++++++++++
 faq.html     | 15 +++++++++++++++
 2 files changed, 30 insertions(+)
 create mode 100644 contact.html
 create mode 100644 faq.html
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git chechkout -b ft/home-page-redesi
gn
git : 'chechkout' n'est pas une commande git. Voir 'git --help'.

La commande la plus ressemblante est
        checkout
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout -b ft/home-page-redesig
n
fatal: Une branche nommée 'ft/home-page-redesign' existe déjà.
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout  ft/home-page-redesign
Basculement sur la branche 'ft/home-page-redesign'
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git rebase --help
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git add .
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git commit -m"rebase a commit"
[ft/home-page-redesign d652731] rebase a commit
 1 file changed, 2 insertions(+)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout main
Basculement sur la branche 'main'
Votre branche est en avance sur 'origin/main' de 2 commits.
  (utilisez "git push" pour publier vos commits locaux)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout  ft/home-page-redesign
Basculement sur la branche 'ft/home-page-redesign'
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git add .
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git status
Sur la branche ft/home-page-redesign
rien à valider, la copie de travail est propre
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout -b ft/home-page-redesign ft/faq-page
fatal: Une branche nommée 'ft/home-page-redesign' existe déjà.
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout main
Basculement sur la branche 'main'
Votre branche est en avance sur 'origin/main' de 2 commits.
  (utilisez "git push" pour publier vos commits locaux)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push
Énumération des objets: 9, fait.
Décompte des objets: 100% (8/8), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (5/5), fait.
Écriture des objets: 100% (5/5), 873 octets | 291.00 Kio/s, fait.
Total 5 (delta 2), réutilisés 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote: Bypassed rule violations for refs/heads/main:
remote: 
remote: - At least 1 approving review is required by reviewers with write access.
remote: 
To https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions.git
   9fb94dc..c2e4f4e  main -> main
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git checkout ft/home-page-redesign
Basculement sur la branche 'ft/home-page-redesign'
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git rebase main
La branche courante ft/home-page-redesign est à jour.
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git add .
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git commit -m"rebase"
[ft/home-page-redesign a8e4f0b] rebase
 1 file changed, 1 insertion(+)
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$
git push 
```
```bash
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push --set-upstream origin ft/home-page-redesign
Énumération des objets: 8, fait.
Décompte des objets: 100% (8/8), fait.
Compression par delta en utilisant jusqu'à 4 fils d'exécution
Compression des objets: 100% (6/6), fait.
Écriture des objets: 100% (6/6), 596 octets | 596.00 Kio/s, fait.
Total 6 (delta 4), réutilisés 0 (delta 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote: 
To https://github.com/Annette-Bwemere-Salama/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
La branche 'ft/home-page-redesign' est paramétrée pour suivre la branche distante 'ft/home-page-redesign' depuis 'origin'.
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ git push
Everything up-to-date
anette-bwemere@anettebwemere-HP-EliteBook-840-G3:~/BlockchainOpen/Gym-Git-Exercise-Solutions/Gym-Git-Exercise-Solutions$ 

```