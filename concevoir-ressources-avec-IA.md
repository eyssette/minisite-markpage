---
style: .admonitionTitle{font-weight:bold!important;} .user:before{content:"👤   Prompt"; display:block; margin-bottom:5px; font-weight:bold} .IA:before{content:"🤖   Réponse de l'IA"; display:block; margin-bottom:5px; font-weight:bold;} .user, .IA {margin-bottom:1em ; padding:1em; padding-left:2em; border:1px solid \#AAA; border-radius:20px} .user {background-color:\#EEE} .IA{background-color:white} @media screen and (min-width:601px){footer{font size:1.3em}} .displayHomepage img {max-width:500px; display:block; margin:auto; margin-bottom:3em} .admonitionContent aside {text-align:right; color:\#4f0101; margin-bottom:1em} aside img {display:block; margin:1em auto; max-width:none!important} aside, pre {width:auto; overflow:auto}
searchbar: false
linkToHomePage: true
---

# Concevoir des ressources avec l'IA

Nous nous concentrons ici sur les utilisations pertinentes de l'IA pour la **conception de ressources éducatives** et nous proposons un **repérage de pratiques** fondé sur la distinction de différents gestes professionnels et différents types d'utilisation de l'IA.

> Nous avons identifié **trois gestes professionnels** essentiels : 
> 
> ![](https://minio.apps.education.fr/codimd-prod/uploads/upload_84c25341bd50db759fbdff698fb7e8fe.png)
> 
> Pour chacun de ces gestes professionnels, on peut envisager **trois types d'utilisation** de l'IA :
> 
> ![](https://minio.apps.education.fr/codimd-prod/uploads/upload_b37fef18b1cc723c70938aad6bdbde49.png)


Nous vous proposons de partir de cette distinction des usages de l'IA et de vous donner des exemples de la manière dont on peut utiliser à profit l'IA d'un point de vue professionnel.


## 🛠️  Créer


    
### Principe général

Les IA génératives (IAG) sont particulièrement adaptées pour produire une première version d'un document ou bien pour donner des idées lors de la création d'un cours.

Le document produit doit souvent être retravaillé, les formulations sont parfois à reprendre et le risque d'hallucinations reste toujours présent. Il faut toujours vérifier la pertinence du document produit.

Mais avec certaines techniques de prompt, on peut tout de même obtenir des résultats très intéressants et tout à fait exploitables.

### 📅 Planification d'un cours

Lorsqu'on est dans la phase de préparation d'un nouveau cours, une IA générative peut servir à explorer une thématique d'un programme.

<!--Plus précisément on peut se servir de l'IA pour :

1. trouver des idées pour un cours
2. faire une liste des concepts importants et les définir
3. créer une fiche d'objectifs et de compétences-->

#### 1/ Trouver des idées pour un cours

Si le prompt est trop général, on va avoir des réponses également trop générales. Cela peut fournir déjà quelques idées, mais ce n'est pas le plus pertinent.

:::exemple collapsible Exemple en Français (4ème) sur le thème "Dire l'amour" : prompt trop général (quelles sont les idées intéressantes ?)

Tu dois préparer un cours en français sur le thème "Dire l'amour" pour des élèves de quatrième. Quelles sont les idées intéressantes à travailler sur ce thème ? {.user}

<div markdown class="IA">

Bien sûr ! Voici une liste d'idées pertinentes que vous pourriez explorer dans un cours sur le thème "Dire l'amour" pour des élèves de quatrième :

##### Les différentes formes d'expression de l'amour :

L'amour familial
L'amour amical
L'amour romantique

##### Les expressions littéraires de l'amour :

La poésie amoureuse
Les lettres d'amour
Les romans d'amour

##### Les métaphores et symboles associés à l'amour :

Les symboles traditionnels de l'amour (cœur, rose, etc.)
Les métaphores poétiques pour décrire l'amour

##### L'amour dans l'art et la musique :

Les tableaux célèbres représentant l'amour
Les chansons d'amour et leurs messages

##### Les différentes langues de l'amour :

Le langage corporel
Les mots doux et les compliments
Les cadeaux et gestes d'affection
    
##### Les figures littéraires liées à l'amour :

Les personnifications de l'amour
Les allégories amoureuses

##### Les changements culturels dans la façon de déclarer son amour :

Évolution des normes sociales et des attentes
L'influence des médias sociaux sur l'expression de l'amour

##### L'amour dans la langue française :

Expressions idiomatiques liées à l'amour
L'importance des mots dans la déclaration d'amour
    
##### Les grandes déclarations d'amour dans la littérature et l'histoire :

Roméo et Juliette de Shakespeare
Les lettres passionnées de grands personnages historiques

##### Les défis de l'expression de l'amour :

La peur du rejet
Les stéréotypes de genre liés à l'expression des sentiments

##### L'amour dans les contes et les légendes :

Les histoires d'amour mythologiques
Les contes de fées et l'amour véritable

##### L'évolution de la notion d'amour au fil du temps :

Les différences entre l'amour romantique aujourd'hui et dans le passé
Les influences culturelles et sociales sur la perception de l'amour    
    
</div>

:::

On peut alors chercher à préciser son prompt pour que l'IA fournisse une réponse plus pertinente.

:::exemple collapsible Exemple en Français (4ème) sur le thème "Dire l'amour" : prompt plus précis (formulation de problématiques précises)

Quelles sont les problématiques littéraires intéressantes à aborder dans le cadre d'un cours de français sur le thème "Dire l'amour" en quatrième ? Fais une liste de 20 problématiques sous la forme d'une tension entre deux grandes perspectives possibles. Fais seulement la liste, n'ajoute pas d'explication ou de reformulation. {.user}

<div markdown class="IA">

1. La subjectivité de l'amour vs l'universalité des émotions.
1. L'expression littéraire de l'amour comme réalité vs l'expression comme construction artistique.
1. L'amour comme inspiration créative vs l'amour comme objet d'analyse intellectuelle.
1. L'authenticité émotionnelle vs la stylisation artistique dans la poésie amoureuse.
1. La représentation du bonheur amoureux vs l'exploration des tourments de l'amour.
1. L'usage des figures de style pour amplifier l'amour vs leur utilisation pour en atténuer l'intensité.
1. La temporalité de l'amour dans la littérature : instantanéité vs évolution.
1. L'impact des mouvements littéraires sur la représentation de l'amour.
1. L'amour comme source de conflictualité dans le récit vs l'amour comme harmonie.
1. L'approche réaliste des relations amoureuses vs l'utilisation de l'allégorie dans la poésie amoureuse.
1. La représentation des personnages féminins et masculins dans la littérature amoureuse : stéréotypes vs subversion.
1. L'amour comme métaphore sociale ou politique vs l'amour comme expérience personnelle.
1. La narration à la première personne dans les textes amoureux vs la narration à la troisième personne.
1. L'amour comme quête individuelle vs l'amour comme thème collectif.
1. La place de l'humour et de l'ironie dans la littérature amoureuse vs la gravité des émotions.
1. L'influence de la biographie de l'auteur sur la représentation de l'amour vs la création d'universalité littéraire.
1. La tension entre l'explicitation des sentiments amoureux et la suggestion dans les textes.
1. L'amour comme source de résilience dans la littérature vs l'amour comme fragilité.
1. La comparaison entre l'amour idéalisé dans la fiction et l'amour vécu au quotidien.
1. La voix de l'auteur dans la déclaration d'amour : effacement de soi vs affirmation individuelle.

</div>

:::

<!-- 
Quelles sont les principales idées à connaître sur le thème de ?
Quelles sont les principales théories de … en … ?
Quelles sont les différentes explications possibles de … ?
-->


#### 2/ Proposer un plan général de cours

:::exemple collapsible Exemple sur les réseaux sociaux en SNT (secondes)

<div markdown class="user">

Tu es un conseiller en pédagogie qui aide les enseignants à planifier des séances de cours sur une thématique précise.
Tu vas proposer une planification détaillée comprenant plusieurs séances pour traiter une thématique en indiquant les éléments suivants pour chaque séance: 
- Objectifs (acquisition, mémorisation, transfert);
- Tâches didactiques (nature et ordre);
- Démarche pédagogique;
- Rôle de l’évaluation;
- Organisation (matérielle et humaine);


Je suis un enseignant de lycée et je veux faire un cours sur les réseaux sociaux pour des élèves de seconde. L’ensemble de la séance ne doit pas dépasser six heures.
Voici les contenus que je souhaite traiter:
- Identité numérique, e-réputation, identification, authentification ;
- Réseaux sociaux existants;
- Modèle économique des réseaux sociaux;
- Rayon, diamètre et centre d’un graphe :
- Notion de « petit monde » Expérience de Milgram;
- Cyberviolence.    

</div>

<div markdown class="IA">

our planifier une série de séances sur les réseaux sociaux pour des élèves de seconde, nous allons diviser le contenu en modules et allouer le temps de manière efficace. Voici une proposition de planification détaillée :

##### Séance 1: Introduction aux Réseaux Sociaux et Identité Numérique (1h30)

Objectifs :

Comprendre ce que sont les réseaux sociaux et leur impact sur l'identité numérique.
Sensibiliser sur l'importance de l'e-réputation.

Tâches didactiques :

Introduction aux différents réseaux sociaux et à leur utilisation.
Discussion sur l'identité numérique et l'e-réputation.

Démarche pédagogique :

Exposé interactif avec des exemples concrets.
Analyse de cas réels d'e-réputation.

Rôle de l’évaluation :

Quiz rapide pour évaluer la compréhension des concepts clés.
Organisation :

Utilisation d'un vidéoprojecteur pour présenter des études de cas.
Travail en petits groupes pour discuter des impacts personnels.

##### Séance 2: Modèle Économique des Réseaux Sociaux (1h)
Objectifs :

Découvrir comment les réseaux sociaux génèrent des revenus.
Tâches didactiques :

Présentation des modèles économiques (publicité, données utilisateurs, etc.).
Démarche pédagogique :

Exposé suivi d'une discussion guidée.
Rôle de l’évaluation :

Questions de réflexion pour s'assurer de la compréhension.
Organisation :

Utilisation d'un tableau interactif pour schématiser les modèles économiques.

##### Séance 3: Théorie des Graphes - Bases et Applications (1h30)
Objectifs :

Comprendre les concepts de base de la théorie des graphes.
Appliquer ces concepts aux réseaux sociaux.
Tâches didactiques :

Introduction aux notions de rayon, diamètre et centre d'un graphe.
Exercices d'application sur des graphes simples.
Démarche pédagogique :

Cours magistral suivi d'exercices pratiques.
Rôle de l’évaluation :

Exercices notés pour évaluer la compréhension et l'application des concepts.
Organisation :

Utilisation de logiciels de graphes pour visualiser et manipuler des exemples.

##### Séance 4: Notion de « Petit Monde » et Expérience de Milgram (1h)
Objectifs :

Comprendre la théorie du petit monde et son application aux réseaux sociaux.
Tâches didactiques :

Explication de l'expérience de Milgram.
Analyse de son application dans le contexte des réseaux sociaux modernes.
Démarche pédagogique :

Présentation interactive avec des exemples historiques et contemporains.
Rôle de l’évaluation :

Discussion dirigée pour évaluer la compréhension.
Organisation :

Utilisation de vidéos et d'articles pour illustrer l'expérience de Milgram.

##### Séance 5: Cyberviolence (1h)
Objectifs :

Sensibiliser les élèves aux formes et aux conséquences de la cyberviolence.
Tâches didactiques :

Définition et exemples de cyberviolence.
Discussion sur les moyens de prévention et d'action.
Démarche pédagogique :

Discussions en classe et étude de cas.
Rôle de l’évaluation :

Débat en classe pour évaluer la compréhension et la capacité de réaction des élèves.
Organisation :

Utilisation de l'espace de classe pour faciliter la discussion en groupe.

##### Séance 6: Synthèse et Projet (1h)
Objectifs :

Synthétiser les connaissances acquises.
Appliquer les concepts appris à un projet créatif.
Tâches didactiques :

Récapitulatif des séances précédentes.
Travail sur un projet de groupe : création d'un plan de gestion de l'identité numérique.
Démarche pédagogique :

Travail collaboratif avec accompagnement de l'enseignant.
Rôle de l’évaluation :

Présentation des projets de groupe et évaluation par les pairs et l'enseignant.
Organisation :

Mise à disposition de matériel informatique pour la recherche et la création de présentations.
Chaque séance devrait être adaptée en fonction des réactions et de l'engagement des élèves, avec une flexibilité pour approfondir les sujets qui suscitent le plus d'intérêt ou de débat.    

</div>

:::

:::exemple collapsible Exemple en philosophie (terminales) pour un cours sur la philosophie du corps

<div markdown class="user">

Propose un plan de cours sur la philosophie du corps pour des élèves de terminale. Fais juste une liste de thématiques intéressantes.

</div>

<div markdown class="IA">

Bien sûr, voici une liste de thématiques intéressantes pour un cours sur la philosophie du corps destiné aux élèves de terminale :

##### Introduction à la philosophie du corps

Définitions et enjeux
Dualisme vs monisme

##### La phénoménologie du corps

L'approche de Merleau-Ponty
L'expérience corporelle et la perception

##### Identité et individuation

Le rôle du corps dans la construction de l'identité
La question de l'individuation

##### Corps et éthique

Bioéthique et dilemmes éthiques liés au corps
Manipulation génétique et reproduction assistée
    
##### Corps et politique

Les implications politiques du contrôle du corps
Droits du corps et libertés individuelles

##### Normes corporelles et représentations sociales

Influences culturelles et sociétales sur la perception du corps
Stigmatisation et discrimination liées au corps
    
##### Technologie et corps

Impacts des prothèses et des technologies sur le corps
Réflexion sur l'augmentation technologique du corps

##### Genre et corps

La construction sociale du genre et son lien avec le corps
Corps queer et perspectives post-genre

##### Corps et spiritualité

Le corps dans les traditions religieuses
La dimension spirituelle de l'expérience corporelle

##### Le corps dans l'art et la littérature

Représentations artistiques du corps
Analyse de textes littéraires explorant la philosophie du corps

##### Corps et environnement

Relations entre le corps et l'environnement naturel
Éthique environnementale et responsabilité corporelle
    
##### Le futur du corps

Transhumanisme et augmentation humaine
Débats éthiques sur les avancées technologiques liées au corps

</div>

:::

#### 3/ Dégager des étapes pour un cours sur un point précis

:::exemple collapsible Exemple en philosophie (terminales) pour expliquer le concept d'idéologie selon Marx

Propose un ensemble d'étapes claire qui expliquent pas à pas le concept d'idéologie selon Marx à un élève de lycée niveau terminale. {.user}

<div markdown class="IA">

Comprendre le Concept d'Idéologie Selon Marx - Niveau Terminale

1/ **Introduction**
- **Définition simple :** L'idéologie, selon Karl Marx, désigne les idées dominantes d'une société, généralement façonnées par la classe sociale qui détient le pouvoir économique.
- **Contexte historique :** Marx a développé ses idées au 19e siècle, en réaction aux transformations liées à la révolution industrielle.

2/ **Base Matérielle de la Société**
- **Définition simple :** La société repose sur la façon dont les gens produisent leurs biens et services (forces productives et relations de production).
- **Exemple :** Une société agricole avec des paysans aura une base matérielle différente de celle d'une société industrielle.

3/ **Superstructure et Idéologie**
- **Définition simple :** La superstructure englobe les idées, croyances, et institutions d'une société, y compris l'idéologie.
- **Exemple :** Les lois, les médias, la religion, etc.

4/ **Citation Fondamentale**
- **Citation :** "Les idées de la classe dominante sont les idées dominantes."
- **Explication :** La classe qui contrôle l'économie a également le pouvoir d'influencer les idées qui prévalent dans la société.

5/ **Analogie Photographique**
- **Explication simple :** Imagine que l'idéologie fonctionne comme une photo inversée de la réalité, tout comme une photo négative dans une vieille caméra.
- **Exemple :** L'idéologie peut nous donner une vision déformée de la réalité, comme si nous regardions le monde à travers un filtre.

6/ **Fausse Conscience et Discours**
- **Définition simple :** Les idées dominantes peuvent créer une "fausse conscience" où les gens ne voient pas la réalité telle qu'elle est, mais plutôt telle que la classe dominante veut qu'ils la voient.
- **Exemple :** Des discours politiques qui masquent les inégalités économiques.

7/ **Évolution de la Définition**
- **Évolution :** Initialement, Marx opposait clairement l'idéologie à la réalité matérielle. Plus tard, il a opposé l'idéologie à la science marxiste, considérée comme une libération de croyances pré-scientifiques.

8/ **Conclusion**
- **Récapitulation :** L'idéologie chez Marx est une manière dont les idées sont façonnées par la structure économique de la société. Comprendre cela permet de questionner les idées dominantes et d'aspirer à une pensée plus critique.

9/ **Lecture Recommandée**
- **Pour aller plus loin :** Lire des extraits de "L'Idéologie Allemande" ou d'autres écrits de Marx pour approfondir la compréhension.

10/ **Discussion et Réflexion**
- **Discussion :** Engager une conversation sur la manière dont ces idées s'appliquent aux événements actuels.
- **Réflexion :** Réfléchir sur la manière dont les idées de Marx peuvent aider à comprendre les mécanismes sociaux dans le monde d'aujourd'hui.

</div>

:::


#### 4/ Créer une fiche d'objectifs et de compétences

:::exemple collapsible Un exemple en Mathématiques (secondes) sur les droites du plan

<div markdown class="user">
Tu es un conseiller en pédagogie qui aide les enseignants à réaliser des fiches d’objectifs et de compétences à atteindre pour les élèves.
Je suis un enseignant de mathématiques en lycée et je fais un cours sur les droites du plan pour des élèves de secondes.
Voici les capacités attendues décrites dans le bulletin officiel :
Déterminer une équation de droite à partir de deux points, un point et un vecteur directeur ou un point et la pente.
Déterminer la pente ou un vecteur directeur d’une droite donnée par une équation ou une représentation graphique.
Tracer une droite connaissant son équation cartésienne ou réduite.
Établir que trois points sont alignés ou non.
Déterminer si deux droites sont parallèles ou sécantes.
Résoudre un système de deux équations linéaires à deux inconnues, déterminer le point d’intersection de deux droites sécantes.
</div>

<div markdown class="IA">

Fiche d'Objectifs : Les Droites du Plan

##### Objectif Général
Comprendre et maîtriser les concepts et les techniques de base de la géométrie analytique pour étudier les droites dans le plan cartésien.

##### Objectifs Spécifiques

1/ Détermination d'équations de droite
- Calculer l'équation d'une droite passant par deux points donnés.
- Déduire l'équation d'une droite à partir d'un point et d'un vecteur directeur.
- Utiliser un point et la pente pour établir l'équation d'une droite.

2/ Analyse de la pente et du vecteur directeur
- Extraire la pente d'une droite à partir de son équation.
- Identifier un vecteur directeur pour une droite représentée graphiquement ou par une équation.

3/ Représentation graphique de droites
- Tracer une droite en utilisant son équation sous forme cartésienne ou réduite.

4/ Alignement de points
- Vérifier l'alignement de trois points dans le plan.

5/ Étude des positions relatives de droites
- Déterminer si deux droites sont parallèles.
- Identifier si deux droites sont sécantes et, le cas échéant, trouver leur point d'intersection.

6/ Résolution de systèmes d'équations
- Résoudre un système de deux équations linéaires à deux inconnues.
- Appliquer la résolution de systèmes pour trouver l'intersection de deux droites.

##### Fiche de Compétences : Les Droites du Plan

1/ Calcul et Analyse
- Effectuer des calculs pour déterminer des équations de droites.
- Analyser des équations pour en extraire des caractéristiques clés comme la pente et le vecteur directeur.

2/ Représentation et Interprétation
- Représenter graphiquement des droites à partir d'équations.
- Interpréter des graphiques pour en déduire des équations.

3/ Raisonnement et Démonstration
- Utiliser le raisonnement logique pour vérifier l'alignement de points.
- Démontrer la parallélisme ou l'intersection de droites.

4/ Résolution de Problèmes
- Appliquer des méthodes algébriques pour résoudre des systèmes d'équations.
- Utiliser des compétences analytiques pour résoudre des problèmes géométriques complexes.
</div>
:::


### ✏️ Activités & documents

#### 1/ Créer un texte support pour une activité

Les IA permettent de générer facilement un texte exploitable en classe comme support de réflexion ou pour faire un exercice.

On peut spécifier des contraintes à respecter, au niveau du contenu ou bien au niveau de la formulation (vocabulaire employé, niveau de difficulté, style …).

:::exemple collapsible Création de deux textes supports en Français (CM1/CM2) pour faire comprendre la distinction entre registre soutenu et registre familier

Ecris un texte d'environ 50 mots sur le thème du judo avec un registre soutenu, puis le même texte avec un registre familier, pour des élèves en CM1-CM2. {.user}

<div markdown class="IA">
    
##### Registre soutenu :
Au cours des séances de judo, une effervescence empreinte d'enthousiasme nous animait. Revêtus de nos kimonos hebdomadaires, nous nous exerçions sur le tatami sous les directives bienveillantes du professeur. Les subtilités des techniques, entre chutes et prises, se dévoilaient, façonnant ainsi des moments d'apprentissage et d'épanouissement au sein de cette discipline raffinée.

##### Registre familier :
Pendant nos cours de judo, on était à fond ! Tous les mardis, on se mettait nos kimonos et on se laissait guider par le prof sur le tatami. Il nous montrait des trucs chelous, genre des chutes bizarres, et on essayait de pas se ramasser comme des quiches. C'était trop marrant !

</div>
    
:::

:::exemple collapsible Création d'un texte support en Anglais (lycée) sur la distinction entre la première et la deuxième génération des droits humains

Crée un texte d'environ 100 mots en anglais, niveau lycée, qui explique ce que sont les deux grandes générations de droits humains {.user}

<div markdown class="IA">

Human rights are categorized into two broad generations, each reflecting the evolving societal needs and aspirations.
    
The first generation, often termed "civil and political rights," emerged in the 18th and 19th centuries. These rights encompass individual liberties, such as freedom of speech, the right to a fair trial, and the prohibition of torture. They were vital during struggles for democracy and against oppressive regimes.

The second generation, known as "economic, social, and cultural rights," emerged in the 20th century. These rights focus on collective well-being, including the right to work and an adequate standard of living. They address social and economic inequalities and are particularly crucial in promoting social justice and human dignity.

</div>
 
:::

#### 2/ Créer une image support

:::exemple collapsible Création d'une image en physique (6ème) pour illustrer les états de la matière 

Description de l'image : Un glacier au fond, quelqu'un en gros plan qui boit de l'eau et de la vapeur d'eau qui sort de sa bouche {.user}

![](https://minio.apps.education.fr/codimd-prod/uploads/upload_0d27f2c969b4e6957b85fc238e292055.png) {.IA}


:::

:::exemple collapsible Création d'une image en Langues comme support d'une discussion (ici sur le port de l'uniforme en classe)

<aside><p>Pour les images, on obtient souvent de meilleurs résultats en les décrivant en anglais. On peut aussi d'abord faire sa description en français et utiliser un outil comme <a href="https://www.deepl.com/translator">Deepl</a> pour avoir un équivalent en Anglais</p>

    <p>Autre astuce : on peut utiliser une IA générative de texte (exemple : ChatGPT) pour lui faire concevoir le prompt le plus efficace pour obtenir une image avec une autre IA qui crée des images (exemple : Dall-E).</p>
</aside>

Two students are chatting opposite each other. The boy is wearing a strict school uniform with a closed black jacket and tie, while the girl is dressed in green basketball pants and a red T-shirt. {.user}


![](https://minio.apps.education.fr/codimd-prod/uploads/upload_7baebd8411f20ef6e43f8b4a83a4b007.png) {.IA}

<div markdown class="IA">
    
Autre image générée avec le même prompt, en choisissant un style réaliste.
    
![](https://minio.apps.education.fr/codimd-prod/uploads/upload_8049db0403a45cccb08002411f13ab2f.png)

</div>

:::


#### 3/ Créer une liste des concepts importants et de leurs définitions

:::exemple collapsible Définir une liste de termes et expliquer la signification d'une liste de dates dans un cours en histoire (5ème)

Dans le cadre d'un cours pour des élèves au collège en 5e sur l'empire byzantin et l'empire carolingien, fais une liste en définissant les termes suivants : empire, patriarche, missionnaire, missi dominici, monastère, capitulaire, écriture caroline ; puis explique la signification de ces dates : 800, 843, 1054, 1453 {.user}

<div markdown class="IA">

Bien sûr, voici une liste définissant les termes que vous avez mentionnés pour un cours sur l'Empire byzantin et l'Empire carolingien :

- Empire : Un vaste territoire sous l'autorité d'un seul dirigeant, généralement un empereur.
- Patriarche : Le chef de l'Église orthodoxe orientale, responsable d'une région spécifique. Le patriarche est comparable au titre de pape dans l'Église catholique, bien que les deux aient des différences doctrinales.
- Missionnaire : Une personne envoyée pour propager une religion, une foi ou une idéologie particulière dans une région spécifique.
- Missi Dominici : Des émissaires envoyés dans l'Empire carolingien pour superviser les affaires locales et s'assurer que les directives royales étaient suivies.
- Monastère : Un établissement religieux où des moines ou des moniales vivent en communauté, consacrés à la prière, à l'étude et au travail.
- Capitulaire : Un capitulaire est une disposition législative ou un décret émis par un souverain, en particulier dans le contexte de l'Empire carolingien. 
- Écriture caroline : style d'écriture développé à l'époque de Charlemagne, caractérisé par des lettres claires et uniformes, jouant un rôle important dans la préservation des textes et des connaissances au sein de l'Empire carolingien.

En ce qui concerne les dates spécifiques :

- 800 : Couronnement de Charlemagne comme empereur par le pape Léon III à Rome, marquant le début du Saint Empire romain germanique.
- 843 : Le traité de Verdun, qui a divisé l'Empire carolingien en trois parties entre les petits-fils de Charlemagne, marquant le début de la France, de l'Allemagne et de la Lotharingie.
- 1054 : Le schisme entre l'Église catholique romaine et l'Église orthodoxe orientale, connu sous le nom de Grand Schisme, résultant en une division permanente entre les deux branches du christianisme.
- 1453 : La chute de Constantinople aux mains des Ottomans, mettant fin à l'Empire byzantin et marquant la fin de l'Antiquité et le début de la Renaissance.

</div>


:::

:::exemple collapsible Un exemple en EMC (secondes) sur le thème : fondements et fragilités du lien social

Tu dois préparer un cours en éducation morale et civique sur les fondements et les fragilités du lien social à des élèves de secondes. Fais une liste de termes techniques sur ce sujet et donne leur définition. {.user}

<div markdown class="IA">

Bien sûr, voici une liste de termes techniques liés aux fondements et aux fragilités du lien social en éducation morale et civique, accompagnés de leurs définitions :

##### Lien social :

Définition : Le lien social se réfère aux relations interpersonnelles qui connectent les individus au sein d'une communauté ou d'une société. Il englobe les interactions, les normes, les valeurs et les institutions qui contribuent à la cohésion sociale.

##### Cohésion sociale :

Définition : La cohésion sociale représente le degré de solidarité, d'unité et de stabilité au sein d'une société. Elle mesure la capacité des individus à vivre ensemble harmonieusement malgré leurs différences.

##### Capital social :

Définition : Le capital social désigne les ressources provenant des relations sociales, telles que la confiance, la coopération et le soutien mutuel. Un niveau élevé de capital social favorise le bien-être collectif.

##### Déviance sociale :

Définition : La déviance sociale se réfère aux comportements, normes ou valeurs qui s'écartent des attentes ou des normes établies au sein d'une société, pouvant entraîner des conséquences négatives sur le lien social.

##### Inclusion sociale :

Définition : L'inclusion sociale vise à garantir la participation équitable de tous les individus à la vie sociale, économique et politique, en minimisant les barrières qui pourraient exclure certains groupes.

##### Exclusion sociale :

Définition : L'exclusion sociale se produit lorsque des individus ou des groupes sont volontairement ou involontairement marginalisés de la société, les privant ainsi d'accès aux ressources et opportunités essentielles.

##### Multiculturalisme :

Définition : Le multiculturalisme reconnaît et valorise la diversité culturelle au sein d'une société. Il encourage le respect des différences et la coexistence pacifique des différentes identités culturelles.
    
##### Intégration sociale :

Définition : L'intégration sociale implique l'incorporation réussie des individus dans la société, en favorisant leur participation active et leur adhésion aux normes et valeurs communes.

##### Anomie :

Définition : L'anomie se réfère à un état de désintégration sociale où les normes et les valeurs perdent leur influence, entraînant une confusion et une perte de repères au sein de la société.
    
##### Solidarité :

Définition : La solidarité représente le sentiment d'interdépendance et de responsabilité mutuelle entre les membres d'une société, contribuant à renforcer le tissu social.
    
##### Normes sociales :

Définition : Les normes sociales sont des règles tacites ou explicites qui définissent le comportement attendu au sein d'une société, jouant un rôle clé dans la préservation du lien social.    
    
</div>


:::

:::exemple collapsible Un exemple en SVT (secondes) sur l'organisme pluricellulaire

<div markdown class="user">
Tu es un conseiller en pédagogie qui aide les enseignants à créer une liste de définitions des notions importantes sur un thème, avec un exemple à chaque fois
Je suis un enseignant de sciences de la vie et de la Terre en lycée et je fais un cours sur l’organisme pluricellulaire pour des élèves de secondes.
Voici les notions fondamentales décrites dans le bulletin officiel:
cellule, matrice extracellulaire/paroi, tissu, organe ; organite, spécialisation cellulaire, ADN, double hélice, nucléotides (adénine, thymine, cytosine,guanine), complémentarité, gène, séquence.
</div>

<div markdown class="IA">
Pour créer une liste de définitions des notions importantes sur le thème de l'organisme pluricellulaire, voici une ébauche de définitions accompagnées d'exemples pour chacune des notions que vous avez mentionnées :

- Cellule : Unité de base structurale et fonctionnelle de tous les organismes vivants. Elle est considérée comme l'unité élémentaire de la vie.
	- Exemple : Une cellule épithéliale qui tapisse l'intérieur de la bouche.

- Matrice extracellulaire/Paroi : Ensemble complexe de molécules sécrétées par les cellules qui fournit un support structurel et biochimique aux cellules environnantes.
	- Exemple : La matrice extracellulaire du cartilage, riche en collagène et en protéoglycanes.

- Tissu : Groupe de cellules similaires et de leurs produits extracellulaires qui accomplissent une fonction spécifique.
	- Exemple : Le tissu musculaire qui permet la contraction et le mouvement.

- Organe : Structure composée de plusieurs types de tissus qui travaillent ensemble pour accomplir une fonction spécifique.
	- Exemple : Le cœur, un organe composé de tissu musculaire, de tissu nerveux et de vaisseaux sanguins.

- Organite : Compartiment spécialisé à l'intérieur d'une cellule qui remplit une fonction spécifique.
	- Exemple : Les mitochondries, organites responsables de la production d'énergie.

- Spécialisation cellulaire : Processus par lequel une cellule non différenciée devient transformée en une cellule avec une fonction spécifique.
	- Exemple : Les globules rouges spécialisés dans le transport de l'oxygène.

- ADN : Acide désoxyribonucléique, la molécule qui porte l'information génétique des organismes vivants.
	- Exemple : L'ADN contenu dans le noyau d'une cellule de peau humaine.

- Double hélice : Structure de l'ADN caractérisée par deux brins enroulés l'un autour de l'autre.
	- Exemple : La représentation classique de l'ADN, souvent comparée à une échelle torsadée.

- Nucléotides (adénine, thymine, cytosine, guanine) : Les blocs de construction de l'ADN, chacun composé d'une base azotée, d'un sucre et d'un groupe phosphate.
	- Exemple : La séquence de nucléotides dans un fragment d'ADN qui pourrait être ATCGAA.

- Complémentarité : Principe selon lequel les bases nucléotidiques de l'ADN s'apparient spécifiquement (A avec T et C avec G).
	- Exemple : Dans la double hélice de l'ADN, si un brin a la séquence AGTC, le brin complémentaire aura la séquence TCAG.

- Gène : Segment d'ADN qui contient les instructions pour la fabrication d'une protéine ou d'un ensemble de protéines.
	- Exemple : Le gène de l'hémoglobine qui code pour la protéine transportant l'oxygène dans le sang.

- Séquence : Ordre spécifique des nucléotides dans un brin d'ADN.
	- Exemple : La séquence qui code pour une protéine peut être une suite spécifique de plusieurs centaines de nucléotides.

Ces définitions et exemples peuvent être ajustés et enrichis en fonction du niveau de détail que vous souhaitez atteindre et des connaissances préalables de vos élèves. Il est également utile d'intégrer des schémas ou des modèles pour illustrer ces concepts, surtout dans les sciences de la vie et de la Terre où la visualisation peut grandement aider à la compréhension.
</div>

:::

#### 4/ Créer un tableau de distinctions

:::exemple collapsible Distinctions entre l'empire carolingien et l'empire byzantin en Histoire (5ème)

Propose un tableau de distinctions entre l'empire carolingien et l'empire byzantin au niveau collège.

<aside>Avec ce genre de prompt, il faut se méfier des hallucinations possibles de l'IA, mais la structuration proposée peut fournir une base intéressante</aside>

<div markdown class="IA">

| Caractéristiques                | Empire Carolingien         | Empire Byzantin            |
| ------------------------------- | -------------------------- | -------------------------- |
| **Période**                     | 800-888 (après l'effondrement de l'Empire romain d'Occident) | 330-1453 (suite à la fondation de Constantinople en 330 jusqu'à la chute de Constantinople en 1453) |
| **Localisation**                | Europe occidentale         | Bassin méditerranéen, Anatolie |
| **Capitale**                    | Aix-la-Chapelle (principalement sous Charlemagne) | Constantinople (moderne Istanbul) |
| **Langue**                      | Latin et dialectes germaniques | Grec, plus tard le latin (administratif) |
| **Religion**                    | Christianisme, notamment catholique romain | Christianisme orthodoxe |
| **Leaders clés**                | Charlemagne, Louis le Pieux | Empereurs comme Justinien, Basile II |
| **Système politique**           | Monarchie féodale décentralisée | Monarchie impériale centralisée |
| **Relations avec l'Église**     | Étroite alliance avec l'Église catholique | Schisme de 1054 avec l'Église orthodoxe, relations étroites avec l'Église orthodoxe par la suite |
| **Héritage culturel**           | Renaissance carolingienne, préservation des traditions romaines | Héritage grec et romain, codification du droit romain (Corpus Juris Civilis) |
| **Art et architecture**         | Art préroman, influences romaines | Art byzantin, mosaïques, architecture à coupole (exemple : Hagia Sophia) |
| **Relations extérieures**       | Relations avec d'autres royaumes européens, confrontations avec les Vikings et les Sarrasins | Relations avec les États voisins, notamment les Perses et les Arabes, conflits avec les croisés latins |
| **Chute**                       | Fragmentation après la mort de Louis le Pieux en 840 | Prise de Constantinople par les Ottomans en 1453 |

</div>

:::

:::exemple collapsible Distinction de familles de matériau en Technologie (collège)

Fais un tableau de distinctions pour expliquer les différentes familles de matériaux en technologie au niveau collège {.user}

<aside>Avec ce genre de prompt, il faut se méfier des hallucinations possibles de l'IA, mais la structuration proposée peut fournir une base intéressante</aside>

<div markdown class="IA">

| Famille de Matériaux        | Propriétés Générales                         | Exemples                           | Applications Courantes            |
| --------------------------- | ------------------------------------------- | ---------------------------------- | ---------------------------------- |
| **Métaux**                  | Conducteurs de chaleur et d'électricité, malléables, ductiles | Fer, aluminium, cuivre            | Constructions, câblage électrique, ustensiles de cuisine |
| **Polymères**               | Légers, isolants électriques, flexibles      | Plastiques (polyéthylène, PVC), caoutchouc | Emballages, jouets, revêtements     |
| **Céramiques**              | Durs, résistants à la chaleur, isolants     | Porcelaine, céramique technique    | Vaisselle, carreaux, composants électroniques |
| **Composites**              | Combinaison de plusieurs matériaux         | Fibre de verre, fibre de carbone   | Aérospatiale, sports, construction  |
| **Verre**                   | Transparent, rigide, fragile                | Verre ordinaire, verre borosilicaté | Fenêtres, bouteilles, instruments optiques |
| **Matériaux naturels**      | Extraits directement de la nature          | Bois, pierre, coton                | Construction, textiles, artisanat   |
| **Matériaux synthétiques**  | Fabriqués par l'homme à partir de composés chimiques | Nylon, polyester, polystyrène    | Vêtements, emballages, isolants    |


</div>

:::


### 🎯 Évaluations

#### 1/ Créer une liste de questions

##### a) Questions pour la révision d'un cours

En fin de cours sur un chapitre, c'est une pratique courante dans plusieurs matières de proposer une liste de questions de révision du cours, qui peut servir à l'autoévaluation des élèves, ou bien qui peut être le support d'une interrogation en classe. L'IA peut aider à créer une telle liste de questions.

:::exemple collapsible Questions en SES (1ère) pour un cours sur les défaillances du marché

Pour un cours de SES sur les défaillances du marché, fais une liste d'environ 10 questions auxquelles les élèves doivent savoir répondre en fin de cours. Ne réponds pas aux questions, donne juste la liste. {.user}

<aside>Remarque : cela peut être utile pour chatGPT de préciser : "donne juste la liste dans un bloc code prêt à copier" pour pouvoir rapidement copier-coller la proposition</aside>

<div markdown class="IA">

1. Qu'est-ce qu'une défaillance du marché ?
1. Quels sont les types de défaillances du marché les plus courants ?
1. Expliquez le concept d'externalité. Donnez des exemples concrets.
1. Qu'est-ce que l'asymétrie d'information et comment peut-elle causer une défaillance du marché ?
1. Décrivez ce que sont les biens collectifs : comment cela peut-il entraîner des défaillances du marché ?
1. Quelle est la différence entre les biens collectifs et les biens communs ? Donnez des exemples de chaque.
1. Comment les monopoles peuvent-ils causer des défaillances du marché ?
1. Quel rôle le gouvernement peut-il jouer pour remédier aux défaillances du marché ?
1. Donnez des exemples de politiques gouvernementales visant à corriger les défaillances du marché.

</div>

:::

##### b) Questions sur un texte

On peut aussi donner à l'IA un texte et lui demander de trouver des questions intéressantes à poser sur ce texte

:::exemple collapsible Questions sur un texte en anglais à propos de la philosophie morale de Kant en DNL Anglais/Philosophie

<div markdown class="user">

Propose 3 questions en anglais pour vérifier que les étudiants ont compris ce texte : 

« Deontology and consequentialism are key terms in philosophical debate, which describe two opposing approaches to ethical issues. Derived from the Greek word deon, or duty, deontology presumes that actions are right or wrong regardless of consequences. The father of these ‘duty-based’ ethics, Immanuel Kant, argued that subjective and situation-specific assessments are not a reliable source of morality. Universal laws are therefore necessary to govern our behaviour. Kant’s universal laws were born from the notion that humans have intrinsic worth, or dignity, by virtue of their unique rationality. To violate their autonomy- by deceiving them, slaying them or enslaving them- is to disrespect this dignity. In _Groundwork of the Metaphysic of Morals_ he wrote: ‘Every rational being exists as an end in himself and not merely as a means to be arbitrarily used by this or that will’. »

</div>
    
<div markdown class="IA">
Certainly, here are three questions in English to check if students have understood the text on Deontological Ethics and Nonhuman Animals:
- What is the fundamental concept of deontology, and how does it differ from consequentialism in approaching ethical issues?
- According to Immanuel Kant, what is the basis for deontological ethics and the need for universal laws in governing behavior? How does he connect this to the concept of intrinsic worth or dignity?
- In Kant's perspective, what is the significance of treating every rational being as an "end in himself" and not merely as a means to be used by others? How does this relate to respecting human autonomy and dignity?

</div>

Je veux une question autour de la source de nos devoirs moraux (en anglais). Propose 5 formulations. {.user}

<div markdown class="IA">
Certainly, here are five questions formulated around the source of our moral duties:
- What is the source or foundation of moral duties, as explained in the text?
- According to the text, why does Immanuel Kant argue that subjective and situation-specific assessments are unreliable for determining moral duties?
- How does Kant's concept of "duty-based" ethics relate to the idea of universal laws governing our behavior and our moral obligations?
- In the text, what is the role of humans' intrinsic worth and dignity in determining our moral duties?
- Can you explain how Kant's perspective on treating rational beings as "ends in themselves" influences the source of our moral duties?
</div>
    
:::


:::exemple collapsible Questionnaire de lecture en Français sur <i>Les Misérables</i>

<div markdown class="user">
Je suis un enseignant de français en collège et je souhaite poser des questions que le livre "Les misérables" sous forme de QCM.
Fais-moi tout d'abord un résumé
</div>

<div markdown class="IA">
 "Les Misérables" est un roman écrit par Victor Hugo, publié pour la première fois en 1862. Il se déroule en France au XIXe siècle et raconte l'histoire de plusieurs personnages, dont l'un des principaux est Jean Valjean, un ancien forçat qui cherche la rédemption.

L'intrigue tourne autour de la lutte pour la justice sociale et la rédemption personnelle, avec des thèmes tels que la pauvreté, l'injustice, l'amour, la révolution et la quête de sens. Parmi les autres personnages importants, on trouve Cosette, la jeune fille que Valjean prend sous son aile ; Marius, un jeune homme épris de Cosette ; Javert, l'inspecteur de police déterminé à capturer Valjean ; et de nombreux autres personnages secondaires.

Le roman est divisé en cinq parties et couvre une période de plusieurs décennies. Il offre un aperçu profond et poignant de la société française de l'époque, avec un accent particulier sur les conditions de vie des pauvres et les luttes pour la justice et la liberté.

Si vous souhaitez poser des questions sous forme de QCM, je peux vous aider à formuler des questions QCM si vous le souhaitez.   

</div>

Fais le qcm le plus long possible{.user}

<div markdown class="IA">
Bien sûr, voici un QCM relativement long sur "Les Misérables". Assurez-vous de le personnaliser ou de le découper en plusieurs questions si nécessaire pour vos besoins pédagogiques :

Question 1 : Quel est le cadre temporel principal de l'histoire dans "Les Misérables" ?
a) Le XVIIe siècle
b) Le XVIIIe siècle
c) Le XIXe siècle
d) Le XXe siècle

Question 2 : Qui est le personnage central du roman ?
a) Cosette
b) Marius
c) Jean Valjean
d) Éponine

