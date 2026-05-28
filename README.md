# 🏛️ Conseil des Ministres
## Serious Game pédagogique · Terminale STMG Économie · Version 4.0

> Un serious game interactif couvrant les **Thèmes 6.3, 6.4 et 7** du programme officiel d'économie STMG.

---

## 📚 Programme couvert

| Thème | Intitulé officiel |
|-------|-------------------|
| **7** | *Quelle est l'influence de l'État sur l'évolution de l'emploi et du chômage ?* |
| **6.3** | *Quelles sont les principales défaillances du marché et comment l'État peut-il améliorer son fonctionnement ?* |
| **6.4** | *Comment les politiques sociales visent-elles à améliorer la cohésion sociale ?* |

---

## 🎮 Principe du jeu

Les élèves incarnent le **Conseil des Ministres** et disposent de **8 trimestres (2 ans)** pour redresser la situation économique et sociale d'un pays selon le scénario choisi.

Chaque trimestre :
1. Le tableau de bord affiche 13 indicateurs économiques et sociaux
2. L'équipe choisit jusqu'à **3 mesures** parmi 25 politiques, réparties par ministère
3. Un **événement aléatoire** peut survenir et modifier la situation
4. Un **Flash Quiz** pose une question de cours liée aux décisions prises
5. Les indicateurs évoluent selon les impacts cumulés

---

## 🗂️ Fichiers du projet

| Fichier | Rôle | Public |
|---------|------|--------|
| `index.html` | Le jeu complet | Élèves |
| `guide.html` | Fiche aide-mémoire A4 recto-verso à imprimer (politiques, arbitrages, conseils) | Élèves |
| `fiches_scenarios.html` | 6 fiches A4 à imprimer — une par scénario (contexte + objectifs + conseils) | Élèves |
| `decoder.html` | Espace enseignant : décodage des codes + classement en direct | Enseignant |
| `README.md` | Ce fichier | — |

---

## ✨ Fonctionnalités — Version 4.0

### 🗺️ 6 scénarios narratifs

Chaque scénario a un **contexte économique réaliste**, des **objectifs multiples** et un **niveau de difficulté** propre.

| Scénario | Difficulté | Chômage départ | Enjeu principal |
|----------|-----------|----------------|-----------------|
| 🔴 Crise Économique | Très difficile | 14% | Récession, relancer l'emploi |
| 🟡 Situation Standard | Moyen | 12% | Équilibre emploi / déficit |
| 🟢 Boom Économique | Facile | 9% | Éviter la surchauffe inflationniste |
| 🏭 Désindustrialisation | Très difficile | 15% | Chômage structurel, reconversion |
| ⚖️ Fracture Sociale | Difficile | 8% | Inégalités record malgré croissance |
| 🔥 Crise Inflationniste | Difficile | 7% | Inflation à 8,5%, éviter la récession |

Chaque scénario propose **3 objectifs simultanés** (pas uniquement le chômage) et indique les ministères prioritaires.

---

### 🏛️ Conseil des Ministres — 4 portefeuilles

Les décisions ne sont plus prises par un seul ministre. Chaque trimestre, **4 ministres** ont chacun un quota de mesures dans leur domaine :

| Ministre | Portefeuille | Quota/trimestre |
|----------|-------------|-----------------|
| 💼 Travail | Politiques actives + passives | 2 max |
| 💰 Économie | Demande + offre + économie | 2 max |
| 🏥 Affaires Sociales | Politiques sociales | 1 max |
| 🎓 Éducation | Politiques éducation | 1 max |

En mode équipe (2-4 élèves), chacun incarne un ministre et doit **négocier** ses choix avec les autres.

---

### 📊 25 politiques disponibles

Classées par type et ministère, filtrables et triables en jeu :

**💼 Travail — Politiques Actives**
Formation professionnelle · Aides à l'embauche · Réduction du temps de travail · Soutien à la création d'entreprise

**💼 Travail — Politiques Passives**
Indemnisation chômage renforcée · Préretraites

