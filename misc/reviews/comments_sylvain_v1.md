Chapitre 1 (Intro)
==================

Ma compréhension de la problématique: les architectures actuelles ne tiennent pas compte des *wearable*. On vise à montrer ce qu'ils ajoutent, et proposer une architecture qui puisse les accommoder.

Page 12: on dit "puisque les différentes architectures recensées dans la littérature n’ont pas été initialement prévues pour accueillir ce type de matériel, les wearable devices se retrouvent très mal, voir nullement intégrés à celles-ci". Ceci contredit deux affirmations du chapitre 2:

- 2.2.2 sur OSGI: "l'intégration de wearable devices [est] possible, sans effort particulier, grâce à la flexibilité offerte par les architectures basées composants"
- 2.2.3 sur ZigBee: "il semble relativement aisé d’y ajouter de nouveaux capteurs et notamment d’y intégrer des wearable devices"

Il y a donc deux catégories de travaux du chapitre 2 pour lesquels on dit que c'est déjà possible. Ça pose un problème au niveau de la cohérence de la problématique de recherche: on se fait "vendre" au chapitre 1 que le travail est motivé par l'incapacité de prise en charge des wearables, pour découvrir au chapitre 2 que certaines solutions les supportent déjà. Je pense que ceci devrait être clarifié pour éviter qu'un membre du jury adresse le même reproche.

Page 13: c'est la première occurrence dans une phrase du terme "wearable devices". Cependant, ni ici ni plus loin dans l'intro ne dit-on clairement ce que c'est et ce que ça fait. On n'a pas non plus d'exemples (une petite image?). Également, puisque la problématique de la thèse est de prendre en compte les wearable dans l'architecture, on devrait se faire donner une petite idée de ce que ces devices ont de particulier qui les rend difficiles à utiliser dans les solutions actuelles (et justifie donc la contribution de la thèse).

1.6: la description de la problématique de recherche est somme toute assez courte --à peine plus d'une page (excluant la liste des articles). On devrait ici avoir un aperçu de la méthodologie qui a été employée (et qui sera décrite dans la suite de la thèse) pour réaliser chacun de ces objectifs. Il manque également un élément important: à quel point ont-ils été atteints? L'introduction devrait donner un aperçu des résultats obtenus et des conclusions que l'on peut tirer du travail.

J'enverrais la liste des publications à la toute fin de l'intro. Les publis en elles-mêmes ne servent pas vraiment à préciser la problématique de recherche; ce sont plutôt des retombées du travail.

1.7: je trouve que la présentation de chacun des chapitres est un peu télégraphique. Au lieu d'une phrase, je préférerais un paragraphe pour résumer le contenu des chapitres.

Chapitre 2
==========

Finalement, j'ai tout relu.

Page 18, "cette première partie se découpe en trois sous-sections" -> il y en a *quatre*; on ne parle pas ici de l'architecture de 2.2.4 (ajoutée depuis le projet de thèse?). Le même commentaire s'applique à la section 2.4 qui parle seulement des trois premières catégories.

Deux dernières phrases de 2.2.1: on explique en quoi l'architecture n'est pas appropriée pour les wearable devices. Mais à ce stade-ci de la lecture, on ne sait pas encore ce que sont les wearables et ce qu'ils ont de particulier, puisque c'est au chapitre 3 qu'ils sont présentés. Évidemment, on ne peut pas chambouler l'ordre des chapitres, mais dans la séquence actuelle ces affirmations sont difficiles à comprendre et à accepter pour le lecteur.

2.2.2: on présente les OSGI comme "répondant" aux problèmes des architectures de 2.2.1, mais MavHome remonte à 2003 alors que les solutions de 2.2.1 datent de 2014 et 2009.

Fin de 2.2: on a présenté et critiqué quatre types d'architectures, mais pas toujours selon les mêmes dimensions. Parfois on mentionne le coût, d'autres fois la présence de points de défaillance, d'autres fois les exigences en calcul, etc. Ça m'a laissé avec une impression un peu éparse de "qui fait quoi" (ou plutôt, "qui a quel défaut"). Un petit tableau synthèse pourrait rendre les choses plus claires.