Question 3 : Où se déroule principalement l'intrigue de "Les Misérables" ?
a) Paris, France
b) Londres, Royaume-Uni
c) Rome, Italie
d) New York, États-Unis

Question 4 : Quel est le nom de l'inspecteur de police obstiné qui poursuit Jean Valjean tout au long du roman ?
a) Javert
b) Thenardier
c) Marius
d) Éponine

Question 5 : Quel événement historique est au centre de la révolution décrite dans le roman ?
a) La Révolution française
b) La Révolution américaine
c) La Commune de Paris
d) La Révolution russe

Question 6 : Qui est le jeune homme idéaliste épris de Cosette ?
a) Thenardier
b) Marius
c) Javert
d) Gavroche

Question 7 : Quel est le surnom du couple d'aubergistes sans scrupules qui maltraitent Cosette au début de l'histoire ?
a) Les Thenardier
b) Les Javert
c) Les Marius
d) Les Éponine

Question 8 : Quel personnage féminin, ami de Marius, cache un amour non réciproque pour lui ?
a) Cosette
b) Éponine
c) Fantine
d) Thenardier

Question 9 : De quel type d'établissement était propriétaire Thenardier ?
a) Une école
b) Une auberge
c) Un couvent
d) Un café

Question 10 : Quel thème central du roman explore la quête de Jean Valjean ?
a) L'injustice sociale
b) L'amour et la rédemption
c) La révolution politique
d) La richesse et la prospérité