**💰 Économie — Politiques de Demande**
Investissement public · Baisse de la TVA · Prime à la consommation

**💰 Économie — Politiques d'Offre**
Baisse des charges patronales · Assouplissement du droit du travail · Subventions à l'innovation

**💰 Économie — Politiques Économiques**
Réforme fiscale progressive · Politique de la concurrence · Austérité budgétaire · Soutien au crédit des entreprises · Politique industrielle sectorielle · Lutte contre l'inflation

**🏥 Affaires Sociales**
Couverture santé renforcée · RSA/minima sociaux · Logement social · Aide alimentaire d'urgence · Amélioration des retraites

**🎓 Éducation**
Investissement massif dans l'éducation · Développement de l'apprentissage

---

### 📈 13 indicateurs économiques et sociaux

| Catégorie | Indicateurs |
|-----------|-------------|
| Emploi | Taux de chômage · Taux d'emploi · Taux d'activité |
| Budget | Budget de l'État |
| Économie | Croissance · Déficit public · Dette publique · Inflation |
| Social | Taux de pauvreté · Inégalités (Gini) · Popularité |
| Acteurs | Satisfaction entreprises · Satisfaction salariés |

Le **dashboard est repliable** : les 5 indicateurs prioritaires sont toujours visibles, les 8 autres s'affichent au clic. Un **point rouge clignotant** signale les indicateurs en zone critique.

---

### 🎲 23 événements aléatoires

Probabilité d'occurrence par trimestre selon le scénario (55% à 70%).

**Négatifs :** Crise économique mondiale · Crise bancaire · Grève générale · Délocalisation majeure · Innovation destructrice d'emplois · Fermeture d'usines · Manifestations étudiantes · Crise du logement · Vague de pauvreté · Scandale sanitaire · Guerre commerciale · Hausse des prix de l'énergie · Crise des réfugiés · Pandémie sanitaire

**Positifs :** Transition écologique · Plan de relocalisation réussi · Implantation multinationale · Succès relocalisation · Boom transition écologique · Accord commercial favorable · Innovation sociale réussie · Innovation technologique

---

### 🧠 Flash Quiz pédagogique

À chaque fin de trimestre (70% de chance), une **question de cours** apparaît, liée aux politiques que l'équipe vient de choisir ou à l'événement survenu.

- Source mise en scène (BFMTV, France 2, un expert économiste…) pour contextualiser
- 4 propositions avec une seule bonne réponse
- Feedback immédiat avec l'explication du mécanisme économique
- **Bonus popularité** si la réponse est correcte
- **Compteur de série** (🔥×n) si plusieurs bonnes réponses consécutives
- Possibilité de passer la question

Les questions couvrent tous les types de politiques et les notions clés des thèmes 6.3, 6.4 et 7.

---

### 📋 Code de partie — mode compétition

Un **code unique de 5 caractères** est généré en temps réel et affiché en permanence en **doré** dans l'en-tête du jeu. Il encode :
- Le scénario joué
- Le score en cours
- Le taux de chômage final

Les élèves **copient ou dictent** ce code à l'enseignant. Un bouton "📋 Copier" copie directement le code + le contexte complet dans le presse-papiers.

Un lien **"Espace enseignant →"** dans la barre du code ouvre directement `decoder.html` dans un nouvel onglet.

Dans `decoder.html`, un **classement en temps réel** s'affiche dès qu'il y a des élèves : podium 🥇🥈🥉, score, scénario joué, objectif atteint ou non — idéal pour projeter en fin de séance et animer le débriefing.

---

### 📖 Glossaire économique intégré

Un bouton flottant **📖 Glossaire** accessible à tout moment pendant la partie ouvre un modal avec **23 définitions** issues du programme :

- Recherche textuelle en temps réel
- Filtres par catégorie (Emploi · Économie · Budget · Social · Europe)
- Chaque terme : définition précise + exemple concret + référence au thème (6.3 / 6.4 / 7)

---

### 🔍 Filtres et tri des politiques