Il ne faut également pas perdre de vue que l'objectif est de positionner l'état de l'art par rapport à la problématique de la thèse, de façon à bien mettre en évidence le "trou" qui vise à être comblé. Je ne peux pas dire ici que c'est limpide, d'autant plus qu'on dit explicitement que les wearable devices *sont* supportés dans au moins deux de ces cas (voir mes remarques du chapitre 1).

Page 37: ici n représente un vecteur de nombres complexes, alors qu'à la page précédente le même symbole représentait un signal sur une fenêtre. Peut-être changer de lettre? Aussi, on dit que c'est un vecteur "de taille N": j'imagine qu'on veut dire un vecteur à N *dimensions* (taille est un peu vague ici, ça pourrait aussi évoquer le module)?

Page 50: le terme français pour SVM est "machine à vecteurs de support", et non "machine à support de vecteur" (le sens est très différent). Il faudrait que ce soit remplacé partout!



Chapitre 3
==========

Rien à dire; j'ai constaté qu'à quelques mots près, c'est le même texte que pour le projet de thèse. Simplement surveiller mes rares annotations mineures à travers les pages.

Chapitre 4
==========

Je comprends que le chapitre est plus ou moins directement tiré des articles, mais en tant que brique au milieu d'une thèse, certains éléments devraient être ajustés.

## Introduction

Le premier paragraphe de l'intro donne de l'information générale sur les wearables qui sert à motiver leur utilisation. Je trouve que c'est un peu tard au chapitre 4 pour amener ces arguments généraux. Au moins la première moitié de ce paragraphe, qui énonce des généralités, serait mieux placée à la section 1.5 lorsqu'on aborde les wearables pour la première fois. À quelques ajustements près, le chapitre 4 pourrait très bien commencer au deuxième paragraphe.

## Objectifs

Les chapitres 4-5-6 devraient faire écho aux objectifs de recherche qui sont annoncés dans l'introduction, en section 1.6. Il y a trois objectifs, et on s'attend naturellement à ce que chacun fasse l'objet d'un chapitre (c'est d'ailleurs le cas). Par contre, il serait important d'y retrouver l'énoncé des *mêmes* objectifs, ce qui n'est pas tout-à-fait le cas ici.

En intro, la première question de recherche dit: "quels sont les apports que les wearables vont proposer pour améliorer l'assistance?". La question de recherche du chapitre 4 dit plutôt: "peut-on reconnaître les types de sols avec les wearables?" Ça me semble être une sous-question plus éetroite. Il faudrait expliquer pourquoi, parmi tout ce qu'on peut faire avec les wearables, on a choisi ce problème particulier. Également, le lien entre détection des types de sol et assistance n'est pas vraiment établi. On se doute que c'est lié, mais il faut attendre les pages 93-94 avant qu'on en glisse un mot. On parle de réduire les risques de chute, mais ici encore je fais l'avocat du diable: le contexte du reste du travail est celui des maisons intelligentes; en quoi est-ce pertinent de savoir détecter du sable ou de la neige?

Bref, dans sa forme actuelle, je trouve que l'intro de ce chapitre lui donne l'impression d'être un peu parachuté. Je pense que les liens avec le reste de la thèse devraient être resserrés, pour qu'on sente bien qu'il répond aux objectifs annoncés et que son texte fait partie d'une progression dans l'argumentaire. Selon moi, cela inclurait:

- Reprendre mot pour mot quel l'objectif #1 de la section 1.6
- Expliquer qu'on répond à cette question en donnant un *exemple* précis de ce qu'on peut faire avec les wearables: détecter les types de sol (et dire pourquoi on a choisi ce problème)
- Expliquer immédiatement le lien avec la problématique générale de l'assistance
- Enchaîner avec le reste (que je trouve très bien)

## État de l'art

J'accroche sur deux choses au sujet de l'état de l'art ici: son emplacement et sa longueur.