Question 11 : Dans quel contexte historique se déroule la révolution de 1832 dans le roman ?
a) La Restauration
b) La Renaissance
c) La Révolution américaine
d) La Belle Époque

Question 12 : Qui est le personnage qui meurt tragiquement à la fin du roman ?
a) Marius
b) Cosette
c) Éponine
d) Jean Valjean

Question 13 : Quelle est la longueur totale de "Les Misérables" ?
a) 100 pages
b) 500 pages
c) 1000 pages
d) 1500 pages

Question 14 : Quel est le titre original de "Les Misérables" en français ?
a) "Les Pauvres"
b) "Les Révolutionnaires"
c) "Les Malheureux"
d) "Les Misérables"

Question 15 : Quel personnage est souvent associé à l'enfance des rues et à la révolte des pauvres dans le roman ?
a) Marius
b) Thenardier
c) Éponine
d) Gavroche

N'hésitez pas à personnaliser ou à découper ce QCM en plusieurs parties en fonction de vos besoins.
</div>

:::

##### c) Questions sur une image ou une vidéo

Les IA ne sont pas nécessairement limitées à des textes, on peut trouver des IA qui vont proposer des activités à partir d'une image ou d'une vidéo

:::exemple collapsible Pistes pour l'analyse et la discussion d'une image qui reprend l'allégorie de la caverne sous forme moderne

