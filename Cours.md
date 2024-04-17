# R2C1 : Écriture d'un entier positif dans une base b supérieur à 2

 pour écrire un entier positif quelconque dans une base quelconque, il suffit de diviser cet entier par la base voulue, jusqu'à atteindre 0, en notant les restes. Les divisions sont des divisions euclidiennes (51 ÷ 2 = 25.5 donc on poursuit la division avec 25 et on garde 1 en reste)

### exemple 1 : (211)<sub>10</sub> = (?)<sub>3</sub>

##### On réalise la division consécutive de **211** par **3**

211 ÷ 3 = 70 reste **1**

70 ÷ 3 = 23 reste **1**

23 ÷ 3 = 7 reste **2**

7 ÷ 3 = 2 reste **1**

2 ÷ 3 = 0 reste **2**


#### On lis le résultat de bas en haut et on obtient : **21211**. Donc, (211)<sub>10</sub> = (21211)<sub>3</sub>

### exemple 2 : (4967)<sub>10</sub> = (?)<sub>7</sub>

##### On réalise la division consécutive de **4967** par **7**

4967 ÷ 7 = 709 reste **4**

709 ÷ 7 = 101 reste **2**

101 ÷ 7 = 14 reste **3**

14 ÷ 7 = 2 reste **0**

2 ÷ 7 = 0 reste **2**


#### On lis le résultat de bas en haut et on obtient : **20324**. Donc, (4967)<sub>10</sub> = (20324)<sub>7</sub>

À l'inverse, il est aussi important de pouvoir écrire un nombre de n'importe quelle base, en base décimale. Pour ce faire, il faut utiliser la multiplication et non la division.

On multiplie chaque chiffre du nombre que l'on veut convertir par la base de ce nombre mise à la puissance appropriée.

Prenons l'exemple de la conversion de **(40342101)<sub>5</sub>** en base **décimale** :

|puissance de 5 |  5<sup>7</sup> |  5<sup>6</sup> |5<sup>5</sup>  | 5<sup>4</sup>  |  5<sup>3</sup> |  5<sup>2</sup> |  5<sup>1</sup> |  5<sup>0</sup> | 
|---------------|----------------|----------------|---------------|----------------|----------------|----------------|----------------|----------------|
|base 5         |       4        |       0        |       3       |      4         |       2        |       1        |       0        |       1        |
|multiplication | 4 x 5<sup>7</sup>|0 x 5<sup>6</sup>|3 x 5<sup>5</sup>|4 x 5<sup>4</sup>|2 x 5<sup>3</sup>|1 x 5<sup>2</sup>|0 x 5<sup>1</sup>|1 x 5<sup>0</sup>|      
|résultat       |     312500     |       0        |      9375     |      2500      |      250       |      25        |       0        |       1        |    

#### on additionne tous ces résultats : 312500 + 0 + 9375 + 2500 + 250 + 25 + 0 + 1 = **324651**. Donc, (40342101)<sub>5</sub> = (324651)<sub>10</sub>


Lorsque vous vous exercez, n'hésitez pas à utiliser un [convertisseur en ligne](https://www.rapidtables.com/convert/number/base-converter.html) pour vérifier vos réponses

#### Entrainez-vous avec les conversions suivantes, puis vérifiez vos réponses sur le convertisseur en lien ci-dessus.

#### (245)<sub>6</sub> = (?)<sub>10</sub>
#### (9001)<sub>10</sub> = (?)<sub>3</sub>
#### (71963)<sub>10</sub> = (?)<sub>9</sub>
#### (10011010)<sub>2</sub> = (?)<sub>10</sub>
