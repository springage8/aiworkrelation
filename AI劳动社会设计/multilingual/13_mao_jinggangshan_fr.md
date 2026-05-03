# La voie de Jinggangshan pour la propriete publique des donnees -- Strategie des bases

> Distillation epistemique de *Pourquoi le pouvoir rouge existe-t-il en Chine ?*, *La lutte a Jinggangshan*, *Une etincelle peut embraser toute la plaine*
> Date de creation : 2 mai 2026
> Sources theoriques : Mao Zedong, *La lutte a Jinggangshan*, *Une etincelle peut embraser toute la plaine*, *Problemes strategiques de la guerre revolutionnaire en Chine*

---

Traduction francaise de l'original chinois de 毛泽东 (Mao Zedong)

---

## I. These centrale

> **"A l'interieur d'un pays, encercles de toutes parts par le pouvoir blanc, il existe pendant longtemps une ou plusieurs petites regions de pouvoir rouge, chose jamais vue dans aucun pays du monde."**
> -- Mao Zedong, *Pourquoi le pouvoir rouge existe-t-il en Chine ?* (1928)

La transformation a l'ere de l'IA est confrontee a la meme question structurelle : **Les infrastructures mondiales de l'IA sont presque a 100% controlees par le capital monopoliste -- les donnees sont sur leurs serveurs, la puissance de calcul dans leurs puces, les modeles dans leurs parametres. Dans ces conditions, comment la propriete publique des donnees pourrait-elle demarrer de zero ?**

La reponse est : **etablir des bases.**

Il ne s'agit pas de "renverser l'ancien systeme puis d'en construire un nouveau", mais de construire d'abord des "places fortes" du nouveau systeme dans les "interstices" de l'ancien -- faire fonctionner le nouveau systeme a l'echelle locale, prouver sa faisabilite, puis l'etendre progressivement.

L'objectif de ce document : concevoir **la premiere base** de la propriete publique des donnees -- ou la construire, comment la construire, comment la faire vivre, comment l'etendre.

---

## II. Pourquoi une base est-elle necessaire ?

### 2.1 Les propositions sans base sont des paroles en l'air

Le document 07 commence par la "Convention mondiale sur les algorithmes" -- c'est du haut vers le bas.
Le document 09 commence par le "cadre de gouvernance internationale" -- c'est du grand vers le petit.

Le probleme commun aux deux : **ils ne disent pas comment faire le premier pas.**

> A l'epoque des premieres grandes revolutions, il y avait aussi deux tendances au sein du Parti :
> - L'une etait le "centrisme urbain" -- d'abord occuper les grandes villes, puis s'etendre aux campagnes (importe d'Union sovietique)
> - L'autre etait "l'epanouissement general" -- lancer des soulvements simultanement dans tout le pays, renverser directement l'ancien regime
> - La pratique a prouve que ces deux approches etaient erronees -- la voie correcte etait "les campagnes encerclent les villes"
>
> Pourquoi ? Pas parce que les campagnes avaient un pouvoir magique -- mais parce que :
> 1. Les forces de l'ennemi etaient les plus concentrees dans les grandes villes -- on ne pouvait pas les affronter directement
> 2. La domination de l'ennemi etait la plus faible dans les campagnes -- il y avait un espace de survie
> 3. La population rurale constituait l'ecrasante majorite -- il y avait une base populaire
> 4. On pouvait etablir un pouvoir dans des regions locales -- prouver d'abord la faisabilite du nouveau systeme a petite echelle

Il en va de meme a l'ere de l'IA.

### 2.2 Ou se trouvent les "campagnes" a l'ere de l'IA ?

Les "campagnes" ne sont pas un concept geographique, mais un **concept structurel** -- designant les **domaines ou la force de l'ennemi est faible, les besoins des masses sont urgents, et ou des systemes alternatifs peuvent etre etablis localement**.

