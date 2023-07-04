Vscode > terminal >

git config --global user.name " nom prenom"

git config --global user.email "adress mail"

git init
---
git add . (pour ajouter)
---
git commit -m"*(`commit toujours accompagner d'un message`)*"



git push *(rajouter les modifs au git hub)*
---
raccourcis

cls -> clean ligne du terminal

git status -> voir le statut

git log -> voir info perso
---
git remote add origin (adress mail a la suite)

git push -u origin `master`
---
git add .

git commit -m "`message`"
git commit -am "`message`" *(raccouris du gitadd & gitcommit)*
---
git status *(bien verifier le chemin)*

git branch -M main *(renomer la branche avant le push)*

///////////////////////////////////////////

>a faire qu'une seule fois
>>
>>git remote add origin https://----.git
>>
>>git push -u origin `main`

///////////////////////////////////////////

git push *(permet de mettre a jour le fichier sur GitHub)*

/////////////////////////////////////////////

git branch *(pour voir sur quel branch on es )*

git branch `nom de la branch`

git checkout `nom de la branch`*(permet d'aller dessus)*

git branch -M `renomer une branch`

git branch -D `nom de la branch a supprimer` 

> raccourcis:
>>git checkout -b `nom de la branche et le -d permet d'aller direct dessus`

git merge `nom de la branch a fusioner sur la principal`

créer la branch en local avant de la push sur le github