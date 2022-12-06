## [LU2IN002] Projet de fin de semestre en langage de programmation java : 

![alt text](https://previews.123rf.com/images/lukaves/lukaves2104/lukaves210400049/167738643-illustration-de-la-cha%C3%AEne-alimentaire-en-for%C3%AAt-pour-l-exercice-scolaire-.jpg)


# Simulation d'écosystème ressource/predateurs : 


### **Membres du groupe :**
- Yanis **BAOUCHE** __(21107473)__
- Xinyu **CHEN** __(21108009)__


## Introduction :

Le thème de notre simulation est la simulation d'une bergerie. Les prédateurs sont des Loups, mais peuvent être étendue  à d'autres types d'animaux par la possibilité facile d'évolution de notre code. Les loups chassent dans un Terrain, cette capacité leur est transmise par une interface chasser, le tableau de ressource contient l'eau, l'herbe et la viande des moutons morts . Chaque animal se déplace grâce à ses coordonnées x et y de manière aléatoire dans la carte, qui est un monde que l'on supposera torique. Chaque Proie possède une vie, représenté par un attribut énergie compris entre 1 et 10 et deux hérités de la classe Animal, une coordonée en x et en y. 
Nous avons implémenté des Interfaces afin de péréniser notre code, dans le cas où nous rajouterions des prédateurs ne chassant pas par exemple (Un piège placer par un chasseur qui atttendrais qu'une proie se soit fait piéger), ou donner un comportement à certaines proies qui se trouvent dans la Rivière et qui n'aurais pas la capacité de se déplacer sur Terre. 

### Respect du cahier des charges :
- [X] Terrain de ressource, d'herbes, d'eau et de viandes.
- [X] Nombre de classe comprise entre 6 et 12.
- [X] Interface, hérédité et exceptions sont incluent dans le code 
- [X] Ressource d'eau et d'énergie (pour les prédateurs) dont l'état interne est modifié naturellement, soit par déplacement de l'agent soit par vieillissement, et une ressource de santé

# Annexes :
### Diagramme UML des classes : 

![Screenshot from 2022-12-03 17-25-41](https://user-images.githubusercontent.com/99649037/205451279-5caec99f-b197-4876-9a08-8d41383b0910.png)
![Screenshot from 2022-12-03 19-04-23](https://user-images.githubusercontent.com/99649037/205455425-d6104ca6-d044-4c97-9ef1-bed3a8186242.png)

### Sources :
https://www.projetecolo.com/predateurs-et-proies-exemples-et-caracteristiques-446.html#:~:text=Exemples%20de%20superpr%C3%A9dateurs-,Pr%C3%A9dateurs%20et%20proies%20%3A%20quels%20sont%2Dils%20et%20quelles%20sont%20leurs,%C3%A9nergie%20sous%20forme%20de%20nourriture.
