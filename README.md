# patrons
patrons/Caleb/2023-12-13
Stratégie
- Patrons comportementaux
- Le Patrons de stratégie une famille d'algoritmes,de les mettre dans de classes separer et ensuitre rendre les objet interchangable. On peut utiliser ce type de patrons pour plusieurs chose comme pour avoir plusieurs different variantes a l"interieur d'un object de disposition et pouvoir passer d'un algorithm a l'autre durant l'execution. Le patrons est aussi utilil lorsqu'on a beaucoup de class et que la seul difference an la facons d'executer un comportement. On peut aussi isoler la logique metier d'une class quand les detail ne sont pas tres important et est res utile si on utilise un gros bloc conditionel.

Concept de programme orientée object
- Dans mon patrons on n'utilise pas vraiment le concept d'heritance ou on emplois la command extends pour partager les methode ou attribut commun a les decendants d'une class specifique. Le concept d'heritance peut etre tres util par contre puisqu'il permet d'organiser des gros code plus efficacement en evitant de repeter le meme non nessecaire code plusieur fois. Dans ce cas, il est beaucoup plus efficase de heriter c'est meme attribue commun d'une certain class parent.
-Dans mon patrons, l'interface PayStrategy se fait implementer deux fois, l'une par PayByPayPal et l'autre par PayByCreditCard, cette interface est utiliser comme un modele appliquer par les classe qui l'implement, un peut comme l'heritage il partage des methode mais specifie a quoi la class doit faire. Chaque classe peut appeler plus d'un interface par contre dans ce partons cela n'est pas necessaire.
-
