# ruby
Réponses aux questions:

2.2) la différence fondamentale entre "puts" et "print" est que le premier affiche, prend en compte les valeurs dans son affichage, tandis que le second ne fait que copier/coller ce que vous avez écrit. Par exemple, si vous écrivez la valeur "nil" après "puts", le terminal ne renverra pas de valeur. Tandis que si vous écrivez "nil" après "print", le terminal renverra la valeur "nil".

2.3)Rien ne se passe, sauf l'ajout d'un "#" au début de ligne. Par contre, si l'on met #{Et avec une voix sexy, ça donne : Bonjour, monde !"} à la deuxième ligne, le message ne s'affiche pas correctement car l'on n'a pas défini de variable à remplacer auparavant, de plus il n'y a plus de guillemet à la fin de la ligne (erreur dans la question ? cf:"Il ne dit pas bonjour")

2.4)Un message d'erreur s'affiche car la string n'a pas de fin, du fait qu'il manque un guillemet au bout de la ligne.

2.5)"#{}" résoud les opérations mathématiques que vous avez mis entre les accolades. On appelle cela une interpolation. Cela peut s'appliquer à des strings également, pas seulement des valeurs mathématiques. Par exemple #{chien+chien} donnera "chienchien".

2.6)Il s'affiche une erreur car le nombre de minutes dans une heure n'est pas une variable qui a été définie.

2.7.a)gets.chomp me permet de rentrer la valeur correspondant à mon nom d'utilisateur directement dans le terminal, qui renvoie la valeur sur la ligne suivante.
2.7.b)Il n'y a pas grande différence entre ces trois programmes si ce n'est que le b) affiche un signe ">" indiquant que l'on peut taper son username, et le c) fait la même chose, juste sans la question et le symbole. Le résultat final est le même.
