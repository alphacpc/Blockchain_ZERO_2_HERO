# BLOCKCHAIN ZEO TO HERO

**Pourquoi devenir développeur blockchain ?**

* Secteur en plein boom, de plus en plus d'offres d'emplois :

    * Start-Ups
    * Grosses entreprises de la tech
    * Banques
    * Gouvernements
    * Entreprises et services
    
* Salaires
    * Start-Ups : 60k - 90K
    * Grosses entreprises : 90K - 180K

<br>

**Les prérequis**
* Savoir coder dans un langage comme Javascript, PHP, Python, C etc.
* Comprendre les principes de base de la cryptographie
* Comprendre les principes de la Blockchain

<br>

**Pourquoi la Blockchain**


Un fichier peut etre dupliqué lorsqu'il est transmis. En revanche, lorsque la quantité transférée est un actif numérique, il est important de s'assurer que celui qui transmet l'actif n'en garde pas une copie. C'est ce qu'on appelle le problème de la **DOUBLE DEPENSE**.Ce problème a été pour la première fois résolu par la Blockchain Bitcoin. En tout cas, à condition d'attendre la validation de 3-5 blocs et de s'assurer que la moitié de la puissance de calcul du réseau n'est pas détenue par un seul acteur. Ce problème doit etre absolument résolu pour toute blockchain afin de permettre le transfert de valeur correct d'un noeud à un autre.


* Supprimer les intermédiaires (Notaires, Avocats, Comptables etc.)
* Peut-on faire confiance aux intermédiaires ?

<br>

**Une révolution technologie**

* La Blockchain est une résolution technologie :
    
    * Transmission de valeur (Propriétés, voitures et autres biens) de façon sécurisée grace aux contrats intelligents.
    * Plus d'intermédiaires dans le processus de la vente.
    * Transfert d'argent rapide dans le monde entier.
    * Plus de capacité grace à ces milliers d'ordinateurs (noeuds) qui travaillent dans un meme réseau.

<br>

**Les domaines potentiels de la Blockchain**

* Droits digitaux
* Paris en ligne
* Marchés privés
* Marchés équitables
* Marchés dérivés
* Management de la dette
* Assurance maladie
* Micro-finance
* E-commerce
* Systèmes de paiement
* Elections (votes)
* Propriété intellectuelle

 <br>

 **QU'es ce que la Blockchain ?**

 * Blockchain = registre qui contient les transactions d'une monnaie virtuelle.
 * La Blockchain grandit lorsque l'on rajoute des blocs
    
    * Bloc: Ensemble horodaté et validé des transactions (crypto monnaie, contrats, données arbitraires). Les blocs sont liés les uns aux autres et forment la Blochain.

* Les transactions ajoutées sont traitées par des ordinateurs connectés au réseau (noeuds).
* Les blocs sont ajoutés au réseau en ordre chronologique.
* La Blockchain Ethereum permet d'y héberger des contrats intelligents avec l'Ether comme monnaie.
* La Blockchain est désignée de façon à etre durable et nn'est pas controlée par une entité. Chaque ordinateur est membre de cette communauté.


<br>

**Définitions**

Une blockchain est un registre distribué basé sur une architecture de données appelée chaine de blocs. Les transactions sont stockées dans des blocs qui sont chainés les uns aux autres d'où le nom blockchain. Un bloc contient, en plus de transactions, l'empreinte digitale du bloc précédent. La modification d'une transaction modifie donc  non seulement le bloc auquel il appartient mais l'ensemble des blocs qui le suivent. La structure en chaine de blocs confère au registre distribué son immutabilité. SOuvent, par abus de langage, on désigne par blockchain tout type de registre distribué et non seulement ceux qui sont basés sur une chaine de blocs.


Une Blockchain est déployée sur un ensemble d'ordinateurs? Chauque ordinateur constitue un noeud du réseau. On distingue habituellement les "noeuds complets" qui contiennent une copie complète de la blockchain et les "noeud légers" qui hébergent une version minimale de la blockchain leur permettant de participer aux échanges sur le réseau.

<br>

**Les mineurs**

* Hébergent une copie de la Blockchain
* Ajoutent de nouvelles liste de transactions (blocs) à la Blockchain
* Vérifient l'intégrité de la Blockchain
* Générent de nouveaux coins
* Exécutent les contrats intelligents

<br>

**Comment fonctionnent les transactions ?**