| Dimension | "Ville" de l'ere IA (ennemi fort) | "Campagne" de l'ere IA (percable) |
|-----------|----------------------------------|----------------------------------|
| Secteur | Moteurs de recherche, reseaux sociaux, e-commerce, cloud computing | Donnees medicales partagees,协作 de donnees agricoles, donnees educatives publiques |
| Region | Silicon Valley, Pekin, Shenzhen | Villes secondaires du Sud global, petits pays europeens |
| Donnees | Donnees comportementales des utilisateurs (verrouillees par les plateformes) | Donnees publiques (gouvernementales, scientifiques, meteorologiques) |
| Application | Chatbots, recommandations de contenu | Services publics (transports, environnement, surveillance sanitaire) |

---

## III. Ou se trouve Jinggangshan ?

### 3.1 Criteres de selection

Selon mon experience du choix de Jinggangshan (la section mediane des monts Luoxiao), une bonne base doit reunir cinq conditions :

```
1. Maillon faible de la domination ennemie
   -> Domaines ou le capital monopoliste n'a pas penetre profondement
   -> Ou des espaces de survie pour des alternatives existent deja

2. Bonne base populaire
   -> Des besoins sociaux urgents que les solutions capitalistes
   actuelles ne peuvent pas satisfaire
   -> Les masses ont la volonte de participer a la transformation

3. Modele economique viable
   -> Capable de s'auto-maintenir et de se developper
   -> Ne dependant pas de financements exterieurs
   (ou dependance limitee en phase initiale)

4. Avantage de "terrain"
   -> Espace de protection institutionnelle (vides juridiques,
   soutien des gouvernements locaux)
   -> Defensibilite technique (architecture ouverte,
   deploiement distribue)

5. Extensibilite
   -> Modele reproductible et generalisable
   -> Ce n'est pas une experience unique
```

### 3.2 Trois candidates pour la base

D'apres une evaluation complete des conditions ci-dessus, les trois directions les plus viables :

#### Candidate 1 : Fonds de confiance public pour les donnees de sante publique en Amerique latine

**Lieu :** Chili ou Bresil

**Pourquoi ici :**
- Les pays d'Amerique latine ont une forte volonte politique de "souverainete numerique" -- le Chili elabore une loi sur la protection des donnees, le Bresil a la LGPD
- La sante publique est un domaine de "faible sensibilite, forte demande" -- personne ne s'oppose a "l'utilisation de l'IA pour diagnostiquer des maladies"
- La Chine/Huawei dispose d'un soutien infrastructurel en Amerique latine -- cables sous-marins, centres de donnees (mais sans dependre de Huawei -- le projet doit etre mene localement)
- Taille de population adaptee (Chili 19 millions), propice a un projet pilote

**Que faire concretement :**
```
Creer un "Fonds de confiance public national pour les donnees de sante publique" :

Sources de donnees :
  -> Donnees de diagnostic anonymisees des hopitaux publics
  -> Donnees de surveillance de sante publique (maladies infectieuses,
  chroniques)
  -> Donnees de sante comportementales fournies volontairement
  par les residents

Utilisations des donnees :
  -> Entrainer des modeles de diagnostic IA localises (pour les
  maladies courantes en Amerique latine -- dengue, maladie de Chagas,
  tuberculose)
  -> Optimiser l'allocation des ressources de sante publique
  -> Recherche pharmaceutique (les nouveaux medicaments utilisant
  les donnees sans payer voient leur prix contraint par le fonds
  de confiance public)

Structure de gouvernance :
  -> Conseil : Gouvernement 1/4 + Representants des etablissements
  de sante 1/4 + Representants des citoyens 1/4 + Experts techniques 1/4
  -> Repartition des benefices : Les retombees economiques de l'IA
  (ex. reduction des depenses medicales grace a une prevention
  plus precise) -> 50% reinvestis dans le systeme de sante publique,
  30% aux contributeurs de donnees (dividende de donnees), 20% couts
  de fonctionnement

Indicateurs de succes :
  -> Couvrir plus de 50% des donnees des hopitaux publics en 2 ans
  -> Au moins 1 modele de diagnostic IA utilise en pratique
  (precision > 90%)
  -> Taux de participation volontaire des residents > 30%
  -> Prouver que la propriete publique des donnees est plus
  efficace que la propriete privee -- les modeles entranes
  sur des donnees partagees sont X% plus precis que ceux entranes
  sur les donnees d'un seul hopital
```

