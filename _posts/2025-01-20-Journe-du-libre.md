# C'est quoi le libre

Le **logiciel libre** est une philosophie et un modèle de développement informatique qui permet aux utilisateurs de :
1. **Exécuter le programme** comme ils le souhaitent, pour n'importe quel usage (liberté 0).
2. **Étudier et modifier** le code source pour comprendre comment il fonctionne ou l'adapter à leurs besoins (liberté 1).
3. **Redistribuer des copies** du programme pour aider les autres (liberté 2).
4. **Distribuer des versions modifiées** du programme pour faire bénéficier toute la communauté des améliorations (liberté 3).
### Origines et histoire
**Xerox et le MIT** :  
Dans les années 1980, des chercheurs du MIT, notamment Richard Stallman, se heurtent à des limitations imposées par des entreprises comme Xerox. Ils souhaitent accéder aux codes sources pour développer ou améliorer des pilotes d'imprimantes, mais les entreprises refusent de partager ces informations.

**Création de GNU** :  
Frustré par cette situation, Richard Stallman lance le projet GNU en 1983. Son objectif : créer un système d'exploitation libre et un ensemble d'outils libres. GNU est un acronyme récursif pour "GNU's Not Unix". L'idée est de reproduire les fonctionnalités d'Unix, mais avec un modèle entièrement libre.

**Manque d’un noyau libre** :  
À la fin des années 1980, le projet GNU avait déjà développé de nombreux outils essentiels (éditeur Emacs, compilateur GCC, etc.), mais manquait d’un noyau fonctionnel pour former un système complet.

**Naissance de Linux** :  
En 1991, Linus Torvalds, alors étudiant, crée un noyau compatible avec Unix : **Linux**. Ce noyau, couplé avec les outils GNU, forme un système d'exploitation complet et libre, souvent appelé **GNU/Linux**.

### Couple GNU et Linux :
- GNU fournit les **outils** (compilateurs, bibliothèques, shell, etc.).
- Linux fournit le **noyau** (le cœur qui gère les ressources matérielles et logicielles).

Ce mariage a donné naissance à un écosystème immense, comprenant des distributions comme Debian, Ubuntu, Fedora, et bien d'autres, qui incarnent les idéaux de liberté logicielle.

Aujourd'hui, le mouvement du logiciel libre inspire aussi des initiatives dans d'autres domaines, comme les données ouvertes, le matériel libre, et les licences Creative Commons pour la culture et le savoir.

### Autre logiciels, protocoles et concepts liés au libre existant
- **GIT pour le versionnage :**
    - **Git** est un système de contrôle de version créé par Linus Torvalds en 2005 pour gérer le développement du noyau Linux.
    - Il est **libre** (sous licence GPLv2) et décentralisé, permettant à plusieurs développeurs de collaborer sur un projet tout en gardant l'historique des modifications.
    - Il a popularisé des plateformes comme GitHub et GitLab (qui peuvent être libres ou propriétaires selon les versions).
- **Linux et son adoption :**
    - **Linux** domine les serveurs avec environ **80 % de part de marché** grâce à sa stabilité, sa flexibilité et son coût nul.
    - Sur le marché de la bureautique, Linux avait moins de **1 %** d’utilisateurs jusqu’à des initiatives comme **Ubuntu (2004)**, qui a rendu Linux plus accessible. Aujourd’hui, environ **5 % des ordinateurs de bureau** utilisent Linux.
    - Les distributions comme Fedora, Debian et Mint ont également contribué à une adoption plus large.
- **Fediverse et protocoles libres de réseaux sociaux :**
    - Le **Fediverse** est un ensemble de réseaux sociaux décentralisés interopérables basés sur des protocoles libres comme **ActivityPub**.
    - Exemples de plateformes :
        - **Mastodon** pour la microblogging (alternative à Twitter/X).
        - **PeerTube** pour le partage de vidéos (alternative à YouTube).
        - **PixelFed** pour les images (alternative à Instagram).
    - Ces outils mettent en avant la décentralisation, la vie privée, et la propriété des données par les utilisateurs.
### Usage du libre
- **Décentralisation :** Les outils libres évitent les monopoles en permettant à chacun d’héberger ses propres services.
- **Interopérabilité :** Les formats ouverts et standards garantissent une communication entre différents outils et plateformes.

