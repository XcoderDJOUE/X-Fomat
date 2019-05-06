# X-Fomat
code de formatage des entier parametrable en javascript 

exple : 

var retour = reformat(parametre1, parametre2, parametre3, parametre4);

=> parametre1 : type String . mettre votre string ici .
=> parametre2 : type entier (integer) . mettre legroupage par caractere ici.
=> parametre3 : type String . mettre le separateur ici.
=> parametre4 : type entier . ordre de separation . valeur : 0 pour une separation monetaire et valeur : 1 pour une separation format telephonique et autre.

exple final : 


var retour = reformat("0918191", 2, " ", 0);
// retour : 0 91 81 91

var retour = reformat("09181917", 2, "-", 1);
// retour : 09-18-19-1