**Risques et reponses :**
| Risque | Reponse |
|--------|---------|
| Pression americaine ("la mise en commun publique des donnees, c'est de la confiscation") | Insister sur le fait qu'il s'agit d'un "fonds de confiance public", pas d'une "confiscation" -- analogue a une bibliotheque publique |
| Alternance politique interrompant la politique | Inscrire dans la loi plutot que par decret ; obtenir un soutien transpartisan |
| Capacite technique insuffisante | Collaborer avec les universites locales ; utiliser des outils IA open source |
| Mauvaise qualite des donnees | Par phases -- commencer par les donnees de haute qualite des grands hopitaux, puis couvrir les structures de base |

---

#### Candidate 2 : Cooperative de donnees de transport dans une ville europeenne

**Lieu :** Une ville allemande (ex. Hambourg) ou neerlandaise (ex. Utrecht)

**Pourquoi ici :**
- L'UE a la legislation la plus forte au monde sur la protection des donnees (RGPD), et elabore actuellement le Reglement sur la gouvernance des donnees (DGA) -- environnement juridique le plus favorable
- Les villes europeennes ont une forte tradition de gestion municipale -- les transports sont un service directement controle par la municipalite
- L'Europe dispose d'un cadre juridique pour les cooperatives -- les cooperatives de donnees ont un statut juridique clair

**Que faire concretement :**
```
Creer une "Cooperative de donnees de transport urbain" :

Sources de donnees :
  -> Donnees de deplacement GPS fournies volontairement par les
  citoyens (via application)
  -> Donnees operationnelles des systemes de transport public
  -> Donnees de flux de trafic des capteurs municipaux

Utilisations des donnees :
  -> Optimiser les itineraires et frequences des transports publics
  -> Reduire les embouteillages (feux de signalisation pilotes par IA)
  -> Fournir une base decisionnelle pour l'urbanisme

Structure de gouvernance :
  -> Les membres de la cooperative (contributeurs de donnees)
  ont une personne, une voix
  -> Election d'un comite de gestion
  -> Toute entite externe (entreprise commerciale) utilisant les
  donnees doit payer, les revenus reviennent aux membres de la
  cooperative

Difference avec la solution capitaliste :
  -> Solution Uber/Waze : collecter les donnees utilisateurs ->
  optimiser la navigation -> vendre des publicites/vendre les
  donnees -> profits aux actionnaires
  -> Solution cooperative : collecter les donnees citoyennes ->
  optimiser les transports -> ameliorer les deplacements publics ->
  revenus aux citoyens
  -> La technologie est presque identique, mais la propriete et
  la repartition sont completement differentes
```

**Attention :** L'Europe est adaptee pour un projet pilote, mais la tradition "reformiste" europeenne pourrait la faire s'arreter a la cooperative -- sans remettre en cause la propriete elle-meme. Un projet pilote en Amerique latine a un potentiel de transformation plus grand -- car les inegalites y sont plus extremes et la dynamique de changement plus forte.

---

#### Candidate 3 : "Cooperative de donnees des livreurs" dans une ville chinoise

**Lieu :** Une ville chinoise de second rang (ex. Changsha, Chengdu)

**Pourquoi ici :**
- La Chine a le plus grand groupe de travailleurs des plateformes au monde -- Rien que Meituan compte 7 millions+ de livreurs
- Les infrastructures numeriques de la Chine sont les plus developpees -- mais toutes les donnees appartiennent aux plateformes
- Le niveau d'exploitation des livreurs est le plus eleve au monde -- les plateformes prennent 20-30% de commission, sans protection du travail
- La Chine dispose d'un cadre juridique syndical -- bien qu'il n'y ait pas actuellement de syndicats independants, la "negociation collective" est legalement autorisee