### Besoins autour du libre
1. **Information et sensibilisation**  
    Beaucoup de gens ignorent les avantages du libre ou n’en comprennent pas l’importance (liberté de choix, indépendance des monopoles, respect de la vie privée).
2. **Formation**
    - Enseigner les outils libres comme LibreOffice, GIMP, Inkscape, etc.
    - Initier à des concepts comme Git, le Fediverse, ou le développement collaboratif.
3. **Suivi et support**
    - Fournir un accompagnement aux entreprises et aux particuliers pour migrer vers des solutions libres.
    - Développer des tutoriels, forums, et centres d’entraide pour encourager l’adoption.
### Libre vs Gratuit
Un **logiciel libre** (free as in freedom) n’est pas forcément gratuit (free as in free beer). La distinction clé repose sur les **libertés fondamentales**, pas sur le prix :
- **Libre** : Le code source est ouvert, modifiable, redistribuable. Exemples : Linux, LibreOffice, GIMP.
- **Gratuit** : Un logiciel peut être gratuit sans être libre. Exemples : Skype, Zoom (gratuits, mais propriétaires).

Certains logiciels libres sont vendus (avec un service ou un support), mais restent libres, car leurs libertés fondamentales sont garanties.

# Déploiement du libre dans les écoles et autres institutions d'état
### Sécurité informatique et outils libres 
- **Firewall et routage libre**
    - Outils comme **PFSense** (pare-feu et routeur basé sur FreeBSD) sont des alternatives robustes et libres pour sécuriser les réseaux.
    - Limites : Ces solutions demandent une expertise pour l'installation, la configuration et le suivi, et dépendent fortement de la communauté pour les mises à jour et le support.
2. **Exemples d'initiatives**
    - **Base Amon** :  
        Maintenue par l’académie de Dijon, cette solution libre pour la sécurité des réseaux scolaires montre l'efficacité du libre dans des contextes spécifiques.
        - Inconvénients : Maintenance et déploiement complexes nécessitant une formation et un suivi, comparé à des solutions propriétaires comme Fortinet.
    - **Ministère de l’Agriculture :**  
        Utilise des solutions libres en se portant garant, prouvant que le modèle fonctionne si des responsables techniques sont identifiés.
3. **Défis spécifiques**
    - **Machines multiples :** Les logiciels libres doivent être optimisés pour fonctionner sur un parc informatique varié, parfois vieillissant.
    - **Retour au propriétaire :** Les institutions reviennent souvent vers des solutions payantes pour leur simplicité (support, mises à jour automatiques, gestion centralisée). Cela limite la souveraineté et l'autonomie.

### Inconvénients du libre dans les institutions
- **Dépendance à la communauté**
    - Le développement et la maintenance reposent sur la communauté, ce qui peut entraîner des délais si celle-ci est petite ou inactive.
    - Contrairement aux entreprises, les communautés libres manquent parfois de garanties ou de support contractuel.
- **Formation et adoption**
    - Les utilisateurs, dès leur formation, sont souvent exposés à des solutions propriétaires (Microsoft, Adobe, etc.), créant une dépendance à long terme.
    - Passer au libre demande un effort d'apprentissage, mais aussi une adoption collective pour garantir l’interopérabilité dans les équipes.
- **Options limitées**
    - Certaines fonctionnalités avancées disponibles dans les logiciels propriétaires ne sont pas toujours présentes dans les outils libres.
    - Exemple : Des institutions peuvent revenir à des solutions comme Microsoft Office pour des options spécifiques non couvertes par LibreOffice.
- **Manque de support direct**
    - Les systèmes de tickets et les supports communautaires sont perçus comme impersonnels et longs, surtout dans des contextes critiques.
- **Fragmentation et hétérogénéité**
    - Adoption inégale du libre selon les académies ou institutions, compliquant la standardisation au niveau national.
    - Exemple : Les listes de sites bloqués varient, avec des solutions allant de systèmes massifs américains à des installations locales artisanales.

### Conséquences structurelles et sociétales
- **Cout des logiciels propriétaires**  
    Les licences des logiciels privés entraînent des dépenses énormes pour les institutions, qui auraient pu être investies dans la formation et l’amélioration des solutions libres.
