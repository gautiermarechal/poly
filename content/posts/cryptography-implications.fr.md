---
title: "La cryptographie et ses implications dans le passé, le présent et le futur"
date: 2021-03-24T23:36:38+02:00
cover:
  image: "/images/cryptography-implications/cryprography-0.jpeg"
  alt: "Cryptography"
  caption: "Antique keys"
  relative: false
categories:
  - Cryptographie
  - Bitcoin
  - Informatique
  - Science
---

Le succès humain sur la planète a été rendu possible grâce à notre capacité à communiquer dans le but de résoudre des problèmes complexes en groupe. Cependant, certains groupes ne se sont pas toujours entendus, provoquant de multiples conflits qui ont façonné notre histoire. La cryptographie s'est révélée être un outil permettant de rendre la communication entre deux parties secrète pour toute autre partie. Cet outil a été bien plus important que nous ne le pensons, et nous explorerons comment il a façonné l'histoire dans le passé, le présent et le futur. Dans un monde où les entités gigantesques et les gouvernements sont de plus en plus présents dans la vie quotidienne des individus, la sécurisation des données avec la cryptographie sera un outil essentiel à utiliser.

La cryptographie existe depuis des milliers d'années.

La première forme de cryptographie a été observée dans l'Égypte ancienne sur les murs des tombes en 1900 av. Des symboles inhabituels ont été gravés sur la tombe de Knumotep II pour confondre le lecteur et renforcer le mystère.

De plus, en 5 avant JC, les spartiates ont créé un dispositif cryptographique appelé Scytale. L'outil était un bâton enveloppé d'un morceau de cuir portant le message. Il n'était lisible que lorsqu'il était enroulé sur ce cylindre de diamètre particulier permettant aux lettres de s'aligner. Le destinataire du message avait besoin d'exactement le même diamètre de Scytale pour déchiffrer le message.

![Spartan Scytale](/images/cryptography-implications/cryptography-1.png "Spartan Scytale")

Un autre excellent exemple est le chiffre de César (ou Cesar Cipher en anglais), du nom de l'empereur qui a créé cette technique pour communiquer secrètement durant une époque de tension au sein de l'empire. La technique est connue sous le nom de **substitution**, consistant à remplacer chaque lettre par une autre que seul le destinataire connaît.