**Que faire concretement :**
```
Creer une "Cooperative de donnees des livreurs" (en commencant
par le plus simple) :

Premiere etape : Surveillance collective
  -> Les livreurs enregistrent et analysent collectivement
  les changements de regles algorithmiques des plateformes
  -> Creer une "base de donnees de suivi des regles algorithmiques"
  -> la plateforme modifie ses regles, tout le monde les analyse
  ensemble
  -> Ce n'est pas une "confrontation technique", c'est une
  "symetrisation de l'information"

Deuxieme etape : Negociation collective
  -> Quand les livreurs disposent des donnees sur les regles
  algorithmiques de la plateforme, ils ont un pouvoir de negociation
  -> "Si le prix unitaire descend en dessous de X, tout le monde
  se deconnecte pendant 15 minutes"
  -> Les donnees rendent l'action collective possible

Troisieme etape : Plateforme autonome
  -> La cooperative de livreurs lance sa propre application
  de repartition des commandes
  -> Au debut, on peut commencer par les "creneaux hors pointe" --
  les commandes que les plateformes ne veulent pas prendre
  (livraisons nocturnes, longues distances)
  -> Elargir progressivement
  -> La cooperative ne prend pas de commission ou prend 5%
  (pour les couts de fonctionnement), le reste va entierement
  aux livreurs

Indicateurs de succes :
  -> Couvrir 1000+ livreurs en 12 mois
  -> Efficacite de livraison de la plateforme cooperative
  non inferieure a celle des plateformes commerciales
  -> Revenus des livreurs augmentes de 20%+ (rien qu'en reduisant
  les commissions)
  -> La propriete des donnees reellement entre les mains des livreurs
```

**Avertissement sur les risques :**
- L'environnement politique chinois est le plus strict concernant les organisations independantes -- c'est une option a haut risque
- Mais l'effet de demonstration en cas de succes y est aussi le plus grand -- car la Chine est le centre mondial de l'economie des plateformes
- **Strategie : ne pas entrer directement en conflit avec le cadre juridique existant, operer dans le cadre des "droits des travailleurs" et de la "loi sur la securite des donnees"**

---

### 3.3 Ma recommandation

Apres evaluation complete, **la premiere base devrait etre etablie en Amerique latine (Candidate 1)**.

Raisons :
1. Espace politique le plus grand -- les pays d'Amerique latine ont une volonte politique de souverainete numerique
2. Fort impact international -- le succes entrainera d'autres pays du Sud global
3. Risque maitrisable -- ne confronte pas directement les interets fondamentaux des Etats-Unis ou de la Chine
4. Infrastructures disponibles -- Huawei et d'autres entreprises chinoises ont des bases de cooperation en Amerique latine
5. Bon effet de demonstration -- reproductible de l'Amerique latine a l'Afrique et a l'Asie

---

## IV. Modele economique de la base

Ce qui determine la survie d'une base, c'est sa capacite a **subvenir elle-meme a ses besoins**.

### 4.1 Sources de revenus

Le fonds de confiance public pour les donnees doit etre economiquement autonome -- capable de fonctionner sans financements exterieurs.

```
Phase initiale (1-2 ans) :
  Financement de demarrage : fonds publics (subventions
  gouvernementales, bourses de recherche) ou fondations
  Petite echelle, couts faibles -- un fonds de confiance
  municipal, serveurs + personnel, cout annuel d'environ
  0,5 a 2 millions USD

Phase intermediaire (2-5 ans) :
  Revenus principaux : redevances d'utilisation des donnees
  Compagnies d'assurance (utilisant les donnees de sante pour
  optimiser les produits d'assurance) -> paiement
  Entreprises pharmaceutiques (utilisant les donnees medicales
  pour la recherche de nouveaux medicaments) -> paiement
  Services d'urbanisme (utilisant les donnees de transport pour
  optimiser la gestion urbaine) -> paiement (budget interne
  du gouvernement)
  -> Les frais aux utilisateurs commerciaux suffisent a couvrir
  les couts de fonctionnement

Phase de maturite (5 ans+) :
  Distribution de dividendes de donnees -- en plus de couvrir
  les couts, un surplus est distribue aux contributeurs de donnees
  Cela prouve que "la propriete publique des donnees est durable"
```