- **Renouvellement matériel**
    - Les institutions suivent souvent un cycle de renouvellement rapide des équipements, rendant difficile le réemploi ou l'adaptation des anciens matériels à des outils libres.
    - Une meilleure gestion du cycle de vie des équipements permettrait de maximiser leur utilisation avec des solutions moins gourmandes.
- **Écosystème global**
    - Les grandes entreprises, en fournissant gratuitement leurs logiciels aux écoles, créent une **dépendance dès le plus jeune âge**. Cela limite l'ouverture vers d'autres solutions et renforce leur monopole.

### Suggestions pour un déploiement efficace du libre
- **Formation des utilisateurs**
    - Mettre en place des programmes de formation au libre dès l'école pour habituer les élèves à des outils comme LibreOffice, GIMP ou Inkscape.
    - Former également les enseignants et le personnel administratif pour garantir une transition fluide.
- **Responsabilité locale et nationale**
    - Nommer des garants dans chaque institution pour le suivi des solutions libres.
    - Créer un cadre national uniforme pour éviter les disparités régionales.
- **Promotion et incitations** 
    - Subventionner ou récompenser les écoles et administrations qui adoptent le libre pour encourager la transition.
    - Fournir des équipements adaptés et optimisés pour les logiciels libres.
- **Renforcer les communautés libres**
    - Soutenir financièrement et logistiquement les projets libres critiques pour garantir leur pérennité.
    - Collaborer avec des acteurs du libre pour développer des solutions spécifiques aux besoins institutionnels.
- **Interopérabilité et standardisation**
    - Favoriser les formats ouverts et les protocoles standards pour éviter le verrouillage technologique.
    - Encourager des solutions décentralisées et transparentes comme le Fediverse pour les communications.

# La publication et l'écriture dans le libre

#### **Alternatives libres aux logiciels propriétaires**

**Pourquoi payer pour un logiciel propriétaire ?**
    - **LibreOffice** est une alternative gratuite et libre à Microsoft Office. Il permet de créer, modifier et exporter des documents dans différents formats, y compris DOCX et PDF.
    - Le passage au libre nécessite souvent une **formation** ou un accompagnement, mais les coûts économiques et éthiques à long terme sont avantageux.

**Outils pour l'écriture et la publication**
- **Joomla** : Pour créer et gérer des sites web (similaire à WordPress).
- **Notepad++** : Éditeur de texte léger, surtout pour le code et des petits projets d'écriture.
- **NotepadQQ** ou **Sublime Text** : Alternatives puissantes, souvent utilisées pour le développement et les projets complexes.
- **Sigil** : Un outil pour créer des livres numériques au format EPUB.
- **Scribus** : Pour des mises en page professionnelles en publication assistée par ordinateur (PAO), notamment le passage de RVB (écran) à CMJN (impression).
- **GIMP** : Pour le traitement d’images, avec des fonctions avancées comme le passage manuel de RVB à CMJN (bien que laborieux).
- **Ghostscript** : Outil en ligne de commande pour convertir et traiter des fichiers PostScript et PDF.
- **Calibre** : Une bibliothèque numérique libre qui convertit des formats comme DOCX, EPUB et PDF, et permet une gestion efficace des fichiers.

#### **Défis du libre dans la publication**

**Barrière de l’installation et de la formation**
    - Les outils libres sont parfois perçus comme complexes, mais cette difficulté est souvent liée à un manque de communication ou de sensibilisation.
    - **Solution :** Développer des guides pratiques, simplifier les processus d'installation et encourager l'accompagnement.
    
**Problèmes techniques et logistiques**
    - Conversion des couleurs (RVB → CMJN) avec des outils comme Scribus ou GIMP peut être difficile pour les non-initiés.
    - **QR codes** dans les œuvres : bien que pratiques pour enrichir une œuvre (liens vers des explications, vidéos, etc.), ils sont perçus comme intrusifs et nécessitent une réflexion graphique et technique pour une meilleure intégration.
    - Archivage et pérennité : les contenus associés aux QR codes doivent être maintenus sur des plateformes stables pour éviter les pertes d'informations. Des solutions comme **archive.org** peuvent aider, mais ne suffisent pas toujours.
    
**Problèmes économiques et environnementaux**
 - Les fichiers lourds (pour les livres numériques augmentés avec photos ou vidéos) peuvent être coûteux à héberger ou incompatibles avec certaines liseuses.