<div markdown class="user">
Tu es un conseiller en pédagogie qui aide les enseignants. Je suis un enseignant de lycée avec des élèves de seconde. Je veux analyser une image et donner des interprétations.
    ![](https://minio.apps.education.fr/codimd-prod/uploads/upload_702077fcd45655174811df2041867c88.png)
</div>

<div markdown class="IA">
    
 Cette image intitulée "La Caverne Moderne" semble être une caricature moderne de la célèbre allégorie de la caverne de Platon. Dans l'allégorie originale, Platon décrit des hommes enchaînés dans une caverne, face à un mur, ne voyant que les ombres projetées par des objets passant devant un feu derrière eux. Platon utilise cette métaphore pour illustrer la situation des humains face à la connaissance : les ombres représentent les perceptions sensorielles du monde, tandis que la réalité hors de la caverne (que les prisonniers ne peuvent voir) représente le monde des idées, accessible seulement par la raison.

Dans l'interprétation moderne que nous avons ici, la caverne semble être remplacée par un espace domestique où une personne est enchaînée non pas par des liens physiques mais par des câbles à son bureau et à son ordinateur. Cela pourrait représenter l'esclavage numérique ou la dépendance à la technologie, où les individus sont "enchaînés" par leur dépendance aux appareils électroniques, réduisant leur vision du monde aux images qui leur sont présentées sur les écrans.

Voici quelques pistes pour l'analyse et la discussion en classe :
 Cette image intitulée "La Caverne Moderne" semble être une caricature moderne de la célèbre allégorie de la caverne de Platon. Dans l'allégorie originale, Platon décrit des hommes enchaînés dans une caverne, face à un mur, ne voyant que les ombres projetées par des objets passant devant un feu derrière eux. Platon utilise cette métaphore pour illustrer la situation des humains face à la connaissance : les ombres représentent les perceptions sensorielles du monde, tandis que la réalité hors de la caverne (que les prisonniers ne peuvent voir) représente le monde des idées, accessible seulement par la raison.

Dans l'interprétation moderne que nous avons ici, la caverne semble être remplacée par un espace domestique où une personne est enchaînée non pas par des liens physiques mais par des câbles à son bureau et à son ordinateur. Cela pourrait représenter l'esclavage numérique ou la dépendance à la technologie, où les individus sont "enchaînés" par leur dépendance aux appareils électroniques, réduisant leur vision du monde aux images qui leur sont présentées sur les écrans.

Voici quelques pistes pour l'analyse et la discussion en classe :

1. **Comparaison avec l'allégorie originale** :
   - Comment cette image reflète-t-elle l'allégorie de la caverne de Platon?
   - Quelles sont les différences et les similitudes dans les deux cas?

2. **Technologie et perception** :
   - En quoi la technologie moderne peut-elle limiter ou déformer notre perception de la réalité?
   - Les chaînes symboliques de la technologie sont-elles aussi restrictives que les chaînes physiques dans l'allégorie de Platon?

3. **Esclavage moderne** :
   - Qu'est-ce que cette image suggère sur notre relation avec la technologie?
   - Pouvons-nous dire que nous sommes "libres" dans notre utilisation des technologies modernes?

4. **Société et individu** :
   - Comment cette image commente-t-elle la société contemporaine et la place de l'individu en son sein?
   - Quelles pourraient être les conséquences à long terme de cet "enchaînement" à la technologie?

5. **Éducation et technologie** :
   - Comment cette image peut-elle être utilisée pour parler de l'utilisation de la technologie dans l'éducation?
   - Quel est le rôle de l'éducateur dans la navigation entre les avantages de la technologie et les risques de dépendance ou de distraction?

Cette image peut servir de point de départ pour une discussion profonde sur la manière dont la technologie influence notre compréhension de la réalité et notre capacité à réfléchir de manière critique. Cela peut également amener les élèves à réfléchir à leur propre usage de la technologie et à envisager des façons de gérer cet usage de manière à favoriser une relation plus équilibrée et consciente avec les outils numériques.  
    
</div>

:::

:::exemple collapsible Création d'une activité sur les volcans (cycle 4) à partir d'une vidéo

<aside>Pour pouvoir travailler à partir d'une vidéo, il faut soit utiliser la version 4 de ChatGPT avec un plugin spécifique, soit une autre IA dédiée à ce type de support</aside>

<div markdown class="user">

Je suis enseignant en cycle 4  et je veux traiter des volcans avec mes élèves.
Je veux créer des questions QCM et vrai faux à partir d'une vidéo.
Tu donneras les feedbacks pour les bonnes et les mauvaises réponses. 
Tu as compris? 

</div>

<div markdown class="IA">

Oui, j'ai compris. Pour créer des questions de type QCM et vrai/faux, j'aurai besoin de voir la vidéo sur les volcans que vous souhaitez utiliser. Pouvez-vous me fournir le lien de cette vidéo ? Une fois que j'aurai accès à la vidéo, je pourrai élaborer des questions adaptées, ainsi que les feedbacks pour les réponses correctes et incorrectes.

</div>

<div markdown class="user">

https://www.youtube.com/watch?v=q3H0un6dDKE

</div>


<div markdown class="IA">

Basé sur la vidéo "COMMENT UN VOLCAN ENTRE-T-IL EN ÉRUPTION ? - Les essentiels de Jamy | Lumni", voici quelques questions de type QCM et vrai/faux, accompagnées de leurs feedbacks :

Questions à Choix Multiples (QCM)

##### Quelle est la principale différence entre les volcans rouges et les volcans gris ?

A) Les volcans rouges sont plus hauts que les volcans gris.  
B) Les volcans rouges émettent principalement de la lave fluide, tandis que les volcans gris sont explosifs et projettent des cendres.  
C) Les volcans gris sont plus fréquents que les volcans rouges.  
D) Les volcans rouges se trouvent uniquement en Indonésie.  

Feedback Correct (B) : Excellent ! Les volcans rouges sont effusifs et émettent de la lave fluide, tandis que les volcans gris sont explosifs et projettent des cendres et des gaz.

Feedback Incorrect : Réessayez. La différence clé entre les volcans rouges et gris réside dans leur type d'éruption : les volcans rouges sont effusifs avec de la lave fluide, tandis que les volcans gris sont explosifs.

##### Que se passe-t-il dans la chambre magmatique d'un volcan avant une éruption ?

A) Le magma se refroidit et se solidifie.  
B) Des bulles de gaz se forment et augmentent la pression.  
C) Le magma sort immédiatement par la cheminée.  
D) La chambre magmatique se vide complètement.  

Feedback Correct (B) : Parfait ! Des bulles de gaz se forment dans la chambre magmatique, augmentant la pression jusqu'à l'éruption.

Feedback Incorrect : Pas tout à fait. Avant une éruption, des bulles de gaz se forment dans la chambre magmatique, augmentant la pression.

Questions Vrai/Faux

##### Vrai ou Faux : Les volcans gris sont moins dangereux que les volcans rouges.

Réponse : Faux.

Feedback : Correct, c'est faux. Les volcans gris sont souvent plus dangereux en raison de leurs éruptions explosives et rapides.


##### Vrai ou Faux : La lave est appelée magma lorsqu'elle est à l'extérieur de la terre.

Réponse : Faux.

Feedback : Bien joué, c'est faux. La roche en fusion est appelée magma lorsqu'elle est sous la surface et devient de la lave lorsqu'elle sort à l'extérieur.

</div>

:::


#### 2/ Créer un quiz avec plusieurs types de question à intégrer dans un logiciel

Le principe est d'abord d'apprendre à l'IA la syntaxe du logiciel pour ensuite lui faire produire un quiz qui respecte cette syntaxe.

:::exemple collapsible Créer des quiz avec la syntaxe de Text2quiz

<div markdown class="user">

Je t'explique la syntaxe de text2quiz pour rédiger un quiz, qui est la suivante :
- pour un vrai/faux : écrire "VF || Proposition || V"  avec à la fin V si c'est vrai / F si c'est faux
- pour une flashcard : écrire "Flashcard || Question || Réponse"
- pour une remise dans l'ordre de plusieurs items : écrire "Ordre || Item 1 | Item 2 | Item 3 || Consigne" ; pour 4 items ce serait : "Ordre || Item 1 | Item 2 | Item 3  | Item 4 || Consigne" Attention, la consigne ou la question qui explique ce qu'il faut faire doit être mise à la fin ici
- pour un QCM : écrire "QCM || Question || Réponse 1 | Réponse 2 | Réponse 3 | Réponse 4" et ajouter  "V:" juste devant chaque réponse vraie 
- pour l'association entre un item et son étiquette : écrire "Association || {{Item 1 | Étiquette 1}}{{Item 2 | Étiquette 2}}" et ajouter {{Item 3 | Étiquette 3}} et ainsi de suite s'il y a plusieurs items

As-tu compris la syntaxe ? Réponds simple par oui ou par non. Tu devras ensuite produire des quiz en respectant la syntaxe de text2quiz que tu viens d'apprendre et que tu devras retenir pour tous les prochains quiz que je te demanderai de faire.
</div>

Oui {.IA}

Propose un quiz de 8 questions avec tous les types de question sur les états de la matière en physique pour des élèves de 5e au collège {.user}

<div markdown class="IA">
VF || L'eau bout à une température de 100 degrés Celsius || V
Flashcard || Quel est le terme pour le passage de l'état gazeux à l'état liquide ? || Condensation
QCM || Quel est l'état de la matière qui a une forme définie ? || V: Solide | Liquide | Gaz
Association || {{Eau solide | Glace}}{{Eau liquide | Eau du robinet}}{{Eau gazeuse | Vapeur}} || Associez chaque état de l'eau à sa description.
Flashcard || Qu'est-ce qui caractérise un gaz en termes de forme et de volume ? || Un gaz n'a ni forme ni volume définis, il remplit complètement le conteneur qui le contient
Ordre || Solide | Liquide | Gaz || Mettez ces états de la matière dans l'ordre croissant de l'agitation moléculaire.
VF || Les molécules dans un état solide sont plus éloignées les unes des autres par rapport à l'état liquide || F
VF || Dans l'état gazeux, les molécules sont étroitement liées || F

:::

#### 3/ Créer un corrigé

L'IA peut même proposer une correction d'une évaluation. Pour des questions simples, cela permettrait d'obtenir des formulations déjà rédigées, que l'on peut simplement améliorer (pour gagner du temps).

Pour des questions plus complexes, les réponses risquent d'être plus vagues et de comporter davantage d'hallucinations, mais ce type de document peut éventuellement être le support d'un exercice à faire faire aux élèves : on peut leur proposer de corriger et d'améliorer le corrigé de l'IA.

:::exemple collapsible Corrigé d'un sujet de Francais (brevet)
 
<div markdown class="user">
Tu es un conseiller en pédagogie qui aide les enseignants à créer les corrections d'évaluation. Je suis un enseignant de français en collège avec des élèves de troisièmes qui vont passer l'épreuve du brevet. Je vais te donner le PDF d'un sujet de Français et tu vas la correction de ce sujet en répondant à chaque question. Voici le PDF: https://eduscol.education.fr/document/53331/download
</div>

<div markdown class="IA">
Le sujet de l'examen de français pour la session 2023 du Diplôme National du Brevet semble être divisé en deux grandes parties : la compréhension et les compétences d’interprétation, et les compétences linguistiques et grammaticales. Voici les questions telles qu'elles sont présentées dans le document :

Compréhension et compétences d’interprétation (30 points)

- À propos du texte de Michel Pastoureau, "Les couleurs de nos souvenirs":
- a) Où et quand se situe ce souvenir ? (2 points)
- b) Qui est le personnage principal ? Qui est le narrateur ? À quel genre littéraire appartient ce texte ? (3 points)

- Qu’est-ce qui montre dans le texte que l’achat du blazer est un événement important dans la vie du personnage ? (3 points)

- Que pensez-vous de l’attitude du vendeur ? (3 points)

- Pourquoi le personnage du jeune homme ressent-il de la « honte » ? (3 points)

- Qu’est-ce qui vous paraît comique dans le passage de l'essayage du blazer ? (3 points)

- Pourquoi ce souvenir est-il important pour le narrateur ? (3 points)

- Comment jugez-vous l’attitude du jeune personnage ? La comprenez-vous ? (4 points)

- Quels liens pouvez-vous établir entre le texte et la photographie "Essayage" de Richard Kalvar, 1975 ? (6 points)

Compétences linguistiques et grammaticales (20 points)
9. Analyse des temps et modes des verbes dans deux phrases données. (3 points)

- À propos du mot "importable":
- a) Expliquez la formation de ce mot. (1,5 point)
- b) Donnez la nature de ce mot. (0,5 point)
- c) Proposez un mot construit sur le même modèle qu’« importable » à partir du verbe « imaginer ». (1 point)

- Analyse grammaticale d'une phrase. (2 points)

- Analyse logique et réécriture d'un passage. (2 points)

- Réécriture d'un passage en changeant "les adolescents" par "un adolescent" et "des idées" par "un avis". (10 points)

Pour commencer la correction, je vais répondre à la première question de compréhension et compétences d’interprétation :

- a) Ce souvenir se situe dans un magasin de vêtements pour hommes, dans une ville de banlieue sud, au printemps 1960. (2 points)
- b) Le personnage principal est l'auteur lui-même en tant que jeune garçon, Michel Pastoureau, qui est également le narrateur. Le texte appartient au genre littéraire autobiographique puisqu'il s'agit d'un souvenir personnel de l'auteur. (3 points)

Pour les réponses suivantes, je vais procéder étape par étape pour chaque question. Voulez-vous que je continue avec les réponses aux autres questions ou avez-vous une demande spécifique pour la suite ?
    
</div>
 
Continue avec les réponses aux autres questions. {.user}
    
    
<div markdown class="IA">
  Très bien, poursuivons avec les réponses aux questions de compréhension et compétences d’interprétation :

2. L'importance de l'achat du blazer dans la vie du personnage:

- L'événement est marqué par la minutie avec laquelle le narrateur décrit le processus d'achat, soulignant ses sentiments et perceptions, en particulier en ce qui concerne la couleur du blazer.
- L'importance est également soulignée par la réaction émotionnelle intense du narrateur : la honte ressentie lors du mariage et l'attention particulière qu'il porte aux nuances de couleur, qui semblent avoir un impact profond sur lui. (3 points)

3. L'attitude du vendeur:

- Le vendeur est décrit comme obséquieux et ironique, soulignant de manière déplaisante la corpulence du narrateur. Cette attitude peut être perçue comme moqueuse et manquant de sensibilité envers les sentiments d'un jeune client. (3 points)

4. La honte ressentie par le jeune homme:

- La honte provient de la conscience aiguë du narrateur des nuances de couleur et de leur signification sociale. Il ressent une honte intense car il est forcé de porter un vêtement qui, selon lui, ne correspond pas à la norme souhaitée et qui pourrait le faire paraître ridicule aux yeux des autres. (3 points)

5. Le comique dans le passage de l'essayage:

- L'aspect comique réside dans l'exagération des étapes de l'essayage et la série d'interventions des vendeurs et du chef de rayon, qui semblent disproportionnées par rapport à l'enjeu de la situation, à savoir le choix d'un blazer pour un jeune garçon. (3 points)

6. L'importance du souvenir pour le narrateur:

- Ce souvenir est significatif car il représente un moment de transition dans la vie du narrateur, marquant la fin de son enfance et le début de l'adolescence avec ses préoccupations sociales et esthétiques. C'est aussi un moment où il se confronte aux normes sociales et à la notion de vulgarité, qui influenceront sa perception future des couleurs et de leur importance. (3 points)

7. L'attitude du jeune personnage:

- L'attitude du jeune Michel Pastoureau peut être jugée comme étant celle d'un adolescent typique, qui commence à développer et à exprimer ses propres opinions et goûts, même s'ils vont à l'encontre des désirs de sa mère ou des normes sociales. Elle est compréhensible dans le contexte de la recherche d'identité propre à cette période de la vie. (4 points)

8. Liens entre le texte et la photographie "Essayage" de Richard Kalvar:

- Les deux œuvres traitent de la thématique de l'essayage et de l'importance de l'apparence extérieure. La photographie pourrait illustrer le moment de tension et de choix décrit dans le texte, mettant en lumière les aspects sociaux et personnels liés au vêtement. Une description détaillée de l'image serait nécessaire pour développer davantage cette réponse. (6 points)

Passons maintenant aux compétences linguistiques et grammaticales :

9. Analyse des temps et modes des verbes:
a) Les verbes "entends" et "ont" sont au présent de l'indicatif. (1 point)
b) Le présent est utilisé pour exprimer une action qui se poursuit dans le temps pour "entends" et une vérité générale pour "ont". (2 points)

10. À propos du mot "importable":
a) Le mot est formé par la préfixation du mot "portable" avec le préfixe "in-", qui indique la négation. (1,5 point)
b) C'est un adjectif qualificatif. (0,5 point)
c) En utilisant le verbe "imaginer", on pourrait former le mot "inimaginable". (1 point)

11. Analyse grammaticale d'une phrase:
a) "L’odieux vendeur" est le sujet de la phrase. (1 point)
b) En posant la question "qui est-ce qui convainquit ma mère ?", on identifie le sujet. (1 point)

12. Analyse logique et réécriture d'un passage:
a) Le lien logique est celui de la cause à l'effet; l'écart de nuance est la cause de la bouleversement du narrateur. (1 point)
b) "... cet infime écart de nuance me bouleversait car j’imaginais tous les regards portés sur ce blazer odieux et méprisable." (1 point)

13. Réécriture d'un passage:

- "Un adolescent a sur la vulgarité un avis qui lui est propre. Il serait souvent bien en peine de l'expliquer ou de le faire partager à un adulte, mais le vulgaire – son vulgaire – a pour lui quelque chose d’absolument rédhibitoire." (10 points)

Cela couvre les réponses aux questions basées sur le texte fourni. Si vous avez besoin d'explications supplémentaires ou d'assistance pour d'autres questions, n'hésitez pas à demander. 

</div>

:::



## ♻️  Adapter / changer de format

### Principe général

Les IA génératives peuvent créer du contenu, mais aussi transformer un contenu dans un autre format ou bien l'adapter à des contraintes spécifiques.

On peut ainsi utiliser l'IA pour créer à partir d'un document une synthèse sous forme :
- d'un résumé
- d'une carte mentale
- d'un tableau

On peut aussi utiliser l'IA dans le cadre de la différenciation afin d'adapter son document à des besoins particuliers.

Les IA génératives peuvent aussi adapter le document pour qu'il respecte un format informatique spécifique (notamment des formats propres à des logiciels de quiz).

### 📅 Planification d'un cours

#### Transformer son plan de cours en carte mentale

:::exemple collapsible Exemple d'une séquence en Philosophie sur l'éthique et la philosophie morale

<div markdown class="user">

Je veux que tu transforme le plan de mon cours en une carte mentale au format Markdown : 

Séquence 1 : Éthique et philosophie morale  
Chapitre 1 : Le bonheur  
Q1 – Peut-on parvenir au bonheur ?  
Q1a – Peut-on savoir ce qu'est le bonheur ?  
Q1b – Le désir nous fait-il nécessairement souffrir ?  
Q1c – Que pouvons-nous face au tragique de l'existence ?  
Q2 - Le bonheur est-il le but de l'existence ?  
Chapitre 2 : La morale  
Q1 – Y a-t-il une vérité en morale ?  
Q1a – La morale est-elle subjective ?  
Q1b - La morale est-elle relative à chaque culture ?  
Q2 – Comment peut-on savoir ce qui est bien et ce qui est mal ?  
Q2a – La morale repose sur nos sentiments, sur notre sensibilité ?  
Q2b – Comment la réflexion peut-elle nous guider moralement ?  

</div>

<div markdown class="IA">

<pre>
&num; Séquence 1 : Éthique et Philosophie Morale

&num;&num; Chapitre 1 : Le Bonheur
   - Q1 – Peut-on parvenir au bonheur ?
      - Q1a – Peut-on savoir ce qu'est le bonheur ?
      - Q1b – Le désir nous fait-il nécessairement souffrir ?
      - Q1c – Que pouvons-nous faire face au tragique de l'existence ?
   - Q2 - Le bonheur est-il le but de l'existence ?

&num;&num; Chapitre 2 : La Morale
   - Q1 – Y a-t-il une vérité en morale ?
      - Q1a – La morale est-elle subjective ?
      - Q1b - La morale est-elle relative à chaque culture?
   - Q2 – Comment peut-on savoir ce qui est bien et ce qui est mal ?
      - Q2a – La morale repose sur nos sentiments, sur notre sensibilité ?
      - Q2b – Comment la réflexion peut-elle nous guider moralement ?
</pre>

<aside>On peut ensuite copier-coller ce Markdown dans une application comme <a href="https://mymarkmap.netlify.app/">myMarkmap</a>, ce qui produirait alors la carte mentale ci-dessous <a href="https://mymarkmap.netlify.app/#---%0AmaxWidth:%20200%0A---%0A%0A#%20S%C3%A9quence%201%20:%20%C3%89thique%20et%20Philosophie%20Morale%0A%0A##%20Chapitre%201%20:%20%5C%5CLe%20Bonheur%0A%20%20%20-%20Q1%20%E2%80%93%20Peut-on%20parvenir%20au%20bonheur%20?%0A%20%20%20%20%20%20-%20Q1a%20%E2%80%93%20Peut-on%20savoir%20ce%20qu'est%20le%20bonheur%20?%0A%20%20%20%20%20%20-%20Q1b%20%E2%80%93%20Le%20d%C3%A9sir%20nous%20fait-il%20n%C3%A9cessairement%20souffrir%20?%0A%20%20%20%20%20%20-%20Q1c%20%E2%80%93%20Que%20pouvons-nous%20faire%20face%20au%20tragique%20de%20l'existence%20?%0A%20%20%20-%20Q2%20-%20Le%20bonheur%20est-il%20le%20but%20de%20l'existence%20?%0A%0A##%20Chapitre%202%20:%20%5C%5CLa%20Morale%0A%20%20%20-%20Q1%20%E2%80%93%20Y%20a-t-il%20une%20v%C3%A9rit%C3%A9%20en%20morale%20?%0A%20%20%20%20%20%20-%20Q1a%20%E2%80%93%20La%20morale%20est-elle%20subjective%20?%0A%20%20%20%20%20%20-%20Q1b%20-%20La%20morale%20est-elle%20relative%20%C3%A0%20chaque%20culture?%0A%20%20%20-%20Q2%20%E2%80%93%20Comment%20peut-on%20savoir%20ce%20qui%20est%20bien%20et%20ce%20qui%20est%20mal%20?%0A%20%20%20%20%20%20-%20Q2a%20%E2%80%93%20La%20morale%20repose%20sur%20nos%20sentiments,%20sur%20notre%20sensibilit%C3%A9%20?%0A%20%20%20%20%20%20-%20Q2b%20%E2%80%93%20Comment%20la%20r%C3%A9flexion%20peut-elle%20nous%20guider%20moralement%20?"><img src="https://minio.apps.education.fr/codimd-prod/uploads/upload_4e469f52fd86ed9b23bb5aeaf281a423.png" /></a>  
</aside>


</div>



:::

### ✏️ Activités & documents

#### 1/ Faire le résumé d'un document long

:::exemple collapsible Résumé d'un article de niveau universitaire sur les discriminations pour le rendre accessible à des élèves (terminale)

<div markdown class="user">
Fais un résumé pour des élèves de lycée en terminale de ce document : 
https://www.dicopo.org/spip_article73.html
</div>

<div markdown class="IA">
Le document que vous avez demandé de résumer traite du sujet des discriminations. Voici un résumé adapté pour des élèves de lycée en terminale :

Résumé du Document sur les Discriminations

##### Définition de la Discrimination
Le document commence par une définition générale de la discrimination proposée par Kasper Lippert-Rasmussen. Selon cette définition, une discrimination se produit lorsqu'une personne A traite une personne B différemment d'une personne C, et cette différence de traitement est désavantageuse (ou avantageuse) pour B. De plus, cette différence doit être liée à l'appartenance de B et C à des groupes sociaux distincts et significatifs.

##### Aspects de la Discrimination
- **Discrimination et Traitement Différencié :** La discrimination inclut toutes les différences de traitement basées sur l'appartenance à certains groupes, qu'elles soient justes ou injustes. Il y a un débat sur le fait de savoir si la discrimination doit être considérée comme intrinsèquement négative ou si elle doit être évaluée en fonction de sa justice ou de son injustice.
- **Discrimination et Groupes Socialement Saillants :** La discrimination est souvent liée à l'appartenance à des groupes sociaux importants (comme le genre, la race, la religion). Les discriminations basées sur des caractéristiques moins saillantes socialement, comme la couleur des yeux, sont moins susceptibles d'être considérées comme discriminatoires.
- **Discrimination et Explication Appropriée :** La discrimination doit être liée à l'appartenance à un groupe saillant. Par exemple, si une personne est désavantagée non pas à cause de son appartenance à un groupe, mais en raison de ses compétences, cela ne constitue pas une discrimination.

##### Conclusion
Le document conclut que la discrimination est un phénomène complexe qui s'entremêle avec des préjugés individuels et des pratiques sociales. Elle affecte non seulement les individus mais aussi les structures sociales et institutionnelles. La lutte contre la discrimination implique de comprendre son impact sur l'autonomie et les choix des individus appartenant à des groupes désavantagés.

</div>

:::

#### 2/ Faire la carte mentale d'un document

L'IA générative peut être utilisée pour transformer un texte en carte mentale, ou du moins pour proposer une première version (car il faut souvent retravailler ce que propose l'IA).

:::exemple collapsible Carte mentale sur un texte d'un philosophe (terminales)

<div markdown class="user">

Transforme ce texte sur la reconnaissance sociale selon Honneth en une carte mentale en markdown :
    
Honneth [formule] deux thèses. Premièrement, le sujet de l’action n’existe qu’à condition d’être reconnu : il n’est pas de sujet moral ou pratique dont la valeur n’ait d’abord été confirmée par les autres. Deuxièmement, la nécessité d’être reconnu prend sa source dans l’expérience du mépris (Miβachtung), c’est-à-dire dans l’expérience fondatrice d’un manque de reconnaissance. […]
Le premier mode de reconnaissance mutuelle est la relation d’amour, par laquelle l’individu parvient à la “confiance en soi”, c’est-à-dire à une certaine sécurité émotionnelle. Axel Honneth s’appuie sur l’œuvre du psychanalyste anglais Donald Winnicott, qui montre par quelles étapes l’enfant accède à un équilibre satisfaisant entre la symbiose avec la mère (qui permet la sécurité) et l’affirmation de soi (qui permet l’autonomie). Au terme de ce processus, l’individu acquiert la “capacité à être seul”, condition nécessaire de toute créativité, que celle-ci soit enfantine ou adulte. Les affects et les besoins de l’individu se voient alors reconnus, non seulement au sens où il lui devient possible de les éprouver légitimement, mais également en ceci qu’il peut les faire connaître aux autres en toute tranquillité. Honneth clôt ce premier moment en soulignant qu’il ne sépare pas abstraitement la reconnaissance “privée” que rend possible l’amour et la reconnaissance “publique” dont il va être question. Il précise qu’un individu ne saurait participer à la vie publique de façon autonome sans la confiance en soi minimale que le lien d’amour a pu élaborer.
Le deuxième mode de reconnaissance mutuelle est la relation juridique, par laquelle l’individu se voit reconnu comme une personne dotée de droits. Le respect de soi est l’effet subjectif de cette reconnaissance, la responsabilité morale de l’individu se trouve alors reconnue. Les droits reconnaissent en effet à l’individu “la capacité de se prononcer d’une manière rationnelle et autonome sur les questions morales”.
L’estime sociale désigne le troisième mode de reconnaissance. Ce qui est estimé (et donc reconnu), ce sont les capacités et les qualités singulières des individus. Être estimé, cela ne revient pas à être reconnu juridiquement. La reconnaissance juridique porte sur une qualité universellement partagée (la capacité morale) ; de façon toute différente, “Une personne ne peut se juger “estimable” que si elle se sent reconnue dans des prestations qui ne pourraient être aussi bien assurées par d’autres”. L’individu acquiert le sentiment de sa propre valeur grâce à la sympathie sociale (ou solidarité) qui lui est manifestée.

</div>

<div markdown class="IA">

<pre>
&num; La reconnaissance sociale selon Honneth

&num;&num; Thèses d'Honneth
- **Première Thèse**
  - Sujet de l'action n'existe qu'à travers la reconnaissance.
  - Aucun sujet moral/pratique sans confirmation par autrui.
- **Deuxième Thèse**
  - Nécessité de reconnaissance provient de l'expérience du mépris.
  - Mépris (Miβachtung) crée un manque de reconnaissance.

&num;&num; Modes de Reconnaissance Mutuelle
&num;&num;&num; 1. Relation d'Amour
- S'appuie sur Donald Winnicott.
- Processus d'accès à l'équilibre entre symbiose et affirmation de soi.
- aboutit à la "confiance en soi" et "capacité à être seul".
- Condition nécessaire à la créativité.
- Reconnaissance "privée" de l'amour est liée à la reconnaissance "publique".

&num;&num;&num; 2. Relation Juridique
- Individu reconnu comme personne dotée de droits.
- Respect de soi comme effet subjectif.
- Responsabilité morale reconnue.
- Droits permettent la capacité de se prononcer de manière rationnelle et autonome sur les questions morales.

&num;&num;&num; 3. Estime Sociale
- Troisième mode de reconnaissance.
- Estime des capacités et qualités singulières des individus.
- Différence avec la reconnaissance juridique.
- L'estime sociale provient de la sympathie sociale et solidarité.
- L'individu acquiert le sentiment de sa propre valeur.

</pre>
    
</div>