### 4.2 Mecanisme de repartition

```
Formule de repartition des revenus :

Revenu annuel total = Σ(redevances des utilisateurs commerciaux)
+ soutien budgetaire public

Priorite de repartition :
  Premier : couts de fonctionnement (serveurs, bande passante,
  salaires) -- environ 30%
  Deuxieme : fonds de reserve publique (mise a niveau technique,
  gestion des risques) -- environ 20%
  Troisieme : dividendes de donnees (distribues aux contributeurs
  de donnees) -- environ 50%

Repartition individuelle des dividendes de donnees :
  Part de base (60%) : distribuee egalement a tous les
  contributeurs de donnees
  -- Parce que la nature des donnees est sociale, pas individuelle
  -- La valeur individuelle de chaque donnee est limitee,
  la valeur collective est immense
  Part de contribution (40%) : variable selon la quantite/
  qualite des donnees
  -- Mecanisme d'incitation necessaire -- sinon personne ne
  voudra contribuer davantage
```

---

## V. Modele organisationnel de la base

### 5.1 Principes de gouvernance

```
Application du centralisme democratique a la propriete publique
des donnees :

Democratie :
  -> Les contributeurs de donnees (les "citoyens des donnees")
  elisent le conseil a raison d'une personne, une voix
  -> Les decisions majeures (autorisation des donnees, proportions
  de repartition des revenus, modifications des regles) doivent
  etre soumises au vote de tous
  -> Transparence algorithmique -- tous les enregistrements
  d'utilisation des donnees sont visibles par les membres

Centralisme :
  -> Le conseil est responsable des decisions de gestion quotidienne
  -> L'equipe technique a une autonomie professionnelle
  (ce n'est pas "chaque ligne de code doit etre vote")
  -> Une fois une decision prise, elle doit etre executee --
  c'est la garantie de l'efficacite

Cle : equilibre entre democratie et centralisme
  -> Pas de democratie = nouvelle forme de "bureaucratie des donnees"
  -> Pas de centralisme = inefficacite, incapacite a prendre
  la moindre decision
```

### 5.2 Structure organisationnelle

```
Structure organisationnelle du fonds de confiance public
pour les donnees :

+--------------------------------------------------+
|          Assemblee des citoyens des donnees        |
|     (tous les contributeurs de donnees,            |
|             une personne, une voix)                |
|            Organe supreme de pouvoir               |
+--------------------------------------------------+
|                      Election                      |
|                         v                          |
+--------------------------------------------------+
|              Conseil (7-11 personnes)              |
|    4 representants des contributeurs de donnees    |
|    + 2 experts techniques + 2 representants        |
|   communautaires + 1 representant du gouvernement  |
|             (sans droit de veto)                   |
|       Mandat de 2 ans, renouvelable une fois       |
+--------------------------------------------------+
|   Nomination    |         Election                 |
|        v        |            v                     |
|  Equipe de      |  Comite de surveillance          |
|  direction      |  algorithmique                   |
| (operations     |  (audit, plaintes, recours)      |
|  quotidiennes)  |                                  |
+--------------------------------------------------+
```

---

## VI. De la base au pays tout entier -- voie d'expansion

### 6.1 Expansion horizontale : de 1 a 10

Quand un projet pilote de fonds de confiance des donnees fonctionne avec succes pendant 2-3 ans, commencer a le reproduire :

