PS C:\Users\User\Desktop\git_ça> git status                               
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Fichier2.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\User\Desktop\git_ça> git commit -m "David était à Paris"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Fichier2.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\User\Desktop\git_ça> git add                                                         
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config set advice.addEmptyPathspec false"
PS C:\Users\User\Desktop\git_ça> git add Fichier2.txt
PS C:\Users\User\Desktop\git_ça> git commit -m "David était à Paris"
[master 12f87a8] David était à Paris
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Fichier2.txt
PS C:\Users\User\Desktop\git_ça> echo "Boukala m'aide"> Fichier3.txt
PS C:\Users\User\Desktop\git_ça> git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Fichier3.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\User\Desktop\git_ça> git add Fichier3.txt
PS C:\Users\User\Desktop\git_ça> git commit -m "Boukala m'aide"
[master 2850f25] Boukala m'aide
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Fichier3.txt
PS C:\Users\User\Desktop\git_ça> 
voici les commandes utilisés pour l'exercice 1 qui consistait à créez un dépôt vide, ajoutez trois fichiers en trois commits, et affichez l'historique en une ligne par commit. Puis affichez le graphe.
Ici on peut juste voir ceux utilisés pour le fichier car pour les deux autres j'ai dû nettoyer le terminal avec clear.
la modiification d'un fichier de mon travail.

##sujet 1
un commit dans Git est l'action de sauvegarder l'état à un instant précis mais c'est aussi l'enregistrement.

##sujet 2
git lui est logiciel de gestion de version locale