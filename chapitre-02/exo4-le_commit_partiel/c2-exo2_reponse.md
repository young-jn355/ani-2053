PS C:\Users\User\Desktop\GET_TEG\ani-2053> git add -p
diff --git a/chapitre-02/exo1-le_depot_d_essai/c2-exo1_reponse.md b/chapitre-02/exo1-le_depot_d_essai/c2-exo1_reponse.md
index d807f5a..3506c43 100644
--- a/chapitre-02/exo1-le_depot_d_essai/c2-exo1_reponse.md
+++ b/chapitre-02/exo1-le_depot_d_essai/c2-exo1_reponse.md
@@ -35,12 +35,8 @@ PS C:\Users\User\Desktop\git_ça> git commit -m "Boukala m'aide"
  1 file changed, 0 insertions(+), 0 deletions(-)
  create mode 100644 Fichier3.txt
 PS C:\Users\User\Desktop\git_ça> 
-voici les commandes utilisés pour l'exercice 1 qui consistait à créez un dépôt vide, ajoutez trois fichiers en trois commits, et affichez l'historique en une ligne par commit. Puis affichez le graphe.
+voici les commandes utilisés pour l'exercice 1 qui consistait à créez un dépôt vide. Ajoutez trois fichiers en trois commits, et affichez l'historique en une ligne par commit. Puis affichez le graphe.
 Ici on peut juste voir ceux utilisés pour le fichier car pour les deux autres j'ai dû nettoyer le terminal avec clear.
 la modiification d'un fichier de mon travail.
 
-##sujet 1
-un commit dans Git est l'action de sauvegarder l'état à un instant précis mais c'est aussi l'enregistrement.
-
-##sujet 2
-git lui est logiciel de gestion de version locale
\ No newline at end of file
+il existe un différence entre git et gitHub git lui est un logiciel de gestion local et Git hub est un service en ligne qui héberge des projrts utilisant Git. 
\ No newline at end of file

git add -p m'a permit de choisir quelles parties de mes modifications est ce que je mettre dans le prochain commit .

(1/1) Stage this hunk [y,n,q,a,d,s,e,p,P,?]? s
Split into 2 hunks.
@@ -35,7 +35,7 @@ PS C:\Users\User\Desktop\git_ça> git commit -m "Boukala m'aide"
  1 file changed, 0 insertions(+), 0 deletions(-)
  create mode 100644 Fichier3.txt
 PS C:\Users\User\Desktop\git_ça> 
-voici les commandes utilisés pour l'exercice 1 qui consistait à créez un dépôt vide, ajoutez trois fichiers en trois commits, et affichez l'historique en une ligne par commit. Puis affichez le graphe.
+voici les commandes utilisés pour l'exercice 1 qui consistait à créez un dépôt vide. Ajoutez trois fichiers en trois commits, et affichez l'historique en une ligne par commit. Puis affichez le graphe.
 Ici on peut juste voir ceux utilisés pour le fichier car pour les deux autres j'ai dû nettoyer le terminal avec clear.
 la modiification d'un fichier de mon travail.

 Ici s m'a permit de découper le bloc en petit morceau et choisir le bloc que j'ai vais ajouter.
 
(1/2) Stage this hunk [y,n,q,a,d,k,K,j,J,g,/,e,p,P,?]? y
@@ -39,8 +39,4 @@
 Ici on peut juste voir ceux utilisés pour le fichier car pour les deux autres j'ai dû nettoyer le terminal avec clear.
 la modiification d'un fichier de mon travail.
 
-##sujet 1
-un commit dans Git est l'action de sauvegarder l'état à un instant précis mais c'est aussi l'enregistrement.
-
-##sujet 2
-git lui est logiciel de gestion de version locale
\ No newline at end of file
+il existe un différence entre git et gitHub git lui est un logiciel de gestion local et Git hub est un service en ligne qui héberge des projrts utilisant Git. 
\ No newline at end of file

Me permet d'ajouter le bloc dans le prochain commit

(2/2) Stage this hunk [y,n,q,a,d,K,J,g,/,e,p,P,?]? n

PS C:\Users\User\Desktop\GET_TEG\ani-2053> git commit -m "la première correction"
[main 57a05dc] la première correction
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\User\Desktop\GET_TEG\ani-2053> git add .
PS C:\Users\User\Desktop\GET_TEG\ani-2053> git commit -m "seconde correction"
[main b76e374] seconde correction
 1 file changed, 1 insertion(+), 5 deletions(-)
PS C:\Users\User\Desktop\GET_TEG\ani-2053> cd ..
PS C:\Users\User\Desktop\GET_TEG> cd .\ani-2053
PS C:\Users\User\Desktop\GET_TEG\ani-2053> l

Pour commencer j'ai eu des petites difficultés avec git add -p car j'ai rajouté deux phrases à la fin et quand je tapais s on me disais cannot split this hunk et ne pouvais séparer les deux ajouts . Donc j'ai plûtot ajouter une phrase à la fin et corrigé quelque chose après j'ai encore essayé et avec s les erreurs ont pû être seéparé.