```
Strategie de reproduction :

Premiere etape : Documenter -- transformer tous les processus,
solutions techniques et documents juridiques du pilote en
"kit d'outils open source"
  La ville suivante n'a pas besoin de repartir de zero
  Reduire le cout de reproduction

Deuxieme etape : Formation -- les operateurs du premier pilote
deviennent des "instructeurs semenciers"
  Aller dans la ville suivante pour aider a etablir le nouveau pilote
  L'experience est le meilleur manuel

Troisieme etape : Mise en reseau -- etablir des accords de
partage de donnees entre les differents pilotes
  Les fonds de confiance se connectent entre eux -- les donnees
  circulent a plus grande echelle, la valeur est plus grande
  Former une "alliance des fonds de confiance des donnees" --
  negociation commune, normes communes, gouvernance commune

Quatrieme etape : Standardisation -- sur la base de l'alliance,
elaborer une "norme nationale des fonds de confiance des donnees"
  De "l'exploration individuelle" a la "normalisation unifiee"
  Fournir une base pratique pour la legislation au niveau national
```

### 6.2 Approfondissement vertical : de la faible sensibilite a la haute sensibilite

```
Domaines d'extension :

Premiere phase : Donnees publiques (donnees gouvernementales
ouvertes, donnees meteorologiques, donnees scientifiques)
  -> Les plus faciles -- les gouvernements ont une dynamique
  d'ouverture des donnees
  -> Donnees de haute qualite, peu controversees
  -> Etablir la confiance et la base technique

Deuxieme phase : Donnees de la vie quotidienne (donnees de sante,
donnees de transport, donnees educatives)
  -> Etroitement liees a la vie quotidienne des gens
  -> Sentiment de reussite le plus fort
  -> Un modele de depistage precoce des maladies qui sauve
  des vies -> plus efficace que cent articles

Troisieme phase : Donnees economiques (donnees de consommation,
donnees de chaine d'approvisionnement, donnees financieres)
  -> Touchent aux interets fondamentaux -- c'est la veritable
  "moyen de production"
  -> A ce stade, le capital commence a contre-attaquer
  -> C'est alors la force politique, et non la force technique,
  qui doit faire avancer

Quatrieme phase : Pouvoir de gestion des algorithmes
  -> Non seulement les donnees sont publiques, mais aussi
  la democratisation du "pouvoir algorithmique"
  -> De "tes donnees te reviennent" a "ton processus de travail
  te revient"
  -> C'est la transformation la plus radicale
```

### 6.3 De l'economique au politique

La base n'est pas seulement une "experience economique" -- c'est aussi une "entite politique".

```
Signification politique du fonds de confiance des donnees :

1. C'est un modele microscopique de nouvelles relations sociales
  -> Ici, les donnees ne sont pas une marchandise, mais une
  richesse publique
  -> Ici, l'algorithme n'est pas une boite noire, mais un outil
  transparent
  -> Ici, le travailleur n'est pas un outil, mais un decideur
  -> Cela montre qu'"une autre societe de l'IA" est possible

2. C'est une ecole de formation des cadres
  -> L'exploitation d'un fonds de confiance des donnees necessite
  des competences techniques, de gouvernance, juridiques et
  organisationnelles
  -> Ces competences ne peuvent etre acquises que dans la pratique
  -> Chaque operation reussie forme les futurs leaders de la
  transformation

3. C'est un point d'accumulation de forces
  -> Le fonds de confiance des donnees ne gere pas seulement
  les donnees, il gere aussi les "personnes"
  -> Les liens entre les contributeurs de donnees -> peuvent
  se developper en organisations politiques
  -> Le fonds de confiance des donnees peut etre un hybride de
  "syndicat + cooperative + service public"
```

---

## VII. Erreurs a eviter par la base

### 7.1 Lecons de l'histoire

**Lecon 1 : L'echec des soulvements urbains de 1927**
- Lancer des insurrections armees ouvrieres dans les grandes villes (Shanghai, Changsha)
- Toutes ont echoue -- parce que la domination de l'ennemi dans les villes etait trop forte
- Lecon : **Defier l'ennemi la ou il est le plus fort, ce n'est pas du courage, c'est de la temerite**