La liste des 25 politiques est filtrable et triable en temps réel :

- **Filtres par ministère** : onglets Conseil des ministres / Travail / Économie / Social / Éducation
- **Filtres par type** : Actives · Passives · Demande · Offre · Économie · Social · Éducation
- **Filtres rapides** : Finançables uniquement · Sélectionnées uniquement
- **Tri** : par défaut · coût croissant · coût décroissant · impact total · alphabétique

---

### 📋 Journal des actions + graphiques d'évolution

Un **panneau latéral** persistent pendant toute la partie affiche :

- **Graphiques sparkline** pour 6 indicateurs clés (onglets cliquables : Chômage, Emploi, Budget, Croissance, Déficit, Pauvreté) — évolution depuis le début de la partie
- **Journal des décisions** : pour chaque trimestre passé, les politiques choisies, l'événement survenu, et les indicateurs qui ont bougé

---

### 📊 Rapport de mi-parcours

Après le 4e trimestre (mi-mandat), un **bilan automatique** s'affiche :
- Progression vers l'objectif de chômage (barre de progression)
- Tableau comparatif départ / maintenant / objectif
- Recommandations stratégiques pour la seconde année

---

### 🏆 Bilan final et scoring

En fin de partie, évaluation sur **4 dimensions** :
- Lutte contre le chômage
- Création d'emplois
- Gestion budgétaire
- Équilibre social (satisfaction entreprises vs salariés)

Les scénarios terminés sont mémorisés. Une fois les **6 scénarios** complétés, un écran de félicitations s'affiche.

---

## 📁 Espace Enseignant — decoder.html

Interface dédiée à l'enseignant, thème sombre professionnel, aucune dépendance externe.

