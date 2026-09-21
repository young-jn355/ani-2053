PS C:\Users\User\Desktop\GET_TEG\ani-2053\chapitre-02> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   exo1-le_depot_d_essai/c2-exo1_reponse.md

no changes added to commit (use "git add" and/or "git commit -a")
Ici Git a remarquéque le fichier a été modifié par au dernier commit mais ces changements ne sont pas encore prêts à être sauvegardés définitivements.

PS C:\Users\User\Desktop\GET_TEG\ani-2053\chapitre-02> git add .
Ici le fichier est passé de l'état de modifié à l'état d'indexé et est passé de la zone de préparation et fera partie des prochains instantanée.

PS C:\Users\User\Desktop\GET_TEG\ani-2053\chapitre-02> git commit -m "l'exercice sur la modification "
[main 730ebe8] l'exercice sur la modification
 1 file changed, 2 insertions(+), 1 deletion(-)
 les modifications ont été officiellement enregistrées dans l'historique locale