**Correspondance a l'ere de l'IA :**
- Ne pas essayer d'affronter directement Google et OpenAI au debut
- Ne pas essayer de "renverser le capitalisme de l'IA"
- Etablir des bases la ou l'ennemi n'attache pas d'importance (donnees publiques, donnees de sante, donnees agricoles)

**Lecon 2 : L'aventurisme "gauchiste" de Wang Ming**
- Exiger que l'Armee rouge attaque les grandes villes et livre bataille decisivement au Guomindang
- Resultat : echec de la cinquieme campagne d'encerclement et de repression, marche force de la Longue Marche
- Lecon : **Quand le rapport de forces est defavorable, ne pas livrer bataille de position -- mener une guerre de guerilla**

**Correspondance a l'ere de l'IA :**
- Ne pas esperer "qu'une seule solution change toute l'industrie de l'IA"
- Ne pas surestimer la possibilite d'une transformation institutionnelle a court terme
- Mener une "guerre de guerilla" -- remporter de petites victoires dans des regions locales, accumuler des forces

**Lecon 3 : Le separatisme de Zhang Guotao**
- Pendant la Longue Marche, ne pas obeir au commandement central, creer un comite central parallele
- Resultat : la division a affaibli les forces revolutionnaires
- Lecon : **L'unite de la strategie globale est necessaire -- l'action dispersee ne signifie pas l'autonomie de chacun**

**Correspondance a l'ere de l'IA :**
- Les fonds de confiance des donnees des differentes bases doivent suivre des principes et des normes communs
- Ne pas "inventer chacun sa propre propriete publique des donnees"
- Disposer d'un cadre theorique unifie (fourni par ce depot) et d'un guide pratique

### 7.2 Erreurs a eviter aujourd'hui

```
Erreur 1 : Attendre le plan parfait
  "La theorie n'est pas encore assez complete, attendons d'avoir
  pense a tous les details avant d'agir"
  -> Il n'y aura jamais de plan parfait
  -> La pratique est le critere unique de la verite --
  commencez d'abord, ameliorez en faisant

Erreur 2 : Vouloir s'etendre trop vite
  "Ce projet pilote est bon, generalisons-le tout de suite
  a tout le pays"
  -> Qui va vite n'arrive pas -- sans base solide,
  l'expansion ne peut que s'effondrer
  -> D'abord prendre racine profondement dans un endroit,
  puis reproduire

Erreur 3 : Travailler en vase clos
  "Nous concevons, construisons et exploitons nous-memes"
  -> Une organisation qui ne s'integre pas aux masses locales
  est vouee a l'echec
  -> Le fonds de confiance des donnees doit etre des le debut
  "un projet des masses elles-memes"

Erreur 4 : Determinisme technologique
  "Si la solution technique est bonne, les gens viendront
  naturellement"
  -> Le cœur du fonds de confiance public n'est pas la
  technologie (bien que la technologie soit importante)
  -> Le cœur, c'est la confiance, la gouvernance, la repartition --
  ce sont des problemes sociaux, pas des problemes techniques

Erreur 5 : Pessimisme
  "A quoi sert une si petite echelle ? Cela ne changera pas
  la donne."
  -> Une etincelle peut embraser toute la plaine
  -> Chaque projet pilote reussi est la meilleure refutation
  de la these "il n'y a pas d'alternative"
```

---

## VIII. Conclusion : De Jinggangshan a toute la Chine

En 1927, l'Insurrection des Moissons d'Automne a la frontiere du Hunan et du Jiangxi a echoue. Mao Zedong a conduit les troupes rescapees vers Jinggangshan.

Personne n'aurait pu imaginer a l'epoque que cette base reculee dans les montagnes deviendrait le point de depart de la victoire de la revolution chinoise.

Il en va de meme a l'ere de l'IA. Aujourd'hui, un fonds de confiance public pour les donnees de sante publique etabli dans une ville d'Amerique latine -- de taille modeste, d'impact limite, susceptible d'etre ferme a tout moment -- represente neanmoins une possibilite : **une autre alternative au capital monopoliste de l'IA.**

