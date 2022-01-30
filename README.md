# JDBC
Mettre en oeuvre jdbc, pour faire accès à partir d'une application java standalone à une base creer manuellement

## Première étape
Créer notre propre base de donnée Il faut télécharger mysql avec ses connectors (jar file )

  
## Deuxième étape
Créer une Base de donnée "Company" et une table "Employees"

![3](https://user-images.githubusercontent.com/88480955/151720372-a2440cde-d8be-4182-be55-a45c2b0e9926.PNG)
  
## Troisième étape
Insérer les données 
![4](https://user-images.githubusercontent.com/88480955/151720400-e7bca273-3bb0-449d-a9d2-cc0979f74f4a.PNG)

nous aurons donc la table suivante:

![5](https://user-images.githubusercontent.com/88480955/151720505-2851a7e7-1853-414b-9e9e-badfae92ddc0.PNG)

## Quatrième étape
Ajouter le jar file sur eclipse en cliquant sur build path et add external jar files(des connectors de java peuvent  avec my sql (8.0.28)  être installés donc il faut uniquement les sélectionner)
![9](https://user-images.githubusercontent.com/88480955/151721179-0fba37cd-6799-4b31-acec-291ac696cc29.PNG)
## Résultat:
Enfin j'ai pu accéder à ma base de donne "company" sur mysql à partir du script java (sur éclipse) par l'intermediaire du driver qui est le jar file
Voici les requetes effectuées.
  
### select * from employees where ID=1020
  
![7](https://user-images.githubusercontent.com/88480955/151721157-febe3cac-06dc-4c3d-a335-15de5a1eac59.PNG)
  
  
### select * from employees
  
<image> ![8](https://user-images.githubusercontent.com/88480955/151721171-deacf54d-12af-40c6-baea-45d2992515f6.PNG)


    