**Fonctionnalités :**
- Saisie nom + code → décodage instantané avec aperçu en temps réel
- Validation du checksum (détecte les codes mal recopiés)
- Tableau de classe : scénario joué, score, grade A/B/C/D, chômage final, objectif atteint ✅/❌
- Colonnes triables (clic sur l'en-tête)
- Statistiques de classe en direct (score moyen, chômage moyen, taux de réussite)
- Légende des scénarios avec comptage par scénario
- **Export CSV** compatible Excel (avec BOM UTF-8)
- Persistance localStorage : les données restent si on ferme et rouvre le fichier en cours de séance

---

## 🖨️ Fiches scénarios — fiches_scenarios.html

6 pages A4 à imprimer (1 par équipe selon le scénario choisi).

**Contenu de chaque fiche :**
- En-tête couleur avec nom du scénario et niveau de difficulté
- Contexte narratif complet
- Tableau des indicateurs de départ avec niveaux d'alerte
- Les 3 objectifs à atteindre avec cibles chiffrées
- Priorités par ministre (haute / moyenne / faible)
- L'arbitrage économique central du scénario
- 3-4 conseils stratégiques (sans donner les réponses)
- Box d'avertissement : erreur classique ou notion clé du programme

---

## 🖨️ Guide élève — guide.html

Fiche **2 pages A4 recto-verso** à imprimer et distribuer avant la séance.

**Contenu :**
- En-tête à remplir (nom, classe, scénario, score)
- Les 4 ministres et leurs quotas
- **Tableau complet indicateur par indicateur** : mécanisme économique + toutes les politiques qui agissent dessus + effets chiffrés + coût + effets secondaires ⚠️
- Les 4 grands arbitrages (Croissance vs Inflation, Déficit vs Emploi, etc.)
- Tableau des 6 scénarios avec stratégie conseillée
- 6 conseils stratégiques

---

## 🚀 Déploiement

### Sur GitHub Pages (recommandé)

1. Créez un repository GitHub
2. Uploadez les **5 fichiers** dans le même dossier : `index.html`, `decoder.html`, `guide.html`, `fiches_scenarios.html`, `README.md`
3. **Settings → Pages → Branch : main → Folder : / (root) → Save**
4. Le jeu est accessible à : `https://[username].github.io/[nom-repo]/`
5. Le décodeur enseignant : `https://[username].github.io/[nom-repo]/decoder.html`
6. Le guide élève imprimable : `https://[username].github.io/[nom-repo]/guide.html`
7. Les fiches scénarios : `https://[username].github.io/[nom-repo]/fiches_scenarios.html`

> ⚠️ Tous les fichiers doivent être dans le **même dossier** — le lien "Espace enseignant" dans le jeu pointe vers `decoder.html` en chemin relatif.

### En local (sans internet)

Double-clic sur `index.html` — fonctionne directement dans le navigateur, aucune installation.

---

## 💻 Utilisation en classe

**Durée recommandée :** 1h40 à 2h

**Configuration :**
- Par équipes de 2 à 4 élèves · 1 ordinateur par équipe
- Navigateur moderne (Chrome, Firefox, Edge, Safari)
- Connexion internet uniquement au premier chargement (fonctionne ensuite hors ligne)
- Imprimer `guide.html` en A4 recto-verso avant la séance

**Déroulement suggéré :**

| Durée | Phase |
|-------|-------|
| 10 min | Distribution du guide · Présentation des scénarios · Choix par équipe |
| 5 min | Lecture du briefing de mission et des objectifs |
| 10 min | Phase de diagnostic |
| 60 min | 8 trimestres de décisions + quiz + événements + mi-parcours |
| 25 min | Débriefing collectif : comparaison des codes, discussion des arbitrages, lien avec le cours |

**Idées de débriefing :**
- Quelle équipe a le meilleur score ? Quel scénario ? Pourquoi ?
- Quels arbitrages ont été les plus difficiles ? (Déficit vs Emploi, Inflation vs Croissance…)
- Quelles politiques avez-vous le plus utilisées ? Pourquoi ?
- Comment les événements ont-ils perturbé votre stratégie ?
- Quel ministre avait le plus de pouvoir selon le scénario ?

---

## 📚 Notions du programme abordées

### Thème 7 — Politiques de l'emploi
- Taux de chômage, taux d'emploi, taux d'activité
- Chômage structurel, conjoncturel, frictionnel
- Politiques actives vs passives
- Politiques de demande vs d'offre
- Population active, plein emploi, sous-emploi

### Thème 6.3 — Politiques économiques
- Politiques budgétaires : relance keynésienne vs austérité
- Effet multiplicateur de l'investissement public
- Politiques fiscales : progressivité, redistribution
- Politique de la concurrence (anti-monopoles, PME)
- Contraintes européennes : règle des 3% de déficit, BCE
- Arbitrage croissance / déficit / dette / inflation

### Thème 6.4 — Politiques sociales
- Protection sociale : santé, retraites, minima sociaux (RSA)
- Lutte contre la pauvreté : logement, aide alimentaire
- Réduction des inégalités : fiscalité progressive, Gini
- Financement de l'État-providence
- Arbitrage efficacité / équité

---

## 🛠️ Technologies

- **React 18** via CDN (pas de build, pas de Node.js)
- **Babel Standalone** pour la transpilation JSX dans le navigateur
- **LocalStorage API** pour la sauvegarde automatique
- **HTML5 / CSS3** natif, design responsive
- **SVG** pour les graphiques sparkline
- Aucune dépendance npm · Aucune installation requise

---

## 📱 Compatibilité

✅ Ordinateurs Windows, Mac, Linux  
✅ Tablettes (interface adaptée)  
✅ Smartphones (affichage responsive)  
✅ Chrome · Firefox · Edge · Safari

---

## 📄 Licence

Projet sous licence **MIT** — libre d'utilisation, de modification et de distribution pour l'enseignement.

---

## 👥 Crédits

Développé par **Katia** avec l'assistance de **Claude (Anthropic)**  
Programme : **STMG Terminale — Économie-Droit**  
Thèmes couverts : **6.3 · 6.4 · 7**  
Version : **4.0** · Mai 2026

---

*Bon jeu et bon enseignement ! 🎓*
