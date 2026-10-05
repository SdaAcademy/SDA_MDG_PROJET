# 📊 Projet Pratique — Data Analytics
## Analyse univariée sous Excel
### Cas d’entreprise : Makala Distribution Group (MDG)

> **Semaine 3 — Projet bref | Fiche apprenant**

---

## 🎯 Contexte du projet

Vous êtes **Junior Data Analyst chez Makala Distribution Group (MDG)**.

La direction souhaite disposer d'une première lecture fiable de la base de données avant d'aller plus loin dans les comparaisons entre agences, clients ou produits.

Le chef formule la demande suivante :

> **« Avant de comparer les agences, les clients ou les produits, je veux savoir si notre base est fiable et ce que chaque variable nous apprend réellement sur notre activité. »**

Votre mission consiste donc à partir du fichier :

**`Base_MDG_Apprenants_A_COMPLETER.xlsx`**

pour :

1. contrôler la qualité de la base ;
2. construire les variables calculées nécessaires ;
3. réaliser une analyse univariée ;
4. produire des tableaux et graphiques adaptés ;
5. interpréter les résultats ;
6. faire ressortir des **insights métier** utiles à la décision.

---

# 👨‍💼 Votre rôle

Vous travaillez comme un **Junior Data Analyst**.

Votre travail ne consiste pas uniquement à produire des chiffres ou des graphiques. Vous devez montrer votre capacité à passer d'une **question métier** à une **analyse structurée**, puis à une conclusion exploitable.

La démarche attendue est :

**Question métier → Variable → Type de variable → Contrôle qualité → Indicateurs → Graphique → Résultat → Interprétation → Insight**

---

# 📌 Questions métier à résoudre

## 1. La base est-elle exploitable ?

Effectuez un contrôle général de la qualité des données.

Vous devez notamment contrôler :

- le nombre de lignes ;
- le nombre de colonnes ;
- la période couverte ;
- les valeurs manquantes ;
- les doublons ;
- les formats ;
- les valeurs incohérentes.

### 🎯 Attendu

Présenter clairement votre diagnostic sur la qualité de la base et identifier les éventuels problèmes qui doivent être traités avant l'analyse.

---

## 2. Quelles variables devons-nous construire avant l'analyse ?

Complétez les variables calculées suivantes :

- `CA_brut`
- `Montant_remise`
- `CA_net`
- `Cout_total`
- `Marge`
- `Taux_marge`
- `Annee`
- `Mois`
- `Trimestre`
- `Classe_age`
- `Niveau_satisfaction`
- `Classe_delai`
- `Valeur_transaction`

### 🎯 Attendu

Chaque variable calculée doit être correctement construite et vérifiée.

---

## 3. Que nous apprend la structure de la clientèle ?

Analysez les variables :

- `client_city`
- `segment`
- `sexe`
- `Classe_age`

### 🎯 Objectif

Décrire la structure de la clientèle et identifier les catégories les plus représentées.

Utilisez des **tableaux de fréquences** et des **graphiques adaptés**.

---

## 4. Que nous apprend l'activité commerciale ?

Analysez :

- `product_name`
- `category`
- `positioning`
- `agency_name`
- `salesperson_name`
- `payment_method`
- `canal_vente`

### 🎯 Objectif

Décrire la manière dont l'activité commerciale est répartie selon les produits, catégories, agences, commerciaux et canaux de vente.

---

## 5. Quelle est la transaction « typique » ?

Analysez les variables quantitatives suivantes :

- `quantity`
- `unit_price`
- `discount_rate`
- `CA_brut`
- `CA_net`
- `Marge`
- `Taux_marge`

### 🎯 Objectif

Décrire la distribution des principales variables quantitatives.

Vous devez notamment utiliser des **statistiques descriptives pertinentes**.

---

## 6. Que nous apprend la qualité de service ?

Analysez :

- `satisfaction_score`
- `Niveau_satisfaction`
- `delai_livraison_jours`
- `Classe_delai`

### 🎯 Objectif

Produire une première lecture de la satisfaction client et des délais de livraison.

---

## 7. Comment l'activité se répartit-elle dans le temps ?

Analysez :

- `Mois`
- `Trimestre`

### 🎯 Objectif

