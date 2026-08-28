---
title: Ressources pour les enseignants
# the default layout is 'page'
# icon: fas fa-info-circle
order: 3
lang: fr
page_id: resources
permalink: /ressources/
---

Si vous appréciez ces activités et souhaitez intégrer le codage dans votre classe, votre établissement ou votre district scolaire, nous serons heureux de partager avec vous ce qui a bien fonctionné pour nous et ce qui n’a pas fonctionné. Vous trouverez ci-dessous une brève description de chacun des outils numériques que nous utilisons, suivie de conseils sur leur mise en œuvre à différentes échelles.


# ** Les outils que nous utilisons**

### ** Python**

[Python][Python] est un langage de programmation couramment utilisé dans la recherche scientifique et la science des données. Vous avez peut-être entendu parler d’autres langages, tels que C++, Java, Fortran ou BASIC. Python a tendance à avoir moins de règles de syntaxe et de caractères supplémentaires, ce qui le rend plus lisible et compréhensible que certaines des alternatives. Cela signifie que les élèves peuvent souvent déduire ce que fait le code simplement en le regardant.

Comme nous nous concentrons principalement sur le contenu scientifique, ces activités n’enseignent pas explicitement la programmation. Si vous ou vos élèves souhaitez apprendre les boucles, les conditions, les fonctions et d’autres notions fondamentales de l’informatique, il existe sur Internet des tutoriels gratuits et de grande qualité. Consultez [Python.org][python-wiki], [Khan Academy](https://www.khanacademy.org/computing/computer-science), [DataCamp.com](https://www.datacamp.com/courses/intro-to-python-for-data-science) et la chaîne YouTube [Programming with Mosh][Mosh].

### ** Jupyter**

[Jupyter](https://jupyter.org/) est un logiciel qui vous permet d’écrire du code et d’effectuer des tâches utiles, comme ouvrir un fichier de données, effectuer des calculs et créer des graphiques. Nous l’utilisons comme vous utiliseriez un tableur, mais au lieu de saisir des données dans des cellules, vous saisissez les instructions (**le code**) permettant d’analyser et de visualiser les données. Les chercheurs et les informaticiens l’utilisent dans des organisations telles que le CERN, la NASA, IBM, Google et Microsoft. Les fichiers Jupyter sont appelés **notebooks**, et vous remarquerez peut-être que nous utilisons occasionnellement ce terme pour désigner nos activités.

Jupyter s’exécute dans une fenêtre de navigateur, ce qui le rend plus familier — et moins intimidant — que le terminal informatique vide que vous imaginez peut-être. Les notebooks affichent le code et les résultats du code (texte, tableaux, graphiques) dans la même fenêtre et peuvent inclure du texte mis en forme (gras, italique, différentes tailles de police), des hyperliens et des images, de sorte que les activités peuvent davantage ressembler aux supports pédagogiques avec lesquels les élèves interagissent habituellement.

La façon la plus simple d’exécuter nos activités est d’utiliser un service interactif en ligne comme Google Colaboratory, décrit ci-dessous. Si vous préférez installer Jupyter sur votre ordinateur afin d’exécuter les programmes « localement », téléchargez et installez [Anaconda](https://www.anaconda.com/products/individual). Il contient Jupyter, Python et tous les autres composants nécessaires au fonctionnement de votre ordinateur. Vous pouvez télécharger nos activités et nos données sur [GitHub du projet](https://github.com/adamlamee/CODINGinK12) en affichant un fichier, puis en cliquant avec le bouton droit sur « raw ».

### ** Colab**

Vous pouvez installer Jupyter localement sur votre appareil, mais pour les établissements scolaires K-12, l’installation de logiciels peut être difficile, voire impossible. [Google Colaboratory](https://colab.research.google.com/notebooks/basic_features_overview.ipynb), ou **Colab**, a révolutionné la façon dont nous utilisons les notebooks Jupyter avec les élèves et dans le cadre de la formation professionnelle des enseignants. Le seul inconvénient est qu’il nécessite un compte Google. Si votre établissement utilise Google Classroom, ce n’est pas vraiment un problème. L’exécution d’un notebook sur Colab est idéale pour les ordinateurs plus anciens, car elle n’utilise pas leur processeur pour effectuer les tâches les plus exigeantes. Comme avec Google Docs/Sheets/Slides, vous pouvez l’enregistrer sur votre Drive et le partager avec d’autres personnes, mais il ne prend pas en charge la modification simultanée par plusieurs utilisateurs.

### ** Alternatives à Colab**

Récemment, de nombreux districts scolaires ont commencé à ne plus autoriser Google Colab en raison de préoccupations liées à la confidentialité. Google Colab n’est actuellement pas intégré à leur plateforme éducative, même si nous espérons que cela changera à l’avenir. Si vous cherchez une alternative, voici quelques suggestions qui ont donné de bons résultats auprès d’autres enseignants.

- [Azure](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks?view=azureml-api-2): Si vous préférez utiliser un produit Microsoft, Azure vous permet d’exécuter et d’enregistrer nos notebooks dans le cloud à l’aide de votre compte Microsoft ou Outlook365. Nous avons peu utilisé ce service (en mai 2020), mais c’est une option si vous en avez besoin.

- [Binder](https://mybinder.org): Binder vous permet de transformer un dépôt Git en une collection de notebooks interactifs accessibles aux élèves sans qu’ils aient besoin de créer un compte. Nous avons commencé ce projet sur un serveur JupyterHub dédié, puis nous sommes passés à Binder. Ce projet n’aurait pas pu voir le jour sans l’équipe Binder.

- [GitHub Codespaces](https://github.com/codespaces): Si vous prévoyez de stocker tous vos notebooks dans un dépôt GitHub et que les élèves peuvent créer leur propre compte GitHub, Codespaces constitue un moyen intégré d’exécuter et de modifier les fichiers de notebooks. Chaque compte bénéficie gratuitement de 120 heures d’accès par mois. Les élèves peuvent créer un fork du dépôt de l’enseignant et leurs modifications seront enregistrées dans leur propre dépôt.

- [JupyterEverywhere](https://www.jupytereverywhere.org/): Une version de JupyterNotebook accessible sur le Web, sans compte, avec une interface simplifiée, ce qui la rend utile pour les élèves plus jeunes. Les enseignants peuvent téléverser un notebook et partager le lien avec la classe. Les élèves devront soit partager leur notebook terminé, soit en télécharger une copie afin de conserver leurs modifications.

- [JupyterLite](https://jupyter.org/try-jupyter/lab/): Une autre option sans compte permettant d’exécuter ces notebooks dans un navigateur. Elle peut être intégrée directement dans un [site Web](https://codinginK12.org/jupyterLite) à l’aide de GitHub Pages. Les notebooks fonctionnent bien avec cette solution, mais les élèves devront télécharger les fichiers modifiés pour enregistrer leurs changements.

- [Marimo](https://molab.marimo.io/notebooks): Cette solution nécessite que les élèves créent un compte, mais elle offre une interface similaire à Colab et fonctionne rapidement dans n’importe quel navigateur Web. Les modifications sont enregistrées dans le compte de l’élève, mais peuvent être téléchargées ou partagées avec l’enseignant.

### ** GitHub**

[GitHub](https://github.com/) est à la fois un espace de stockage dans le cloud, un outil de collaboration en équipe et un système de suivi des versions. Les programmeurs professionnels et les organisations l’utilisent pour héberger leur code et suivre qui a effectué quelle modification et à quel moment. Nous l’utilisons pour héberger nos notebooks et les fichiers de données qu’ils analysent. Colab possède une fonctionnalité très pratique qui nous permet de créer une URL ouvrant un notebook sur GitHub dans votre propre fenêtre Colab.

Les boutons « Open In Colab » font exactement cela.

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

# ** Conseils pour la mise en œuvre**

Utilisez nos activités telles quelles, modifiez-les et adaptez-les à vos élèves, ou laissez-nous travailler avec votre équipe. Nous pouvons vous aider à élaborer un plan de mise en œuvre adapté aux besoins et aux ressources de votre organisation. Nous avons une solide expérience dans la prestation de formations professionnelles de qualité et dans la planification stratégique à l’échelle des districts dans les domaines du codage, des sciences physiques, de la pédagogie renouvelée et de la littératie numérique. Planifiez une consultation à l’adresse <[adamlamee@gmail.com](mailto:adamlamee@gmail.com)>.

### ** Visez à toucher la majorité des élèves**

- Un cours dédié à l’informatique n’est peut-être pas la meilleure solution, en particulier pour les élèves dont les emplois du temps sont déjà chargés par des cours de soutien ou des cours optionnels. Les élèves qui prennent le bus ou qui ne disposent pas d’un autre moyen de transport peuvent également ne pas pouvoir participer aux clubs après les cours.

- Intégrer le codage aux cours obligatoires des matières fondamentales améliore l’équité et l’accès, quels que soient les antécédents ou les revenus familiaux des élèves. C’est pourquoi nos activités s’adressent aux enseignants des différentes disciplines. Elles portent principalement sur les sciences pour le moment, mais vous pouvez envoyer vos suggestions ou contribuer à une activité que vous avez créée en écrivant à <[adamlamee@gmail.com](mailto:adamlamee@gmail.com)>.

### **Obtenez leur soutien**

Les données et les témoignages peuvent aider à convaincre les élèves, les parents, les enseignants et les administrateurs de soutenir cette démarche. Voici quelques ressources que nous avons trouvées utiles :

- [What Most Schools Don’t Teach](https://www.youtube.com/watch?v=nKIu9yen5nc) vidéo de CODE.org présentant de nombreuses célébrités encourageant le développement du codage dans l’enseignement K-12

- [Pair Programming](https://www.youtube.com/watch?v=vgkahOzFH2Q) vidéo explicative de CODE.org

- [Ten quick tips for teaching programming](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006023) de PLOS

- [AAPT Recommendations for Computational Physics in the Undergraduate Physics Curriculum](https://www.aapt.org/Resources/upload/AAPT_UCTF_CompPhysReport_final_B.pdf)

- [Salaries and backgrounds](https://orlandodevs.com/blog/orlando-devs-salaries-2017) des programmeurs informatiques de Central Florida, avec l’aimable autorisation de [Orlando Devs](https://orlandodevs.com/)

### ** La formation est essentielle**

- Apprendre à utiliser les outils et comprendre comment le codage peut enrichir votre cours actuel demande du temps. Ce n’est pas comparable à l’apprentissage d’un nouveau logiciel de gestion des notes.

- Ne vous inquiétez pas du débogage du code ou de l’interprétation des messages d’erreur. En revanche, formez les enseignants jusqu’à ce qu’ils aient confiance en leur capacité à accompagner un élève en difficulté dans le processus consistant à annuler une modification, redémarrer l’environnement d’exécution (ou le noyau) et recharger une copie propre du notebook.

- La [déclaration de principe de la NSTA sur le développement professionnel](https://www.nsta.org/about/positions/profdev.aspx) constitue une excellente ressource pour préparer un atelier.

### **Faites-en quelque chose qui vous ressemble**

- Nos activités comportent peu de mise en forme supplémentaire ou de texte explicatif. Si vous préférez fournir à vos élèves des instructions plus détaillées, elles sont faciles à modifier pour changer la présentation, l’ordre des étapes, le type de questions, etc.

- Voir ce que [Seminole County](https://github.com/SCPSscience) et [Orange County](https://github.com/ocps-codes) ont créé pour leurs élèves peut vous donner quelques idées.

- Nos activités sont sous licence CC-BY-SA, ce qui signifie qu’elles sont gratuites à utiliser et à modifier à condition d’en mentionner la source. Consultez la page « About » pour obtenir le texte de la licence. N’hésitez pas non plus à nous écrire à <[adamlamee@gmail.com](mailto:adamlamee@gmail.com)>. Nous aimons savoir comment les enseignants adaptent nos activités.

### **Nourrissez les élèves les plus avancés**

Nos activités permettent aux élèves intéressés d’effectuer davantage d’analyses que ce qui est demandé dans les consignes, et nous sommes souvent étonnés par ce qu’ils parviennent à réaliser. Si cela ne suffit pas, essayez de leur proposer ces autres ressources gratuites (et extraordinaires) :

- [CERN Open Data](http://opendata.cern.ch/?ln=en) comprend des ressources pédagogiques sur la physique des particules et offre aux élèves (ainsi qu’au grand public) la possibilité d’accéder à des données authentiques du Large Hardon Collider et de les analyser. Oui, c’est plutôt génial.

- [Particle Physics Playground](http://particle-physics-playground.github.io/), créé par Matt Bellis, propose des exercices sous forme de notebooks Jupyter utilisant des données provenant des détecteurs de particules CMS et CLEO.

- Le travail de [Shawn Weatherford](http://www.phys.ufl.edu/~sweatherford/) sur vPython et Glowscript.

- [La chaîne YouTube Let’s Code Physics](https://www.youtube.com/channel/UCWBTKIyw-zX-2k63cB6qciQ)

- [STEM Coding](https://u.osu.edu/stemcoding/)

- [Les activités d’astronomie pour le lycée de Dimitrios Theodorakis](https://github.com/DimitriosAstro/Astronomy)

[Mosh]: https://www.youtube.com/watch?v=_uQrJ0TkZlc
[Python]: https://www.python.org/
[python-wiki]: https://wiki.python.org/moin/BeginnersGuide/Programmers
