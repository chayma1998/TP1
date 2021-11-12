# Compte rendu du TP1 
Dans ce TP on va étudier 3 méthodes de résolution numérique de la fonction f(x)=0, en comparant entre elles.

# La méthode de dichotomie
La méthode de dichotomie est une méthode pour trouver une solution approchée à une équation f(x)=0.
Supposons que la fonction f est continue sur l'intervalle [a,b], avec f(a)≤0 et f(b)≥0. On sait donc qu'il existe au moins un réel c dans l'intervalle [a,b] tel que f(c)=0.
L'idée est alors d'évaluer ce que vaut f au milieu de [a,b], et de distinguer les deux cas suivants :
- si f(a+b/2)≤0, alors on sait qu'on a une racine dans l'intervalle [a+b/2,b].
- si f(a+b/2)≤0, alors on sait qu'on a une racine dans l'intervalle [a+b/2,b].
=> Cette méthode est très lente.

# La méthode de point fixe
La méthode du point fixe appliquée à la résolutions d’équations non linéaires consiste à élaborer un schéma itératif, en l’occurence une suite convergente vers un point fixe x d’une certaine application g, ce point fixe est en l’occurence la solution de l’équation f(x)=0.
=> Cette méthode est plus rapide que la précedente.

# La méthode de newton
La méthode de Newton ou méthode de Newton-Raphson est une méthode numérique itérative de résolution numérique des équations du type f(x)=0. Elle repose sur la méthode du point fixe avec une fonction g particulière qui dépend de la dérivée de f.
La méthode de Newton est une méthode de point fixe avec pour application g :
g(x)=x−f(x)/f′(x)

le schéma numérique de la méthode de Newton est donc donné par:
xn+1=xn−f(xn)/f′(xn)

=> Cette méthode est rapide et connue.