![Chiffre César](/images/cryptography-implications/cryptography-2.png#center "Chiffre César")

Il existe de multiples autres exemples historiques de cryptographie utilisés dans le monde antique, qui permettaient aux interactions de rester secrètes entre deux parties.

Au cours de l'histoire, la cryptographie a souvent été utilisée par les monarques ou les empereurs au pouvoir pour communiquer en interne. Les cryptages de communication étaient souvent dédiés à la planification militaire ou à tout écrit religieux. Jules César a utilisé son célèbre chiffre pour organiser des stratégies avec ses généraux. Les papyrus magiques grecs de 100 avant notre ère contenaient des rituels, des hymnes et des sorts écrits dans une langue spécifique contenant du grec ancien qui était impossible à lire pour un lecteur non averti. La création de messages cryptés visait à garder les secrets de communication au sein des groupes et à former l'exclusivité pour les membres du groupe. Les chiffres n'étaient connus que par ses membres.

Cependant, dans les années 700, Al-Khali, un philologue arabe, a écrit la première documentation d'une norme de techniques cryptographiques appelée _Book of Cryptographic Messages_. C'était la première fois qu'une documentation formelle des techniques existait. Cela a donné une nouvelle vision d'approche à la cryptographie. La science a continué à se nourrir dans les années 800, quand Al-Kindi a inventé l'analyse de fréquence, la mesure de la fréquence des lettres dans la langue arabe. Il s'agissait de la toute première technique de rupture de cryptographie connue jamais inventée et a marqué le début du domaine. Cependant, nous ne verrions aucune avancée majeure avant la Seconde Guerre mondiale.

![Tableau d'analyse de fréquence générique](/images/cryptography-implications/cryptography-3.png#center "Tableau d'analyse de fréquence générique")

Pendant la Seconde Guerre mondiale, les Allemands ont créé et utilisé la célèbre machine à rotor appelée Enigma. La machine était essentiellement constituée d'un clavier mécanique, d'un clavier signalétique à lampes et d'un ensemble de rotors intermédiaires. Taper une lettre sur le clavier éclairerait une lettre différente sur le clavier signalétique. Cette substitution était rendue possible grâce à un câblage spécifique commandé par le rotor, qui modifierait les connexions en fonction de la configuration que l'utilisateur pouvait modifier manuellement. Cela a permis à la machine d'opérer une substitution polyalphabétique, ce qui signifie que chaque lettre pouvait être remplacée par des lettres différentes. L'alphabet était remplaçable par plusieurs alphabets. Tout le fonctionnement était électromécanique.

![Enigma Machine utilisée par les nazis pendant la Seconde Guerre mondiale](/images/cryptography-implications/cryptography-4.png#center "Enigma Machine utilisée par les nazis pendant la Seconde Guerre mondiale")

Cette machine était une avancée technologique majeure à l'époque, tout comme son démantèlement par les Britanniques avec l'Ultra. Les Allemands ont communiqué des informations militaires via des codes morse à la radio qui ont été initialement écrits avec Enigma. Les communications étaient incassables et permettaient aux Allemands de profiter du terrain. Lorsque les Britanniques trouvèrent l'algorithme de chiffrage de la machine, les Alliés reprirent l'avantage pour gagner et mettre fin à la guerre. Selon les estimations, la guerre s'est écourtée de deux à quatre ans grâce à ce déchiffrage.

Toutes les techniques ou machines cryptographiques précédentes utilisaient principalement la lexicographie et le matériel. Avec l'arrivée de l'informatique, le même principe de dissimulation des messages a été traduit en logiciel.

La cryptographie moderne utilise les mathématiques pour crypter les données en données illisibles. Le message envoyé est crypté en un ensemble de caractères illisibles, via un algorithme mathématique complexe.

Il existe aujourd'hui deux principaux types de techniques de cryptographie : la cryptographie à **clé symétrique** et la cryptographie à **clé asymétrique** (ou cryptographie à clé publique).

## Clé symétrique

La cryptographie à clé symétrique consiste à ce que l'expéditeur et le destinataire partagent la même clé pour chiffrer et déchiffrer le message. Si Alice envoie un message à Bob, le message sera chiffré avec la clé d'Alice et Bob utilisera cette même clé pour déchiffrer le message. Les clés symétriques sont implémentées selon trois méthodes différentes : **les chiffrements par blocs**, les **chiffrements par flux** et les **fonctions de hachage**.

![Schéma de la méthode cryptographique à clé symétrique](/images/cryptography-implications/cryptography-5.png#center "Schéma de la méthode cryptographique à clé symétrique")

Pour simplifier, les chiffrements par blocs chiffrent des blocs de textes de longueur fixe `f` et les chiffrements par flux chiffrent chaque caractère en les combinant avec des chiffres dans le flux de clé.

![Schéma de chiffrement par bloc](/images/cryptography-implications/cryptography-6.png#center "Schéma de chiffrement par bloc")

![Stream Cipher Schema](/images/cryptography-implications/cryptography-7.png#center "Stream Cipher Schema")

Les deux sont dictés par un algorithme déterministe.

Un algorithme déterministe est un algorithme qui, étant donné une entrée, produira toujours la même sortie avec cette entrée spécifique.

Enfin, les fonctions de hachage sont des fonctions à sens unique qui chiffreront une entrée de message dans une sortie de tableau fixe de chiffres. Les fonctions de hachage ne sont pas réversibles et la seule façon de trouver l'entrée est de forcer brutalement la fonction et de faire correspondre tous les résultats avec le tableau fixe que nous avons. Cependant, le nombre de possibilités est énorme. C'est ce qui fait des fonctions de hachage un outil puissant.

![Schéma de la fonction de hachage](/images/cryptography-implications/cryptography-8.png#center "Schéma de la fonction de hachage")

Le principal problème de la cryptographie à clé symétrique est d'échanger la clé entre l'expéditeur et le destinataire. Cela permet une faille de sécurité. De nos jours, la cryptographie est utilisée sur Internet et les deux parties ne peuvent pas se rencontrer en secret pour échanger la clé. C'est là qu'intervient la cryptographie asymétrique.

## Clé asymétrique

En 1976, des chercheurs ont mis en évidence le problème de sécurité d'avoir une clé unique pour le cryptage et le décryptage et ont proposé un système de paire de clé publique et de clé privée. Une communication chiffrée utiliserait une clé publique pour chiffrer le message et une clé privée pour le déchiffrer. La clé publique peut être distribuée librement alors que la clé privée doit rester secrète. Les deux clés sont mathématiquement liées mais cette relation est complexe et nécessite une résolution de problème difficile.

La principale avancée de cette méthode est que le récepteur qui utilise la clé publique pour déchiffrer le message, vérifie en réalité que le message a été créé par quelqu'un qui possède la clé privée correspondante.

![Schéma de clé asymétrique](/images/cryptography-implications/cryptography-9.png#center "Schéma de clé asymétrique")

Disons qu'Alice et Bob ont tous deux des paires de clés. Alice connaît la clé publique de Bob et le contraire est également vrai. Si Alice chiffre un message avec la clé publique de Bob et l'envoie à Bob, Bob pourra utiliser sa clé privée pour vérifier que le message a été envoyé et chiffré par Alice avec la clé publique de Bob. Par conséquent, la communication est totalement sécurisée et les deux parties n'ont pas besoin d'échanger quoi que ce soit en privé. Tout est basé sur la vérification. Si un tiers, nommé John, intercepte le message, il connaîtra la clé publique de Bob mais ne pourra pas vérifier le message avec sa clé privée. Étant donné qu'une paire de clés est mathématiquement liée, la clé privée de John ne correspond pas à la clé publique de Bob. Il aurait besoin de la clé privée de Bob pour déchiffrer le message.
Cette solution de cryptographie basée sur la vérification a été une avancée révolutionnaire dans le domaine, mais aussi dans l'histoire en général.

Comme indiqué ci-dessus, la cryptographie a toujours été utilisée dans l'histoire par de grandes instances comme les forces militaires et les gouvernements. Avec l'arrivée de l'informatique et d'Internet, le pouvoir passe progressivement de la verticale à l'horizontale. De nos jours, les individus ont beaucoup plus de pouvoir qu'auparavant par rapport aux instances supérieures en tant que gouvernements. L'égalité des chances s'est considérablement accrue avec Internet, ouvrant un large éventail d'alternatives de chemin pour les gens.

Grâce à Internet, les gens sont plus libres, mais de grandes entités contrôlent encore un grand nombre d'internautes. De grandes entreprises telles que Google, Facebook ou Amazon possèdent des données privées sur leurs utilisateurs, brisant le modèle décentralisé de cryptographie. Cependant, cela est sujet à changement. La confiance des gens envers ces géants évolue, à mesure que la prise de conscience de la situation augmente. Des scandales comme Cambridge Analytica mettent en lumière l'excès de pouvoir que possèdent ces instances.

Internet est devenu un panoptique. Un panoptique était un type d'architecture utilisé dans les prisons, conçu par le philosophe Jeremy Bentham. Le concept consistait à avoir un garde placé au milieu d'une salle circulaire, permettant à tous les prisonniers d'être éventuellement observés par le garde. Il était physiquement impossible pour le gardien de surveiller tous les détenus. L'idée principale était que les détenus se sentiraient constamment observés, ne sachant pas où le gardien regarderait à un certain moment dans le temps. Ils agiraient constamment comme ils étaient surveillés. C'est exactement le même sentiment qu'Internet donne aux gens. Une guerre psychologique est constamment engagée dans nos activités privées sur le web.

![Prison Panoptique](/images/cryptography-implications/cryptography-10.png#center "Prison Panoptique")

Le modèle des grandes sociétés Internet pourrait commencer à changer. A titre d'exemple, l'application Signal pour communiquer en privé marque l'arrivée d'un nouveau modèle : une ONG open-source, entièrement dépendante des dons et de la vérification des peer-reviewers. Les examinateurs qui sont des gens comme vous et moi, vérifient que les protocoles cryptographiques Signal utilisés pour chiffrer les communications de messages sont corrects et fiables. Ce modèle commence à attirer l'attention de nombreux utilisateurs. En janvier 2021, 20 millions d'utilisateurs sont passés de Whatsapp à Signal après que Facebook a annoncé qu'il serait en mesure d'accéder aux données Whatsapp.

Ce modèle de pouvoir est également (majoritairement) présent dans Bitcoin. Créés en 2009, les fondamentaux du Bitcoin reposent principalement sur la cryptographie. La cryptographie à clé asymétrique est utilisée dans Bitcoin, permettant aux utilisateurs d'effectuer des transactions privées, empêchant tout tiers en tant que gouvernement ou entreprise d'interférer dans le processus. C'est la première fois dans l'histoire que des individus ont ce pouvoir entre leurs mains. Tout cela grâce aux mathématiques et à la cryptographie.

Si un outil de communication et une monnaie deviennent totalement souverains, distincts d'une instance centralisée, quelle est la limite ? Ce modèle peut s'appliquer à tout autre outil en ligne, la cryptographie étant le principal pilier de ce système révolutionnaire.