D'abord, un évaluateur pourrait arguer que c'était la tâche du chapitre 2 de dresser l'état complet des lieux, sur tous les aspects où la thèse apporte une contribution. Bien sûr, on peut revenir plus tard sur des éléments pour en discuter, mais *introduire* une nouvelle partie d'état de l'art à cet endroit donne l'impression d'un problème dans la structure du texte. Par exemple, pourquoi ce qui est en 2.1 n'est pas une section "état de l'art" du chapitre 5? Je suis d'avis que si on choisit de structurer les concepts d'une certaine manière, il faut le faire uniformément.

Ensuite, je trouve que les travaux de cette section sont énumérés plutôt (trop) succintement. C'était compréhensible pour un article avec une limite de huit pages; or dans une thèse, expliquer en un court paragraphe un travail comme Otis 2016 (alors qu'il s'attaque au même problème que celui du chapitre), ça me semble insuffisant. D'autant plus qu'en comparaison, au chapitre 2, on passe beaucoup plus de temps à expliquer des concepts généraux d'apprentissage machine, alors que je les trouve plus éloignés du sujet que les références de la section 4.2. Une autre conséquence de cette brièveté, c'est que j'ai du mal à voir quel est le problème de ces approches que tente de résoudre la solution amenée ensuite en 4.3.

Pour le reste du chapitre, je n'ai rien à dire (à l'exception des quelques annotations manuscrites). Seul autre point: on pourrait se faire reprocher que la solution proposée n'a pas été comparée à l'état de l'art, alors qu'il existe bel et bien des comparables mentionnés en 4.2 --ce qui rend difficile d'apprécier le progrès réalisé. Ceci devrait être discuté à la fin du chapitre.

Chapitre 5
==========

Le chapitre 4 commençait en énonçant une question de recherche, faisant ainsi un lien avec les objectifs du chapitre 1. Par souci d'uniformité, le chapitre 5 devrait commencer de la même manière, et rappeler cette fois-ci (mot pour mot) la deuxième question de recherche de la section 1.6. Cette symétrie entre les chapitres ajoute à l'effet de cohérence.

Par contre, je ne vois pas vraiment de transition entre le chapitre 4 et le chapitre 5. Après avoir reconnu des types de sols avec succès, pourquoi se tourner vers l'architecture? Je pense qu'il manque un peu de texte "liant" avant 5.1, encore une fois pour renforcer la cohésion entre les parties de la contribution. Ce pourrait être aussi simple que de dire:

- Le chapitre 4 a montré concrètement l'utilité des wearables pour la reconnaissance et l'assistance
- Mais les architectures actuelles ne sont pas adaptées (et dire précisément en quoi), etc.

Ainsi, on rend plus évidente la progression logique de l'argumentation entre les chapitres.

Page 128, "Par ailleurs...": le paragraphe commence en disant que les architectures actuelles ne sont pas appropriées pour les wearable devices --fort bien. Par contre, ce qui suit ne critique pas les architectures elles-mêmes, mais plutôt le logiciel qui fait le traitement (pas modulaire, un seul langage de prog, etc.). Or, la réponse à cette critique est la contribution du chapitre *6*, et non 5. De la même manière, dans le paragraphe suivant, on parle de "déployer des composants logiciels [...] indépendants des langages ou des librairies". Encore une fois, ce n'est pas au chapitre 5 qu'on parle de cela, mais bien au chapitre 6. Par moments, on dirait donc qu'il s'agit de l'intro du mauvais chapitre qu'on est en train de lire. ;-)

Un indice: les expériences de la fin du chapitre devraient servir de confirmation à une affirmation annoncée au début du chapitre. Présentement, je ne vois pas cela. La section 5.3 vérifie la haute disponibilité de l'architecture; c'est donc un signe que ce dont on devrait parler en intro de chapitre est le manque de haute disponibilité des solutions existantes.

