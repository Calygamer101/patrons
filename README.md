# patrons
patrons/Caleb/2023-12-13
Stratégie
- Patrons comportementaux
- Le Patrons de stratégie une famille d'algoritmes,de les mettre dans de classes separer et ensuitre rendre les objet interchangable. On peut utiliser ce type de patrons pour plusieurs chose comme pour avoir plusieurs different variantes a l"interieur d'un object de disposition et pouvoir passer d'un algorithm a l'autre durant l'execution. Le patrons est aussi utilil lorsqu'on a beaucoup de class et que la seul difference an la facons d'executer un comportement. On peut aussi isoler la logique metier d'une class quand les detail ne sont pas tres important et est res utile si on utilise un gros bloc conditionel.

Concept de programme orientée object
- Dans mon patrons on n'utilise pas vraiment le concept d'heritance ou on emplois la command extends pour partager les methode ou attribut commun a les decendants d'une class specifique. Le concept d'heritance peut etre tres util par contre puisqu'il permet d'organiser des gros code plus efficacement en evitant de repeter le meme non nessecaire code plusieur fois. Dans ce cas, il est beaucoup plus efficase de heriter c'est meme attribue commun d'une certain class parent.
- Dans mon patrons, l'interface PayStrategy se fait implementer deux fois, l'une par PayByPayPal et l'autre par PayByCreditCard, cette interface est utiliser comme un modele appliquer par les classe qui l'implement, un peut comme l'heritage il partage des methode mais specifie a quoi la class doit faire. Chaque classe peut appeler plus d'un interface par contre dans ce partons cela n'est pas necessaire.
- Le polymortphisme est utiliser pour identifier le type commun entre plusieur differente object. Par exemple si on cree un tableau avec plusieur different class, le type pour le tableau vas etre dure a trouver pluisuqe qu'il sont toute different, alors il faut utiliser ce qu'il y a en commun. Pour un tableau (Voiture, Velo, Camion) le type pourrai etre vehicule.
- La composition est quand deux classe depende les une sur les autres et on besoins des services de l'autre pour acomplir sont but. Par exemple la class App a une relaiton de dependance avec la class Order qui coexiste afin d'acomplir le but de prendre la bonne demande. Elle import et cree des object en relation.

### Évaluation

2- 4

x CO - n'a pas soumis le lien pour son projet via le formulaire et le lien soumis via commentaire n'était pas valide

x CO - l'image du diagramme UML n'est pas dans le répertoire, mais il est dans le Classroom

x CO - Les identifiants (variables et méthodes), les commentaires, les javadoc et l'indentation rendent le code facile à lire (manque des commentaires explicatifs sur certains nouveaux éléments comme le bloc `static` et le choix d'un BufferedReader au lieu d'un Scanner dans la classe App)

x CO - Les informations dans le README sont bien structurées et faciles à lire. (manque les sources citées)

x CO - le diagramme UML n'utilise pas les bons types et directions de flèches pour signaler le type de relation entre les élements (composition versus héritage versus utilisation)

o MA - Le diagramme de classe UML est cohérent avec votre implémentation du patron.

o MA - Votre analyse démontre votre capacité à reconnaître les concepts de l'OOP dans un contexte concret.

o MA - Le travail correspond entièrement aux spécifications du projet. 