- Les impressions couleur restent chères, limitant les illustrations dans les livres papier.
- Les impressions locales, bien que souvent plus humaines et éthiques, sont parfois difficiles à trouver ou imposent des frais pour vérifier et corriger les fichiers.

#### **Avantages du libre dans la publication**

**Souveraineté et liberté**
- L'autoédition avec des outils libres permet de garder le contrôle sur son œuvre et de s'affranchir des géants comme KDP (Amazon).
- L’usage de licences libres (comme **CC0**, **CC BY-NC**) donne une liberté d’utilisation et de partage tout en protégeant les droits des créateurs.
- L'autoédition permet de ne pas rester bloquer dans un genre (de roman ou de type d'oeuvre ou de genre littéraire) + avoir les droits de liberté d'expression

**Flexibilité et autonomie** 
- Les logiciels libres permettent une personnalisation approfondie et une indépendance des standards imposés par les éditeurs propriétaires.

**Économies**
- En supprimant les coûts de licence, les outils libres réduisent les dépenses pour les créateurs et éditeurs.
#### **Enjeux sociaux et culturels**

**Mindset à changer**
 - Les habitudes d’apprentissage sur des logiciels propriétaires limitent la capacité à explorer des alternatives.
- L’adoption du libre demande un changement de mentalité et une approche collaborative.
- Les process sont pensés différement, mais pas plus dificile
- Linux s'adapte mieux à l'utilisateurices, mais comme on a apprit d'une façon, on perçoit moins les solutions à nos pbs

**Impact des standards**
 - Les normes typographiques et de mise en page, bien qu’utile pour la lisibilité, peuvent être un frein inutile. Le libre encourage une simplification des processus tout en respectant les bonnes pratiques.
 
**Communauté et partage**    
- L'esprit communautaire dans le libre est crucial pour développer et maintenir les outils. Il s'agit d'une **philosophie collaborative**, favorisant l’entraide plutôt qu’une consommation passive.
- Avec adobe ou autre logiciel libre, ça matrixe les cerveaux donc tu perds pas mal de tes libertés de faire

**Formation**
- Introduire des outils libres dès l'école pour contrer l'impact des géants propriétaires qui "capturent" les utilisateurs dès leur jeunesse.
- Passer du proprio au libre, finalement c'est simple et des barrières invisibles juste parce que peu de communication autour
- C'est aussi dur d'entendre le nom du logiciel libre, donc si on découvre pas on peut pas y passer

**Promotion du libre**
- Créer des campagnes de sensibilisation sur les alternatives libres pour l’écriture et la publication.
- Faciliter l'accès aux outils libres en mettant en avant leurs bénéfices pratiques et économiques.

