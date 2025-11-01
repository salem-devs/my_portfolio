
# Projet_1_Portfolio
Portfolio personnel présentant mes projets, compétences et expériences.  
Ce site est responsive et conçu avec HTML et CSS.

## Présentation

Ce portfolio contient :  
- Une **page d’accueil** avec présentation personnelle.  
- Une page **Projets** détaillant mes travaux réalisés.  
- Une page **CV** avec mon parcours et compétences.  
- Une page **Contact** avec formulaire et informations pour me joindre.  

Le design est **responsive**, adapté aux ordinateurs, tablettes et mobiles.

## Installation

1. Cloner le dépôt :  
```bash
git clone https://github.com/salem-devs/Projet_1_Portfolio.git

2. Aller dans le dossier du projet :
cd portfolio
3. Ouvrir index.html dans un navigateur pour visualiser le site.

## Technologies utilisées

HTML5, CSS3

Git & GitHub pour le versioning

Design responsive avec media queries et Flexbox/Grid

portfolio/
├── index.html
├── cv.html
├── projects.html
├── contact.html
├── tyle.css/
├── images/
│   └── (images de projets et portraits)
├── README.md

## LISTE DE COMMANDES

git clone https://github.com/salem-devs/Projet_1_Portfolio.git
  145  ls
  146  cd Projet_1_Portfolio
  147  ls
  148  echo "# Projet_1_Portfolio" >> README.md
  149  git init
  150  git add README.md
  151  git commit -m "premier commit"
  152  git branch -M main
  153  git remote add origin https://github.com/salem-devs/Projet_1_Portfolio.git
  154   git push -u origin main
  155  git log --oneline
  156  ls
  157  git switch -c develop
  158  git status
  159  git add index.html
  160  git commit -m "Integration de ma premiere structure html (index.html)"
  161  git push
  162  git push -u origin develop
  163  git status
  164  git add index.html
  165  git log --oneline
  166  ls
  167  cd  Projet_1_Portfolio
  168  git log --oneline
  169  git status
  170  git add index.html
  171  git commit -m "Creation du menu header"
  172  git log --oneline
  173  git status
  174  git add index.html
  175  git commit -m "Creation du contenu principale dans( main)"
  176  git status
  177  git add .
  178  git commit -m "Creation du contenu de pieds de page (footer)"
  179  git log --oneline
  180  git status
  181  git add style.css
  182  git commit -m "Ajout du premier style css dans le projet"
  183  git push
  184  git status
  185  git add .
  186  git commit -m "Ajout du style Responsive (la version mobile)"
  187  git status
  188  git add .
  189  git commit -m "Modification du style css"
  190  git log --oneline
  191  git status
  192  git add .
  193  git commit -m "Modification du html index"
  194  git status
  195  git add .
  196  git commit -m "Modification dela structure encore"
  197  ls
  198  cd Projet_1_Portfolio
  199  git log --oneline
  200  git push
  201  git log --oneline
  202  git status
  203  git add index.html
  204  git add style.css
  205  git commit -m "Deuxieme modification de la structure et du style"
  206  git switch -c branch_contact
  207  git status
  208  git add .
  209  git commit -m "Ajout de la page contact avec la nouvelle branche branch_contact "
  210  git log --oneline
  211  git status
  212  git add .
  213  git commit -m "Creation du formulaire contact"
  214  git switch develop
  215  git merge branch_contact
  216  git log --oneline
  217  git push
  218  git log --oneline
  219  ls
  220  cd Projet_1_Portfolio
  221  git log --oneline
  222  git branch
  223  git switch -c branch_cv
  224  git switch -c branch_projet
  225  git switch -c responsive
  226  git branch
  227  git status
  228  git add .
  229  git switch branch_contact
  230  git status
  231  git add .
  232  git commit -m "Integration du css dans la page contact"
  233  git switch responsive
  234  git status
  235  git add .
  236  git commit -m "Integration du responsive design dans contact.html avec la branche responsive"
  237  git log --oneline
  238  git push
  239  git branch
  240  git switch branch_contact
  241  git push
  242  git switch develop
  243  git merger branch_contact
  244  git merge branch_contact
  245  git merge responsive
  246  git push
  247  git log --oneline
  248  git branch
  249  git switch branch_projet
  250  git commit -m "Merge avec les autres branches"
  251  git switch branch_projet
  252  git status
  253  git add .
  254  git commit -m "Creation de la structutre complete de la page Projets.html"
  255  git switch responsive
  256  git switch branch_projet
  257  git log --oneline
  258  git status
  259  git add .
  260  git commit -m "Modification de la page projets.html"
  261  git commit --amend -m "Ajout du style css sur la page projets.html"
  262  git log --oneline
  263  git switch responsive
  264  git status
  265  git commit -m "Deuxieme modification du style css"
  266  git add .
  267  git commit -m "Deuxieme modification du style css"
  268  git switch responsive
  269  git status
  270  gid add .
  271  git add projets.html
  272  git status
  273  git commit -m "Ajout de reponsive design dans projets.html"
  274  git switch
  275  git switch develop
  276  git merge branch_projet
  277  git status
  278  git add .
  279  git commit -m "Ajout des images"
  280  git merge branch_projet
  281  git merge responsive
  282  git commit -m "merge avec branch_projet"
  283  git merge responsive
  284  ls
  285  cd Projet_1_Portfoli
  286  Projet_1_Portfolio
  287  cd Projet_1_Portfolio
  288  git log --oneline
  289  git switch branch_contact
  290  git branch
  291  git satus
  292  git status
  293  git add .
  294  git commit "Conflict reslu resolu"
  295  git commit -m "Conflict reslu resolu"
  296  git switch branch_contact
  297  git switch develop
  298  git log -oneline
  299  git log --oneline
  300  git push
  301  git switch branch_contact
  302  git push
  303  git status
  304  git branch
  305  git add .
  306  git commit -m "Modifications terminées sur branch_contact"
  307  git switch develop
  308  git merge branch_contact
  309  git switch branch_contact
  310  git log --oneline
  311  git switch develop
  312  git merge branch_contact --allow-unrelated-histories
  313  git cherry-pick 453c0b1
  314  git cherry-pick d055f72
  315  git push origin develop
  316  git satus
  317  git status
  318  git add .
  319  git commit -m "conflict resolu"
  320  git push
  321  git push origin develop
  322  git branch
  323  git switch branch_cv
  324  git log --oneline
  325  git switch develop
  326  git switch branch_projet
  327  git log --oneline
  328  git status
  329  git add .
  330  git commit -m "Modification encore"
  331  git push
  332  git switch develop
  333  git merge branch_projet
  334  git status
  335  git log --oneline
  336  git reset --hard HEAD~1
  337  git log --oneline
  338  git switch branch_projet
  339  git status
  340  git add .
  341  git commit -m "Modification du css de projets terminer"
  342  ls
  343  cd Projet_1_Portfolio
  344  ls
  345  cd Projet_1_Portfolio
  346  git switch develop
  347  git status
  348  git add .
  349  git commit -m "Modification du style et de la structure"
  350  git switch develop
  351  git merge branch_projet
  352  git branch
  353  git switch branch_cv
  354  git switch develop
  355  git switch branch_cv
  356  git add .
  357  git commit -m "Creation de la page cv.hmtl"
  358  git status
  359  git add .
  360  git commit -m "Integrtion du style css sur la page cv"
  361  git switch develop
  362  git merge branch_cv
  363  git commit -m "Conflit resolu avec branch_cv"
  364  git switch branch_contact
  365  git switch develop
  366  git merge branch_contact
  367  git push
  368  git pull origin develop --rebase
  369  git push origin develop
  370  git push origin develop:q
  371  git switch branch_contact
  372  git status
  373  git add .
  374  git commit -m
  375  git commit -m "modification css de la page contact"
  376  git switch develop
  377  git merge branch_contact
  378  git commit -m
  379  git commit -m "modification de style contact "
  380  git switch branch_contact
  381  git add .
  382  git commit -m "Modification encore"
  383  git switch develop
  384  git merge branch_contact
  385  git switch branch_projet
  386  git status
  387  git commit -m "Modification reussi"
  388  git add .
  389  git commit -m "Modification reussi"
  390  git switch develop
  391  git merge branch_projet
  392  git commit -m "Merge terminer aved branch_projet"
  393  git status
  394  git add .
  395  git commit -m "Arrangement"
  396  git switch branch_contact
  397  git push
  398  git status
  399  ls
  400  cd Projet_1_Portfolio
  401  switch branch develop
  402  git switch branch develop
  403  git branch
  404  git switch develop
  405  git switch branch_cv
  406  git switch develop
  407  ls
  408  cd Projet_1_Portfolio
  409  git switch branch_contact
  410  ls
  411  cd  Projet_1_Portfolio
  412  git switch develop
  413  git branch
  414  git switch branch_contact
  415  git switch develop
  416  git satus
  417  git status
  418  git add .
  419  git commit -m "Eregistrement "
  420  git merge branch_contact
  421  git staut
  422  git status
  423  git add .
  424  git commit -m "Modification reussi du style css de contact"
  425  git add .
  426  git commit -m "Retouche avec la branche develop"
  427  git status
  428  ls
  429  cd Projet_1_Portfolio
  430  git status
  431  git add .
  432  git commit -m "ajout des images de mes projets"
  433  git push
  434  git add .
  435  git commit -m "Modification du diviseur de footer"
  436  git push
  437  git pull origin develop --rebase
  438  git status
  439  git rebase --abort
  440  git pull origin develop --rebase
  441  git status
  442  git rebase --abort
  443  git pull origin develop --rebase
  444  git commit -m "fusion terminer "
  445  git checkout develop
  446  git log --oneline
  447  git branch temp-fusion 6408eb8
  448  git checkout develop
  449  git rebase --abort
  450  git status
  451  git branch
  452  git checkout develop
  453  git merge temp-fusion
  454  git status
  455  git add .
  456  git commit -m "Résolution du conflit dans style.css"
  457  git push origin develop
  458  git add .
  459  git commit -m "Ajout divider dans cv"
  460  git push origin develop
  461  history
