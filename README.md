 # Tp1 
-En premier étape j’ai préparé mon environnement Git, j’ai commencé par la création du clé SSH ensuite j’ai l’ajouter dans le paramètre de mon compte GitHub. 

-En suite j’ai créé un nouveau repository et dans mon git Bash j’ai cloné mon projet sur mon pc. 

-Après j’ai commencé le travail, j’ai créé un fichier index.html qui contiens la phrase “Mon fichier main”, et j’ai valider mon premier commit après avoir ajouté le fichier au index, et pour visualiser l’effet de la commande git diff  j’ai créé une deuxième commit et j’ai modifier le texte du fichier index.html dans la deuxième commit par “hadil” et j’ai exécuter la commande git diff commit_id_1 commit_id_2 et le résultat c’est le mot hadil c’est la différence entre le texte du fichier index.html du premier commit et celui de la deuxième commit.  

-Dans la quatrième étape j’ai créé une nouvelle branche appelle “ma-fonctionnalite” et j’ai switcher le travailler sur cette brache après j’ai modifier le texte du fichier index.html par “Modification dans mon fichier hadil” et j’ai l’ajoute au index sans impact aucune modification sur le fichier du branche main, puis j’ai créé une commit sur cette branche et j’ai pusher dans mon repository a distant la même chose pour la branche main. 

-Le but de cette 5eme étape c’est de simulé un conflit en modifiant la même ligne dans deux branches différentes, puis j’ai fusionné les branches et j'ai résolve ce conflit.   

-Et finalement la dernière étape j’ai utilisé le GITFLOW pour automatiser le processus de synchronisation entre les branches. 
-l'historique des commandes:
$ history
    1  git clone git@github.com:HadilBenhasssen/Tp1gitHub.git
    2  cd Tp1gitHub/
    3  touch index.html
    4  echo "Hello world" > index.html
    5  git add index.html
    6  git add index.html
    7  git commit -m "Premier commit : ajout de index.html"
    8  git log
    9  git diff commit_id_1 commit_id_2
   10  git branch ma-fonctionnalite
   11  git checkout ma-fonctionnalite
   12  git add
   13  git commit -m "Modification de ma-fonctionnalite"
   14  git push origin ma-fonctionnalite
   15  git log
   16  git diff 5c1dc5314f3a70ad78cf552f9ddeda2b8fb741b4  b770d23234a9cb82ead9add6f618a4c35e089d81
   17  git log
   18  git diff 5c1dc5314f3a70ad78cf552f9ddeda2b8fb741b4  b770d23234a9cb82ead9add6f618a4c35e089d81
   19  git add .
   20  git log
   21  git diff 5c1dc5314f3a70ad78cf552f9ddeda2b8fb741b4 b770d23234a9cb82ead9add6f618a4c35e089d81
   22  git branch ma-fonctionnalite
   23  git checkout ma-fonctionnalite
   24  git commit -am "modification dans ma-fonctionnalite"
   25  get checkout master
   26  git checkout master
   27  git checkout main
   28  git commit -am "modification dans master"
   29  echo"modificatio du fichier">index.html
   30  echo "modificatio du fichier">index.html
   31  git commit -am "modification dans master"
   32  git checkout ma-fonctionnalite
   33  echo "modificatio du fichier">index.html
   34  git commit -am "modification dans master"
   35  git checkout master
   36  git checkout main
   37  echo "Hello world" > index.html
   38  git add .
   39  git add .
   40  git checkout main
   41  git commit -am "modification dans master"
   42  git add .
   43  git merge ma-fonctionnalite
   44  ssh-keygen -t ras -b 4096 -C hadil23342267@gmail.com
   45  ssh-keygen -t ras -b 4096 -C hadil23342267@gmail.com
   46  ssh-keygen -t rsa -b 4096 -C hadil23342267@gmail.com
   47  cat~/.ssh/id_rsa.pub
   48  ssh-keygen -t rsa -b 4096 -C hadil23342267@gmail.com
   49  cat~/.ssh/id_rsa.pub
   50  ssh-keygen -t rsa -b 4096 -C hadil23342267@gmail.com
   51  cat ~/.ssh/id_rsa.pub
   52  git config --global user.name "HadilBenHassen"
   53  git config --global user.email hadil23342267@gmail.com
   54  ssh -T git@github.com
   55  git clone git@github.com:HadilBenhasssen/Tp1gitHub.git
   56  git clone git@github.com:HadilBenhasssen/Tp1gitHub.git
   57  git clone git@github.com:HadilBenhasssen/Tp1gitHub.git
   58  ssh -T git@github.com
   59  cd ▒
   60  ls
   61  cd ..
   62  ls
   63  cd C:\Users\HP\Documents
   64  ls
   65  cd ..
   66  ls
   67  explorer
   68  explorer .
   69  git config --global user.name "HadilBenHassen"
   70  git config --global user.email hadil23342267@gmail.com
   71  ssh -T git@github.com
   72  git clone git@github.com:HadilBenhasssen/Tp1
   73  git clone git@github.com:HadilBenhasssen/Tp1
   74  cd Tp1gitHub
   75  cd Tp1gitHub
   76  git config --global user.name "hadilbenhassen"
   77  git config --global user.email hadil23342267@gmail.com
   78  ssh -T git@github.com
   79  git clone git@github.com:HadilBenhasssen/Tp1
   80  cd Tp1
   81  touch index.html
   82  echo "Mon fichier main" > index.html
   83  git add index.html
   84  git add index.html
   85  git commit -m "Premier commit : ajout de index.html"
   86  git log
   87  echo "hadil" > index.html
   88  git add index.html
   89  git add index.html
   90  git commit -m "Premier commit : ajout de index.html"
   91  git log
   92  git diff 2b6ffec70866ff4b2b18d48e9405f025477f368c 19993bd2a344257b6a2ba90327278d82caf81858
   93  git branch ma-fonctionnalite
   94  git checkout ma-fonctionnalite
   95  echo "Modification dans mon fichier hadil" > index.html
   96  git add .
   97  git add .
   98  git commit -m "Modification de ma-fonctionnalite"
   99  git push origin ma-fonctionnalite
  100  git push origin main
  101  git checkout ma-fonctionnalite
  102  echo "Modification de merge dans mon fichier hadil" > index.html
  103  git commit -m "Modification de ma-fonctionnalite"
  104  git commit -am "Modification dans ma-fonctionnalite"
  105  git push origin ma-fonctionnalite
  106  git checkout main
  107  echo "Modification de merge dans mon fichier hadil" > index.html
  108  git commit -am "Modification dans main"
  109  git push origin main
  110  git merge ma-fonctionnalite
  111  git add .
  112  git commit -m "Résolution du conflit"
  113  git commit -m "Résolution du conflit"
  114  git flow init
  115  git flow feature start ma-fonctionnalite
  116  git flow init
  117  git flow init
  118  git flow init
  119  git flow init -f
  120  git flow feature start ma-fonctionnalite
  121  git flow release start ma-version
  122  git flow feature finish ma-fonctionnalite
  123  git flow hotfix start mon-correctif
  124  history
