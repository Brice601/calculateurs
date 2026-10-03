# Calculateurs

Collection de calculateurs pratiques en HTML/CSS/JavaScript pour des besoins financiers courants.

## Calculateurs disponibles

### 📊 Calculateur de rendement composé

**Fichier** : `calculateur-rendement.html`

Visualisez la croissance de votre capital avec intérêts composés **mensuels** et épargne **mensuelle**.

#### Fonctionnalités

- 📈 Simulation de capital initial (optionnel)
- 💰 Paramétrage du salaire et du taux d'épargne
- 📊 Rendement annuel ajustable (5%, 6%, 7%, etc.)
- 📅 Projection sur plusieurs années
- 📉 Graphique interactif montrant l'évolution du capital et des intérêts
- 📋 Tableau détaillé année par année

#### Comment ça marche

**Épargne mensuelle** :
- Salaire annuel ÷ 12 = salaire mensuel
- Salaire mensuel × (taux d'épargne / 100) = montant épargné chaque mois

**Exemple** :
- Salaire annuel : 30 000 €
- Taux d'épargne : 15 %
- **Épargne mensuelle : (30 000 ÷ 12) × 15% = 375 €**

**Intérêts composés** :
- Les rendements sont calculés **mensuellement**
- Chaque mois : (capital actuel × taux annuel ÷ 12) s'ajoute au capital
- Plus c'est fréquent, plus le composé fonctionne en votre faveur

#### Comment utiliser

1. Ouvrez `calculateur-rendement.html` dans votre navigateur
2. Remplissez les paramètres :
   - **Capital initial** : montant de départ (peut être 0)
   - **Salaire annuel** : votre revenu annuel
   - **Taux d'épargne** : pourcentage du salaire à épargner mensuellement (10%, 15%, 20%, etc.)
   - **Rendement annuel** : taux d'intérêt composé (5%, 6%, 7%, etc.)
   - **Nombre d'années** : horizon de simulation
3. Cliquez sur **Calculer**
4. Consultez les résultats :
   - Capital final
   - Total épargné
   - Intérêts gagnés
   - Rendement total en %
5. Explorez le graphique et le tableau détaillé

#### Cas d'usage

- Planification financière personnelle
- Comparaison de scénarios d'épargne
- Visualisation de l'impact des intérêts composés
- Objectifs d'épargne à moyen/long terme
- Démonstration de la puissance du composé mensuel

#### Caractéristiques techniques

- ✅ HTML autonome (aucune dépendance externe hormis Chart.js via CDN)
- ✅ Responsive (mobile, tablette, desktop)
- ✅ Calculs en temps réel
- ✅ Graphiques interactifs
- ✅ Pas de sauvegarde de données (calculs locaux uniquement)
- ✅ Épargne mensuelle avec intérêts composés mensuellement

---

**Licence** : Libre d'utilisation  
**Langage** : HTML5 + CSS3 + JavaScript ES6  
**Dernière mise à jour** : octobre 2026
