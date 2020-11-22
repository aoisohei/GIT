<h1 align='center'>Update Repository</h1>
 
```
git status

# Noubliez pas suprimer ou ajouter les fiches, par example:
# git rm Hierarchical_Clustering.ipynb 
# git add Clustering/

git commit -m "or01"
git push -f github master
```
<h1 align='center'>Les explication</h1>

## 1. On lance git bash du dossier:

```
git status
```
![](https://i.imgur.com/QZgaWf5.png)


Utilisez la commande git rm pour les fiches supprimées:

          Hierarchical_Clustering.ipynb

          K_Means_Clustering.ipynb

Et utilisez la commande git add pour ajouter la dossier:

          Clustering/


## 2. On fait les commandes :

```
git rm Hierarchical_Clustering.ipynb
git rm K_Means_Clustering.ipynb

git add Clustering/
```

![](https://i.imgur.com/4seGF0r.png)

## 3. Voilà toutes les commandes remplies :

```
git status
git commit -m "or01"
git rm Hierarchical_Clustering.ipynb
git rm K_Means_Clustering.ipynb
git add Clustering/
git remote add github https://github.com/aoisohei/delete_images_in_the_folder_that_are_repeated.git
git remote -v
git push -f github master
```

![](https://i.imgur.com/X9KTlCB.png)


## Conclusion.
La cours version, si vous êtes sûr avec remote github :
```
git status
# Noubliez pas suprimer ou ajouter les fiches
git commit -m "or01"
git push -f github master
```

