Bienvenue, ceci est la source du site du Judo Club Broye. Vous trouverez quelques informations pour intéragir avec le site.

Pour modifier du contenu du site, je vous suggère d'utiliser prose.io. Dans tous les cas, un compte github est nécessaire. Pour plus d'information, contactez Christophe.

Pour modifier la liste des membres du comité, allez à http://prose.io/#judobroye/judobroye.github.io/edit/master/_data/members.yml

Pour modifier les évênements (vacances, tournois etc), allez à http://prose.io/#judobroye/judobroye.github.io/edit/master/_data/events.csv

Pour modifier la liste des entraînements, allez à http://prose.io/#judobroye/judobroye.github.io/edit/master/_data/trainings.yml

Pour ajouter ou modifier un article / une news, allez à http://prose.io/#judobroye/judobroye.github.io/tree/master/_posts 

Il existe un moyen simple pour créer une gallerie et l'inclure dans un article. Je vous conseille de copier ce qui a été fait pour le tournoi de Martigny. Pour se faire, il faut:
* ajouter des images
* modifier le fichier _data/gallery.yml (via prose par exemple) pour lister les images du point précédent
* dans un article, insérer la gallery comme suit: {% include gallery.html param=site.data.gallery.martigny variable-param=page.variable %}
* dans la ligne insérée, changer martigny pour le nom donné dans le fichier _data/gallery.yml