> **"Les marxistes ne sont pas des diseurs de bonne aventure ; quant aux developpements et changements futurs, on ne peut et ne doit en indiquer que la grande orientation, sans fixer mecaniquement le jour et l'heure."**
> -- Mao Zedong, *Une etincelle peut embraser toute la plaine*

Mais la grande orientation est claire :

```
Un fonds de confiance des donnees -> dix fonds de confiance
  -> cent fonds de confiance
Une ville -> un pays -> un continent
Sante publique -> donnees de la vie quotidienne -> donnees economiques
Experience economique -> force politique -> transformation
  institutionnelle
```

> **"La Chine est couverte de bois mort, qui s'enflammera bientot pour devenir un feu devorant."**
>
> A l'ere de l'IA, c'est la meme chose -- non, c'est le monde entier -- qui est couvert de bois mort.
> Chomage de remplacement par l'IA, exploitation des donnees, alienation algorithmique -- ces contradictions s'accumulent.
> Ce qui nous manque, ce ne sont pas les "conditions", mais une simple **etincelle**.

> **"La haute vague de la revolution chinoise dont je parle n'est en aucune facon quelque chose de vide, sans signification pratique, de 'possible' comme certains le disent. Elle est comme un navire dont on apercoit la pointe du mat depuis le rivage au loin dans la mer ; elle est comme le soleil levant dont les rayons embrases apparaissent a l'horizon de l'Est ; elle est comme un enfant pres de naitre qui s'agite dans le ventre de sa mere."**
>
> La nouvelle societe de l'ere de l'IA s'agite dans le ventre de l'ancienne societe.

---

## Annexe : Liste de verification pour l'etablissement de la base

### Phase de preparation
- [ ] Le lieu est-il correctement choisi ? (ennemi faible + besoins des masses + espace politique)
- [ ] Y a-t-il au moins 3 organisateurs a plein temps ?
- [ ] L'"enquete et etude" des donnees locales a-t-elle ete realisee ?
- [ ] Au moins un gouvernement local a-t-il apporte un soutien informel ?
- [ ] Y a-t-il un financement operationnel pour la periode experimentale (au moins 6 mois) ?

### Phase de demarrage
- [ ] La premiere Assemblee des citoyens des donnees a-t-elle ete convoquee (participation > 100 personnes) ?
- [ ] Le conseil a-t-il ete elu ?
- [ ] Les statuts du fonds de confiance des donnees ont-ils ete publies (en chinois, anglais et langue locale) ?
- [ ] La plateforme de gestion des donnees open source a-t-elle ete deployee ?
- [ ] Le premier contrat d'utilisation des donnees a-t-il ete signe ?

### Phase d'exploitation
- [ ] Le mecanisme de repartition des revenus est-il clair et transparent ?
- [ ] Y a-t-il un comite independant de surveillance algorithmique ?
- [ ] Le nombre de contributeurs de donnees est-il en croissance continue (croissance mensuelle > 10%) ?
- [ ] Y a-t-il au moins 1 application d'IA concretement produite ?
- [ ] Le taux de satisfaction du groupe couvert est-il > 70% (enquete reguliere) ?

### Phase d'expansion
- [ ] La documentation en "kit d'outils" a-t-elle ete achevee ?
- [ ] Y a-t-il au moins 2 "instructeurs semenciers" pouvant etre envoyes vers de nouveaux pilotes ?
- [ ] Une relation d'alliance a-t-elle ete etablie avec au moins 1 autre projet pilote ?
- [ ] Au moins 1 proposition de loi favorable a la propriete publique des donnees a-t-elle ete poussee ?
- [ ] Y a-t-il une couverture mediatique (au moins 1 reportage approfondi dans un grand media) ?

---

> **"Lire est apprendre, mais utiliser est aussi apprendre, et c'est un apprentissage plus important encore."**
>
> Ce plan n'est pas fait seulement pour etre lu -- il est fait pour etre mis en pratique.