Le registre d'une blockchain est constitué de transactions. La transaction la plus simple est l'échange d'actifs numériques d'un noeud à un autre. Une transaction peut aussi se faire d'un noeud vers un contrat intelligent dans le cadre de l'exécution d'un contrat intelligent sur une blockchain programmable comme Ethereum.


Une transaction se fait entre deux **adresses** avec un certain montant. Voici les donnée d'une transaction:
    
    * From: [compte]
    * To: [compte]
    * Valeur: [integer] en Wei (1Ether = 10**10 Wei)
    * Gas: le montant maximal de gaz utilisé
    * gasPrice: le montant de Wei par gaz
    * Data: ABI string byte
    * Nonce: [integer] qui est incrémenté à chaque transaction pour évider les attaques de type replay


 <br>

 **La signature**

 La signature numérique d'un document garantit à la fois le contenu de ce document et ll'authenticité de la personne qui en est l'auteur. Pour cela, l'auteur prend une empreinte numérique du document (son hash) et le crypte avec sa clé privée. Ainsi, il suffit à la réception du document de décrypter avec la clé publique de l'expéditeur. L'empreinte numérique (garantie l'expéditeur) et la comparer à l'empreinte du document dont on veut vérifier l'authenticité (garantie du document). La signature numérique est utilisée systématiquement sur une Blockchain pour passer une transaction par exemple.

 
 La signature :

    * Est utilisé pour prouver la propriété d'une adresse sans exposé sa clé privé
    * Prover qu'il n'y a pas eu de falsification
    * L'algorithme utilisé est ECDSA (Elliptic Curve Digital Signature Algorithme)
        
        * Les signatures ECDSA se composent de deux nombres entiers: r et s.
        Ethereum utilise également une varibale v (identifiant de récupération) supplémentaire.
        * La signature peut etre noté {r, s, v}


<br>

**Clé privé / Clé publique**

Une clé est un terme issu de la cryptographie. C'est une chaine de caractères qui permet de signer, chiffer ou déchiffrer un message. On distingue en cryptographie les clés privées qui doivent etre gardées secrètes, des clés publiques qui peuvent etre divulguées à tous. Techniquement, la clé publique dérive par un calcul irréversible de la clé privée. Par exemple, la clé privée d'un utilisateur lui permet de transmettre un actif qui lui appartient à un autre noeud de la blockchain. Jusqu'à présent, quand des bitcoins ont été volés à leur détenteur, cela a été du à un vol de clé privée et non à une défaillance de la blockchain Bitcoin.

<br>

* Chaque compte dans le réseau Ethereum possède une clé privée et une clé publique
* Chaque compte Ethereum est représenté par une adresse qui est simplement un hash de la clé publique
* Les comptes peuvent utiliser leur clé privée pour signer une transaction, renvoyant une signature de cette transaction
* Tout le monde peut vérifier la signature générée pour récupérer la clé publique/l'adresse du signataire et vérifier l'intégrité du message qu'il s'agit du meme message qui a été signé par le signataire.
* Chaque clé privée est différente, c'est la clé à ne jamais communiquer
* La clé publique peut etre récupérée à partir de la clé privée.
* Une clé privée ne peut pas étre récupérée à partir de la clé publique
* Clé privée => Clé publique => Compte Ethereum

<br>

**Le Hashage cryptographie**

Le hash d'un fichier est une empreinte numérique de ce fichier. Techniquement, il s'agit d'une chaine de caractéres de longueur fixe calculée à partir du fichier par l'action d'une caractéristique du fichier, tout en ne permettant pas d'inférer le fichier à partir de son empreinte. La plupart du temps, pour des raisons à la fois d'espace mémoire et de confidentialité, seules les empreintes des données sont stockés dans la blockchain et non les données elle-memes.

*   La meme donnée donnera le meme sortie au niveau du hachage, on dit que c'est déterministe.
* La sortie est rapide à calculer
* Il n'est pas possible à partir de la sortie, de trouver l'entrée (sauf par Brute Force)
* Le moindre petit changement dans l'entrée va completement changer la sortie.


<br>

**Les contrats intelligents**

* Du bytecode stocké dans la Blockchain
* Rédigé dans un langage de très haut niveau : Solidity
* Compilé
* Exécuté dans l'EVM
* Le bytecode est déployé sur Ethereum dans une transaction (dans le champs "data" de la transaction)
* Une fois sur la Blockchain, impossible de modifier ou supprimer le contrat
* Il est accessible sur tous les noeuds à jour
* Pour interagir avec le contrat, il faut une machine virtuelle qui interprète le bytecode