<aside>Avec l'application myMarkmap, on obtiendrait la carte mentale suivante : <a href="https://mymarkmap.netlify.app/#---%0AmaxWidth:%20400%0A---%0A%0A#%20La%20reconnaissance%20sociale%20%5C%5Cselon%20Honneth%0A%0A##%20Th%C3%A8ses%20%5C%5Cd'Honneth%0A-%20**Premi%C3%A8re%20Th%C3%A8se**%0A%20%20-%20Sujet%20de%20l'action%20n'existe%20qu'%C3%A0%20travers%20la%20reconnaissance.%0A%20%20-%20Aucun%20sujet%20moral/pratique%20sans%20confirmation%20par%20autrui.%0A-%20**Deuxi%C3%A8me%20Th%C3%A8se**%0A%20%20-%20N%C3%A9cessit%C3%A9%20de%20reconnaissance%20provient%20de%20l'exp%C3%A9rience%20du%20m%C3%A9pris.%0A%20%20-%20M%C3%A9pris%20(Mi%CE%B2achtung)%20cr%C3%A9e%20un%20manque%20de%20reconnaissance.%0A%0A##%20Modes%20de%20%5C%5CReconnaissance%20%5C%5CMutuelle%0A###%201.%20Relation%20d'Amour%0A-%20S'appuie%20sur%20Donald%20Winnicott.%0A-%20Processus%20d'acc%C3%A8s%20%C3%A0%20l'%C3%A9quilibre%20entre%20symbiose%20et%20affirmation%20de%20soi.%0A-%20aboutit%20%C3%A0%20la%20%22confiance%20en%20soi%22%20et%20%22capacit%C3%A9%20%C3%A0%20%C3%AAtre%20seul%22.%0A-%20Condition%20n%C3%A9cessaire%20%C3%A0%20la%20cr%C3%A9ativit%C3%A9.%0A-%20Reconnaissance%20%22priv%C3%A9e%22%20de%20l'amour%20est%20li%C3%A9e%20%C3%A0%20la%20reconnaissance%20%22publique%22.%0A%0A###%202.%20Relation%20Juridique%0A-%20Individu%20reconnu%20comme%20personne%20dot%C3%A9e%20de%20droits.%0A-%20Respect%20de%20soi%20comme%20effet%20subjectif.%0A-%20Responsabilit%C3%A9%20morale%20reconnue.%0A-%20Droits%20permettent%20la%20capacit%C3%A9%20de%20se%20prononcer%20de%20mani%C3%A8re%20rationnelle%20et%20autonome%20sur%20les%20questions%20morales.%0A%0A###%203.%20Estime%20Sociale%0A-%20Troisi%C3%A8me%20mode%20de%20reconnaissance.%0A-%20Estime%20des%20capacit%C3%A9s%20et%20qualit%C3%A9s%20singuli%C3%A8res%20des%20individus.%0A-%20Diff%C3%A9rence%20avec%20la%20reconnaissance%20juridique.%0A-%20L'estime%20sociale%20provient%20de%20la%20sympathie%20sociale%20et%20solidarit%C3%A9.%0A-%20L'individu%20acquiert%20le%20sentiment%20de%20sa%20propre%20valeur."><img src="https://minio.apps.education.fr/codimd-prod/uploads/upload_67d1c155ce38e40942f1e3fb7ce3c48a.png" /></a></aside>

<aside>L'IA a repéré la structure mais reste très générale : on a cependant une base pratique que l'on peut reprendre</aside>

:::


:::exemple collapsible Carte mentale en Musique sur le baroque (collège)

<div markdown class="user">
Fais une carte mentale en markdown de cette page pour des élèves de collège :
https://fr.wikipedia.org/wiki/Musique_baroque
</div>

<div markdown class="IA">

<pre>
&num; Musique Baroque (XVIIe - XVIIIe siècle)

&num;&num; Caractéristiques
- Harmonie enrichie
- Basse continue
- Effets vocaux développés

&num;&num; Genres Musicaux
- Musique instrumentale
- Opéra

&num;&num; Géographie
- Europe de l'Ouest
  - France
  - Italie
- Pays germaniques

&num;&num; Compositeurs Célèbres
- Jean-Sébastien Bach
- Georg Friedrich Haendel
- Antonio Vivaldi
- Jean-Philippe Rameau

&num;&num; Instruments Typiques
- Clavecin
- Viole de gambe

&num;&num; Innovations
- Introduction de la basse continue
- Développement de l'opéra

&num;&num; Redécouverte au XXe siècle
- Recherche musicologique
- Interprétation historiquement informée
</pre>

</div>

<aside>Avec l'application myMarkmap, on obtiendrait la carte mentale suivante : <a href="https://mymarkmap.netlify.app/#---%0AmaxWidth:%20200%0A---%0A%0A#%20Musique%20Baroque%20(XVIIe%20-%20XVIIIe%20si%C3%A8cle)%0A%0A##%20Caract%C3%A9ristiques%0A-%20Harmonie%20enrichie%0A-%20Basse%20continue%0A-%20Effets%20vocaux%20d%C3%A9velopp%C3%A9s%0A%0A##%20Genres%20Musicaux%0A-%20Musique%20instrumentale%0A-%20Op%C3%A9ra%0A%0A##%20G%C3%A9ographie%0A-%20Europe%20de%20l'Ouest%0A%20%20-%20France%0A%20%20-%20Italie%0A-%20Pays%20germaniques%0A%0A##%20Compositeurs%20C%C3%A9l%C3%A8bres%0A-%20Jean-S%C3%A9bastien%20Bach%0A-%20Georg%20Friedrich%20Haendel%0A-%20Antonio%20Vivaldi%0A-%20Jean-Philippe%20Rameau%0A%0A##%20Instruments%20Typiques%0A-%20Clavecin%0A-%20Viole%20de%20gambe%0A%0A##%20Innovations%0A-%20Introduction%20de%20la%20basse%20continue%0A-%20D%C3%A9veloppement%20de%20l'op%C3%A9ra%0A%0A##%20Red%C3%A9couverte%20au%20XXe%20si%C3%A8cle%0A-%20Recherche%20musicologique%0A-%20Interpr%C3%A9tation%20historiquement%20inform%C3%A9e"><img src="https://minio.apps.education.fr/codimd-prod/uploads/upload_0fc0069f50fa917ec4f9fb83fad47f46.png" /></a></aside>


<aside>L'IA a laissé de côté un grand nombre d'informations, mais propose des pistes de structuration qui peuvent constituer une base utile</aside>

:::

#### 3/ Extraire les informations importantes dans un tableau

:::exemple collapsible Liste des premiers ministres français

<div markdown class="user">
Je veux faire un tableau de tous les premiers ministres francais avec la période où ils exercent et la durée.

Voici une page où il y a les informations : https://fr.wikipedia.org/wiki/Premier_ministre_fran%C3%A7ais

Présente le tableau en 3 colonnes avec le nom du premier ministre, la période du mandat et la durée
</div>

<div markdown class="IA">

| Premier Ministre         | Période du Mandat                | Durée               |
|---------------------------|----------------------------------|---------------------|
| Michel Debré              | 8 janvier 1959 - 14 avril 1962  | 3 ans, 3 mois       |
| Georges Pompidou          | 14 avril 1962 - 10 juillet 1968  | 6 ans, 3 mois       |
| Maurice Couve de Murville | 10 juillet 1968 - 20 juin 1969   | 11 mois             |
| Jacques Chaban-Delmas     | 20 juin 1969 - 5 juillet 1972    | 3 ans, 15 jours     |
| Pierre Messmer            | 5 juillet 1972 - 27 mai 1974     | 1 an, 10 mois       |
| Jacques Chirac            | 27 mai 1974 - 25 août 1976       | 2 ans, 3 mois       |
| Raymond Barre              | 25 août 1976 - 21 mai 1981      | 4 ans, 9 mois       |
| Pierre Mauroy              | 21 mai 1981 - 17 juillet 1984   | 3 ans, 2 mois       |
| Laurent Fabius             | 17 juillet 1984 - 20 mars 1986  | 1 an, 8 mois        |
| Jacques Chirac            | 20 mars 1986 - 10 mai 1988      | 2 ans, 2 mois       |
| Michel Rocard              | 10 mai 1988 - 15 mai 1991       | 3 ans, 5 jours      |
| Édith Cresson              | 15 mai 1991 - 2 avril 1992      | 10 mois, 18 jours   |
| Pierre Bérégovoy          | 2 avril 1992 - 29 mars 1993     | 11 mois, 27 jours   |
| Édouard Balladur           | 29 mars 1993 - 17 mai 1995      | 2 ans, 1 mois        |
| Alain Juppé                 | 17 mai 1995 - 2 juin 1997      | 2 ans, 16 jours      |
| Lionel Jospin               | 2 juin 1997 - 6 mai 2002        | 4 ans, 11 mois      |
| Jean-Pierre Raffarin       | 6 mai 2002 - 31 mai 2005        | 3 ans, 25 jours      |
| Dominique de Villepin      | 31 mai 2005 - 17 mai 2007       | 1 an, 11 mois       |
| François Fillon             | 17 mai 2007 - 15 mai 2012      | 5 ans               |
| Jean-Marc Ayrault           | 15 mai 2012 - 31 mars 2014      | 1 an, 10 mois       |
| Manuel Valls                | 31 mars 2014 - 6 décembre 2016 | 2 ans, 8 mois        |
| Bernard Cazeneuve           | 6 décembre 2016 - 15 mai 2017  | 5 mois, 9 jours      |
| Édouard Philippe            | 15 mai 2017 - 3 juillet 2020   | 3 ans, 1 mois        |
| Jean Castex                 | 3 juillet 2020 - 16 mai 2022   | 1 an, 10 mois       |
| Élisabeth Borne             | 16 mai 2022 - 2024             | (en cours)          |
| Gabriel Attal              | depuis 2024                    | (en cours)          |


</div>

:::

:::exemple collapsible Présentation des principaux mouvements artistiques

<div markdown class="user">
Présente sous forme de tableau les principaux mouvements artistique.

3 colonnes :
- nom du mouvement
- date
- Définition et éventuellement artistes correspondants.

Voici le lien : https://barnies.fr/mouvements-artistiques/
</div>

<div markdown class="IA">

| Mouvement Artistique     | Date                      | Définition et Artistes Correspondants                                                                                                  |
| ------------------------ | ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Humanisme                | XVe siècle                | Courant intellectuel et artistique d'origine italienne, centré sur l'homme et influencé par la redécouverte de l'Antiquité.            |
| Maniérisme               | 1520-1600                 | Style caractérisé par des inventions extravagantes et une culture de cour raffinée.                                                    |
| Naturalisme              | XVIe siècle               | Courant visant une représentation fidèle et dénuée d’idéalisation, mettant en honneur les scènes de la vie courante.                   |
| Baroque                  | XVIIe siècle              | Production principalement religieuse, cherchant à émouvoir par le pouvoir de séduction de l’œuvre d’art.                               |
| Classicisme              | XVIIe siècle              | Mouvement prônant la beauté idéale et l'équilibre, inspiré de l'Antiquité classique.                                                   |
| Rocaille                 | 1715-1770                 | Style ornemental promouvant la libération des formes, avec une préférence pour les lignes courbes.                                     |
| Pittoresque              | 1750-1800                 | Peinture représentant la nature dans sa variété, souvent associée à des ruines antiques.                                               |
| Néoclassicisme           | 1750-1830                 | Mouvement favorisant une reproduction exacte du modèle grec ou romain, dans le cadre du Grand Tour.                                    |
| Style Empire             | 1805-1830                 | Style marquant la domination politique de Napoléon Bonaparte, associé à l’égyptolomanie.                                               |
| Romantisme               | 1790-1848                 | Art émotif et fantastique, prônant la liberté de la créativité et retranscrivant des sentiments comme la mélancolie.                   |
| Académisme               | XIXe siècle               | Art classique considéré comme la perfection, avec un respect de l’équilibre des formes et des sujets savants.                          |
| Orientalisme             | XVIIIe et XIXe siècles    | Courant dominé par une atmosphère fabuleuse et un fantasme du monde musulman.                                                          |
| Réalisme                 | 1840-1880                 | Mouvement représentant le monde contemporain dans ses aspects les plus réels, souvent indignes et vulgaires.                           |
| Impressionnisme          | 1874-1886                 | Basé sur la capture de la lumière naturelle, avec une représentation esquissée et inachevée pour rendre la fugacité de la vie moderne. |
| Pointillisme             | 1886-1900                 | Technique de pose de couleur pure en petits points pour figurer la décomposition de la lumière.                                        |
| Post-impressionnisme     | 1895-1910                 | Regroupe divers styles et artistes comme Paul Cézanne et Vincent Van Gogh, cherchant à échapper au réalisme descriptif.                |
| Fauvisme                 | 1904-1908                 | Toiles aux couleurs vives et spontanéité crue, marquant une vision personnelle de l’art.                                               |
| Expressionnisme          | 1905-1920                 | Privilégie les émotions subjectives et l’usage émotionnel et symbolique de la couleur.                                                 |
| Cubisme                  | 1908-1913                 | Utilisation du cube pour fragmenter les compositions, multipliant les points de vue.                                                   |
| Futurisme                | 1909-1930                 | Représentation du dynamisme des grandes villes, avec une passion pour la vitesse et le progrès technique.                              |
| Constructivisme          | 1913-1930                 | Utilisation de formes géométriques abstraites, avec une fascination pour l’espace tridimensionnel.                                     |
| Dada                     | 1916-1922                 | Courant exprimant la rage envers la guerre et remettant en cause l’ordre établi.                                                       |
| Nouvelle Objectivité     | 1924-1933                 | Style réaliste allemand avec un engagement social, critiquant les horreurs de la guerre et la montée du nazisme.                       |
| Surréalisme              | 1924-1959                 | Refus de la logique et de la raison, libération de l’inconscient, des phobies, désirs et rêves réprimés.                               |
| Réalisme social          | 1930-1940                 | Art populaire américain à contenu social, archivant les conditions de vie des zones rurales appauvries.                                |
| Art Nouveau              | 1890-1915                 | Mouvement international favorisant la dimension végétale et organique, en rupture avec les styles historiques passés.                  |
| Bauhaus                  | 1919-1933                 | École allemande produisant un design fonctionnel de qualité pour améliorer la société.                                                 |
| Art Déco                 | 1920-1940                 | Art luxueux et décoratif, célébrant la vitesse, le voyage et le luxe.                                                                  |
| Abstraction organique    | Années 1940 - Années 1950 | Formes arrondies et abstraites inspirées de la nature, influençant les designers américains et scandinaves.                            |
| Art Brut                 | 1945                      | Art populaire et autodidacte, produisant des œuvres hors du système traditionnel.                                                      |
| Expressionnisme abstrait | 1945-1950                 | Investissement corporel dans la peinture, avec un focus sur les émotions humaines.                                                     |
| CoBrA                    | 1948-1951                 | Art expressionniste et populaire, cherchant une innocence perdue dans l’art enfantin et préhistorique.                                 |
| Pop Art                  | 1956-1970                 | Inspiration tirée de la publicité, des médias et du design, avec un intérêt pour la culture populaire de masse.                        |
| Nouveau Réalisme         | 1960-1970                 | Incorporation d’objets quotidiens dans les œuvres, avec un goût pour la fabrication.                                                   |
| Minimalisme              | 1965 - Années 1970        | Utilisation de structures simples et géométriques pour une expérience visuelle.                                                        |
| Art conceptuel           | 1965                      | Réduction de l’œuvre d’art à un moyen d’exprimer une idée ou un concept.                                                               |
| Hyper-réalisme           | 1965                      | Peinture et sculpture descriptives et figuratives, copiant les photographies                                                           |


</div>

:::

:::exemple collapsible Transformer un texte en tableau

<div markdown class="user">

Transforme ce texte en tableau en 3 colonnes :
    