**Soutenir l’impression locale** 
 - Encourager l’impression chez des imprimeurs locaux pour des tirages à petite échelle, souvent plus compétitifs que les solutions des géants.
 - (sans compter l'aspect humain de la chose)
 - Sans FDP si on va chercher directement chez l'imprimeur, ça limite les frais
 
  **Développer des ressources en français**
- La documentation et les tutoriels sont souvent en anglais, ce qui limite l’accessibilité pour les francophones.

**Convergence avec le matériel**
 - Standardiser et démocratiser les claviers ergonomiques (par exemple, le **bépo**, qui facilite la frappe en français avec des majuscules accentuées) pour simplifier l’usage des outils d’écriture libre.
 - Soucis: tu changes de PC (chez un pote, une entreprise ou autre), t'as pas les mêmes clavier
# Numérique éducatif et le libre

#### **Outils éducatifs libres et open source**

**Scratch
 - Développé par le MIT, Scratch est une plateforme open source qui permet aux enfants de s'initier au **codage par blocs**, une approche visuelle et intuitive.
 - Accessible dès le plus jeune âge, Scratch pose les bases de la logique algorithmique sans nécessiter de compétences en programmation textuelle.

**Raspberry Pi**
- Mini-ordinateur polyvalent et économique, idéal pour des projets connectés ou des initiations à la programmation.
 - Compatible avec des langages comme Python et largement utilisé dans l’éducation et les projets DIY.
 
**BBC Micro:bit**
- Plus petit et plus accessible que la Raspberry Pi, il est conçu pour l’apprentissage initial avec des blocs de programmation.
- Comprend un petit écran LED et des capteurs, parfait pour introduire l’électronique et l’informatique aux débutants.

**Robot Timeo (?) et similaires**
 - Ces robots simplifient l’apprentissage de la robotique et de la programmation, combinant électronique et codage ludique.
 - Ils s’intègrent souvent dans des programmes éducatifs pour développer des compétences STEM.
 
**Importance des communautés libres**
 - La documentation et les ressources partagées par les communautés permettent de démocratiser l’accès aux outils et de résoudre les problèmes rapidement.
 - Exemple : les forums autour de Raspberry Pi ou Scratch regorgent de tutoriels pour accompagner enseignants et élèves.

#### **Enjeux éducatifs et sociétaux**

**Formation au sens critique**
- Avec l’accès massif à Internet, apprendre à **vérifier les informations** et à exercer un regard critique est essentiel.
 - Les communautés comme Wikipedia montrent l’efficacité d’un modèle où les contributions sont contrôlées par un collectif, mais cela demande un équilibre pour éviter un contrôle excessif qui pourrait restreindre la liberté d’expression.
 
**Rôle de l’éducation populaire en informatique**
 - **Démystifier l’informatique pour tous :** développer des programmes éducatifs qui expliquent les bases de la logique, des systèmes et des technologies.
 - **Passer de consommateur à utilisateur actif :** Enseigner comment les outils fonctionnent pour encourager une appropriation autonome.
 
**Nocode et ses limites**
 - Les outils "nocode" simplifient les tâches techniques, mais masquent la logique sous-jacente.
 - Problème : Quand un système tombe en panne, peu de gens savent le réparer, entraînant une dépendance accrue aux spécialistes ou aux entreprises tierces.
 
 **Langue et intercommunication**
  - L’exposition aux outils numériques, souvent en anglais, aide les apprenants à développer des compétences linguistiques, essentielles pour la collaboration et l’université.
  - La documentation bilingue (français/anglais) doit être encouragée pour surmonter les barrières linguistiques.
  
**Sécurité informatique**
 - La sensibilisation aux notions de sécurité dès le plus jeune âge (gestion des mots de passe, protection des données personnelles) est cruciale dans un monde connecté.
#### **État actuel et défis du numérique éducatif :**

**Retard éducatif en informatique**
- Bien que des progrès soient visibles, nous avons environ **25 ans de retard** dans l’éducation numérique par rapport aux besoins actuels.
- Ce retard est particulièrement perceptible pour les personnes non initiées, pour qui l'informatique reste abstraite.

**Éducation coûteuse mais essentielle**
- L’accès à l’informatique aide les élèves à développer des compétences fondamentales transférables (logique, rigueur, résolution de problèmes).
- Avec le **droit d'écriture numérique** accessible à tous, la transmission d’informations est facilitée et gratuite grâce au rôle du libre.

**Accessibilité pour tous**
  - L’objectif est de rendre les outils numériques et leurs logiques accessibles sans coûts prohibitifs, tout en limitant les inégalités d'accès


#### **Avantages des outils libres en éducation :**

**Économies**
- Les logiciels libres comme Scratch, LibreOffice ou GIMP éliminent les coûts de licences souvent élevés dans l’éducation.

**Souplesse et personnalisation**
 - Les outils libres permettent d’adapter les programmes éducatifs aux besoins locaux, sans dépendre d’un fournisseur unique.
 
**Encouragement à l’autonomie**
- En apprenant à documenter et à maintenir leurs projets, les élèves acquièrent une compréhension plus profonde et des compétences transférables.

 **Communautés actives
  - Les enseignants et élèves bénéficient de forums et de ressources créés par des utilisateurs du monde entier, enrichissant les approches pédagogiques.

### Propositions pour améliorer le numérique éducatif :

 **Inclure le libre dès le début
 - Introduire Scratch, Raspberry Pi, et d'autres outils libres dans les cursus dès l’école primaire.
 - Former les enseignants à ces outils pour les intégrer efficacement dans leurs pratiques pédagogiques.
 
**Mettre l’accent sur la logique et la sécurité**  
  - Avant d’enseigner des outils spécifiques, insister sur la logique informatique et les notions de sécurité pour bâtir des bases solides.
  
**Créer des ressources accessibles
 - Traduire et adapter la documentation en français pour encourager une adoption plus large.
.
# Alternative libre connu


![image](/assets/img/2025-01-20-Journe-du-libre/th-1953955382.jpg)