Ceci dit, un des reproches de la section 2.1, c'est le manque de support des solutions existantes pour les wearable devices. On s'attend donc à se faire expliquer, une fois la nouvelle architecture présentée, en quoi elle fait mieux que les autres sur ce point. Or, on vante sa haute disponibilité, mais on ne discute pas son adéquation au contexte des wearables. En fait, le mot wearable apparaît à la deuxième page du chapitre, et ensuite plus du tout jusqu'au chapitre suivant. Il y a donc une ficelle qui ne me semble pas attachée en termes d'argumentation.

Finalement, la fin de 5.1 dit que l'architecture est une *extension* de Plantevin 2018. Un membre du jury qui voit ce mot va s'attendre à une mention explicite de ce en quoi ton travail étend le précédent; comme il s'agit d'une contribution de ta thèse, il est important que la frontière entre l'existant et le nouveau soit évidente. J'ai trouvé une remarque à l'effet que "sa conception [de Valère] n'est pas adaptée aux environnements de recherche", mais ça reste assez vague. En fait, j'ai du mal à repérer un endroit dans le texte où on décrit clairement quelles parties de ton architecture sont identiques à celle de Valère, lesquelles sont différentes ou ajoutées, etc. Peut-être que de placer deux figures côte à côte serait pertinent. (Globalement, j'atténuerais cette idée de "continuité directe" avec les travaux de Valère partout dans le texte.)

Sinon, comme au chapitre 4, une fois le passage plus difficile de l'intro derrière soi, le reste du texte file tout droit et je n'ai que peu de choses à mentionner.

Chapitre 6
==========

C'est drôle, je trouve que le premier paragraphe de ce chapitre ferait une meilleure intro s'il était déplacé au chapitre 5! Ici on parle d'architecture, de la difficulté d'ajouter de nouveaux capteurs, etc.

Je vais répéter ici ce que j'ai dit pour les chapitres 4 et 5:

- On devrait se référer explicitement à l'un des objectifs de 1.6 (le troisième, en toute logique).
- J'aimerais voir une transition plus claire avec le chapitre précédent.

Je pense aussi qu'il faudrait mettre un peu plus d'effort pour vendre l'idée que le problème de modularité logicielle est spécifique à (ou du moins exacerbé par) la présence de wearable devices. Alors que les contributions des chapitres 4 et 5 ont un lien évident avec les wearables, celle du chapitre 6 me semble un peu vivre dans son monde. Ne pourrait-on pas désirer cette solution sans même vouloir utiliser les wearables?

Également, même commentaire que 4.2 à propos de 6.2, qui est elle aussi une section d'état de l'art à un endroit que je ne trouve pas approprié. Dans ce cas-ci, on parle d'une section quand même substantielle de près de 7 pages. Une solution facile serait de simplement déplacer 6.2 comme section du chapitre 2, et d'ajouter des bouts de texte de liaison appropriés.

Comme le principal objectif du workbench est la modularité, j'appuierais davantage en fin de chapitre sur le fait que le pipeline d'exemple fait interagir des composants écrits en JS, Go, et Python.

Conclusion
==========

Je trouve que la conclusion explique beaucoup plus clairement la cohérence entre les différentes parties de la contribution. En fait, on fait ici mention de liens que je n'ai pas vus avant dans le texte:

- Page 192, en bas: on dit que le cas pratique du chapitre 4 a permis d'identifier les lacunes des architectures existantes, motivant ainsi le développement de la solution (du chapitre 5). Or, je ne vois ni à la fin du chapitre 4, ni au début du chapitre 5, un inventaire explicite desdites lacunes, lesquelles auraient été découvertes grâce aux expériences qui ont été menées. (Voir mes notes sur le manque de transition entre 4 et 5.)

- "les différents types de sols peuvent représenter des dangers dans un habitat intelligent": OUI! --mais c'est un point qu'on aurait dû se faire expliquer au chapitre 4.

- les microservices permettent d'abstraire le type de capteurs avec lequel on fait les traitements, donc ils sont plus appropriés aux wearables: OUI! --mais encore une fois, il me semble que le chapitre 6 ne le dit pas aussi clairement que la conclusion.

Contrairement à ce que dit Sébastien, je pense qu'il ne faut pas de majuscules quand on dit "le chapitre X". :-P 