Le neurologue Antonio Damasio distingue trois formes de Soi : 
– Le proto-soi désigne le fait qu'il existe dans le cerveau un ensemble de réseaux neuronaux qui représentent les états physiques internes de l'organisme ; le proto-soi est largement non-conscient, mais il est aussi ce qui rend possible la conscience de son propre corps comme le sien ;
– Le soi central désigne un certain sentiment de soi qui émerge dans l'instant présent lors des interactions avec l'environnement, dans la perception, l'action ou la pensée présente ; il est au fondement de la capacité de reconnaître ses propres actes comme provenant de soi comme étant sous son contrôle ;
– Le soi autobiographique désigne la capacité de se reconnaître comme étant le même à travers le temps grâce à un ensemble de souvenirs de son propre passé qui permettent de forger une certain image générale de soi.

</div>

<div markdown class="IA">

| Formes de Soi        | Description                                                                                                           | Fonctionnalités                                                                                                   |
|----------------------|-----------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| Proto-soi            | Ensemble de réseaux neuronaux représentant les états physiques internes de l'organisme. Non-conscient mais rend possible la conscience du corps comme le sien.          | Permet la conscience de son propre corps.                                                                           |
| Soi central          | Sentiment de soi émergeant dans l'instant présent lors des interactions avec l'environnement (perception, action, pensée). Fondamental pour reconnaître ses propres actes comme relevant de soi et sous contrôle. | Fondement de la capacité à reconnaître ses propres actes.                                                        |
| Soi autobiographique | Capacité de se reconnaître comme le même à travers le temps grâce à des souvenirs du passé, forgeant une image générale de soi.                                                | Permet la continuité de l'identité à travers le temps.                                                          |


</div>

:::


#### 4/ Adapter un document pour un élève à besoin éducatif particulier

:::exemple collapsible Mise en gras des termes importants et texte plus aéré

<div markdown class="user">

Recopie le texte suivant en mettant en gras les termes importants et en sautant une ligne entre chaque phrase :

De nombreux progrès techniques se produisent tout au long du XIXe siècle. Ils sont l’œuvre de techniciens, puis, progressivement, d’ingénieurs et de savants. La machine à vapeur est mise au point par James Watt en 1763. Elle fonctionne d’abord au bois, puis au charbon et enfin au coke (dérivé du charbon). Elle est utilisée dans un grand nombre de domaines industriels et devient la source d’énergie d’usines de plus en plus grosses, notamment dans le textile (machines à filer et à tisser) et dans la métallurgie. Peu à peu perfectionnée, la machine à vapeur fait fonctionner les locomotives, les bateaux et les machines agricoles. 

</div>

<div markdown class="IA">

De nombreux **progrès techniques** se produisent tout au long du **XIXe siècle**.

Ils sont l’œuvre de **techniciens**, puis, progressivement, d’**ingénieurs** et de **savants**.

La **machine à vapeur** est mise au point par **James Watt** en **1763**.

Elle fonctionne d’abord au **bois**, puis au **charbon** et enfin au **coke** (dérivé du charbon).

Elle est utilisée dans un grand nombre de **domaines industriels** et devient la source d’énergie d’**usines de plus en plus grosses**, notamment dans le **textile** (machines à filer et à tisser) et dans la **métallurgie**.

Peu à peu **perfectionnée**, la **machine à vapeur** fait fonctionner les **locomotives**, les **bateaux** et les **machines agricoles**.


</div>

:::


### 🎯 Évaluations

#### Transformer un QCM dans un format spécifique à un logiciel de quiz

Si on a déjà un quiz, mais qu'on veut pouvoir l'intégrer dans un logiciel, il faut d'abord apprendre à l'IA la syntaxe du logiciel pour chaque type de question.

:::exemple collapsible Utilisation de Text2quiz pour créer des flashcards

<div markdown class="user">
Pour faire une flashcard avec le logiciel Text2quiz, il faut utiliser cette syntaxe. Pour chaque carte, on écrit : "Flashcard || Texte de la question || texte de la réponse".  Je te donnerai ensuite des flashcards à créer. Tu devras respecter cette syntaxe. Tu as compris ? Dis-moi simplement oui ou non. Rien de plus.
</div>

<aside>Il faut d'abord faire apprendre à l'IA le format spécifique au logiciel</aside>

<div markdown class="IA">
Oui
</div>

<div markdown class="user">

Voici une liste de questions avec à chaque fois la réponse. Transforme cette liste en une série de flashcards avec la syntaxe de text2quiz ci-dessus. 

Quelles sont les quatre démarches importantes en philosophie ?
Pour chaque démarche, quelle est la question qu'il faut se poser ?

En philosophie, les quatre démarches importantes sont : analyser, problématiser, argumenter et mobiliser ses connaissances.

Pour analyser, il faut se demander : « Qu'est-ce que cela veut dire ? ».
Pour problématiser, il faut se demander : « Est-ce vraiment si simple ? ».
Pour argumenter, il faut se demander : « Qu'est-ce qui permet de dire cela ? ».
Pour mobiliser ses connaissances, il faut se demander : « Comment approfondir ? ».
On peut dire que faire de la philosophie, c'est comme regarder ses propres lunettes. Qu'est-ce que cela veut dire ?

Regarder ses propres lunettes, c'est examiner les idées avec lesquelles on pense, afin de chercher à les rendre plus claires et plus précises : cela revient à analyser ses idées.

On peut dire que faire de la philosophie, c'est comme être un taon qui pique un cheval un peu mou. Qu'est-ce que cela veut dire ?

Cette image désigne la démarche de Socrate. Être comme un taon qui pique un cheval un peu mou, c'est réveiller son esprit critique et questionner ce qui nous semble évident : cela revient à problématiser.

On peut dire que faire de la philosophie, c'est comme placer les idées sur une balance. Qu'est-ce que cela veut dire ?

Épictète propose cette image de la balance. Placer une idée sur une balance, c'est examiner les arguments et les objections afin de déterminer si l'idée est convaincante : cela revient à argumenter.

Comme le dit Épictète, il ne faut pas vomir ce qu'on a appris, mais le digérer. Quel est le sens de cette image ?

Vomir ce qu'on a appris, ce serait simplement recracher ses connaissances, sans les avoir intégrées, et sans organisation. Digérer ce qu'on a appris, c'est s'approprier des connaissances afin de les faire siennes et pouvoir ainsi les mobiliser pour développer sa propre réflexion.

Quelle est l'histoire que raconte Platon à propos de Thalès ? Quel est le sens de cette histoire ?

Thalès se promène en regardant les étoiles et tombe dans un puits parce qu'il regardait le ciel au lieu de regarder ses pieds. Cette histoire illustre une moquerie classique contre la philosophie qui serait une réflexion trop abstraite et déconnectée du réel.

</div>

<div markdown class="IA">

<pre>
Flashcard || Quelles sont les quatre démarches importantes en philosophie ? || Les quatre démarches importantes en philosophie sont : analyser, problématiser, argumenter et mobiliser ses connaissances.
Flashcard || Pour chaque démarche, quelle est la question qu'il faut se poser ? || Pour analyser, il faut se demander : « Qu'est-ce que cela veut dire ? ». Pour problématiser, il faut se demander : « Est-ce vraiment si simple ? ». Pour argumenter, il faut se demander : « Qu'est-ce qui permet de dire cela ? ». Pour mobiliser ses connaissances, il faut se demander : « Comment approfondir ? ».
Flashcard || On peut dire que faire de la philosophie, c'est comme regarder ses propres lunettes. Qu'est-ce que cela veut dire ? || Regarder ses propres lunettes, c'est examiner les idées avec lesquelles on pense, afin de chercher à les rendre plus claires et plus précises : cela revient à analyser ses idées.
Flashcard || On peut dire que faire de la philosophie, c'est comme être un taon qui pique un cheval un peu mou. Qu'est-ce que cela veut dire ? || Cette image désigne la démarche de Socrate. Être comme un taon qui pique un cheval un peu mou, c'est réveiller son esprit critique et questionner ce qui nous semble évident : cela revient à problématiser.
Flashcard || On peut dire que faire de la philosophie, c'est comme placer les idées sur une balance. Qu'est-ce que cela veut dire ? || Épictète propose cette image de la balance. Placer une idée sur une balance, c'est examiner les arguments et les objections afin de déterminer si l'idée est convaincante : cela revient à argumenter.
Flashcard || Comme le dit Épictète, il ne faut pas vomir ce qu'on a appris, mais le digérer. Quel est le sens de cette image ? || Vomir ce qu'on a appris, ce serait simplement recracher ses connaissances, sans les avoir intégrées, et sans organisation. Digérer ce qu'on a appris, c'est s'approprier des connaissances afin de les faire siennes et pouvoir ainsi les mobiliser pour développer sa propre réflexion.
Flashcard || Quelle est l'histoire que raconte Platon à propos de Thalès ? Quel est le sens de cette histoire ? || Thalès se promène en regardant les étoiles et tombe dans un puits parce qu'il regardait le ciel au lieu de regarder ses pieds. Cette histoire illustre une moquerie classique contre la philosophie qui serait une réflexion trop abstraite et déconnectée du réel.
</pre>

<aside>On peut alors copier-coller le quiz dans text2quiz : <a href="https://text2quiz.vercel.app/?v=1.0#Flashcard%20%7C%7C%20Quelles%20sont%20les%20quatre%20d%C3%A9marches%20importantes%20en%20philosophie%20?%20%7C%7C%20Les%20quatre%20d%C3%A9marches%20importantes%20en%20philosophie%20sont%20:%20analyser,%20probl%C3%A9matiser,%20argumenter%20et%20mobiliser%20ses%20connaissances.%0AFlashcard%20%7C%7C%20Pour%20chaque%20d%C3%A9marche,%20quelle%20est%20la%20question%20qu'il%20faut%20se%20poser%20?%20%7C%7C%20Pour%20analyser,%20il%20faut%20se%20demander%20:%20%C2%AB%20Qu'est-ce%20que%20cela%20veut%20dire%20?%20%C2%BB.%20Pour%20probl%C3%A9matiser,%20il%20faut%20se%20demander%20:%20%C2%AB%20Est-ce%20vraiment%20si%20simple%20?%20%C2%BB.%20Pour%20argumenter,%20il%20faut%20se%20demander%20:%20%C2%AB%20Qu'est-ce%20qui%20permet%20de%20dire%20cela%20?%20%C2%BB.%20Pour%20mobiliser%20ses%20connaissances,%20il%20faut%20se%20demander%20:%20%C2%AB%20Comment%20approfondir%20?%20%C2%BB.%0AFlashcard%20%7C%7C%20On%20peut%20dire%20que%20faire%20de%20la%20philosophie,%20c'est%20comme%20regarder%20ses%20propres%20lunettes.%20Qu'est-ce%20que%20cela%20veut%20dire%20?%20%7C%7C%20Regarder%20ses%20propres%20lunettes,%20c'est%20examiner%20les%20id%C3%A9es%20avec%20lesquelles%20on%20pense,%20afin%20de%20chercher%20%C3%A0%20les%20rendre%20plus%20claires%20et%20plus%20pr%C3%A9cises%20:%20cela%20revient%20%C3%A0%20analyser%20ses%20id%C3%A9es.%0AFlashcard%20%7C%7C%20On%20peut%20dire%20que%20faire%20de%20la%20philosophie,%20c'est%20comme%20%C3%AAtre%20un%20taon%20qui%20pique%20un%20cheval%20un%20peu%20mou.%20Qu'est-ce%20que%20cela%20veut%20dire%20?%20%7C%7C%20Cette%20image%20d%C3%A9signe%20la%20d%C3%A9marche%20de%20Socrate.%20%C3%8Atre%20comme%20un%20taon%20qui%20pique%20un%20cheval%20un%20peu%20mou,%20c'est%20r%C3%A9veiller%20son%20esprit%20critique%20et%20questionner%20ce%20qui%20nous%20semble%20%C3%A9vident%20:%20cela%20revient%20%C3%A0%20probl%C3%A9matiser.%0AFlashcard%20%7C%7C%20On%20peut%20dire%20que%20faire%20de%20la%20philosophie,%20c'est%20comme%20placer%20les%20id%C3%A9es%20sur%20une%20balance.%20Qu'est-ce%20que%20cela%20veut%20dire%20?%20%7C%7C%20%C3%89pict%C3%A8te%20propose%20cette%20image%20de%20la%20balance.%20Placer%20une%20id%C3%A9e%20sur%20une%20balance,%20c'est%20examiner%20les%20arguments%20et%20les%20objections%20afin%20de%20d%C3%A9terminer%20si%20l'id%C3%A9e%20est%20convaincante%20:%20cela%20revient%20%C3%A0%20argumenter.%0AFlashcard%20%7C%7C%20Comme%20le%20dit%20%C3%89pict%C3%A8te,%20il%20ne%20faut%20pas%20vomir%20ce%20qu'on%20a%20appris,%20mais%20le%20dig%C3%A9rer.%20Quel%20est%20le%20sens%20de%20cette%20image%20?%20%7C%7C%20Vomir%20ce%20qu'on%20a%20appris,%20ce%20serait%20simplement%20recracher%20ses%20connaissances,%20sans%20les%20avoir%20int%C3%A9gr%C3%A9es,%20et%20sans%20organisation.%20Dig%C3%A9rer%20ce%20qu'on%20a%20appris,%20c'est%20s'approprier%20des%20connaissances%20afin%20de%20les%20faire%20siennes%20et%20pouvoir%20ainsi%20les%20mobiliser%20pour%20d%C3%A9velopper%20sa%20propre%20r%C3%A9flexion.%0AFlashcard%20%7C%7C%20Quelle%20est%20l'histoire%20que%20raconte%20Platon%20%C3%A0%20propos%20de%20Thal%C3%A8s%20?%20Quel%20est%20le%20sens%20de%20cette%20histoire%20?%20%7C%7C%20Thal%C3%A8s%20se%20prom%C3%A8ne%20en%20regardant%20les%20%C3%A9toiles%20et%20tombe%20dans%20un%20puits%20parce%20qu'il%20regardait%20le%20ciel%20au%20lieu%20de%20regarder%20ses%20pieds.%20Cette%20histoire%20illustre%20une%20moquerie%20classique%20contre%20la%20philosophie%20qui%20serait%20une%20r%C3%A9flexion%20trop%20abstraite%20et%20d%C3%A9connect%C3%A9e%20du%20r%C3%A9el.%0A">lien vers le quiz</a>
</aside>

</div>

:::

## 📈  Évaluer / améliorer

### Principe général

On peut demander à une IA générative d'analyser un document de cours afin de faire des suggestions d'amélioration soit dans le contenu abordé, soit dans la formulation.

L'IA peut fonctionner ainsi comme une forme d'assistant rédactionnel et d'outil de relecture de nos documents.

### 📅 Planification d'un cours

On peut utiliser l'IA pour lui faire analyser ce qu'on a préparé afin de voir si notre cours est complet ou bien si des formulations peuvent être améliorées.

#### Faire analyser son plan de cours
:::exemple collapsible Améliorations d'un cours sur le Web en SNT (secondes)