Identifier la répartition temporelle de l'activité et faire ressortir d'éventuelles périodes particulièrement représentées.

---

## 8. Quelles variables présentent des valeurs atypiques ?

Identifiez les éventuels **outliers**.

Pour chaque valeur atypique identifiée, vous devez réfléchir à sa nature :

- est-elle plausible ?
- doit-elle être vérifiée ?
- constitue-t-elle une erreur ?
- doit-elle être exclue de l'analyse ?

### ⚠️ Important

Ne supprimez pas automatiquement une valeur atypique.

Une valeur extrême peut être une véritable observation métier et non une erreur de données.

---

# 📊 Livrable attendu

Votre travail doit être réalisé dans **Excel**.

Le fichier final doit présenter au minimum :

### 1. Variables calculées
Les variables demandées doivent être complétées et correctement calculées.

### 2. Contrôles qualité
Présentez les résultats de vos contrôles :

- dimensions de la base ;
- valeurs manquantes ;
- doublons ;
- formats ;
- incohérences ;
- autres anomalies pertinentes.

### 3. Tableaux d'analyse
Présentez :

- tableaux de fréquences ;
- statistiques descriptives ;
- indicateurs pertinents.

### 4. Graphiques
Utilisez des graphiques adaptés au type de variable et à la question métier.

### 5. Interprétations
Pour chaque analyse importante, ajoutez une courte interprétation.

### 6. Insights
Faites ressortir les principales informations utiles pour le décideur.

---

# 🧠 Règle d'or du projet

Ne faites pas uniquement :

**Données → Graphique**

Vous devez démontrer la chaîne complète :

**Question métier**
↓  
**Variable**
↓  
**Type de variable**
↓  
**Contrôle qualité**
↓  
**Indicateurs**
↓  
**Graphique**
↓  
**Résultat**
↓  
**Interprétation**
↓  
**Insight métier**

---

# 📁 Organisation recommandée du fichier Excel

Nous vous recommandons d'organiser votre classeur avec les feuilles suivantes :

```text
01_Donnees
02_Qualite_Donnees
03_Variables_Calculees
04_Clientele
05_Activite_Commerciale
06_Transaction
07_Qualite_Service
08_Analyse_Temporelle
09_Outliers
10_Synthese
```

Vous pouvez adapter cette organisation si une autre structure permet de rendre votre analyse plus professionnelle et plus lisible.

---

# 📈 Bonnes pratiques attendues

En tant que Data Analyst, veillez à :

- garder une structure claire ;
- ne pas modifier arbitrairement les données sources ;
- documenter les traitements réalisés ;
- utiliser des noms de variables cohérents ;
- vérifier les formules ;
- choisir les graphiques en fonction du message à transmettre ;
- distinguer les résultats descriptifs des interprétations ;
- justifier les décisions prises concernant les valeurs atypiques ;
- produire des analyses compréhensibles par un décideur non technique.

---

# 💡 Questions à vous poser pendant l'analyse

Pour chaque variable, demandez-vous :

- De quel type de variable s'agit-il ?
- Est-elle qualitative ou quantitative ?
- Quelle mesure est pertinente ?
- Quelle distribution observe-t-on ?
- Existe-t-il des valeurs manquantes ?
- Existe-t-il des valeurs incohérentes ?
- Quelle visualisation permet de mieux comprendre cette variable ?
- Qu'est-ce que cette variable nous apprend sur l'activité de MDG ?
- Quel insight peut être communiqué au chef ?

---

# 🏆 Critère de réussite

Un bon travail n'est pas celui qui contient le plus de graphiques.

C'est celui qui démontre que vous savez :

> **transformer une donnée brute en information utile à la décision.**

Votre analyse doit être **claire, structurée, justifiée et orientée métier**.

---

## 📦 Fichier de travail

Utilisez le fichier fourni par le formateur :

```text
Base_MDG_Apprenants_A_COMPLETER.xlsx
```

---

## 👨‍🏫 Consigne finale

Aucune réponse chiffrée n'est fournie dans cet énoncé.

**À vous de construire l'analyse, de vérifier vos résultats et de défendre vos conclusions comme un véritable Data Analyst.**

---

### MDG — Semaine 3 | Projet apprenant
**Analyse univariée sous Excel**
