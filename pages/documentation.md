# Précis d'utilisation d'Anki

Anki est disponible gratuitement sur Windows, Linux, MacOS et Android. La version iOS est payante. Néanmoins, les révisions sont possibles gratuitement depuis n'importe quelle plateforme
via [ankiweb.net](https://ankiweb.net/about). De plus, nous recommandons la lecture de la [documentation officielle](https://apps.ankiweb.net/docs/manual.fr.html) pour explorer et comprendre
toutes les fonctionnalités. En tout état de cause, nous présentons ici le fonctionnement de façon succinte.

## Notations

La façon dont est rédigé le vocabulaire d'anglais reproduit strictement celle du manuel *The Big Picture*. Nous nous proposons d'en expliciter la forme :
- le slash **/** permet de distinguer différentes tournures. Par exemple : **a beautiful / pretty / graceful hat** appelle la traduction **un beau / joli / gracieux chapeau**.
- la virgule **,** permet de distinguer différentes traductions. Par exemple : **a thief, a robber** appelle la traduction **un voleur #2**. Notez ici la présence du **#2** qui indique que
lorsque je suis en présence du mot **voleur #2**, on attend de moi deux traductions en anglais. Même principe dans le sens contraire et/ou avec un plus grand nombre de traductions.
- Notez les abréviations courantes : **sb** pour **somebody**, **qn** pour **quelqu'un**, **sth** pour **something**, **qch** pour **quelque chose**.

## Paquet

À terme, le paquet **The Big Picture** contiendra tous les chapitres du manuel. En outre, chaque chapitre contiendra tout le vocabulaire et les idiomes. Les points de culture sont laissés à l'appréciation du lecteur.
Afin de savoir quels chapitres ont été tapés, référez vous à la page **Mises à jour** de l'accueil.

Le paquet contient des cartes. Le principe est de faire défiler des cartes, d'essayer de mobiliser la connaissance qui s'y trouve et de la restituer (mentalement). En fonction de votre degré de réussite
que vous estimez vous même sur quatres niveaux (à revoir, difficile, correct, facile), Anki classera les cartes et vous les fera revoir à intervalles différents. Il y a un code couleur, prenez note
de la correspondance anglaise : bleu (nouvelles cartes, **new**), rouge (en cours, **due**) et vert (à réviser, **review**).

Le premier jour vous aurez 30 cartes bleues (30 nouvelles cartes à apprendre). Durant la journée vous apprendez ces cartes mais vous ferez des erreurs, vous transformerez donc les cartes bleues en cartes rouges (en cours d'apprentissage). Et à la fin, vous transformerez ces cartes rouges en cartes sans couleur (tout le vocabulaire de la journée aura été appris). Dès le lendemain, une partie des cartes sans couleur
seront des cartes vertes (à réviser) et de nouvelles cartes bleues apparaîtrons, recommençant ainsi le cycle.

Distinguez bien la différence entre une **note** et une **carte**. Une note correspond à un couple de deux mots (anglais + français par exemple). Une carte correspond à ce couple **mais** dans un seul sens (anglais vers français par exemple). Une
note correspond donc à deux cartes. Notez que Anki compte en **cartes** principalement. S'il vous dit que vous avez 30 cartes à réviser, cela correspond à 15 mots de vocabulaire. Retenez cette nuance si vous souhaitez augmenter la quantité de vocabulaire à apprendre chaque jour.

## Paquet filtré

Puisque **The Big Picture** contient tous les chapitres, Anki vous les fera apprendre progressivement (par intervalles de 30 cartes/jour). Néanmoins, il peut s'avérer nécessaire de n'apprendre ou de ne réviser qu'un seul chapitre.

Mettons que vous vouliez réviser le vocabulaire de **Health_issues**.

Pour faire cela, sélectionnez le paquet **The Big Picture** puis **outils** et **créer un paquet filtré** (notez le raccourcis clavier F qui permet cela). Vous pouvez lui donner un nom, par exemple
"Apprentissage de Health_issues". Mettez une limite de carte suffisamment grande et dans **Chercher**, tapez la commande suivante `tag:The_big_picture::Lifestyles::Health_issues`.
Notez le début avec `tag:` qui permet de dire à Anki que nous allons chercher des cartes avec un tag spécifique. Faites attention aux majuscules, underscores et `::` qui séparent deux mots. La syntaxe
est cruciale.

Le principe reste le même pour réviser d'autres chapitres et d'autres sous catégories de chapitres. Encore une fois, référez vous à [l'index](index.md) qui reprend les notations des parties et chapitres.
Sur téléphone le principe reste analogue. Il faut sélectionner le paquet (par un appui long) et choisir **révisions personnalisées** et **se limiter à des tags particuliers**.

La création d'un paquet filtré va extraire des cartes du paquet d'origine.
Une fois que vous avez fini de réviser votre paquet filtré, vous pourrez continuer sa révision les jours suivants en faisant **reconstruire**. La supression d'un paquet filtré ne supprime pas les cartes
correspondantes : cela fait juste revenir les cartes au paquet d'origine. Finalement, un seul paquet filtré à la fois peut être créé. Il est nécessaire de supprimer l'ancien pour en faire un nouveau.

## Recommandations

Anki repose sur la **régularité**. Son objectif est de vous faire apprendre 30 cartes par jour (quota réglable) et de vous faire réviser toutes les cartes qu'il juge nécessaire ce même jour.
Travaillez et finissez chaque jour les cartes qu'il vous propose dans **The_big_Picture**. En parallèle, utilisez un paquet filtré pour vous préparer à une échéance. Une fois ce paquet filtré supprimé,
les "progrès" réalisés dans ce paquet sont automatiquement téléversé dans votre séance de révision du paquet principal. Prendre du retard détériorera le bon fonctionnement de l'algorithme avec votre mémoire.
Une utilisation **régulière** et assidûe d'Anki vous fera progressez notablement sans même que vous vous en rediez compte. De plus, le système d'apprentissage utilisé renforce la connaissance sur le long terme, évitant ainsi les méandres
du bachotage, souvent présent en cours de langue.