<div markdown class="user">
Tu es un conseiller en pédagogie qui aide les enseignants. Je suis un enseignant de lycée avec des élèves de seconde. Je veux analyser un plan de cours portant sur le Web.
Donne ton avis et des améliorations. Voici le plan :
1. Repères historiques
2. Le fonctionnement du Web
2.1 La composition d’une URL
2.2 Les requêtes HTTP
2.3 L’interaction client-serveur
3. L’écriture d’une page Web
3.1 Le langage HTML
3.2 Le langage CSS
3.3 Le couple HTML-CSS
3.4 Les liens hypertextes
4. Le fonctionnement d’un moteur de recherche
4.1 Les étapes du fonctionnement d’un moteur de recherche
4.2 Le classement des sites
4.3 L’optimisation du référencement
5. Sécurité et vie privée sur le Web
5.1 La gestion des paramètres du navigateur
5.2 L’historique de navigation   
</div>
    
<div markdown class="IA">
Votre plan de cours semble bien structuré et couvre les aspects essentiels que les élèves de seconde devraient connaître sur le Web. Voici quelques suggestions pour l'améliorer :

Repères historiques

- Inclure des anecdotes ou des histoires: Les élèves se souviennent mieux des informations lorsqu'elles sont présentées sous forme de récits. Vous pourriez raconter l'histoire de Tim Berners-Lee et l'invention du Web, par exemple.
- Relier le passé au présent: Montrez comment les développements historiques influencent le fonctionnement actuel du Web.

Le fonctionnement du Web

- Visualisations: Utilisez des diagrammes pour illustrer le fonctionnement d'une URL, les requêtes HTTP et l'interaction client-serveur.
- Activités pratiques: Organisez des démonstrations en direct ou des simulations pour que les élèves visualisent ces concepts en action.

L’écriture d’une page Web

- Projets interactifs: Encouragez les élèves à créer leur propre page web simple. Cela pourrait être un projet qui s'étend sur plusieurs leçons.
- Critique et amélioration de code: Examinez des extraits de code réels et discutez de la façon dont ils pourraient être améliorés.

Le fonctionnement d’un moteur de recherche

- Démos interactives: Présentez des outils qui permettent de voir comment les moteurs de recherche indexent et classent les sites.
- Études de cas SEO: Analysez des cas réels d'optimisation pour les moteurs de recherche et les résultats obtenus.

Sécurité et vie privée sur le Web

- Jeux de rôles: Créez des scénarios où les élèves doivent prendre des décisions sur la gestion de la vie privée et la sécurité en ligne.
- Mises à jour réglementaires: Assurez-vous d'inclure les dernières lois et réglementations en vigueur sur la protection des données et la vie privée sur Internet.

Autres considérations:

- Objectifs d'apprentissage clairs: Pour chaque section, définissez des objectifs d'apprentissage précis que les élèves devraient atteindre.
- Évaluation: Prévoyez des méthodes d'évaluation formative et sommative pour chaque partie du plan de cours. Les quiz, les devoirs pratiques et les projets de groupe peuvent être inclus.
- Ressources supplémentaires: Fournissez une liste de ressources supplémentaires pour les élèves qui souhaitent aller plus loin : articles, vidéos, tutoriels, etc.
- Interdisciplinarité: Intégrez des éléments d'autres disciplines, comme l'histoire, l'économie ou l'art, pour montrer l'influence du Web sur différents domaines.

Enfin, assurez-vous que le plan de cours est flexible. Soyez prêt à passer plus de temps sur les concepts difficiles ou à accélérer si les élèves saisissent rapidement la matière. L'engagement des élèves peut être maintenu par une variété de méthodes pédagogiques et en faisant régulièrement le lien entre la théorie et l'utilisation concrète du Web dans leur vie quotidienne.
</div>

Réécris le plan de cours avec tes remarques. Tu peux changer des titres si cela te paraît pertinent. {.user}

<div markdown class="IA">
    
Bien sûr, voici une version révisée de votre plan de cours, intégrant les suggestions pour renforcer l'apprentissage et l'engagement des élèves :

1. Histoire et Evolution du Web

- Raconter le Web: Découverte des pionniers du Web avec anecdotes et impact sur le monde moderne.
- Ligne du temps interactive: Création d'une chronologie collaborative des événements clés.

2. Architecture et Fonctionnement du Web

- Comprendre les URL: Activité de décomposition et reconstruction d'URL en classe.
- Voyage d'une Requête HTTP: Simulation d'une requête HTTP avec des rôles joués par les élèves.
- Dialogue Client-Serveur: Exercice de groupe pour illustrer l'interaction à l'aide de diagrammes et d'exemples réels.

3. Création de Contenu Web: HTML et CSS

- Ma Première Page HTML: Projet par étapes pour construire une page web simple.
- Styliser avec CSS: Atelier pratique sur l'embellissement d'une page web.
- L'Art de Lier: Jeu de rôle sur les liens hypertextes et leur importance dans la navigation.

4. Exploration et Fonctionnement des Moteurs de Recherche

- Sous le Capot d'un Moteur de Recherche: Démonstration interactive des algorithmes de recherche.
- SEO en Action: Atelier d'analyse et d'optimisation d'une page web existante pour le référencement.

5. Sécurité Numérique et Éthique sur le Web

- Paramètres de Confidentialité: Atelier sur la configuration des paramètres de confidentialité du navigateur.
- Trace Numérique: Discussion et activités pratiques sur l'impact de l'historique de navigation.
- Cookies et Consentement: Jeu-questionnaire sur l'utilisation et la gestion des cookies.
- Sécurité HTTPS: Simulation d'attaques et défense avec HTTPS.
- Droits et Responsabilités: Débat sur les droits numériques et les cas d'étude sur la propriété intellectuelle.

Méthodes d'Évaluation et Ressources Complémentaires

- Objectifs d'Apprentissage et Évaluation: Description des objectifs spécifiques et des critères d'évaluation pour chaque module.
- Ressources pour Aller Plus Loin: Compilation de matériel supplémentaire pour les élèves curieux.

Interactivité et Pratique Transdisciplinaire

- Web et Société: Discussion sur l'impact transdisciplinaire du Web, de l'économie à l'art.
- Technologie et Changement: Réflexion sur le rôle du Web dans l'évolution des sociétés.

En intégrant des activités pratiques, des démonstrations, des discussions de groupe et des projets interactifs, vous favoriserez une meilleure compréhension et une participation active des élèves. Cela contribuera également à développer des compétences pratiques et une pensée critique autour des sujets abordés.
</div>
  
::: 

### ✏️ Activités & documents

#### 1/ Ajouter des images à un document


:::exemple collapsible Exemple

<div markdown class="user">
</div>

<div markdown class="IA">
</div>

:::

#### 2/ Reformuler un passage

:::exemple collapsible Guider l'IA pour lui faire trouver une meilleure formulation

<div markdown class="user">
Formule en moins de mots cette phrase : "Le corps ne joue-t-il pas un rôle beaucoup plus fondamental dans la définition de ce que je suis ?" Fais plusieurs propositions.
</div>

<aside>C'est intéressant de préciser le type d'amélioration que l'on recherche (ici : "en moins de mots"), et de mettre à la fin "fais plusieurs propositions", pour pouvoir faire son choix.</aside>

<div markdown class="IA">
"Le corps ne définit-il pas essentiellement qui je suis ?"
"Le corps n'est-il pas au cœur de ma définition ?"
"En quoi le corps ne façonne-t-il pas essentiellement qui je suis ?"
"Est-ce que l'essence de soi ne dépend pas largement du corps ?"
"N'est-ce pas le corps qui définit profondément mon identité ?"
"Le rôle du corps n'est-il pas fondamental dans ma définition personnelle ?"
</div>

D'autres formulations avec "ce que je suis" {.user}

<aside>On peut ajouter des contraintes en indiquant des termes ou expressions qui doivent être présentes, ou bien au contraire on aurait pu demander à éviter certains termes</aside>

<div markdown class="IA">
"Ce que je suis ne dépend-il pas essentiellement du corps ?"
"En quoi le corps est-il fondamental pour ce que je suis ?"
"Ne joue-t-il pas un rôle crucial dans la définition de ce que je suis ?"
"Le corps n'est-il pas au cœur de ce que je suis ?"
"Est-ce que ce que je suis n'est pas étroitement lié à mon corps ?"
</div>

:::




### 🎯 Évaluations

#### 1/ Faire analyser son évaluation

:::exemple collapsible Améliorer une évaluation en SNT (secondes) sur le web

<div markdown class="user">
Je vais maintenant te donner une évaluation pour tester les connaissances des élèves sur ce cours du WEB
Analyse cette évaluation et propose-moi des suggestions pour l'améliorer. 
1. Vrai ou faux ?
Identifier les propositions exactes.
a. Le langage HTML se présente sous la forme
d’une suite d’instructions comportant des balises
entrantes et fermantes.
b. Le langage CSS permet de sécuriser sa connexion
Internet.
c. Les liens hypertextes permettent de naviguer
d’une page à l’autre et d’un site Web à l’autre.
d. Quand on se connecte sur un site sécurisé, un
cadenas s’affiche devant l’URL.
e. Il est impossible de supprimer les traces laissées sur Internet.

2. QCM
Pour chaque proposition, identifier la bonne
réponse.
a. Le rôle du langage HTML est :
de crypter des informations.
d’être interprété par un navigateur Web.
d’échanger des données entre serveurs.

b. Les navigateurs permettent : 
d’afficher des pages Web.
de coder des pages Web.
de chatter à distance.

c. Pour réaliser un lien vers la page d’accueil de
Wikipédia, on écrit :
`<a href="http://wikipedia.org">Wikipédia</a>`
`<a target="http://wikipedia.org">Wikipédia</a>`
`<a href="http://wikipedia.org>`

3. Recopier et compléter les phrases.
 HTML est l’abréviation de ... .
b. Le langage HTML est un langage de ... .
c. Un fichier HTML est constitué de deux parties : ...
d. Un ... permet d’atteindre une autre page du
même site ou d’un autre site.
</div>
         
<div markdown class="IA">
                    
L'évaluation que vous avez élaborée couvre un certain nombre de points clés sur le Web, mais il y a des possibilités pour la rendre plus robuste et complète.

Vrai ou Faux ?

- Cette section est bien conçue pour tester la compréhension de base des élèves. Vous pourriez envisager d'ajouter plus de questions pour couvrir d'autres sujets importants comme la sécurité sur le Web, les moteurs de recherche et les bases des requêtes HTTP.

QCM

- Les questions à choix multiples sont bonnes pour évaluer la reconnaissance des connaissances. Cependant, la question c manque d'une réponse correcte. Vous pouvez ajouter des questions supplémentaires qui couvrent des sujets comme les requêtes HTTP, le fonctionnement des moteurs de recherche et les principes de base de la sécurité sur le Web.
- Assurez-vous que les questions sont formulées de manière à ce qu'il y ait une seule réponse correcte, et évitez les erreurs de syntaxe ou de formatage comme dans l'option c de la dernière question, qui n'a pas de guillemet fermant.

Recopier et compléter les phrases

- Cette partie est utile pour évaluer la capacité de rappel des élèves. Cependant, pour une évaluation plus approfondie, vous pourriez demander aux élèves de compléter non seulement des phrases mais aussi de petits blocs de code ou des structures URL, par exemple.
- Une autre amélioration pourrait être d'ajouter des questions qui nécessitent des réponses descriptives pour évaluer la compréhension conceptuelle, pas seulement la mémorisation.

Suggestions générales pour l'amélioration :

- Inclure des études de cas pratiques : Des questions basées sur des études de cas pratiques où les élèves doivent appliquer leurs connaissances à des scénarios réels.
- Utiliser des questions ouvertes : Ajoutez des questions qui nécessitent une réponse écrite pour expliquer un concept ou un processus. Cela peut aider à évaluer la compréhension en profondeur.
- Intégration des éléments de codage : Pour les parties sur HTML et CSS, demandez aux élèves de corriger ou de compléter un bloc de code.
- Tests de compréhension de lecture : Intégrez des extraits de code ou des diagrammes et posez des questions qui testent la compréhension de ce qu'ils représentent.
- Questions d'application : Posez des questions qui nécessitent que les élèves appliquent ce qu'ils ont appris pour résoudre un problème ou accomplir une tâche.

Voici un exemple de question améliorée pour chaque section :

Vrai ou Faux ?
f. Un cookie Internet peut stocker des informations sur les préférences de l'utilisateur pour un site Web spécifique.

QCM
d. Un protocole sécurisé pour les transactions sur Internet est :

- FTP
- HTTP
- HTTPS

Recopier et compléter les phrases.
e. Une URL complète se compose de ... , ... , et ... .

En intégrant ces types de questions, vous pouvez offrir une évaluation plus complète de la compréhension des élèves et de leur capacité à utiliser les connaissances dans des contextes variés.
</div>
                        
<div class="user">
Redonne-moi l'évaluation complétée avec tes remarques et tes ajouts.
Donne à chaque fois la bonne réponse.
</div>
    
<div markdown class="IA">
                        
Voici l'évaluation révisée avec les remarques et les ajouts, accompagnée des bonnes réponses.
Vrai ou Faux ?

Indiquez si les propositions suivantes sont vraies ou fausses.

a. Le langage HTML se présente sous la forme d’une suite d’instructions comportant des balises entrantes et fermantes. [Vrai]
b. Le langage CSS permet de sécuriser sa connexion Internet. [Faux] - CSS est utilisé pour le style des pages web, pas pour la sécurité.
c. Les liens hypertextes permettent de naviguer d’une page à l’autre et d’un site Web à l’autre. [Vrai]
d. Quand on se connecte sur un site sécurisé, un cadenas s’affiche devant l’URL. [Vrai]
e. Il est impossible de supprimer les traces laissées sur Internet. [Faux] - Il est possible de supprimer certaines traces, bien que certaines informations puissent persister en ligne ou être difficiles à éliminer complètement.
f. Un cookie Internet peut stocker des informations sur les préférences de l'utilisateur pour un site Web spécifique. [Vrai]

QCM

Pour chaque proposition, indiquez la bonne réponse.

a. Le rôle du langage HTML est de :
- Crypter des informations.
- Être interprété par un navigateur Web. [Bonne réponse]
- Échanger des données entre serveurs.

b. Les navigateurs permettent de :
- Afficher des pages Web. [Bonne réponse]
- Coder des pages Web.
- Chatter à distance.

c. Pour réaliser un lien vers la page d’accueil de Wikipédia, on écrit :
- `<a href="http://wikipedia.org">Wikipédia</a>` [Bonne réponse]
- `<a target="http://wikipedia.org">Wikipédia</a>`
- `<a href="http://wikipedia.org>`

d. Un protocole sécurisé pour les transactions sur Internet est :
- FTP
- HTTP
- HTTPS [Bonne réponse]

Recopier et compléter les phrases.

Indiquez la bonne réponse pour chaque espace vide.

a. HTML est l’abréviation de Hypertext Markup Language.
b. Le langage HTML est un langage de balisage.
c. Un fichier HTML est constitué de deux parties principales : la tête (head) et le corps (body).
d. Un lien hypertexte permet d’atteindre une autre page du même site ou d’un autre site.
e. Une URL complète se compose du protocole, du nom de domaine et du chemin d'accès.

Vous pouvez utiliser cette évaluation révisée pour tester les connaissances de vos élèves après avoir enseigné le cours sur le Web. Les réponses fournies peuvent également servir de guide de correction.                    
                        
</div>

:::           
    
    
    
#### 2/ Faire analyser son corrigé


:::exemple collapsible Exemple

<div markdown class="user">
</div>

<div markdown class="IA">
</div>

:::