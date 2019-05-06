# X-Fomat
code de formatage des entier parametrable en javascript 

exple : 

var retour = reformat(parametre1, parametre2, parametre3);

=> parametre1 : type String . mettre votre string ici .
=> parametre2 : type entier (integer) . mettre legroupage par caractere ici.
=> parametre3 : type String . mettre le separateur ici.

exple final : 


var retour = reformat("09181917", 2, " ");
// retour : 09 18 19 17

var retour = reformat("09181917", 2, "-");
// retour : 09-18-19-17
