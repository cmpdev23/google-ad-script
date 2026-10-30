# Google Ads Scripts Collection

Ce dépôt regroupe une collection de scripts Google Ads open source et communautaires trouvés sur GitHub, organisés par auteur ou projet source. Ces scripts permettent d'automatiser la gestion, l'optimisation, l'audit et le reporting de comptes Google Ads.

---

## 📁 Structure du dépôt

```text
├── brainlabs/                   # Scripts par Brainlabs
├── charlesbannister/            # Scripts par Charles Bannister
├── johnoconnor/                 # Scripts par John O'Connor
└── omnicliq/                    # Scripts par Omnicliq
```

---

## 🔍 Contenu des dossiers

### 1. [`brainlabs/`](brainlabs)
Scripts d'optimisation et d'automatisation par Brainlabs :
- **Analyse (`Analyzing`)** : analyse de longueur des textes d'annonces et rotation des annonces.
- **Enchères (`Bidding`)** : planification avancée (ad scheduling), enchères selon audiences in-market, appareils et emplacements.
- **Gestion (`Managing`)** : gestion des budgets, sécurisation du match exact/phrase, détection d'annonces dupliquées, gestion des libellés et des flux shopping.
- **Monitoring (`Monitoring`)** : contrôle de surconsommation budgétaire, alertes d'anomalies de dépenses, vérification d'URL brisées, vérification des refus Google Merchant Center (GMC) et alertes de Quality Score bas.
- **Reporting (`Reporting`)** : outils de search query mining, créateur de heatmaps avec périphériques, insights sur les enchères et rapports sur les extensions.
- **Tests (`Testing`)** : tests A/B et analyse de rotation des annonces.

### 2. [`charlesbannister/`](charlesbannister)
Scripts d'automatisation et d'analyse avancée par Charles Bannister :
- **Détection d'anomalies** : détection de variations inhabituelles de dépenses et de performances.
- **Mots-clés négatifs** : gestion automatique des mots-clés négatifs avec feuilles Google Sheets ou IA.
- **Performance & Rapports** : rapports de campagnes, suivi des tendances Google Shopping et GCLID.
- **Performance PMax & Search Terms** : analyse de n-grams pour Performance Max et campagnes Search standards.
- **Gestion des enchères** : ajustement des enchères basé sur des règles personnalisées.

### 3. [`johnoconnor/`](johnoconnor)
Scripts modulaires par John O'Connor :
- **Enchères (`bidding`)** : enchères basées sur la météo, la localisation ou la distance.
- **Gestion de campagne (`campaign-management`)** : planification horaire des annonces, gestion des budgets et gestion des stocks.
- **Mots-clés (`keywords`)** : gestion des termes de recherche, listes négatives et requêtes.
- **Monitoring & Alertes (`monitoring`)** : vérification des erreurs 404 / liens brisés, alertes automatiques et suivi du Quality Score.
- **Tests A/B (`testing`)** : tests fractionnés (A/B split testing).

### 4. [`omnicliq/`](omnicliq)
Scripts spécialisés pour l'optimisation avancée par Omnicliq :
- **Audits de santé** : audit complet de compte et détection d'anomalies de dépenses (niveau compte et MCC).
- **Protection & Clôturage de requêtes (Query Fencing)** : gestion fine des requêtes concurrents, cross-adgroup et DSA.
- **Performance Max (PMax)** : audit des emplacements et détection des termes de recherche sans conversion.
- **Annonces textuelles & RSA** : constructeur RSA et rapports de performance des éléments (assets).
- **Suivi & Rapports** : analyse n-grams, heatmap de calendrier de diffusion, suivi d'Impression Share et scores d'optimisation.

---

## 🚀 Utilisation générale

1. Connectez-vous à votre interface **Google Ads**.
2. Rendez-vous dans **Outils et paramètres** > **Actions groupées** > **Scripts**.
3. Créez un nouveau script en cliquant sur le bouton **+**.
4. Copiez et collez le code JavaScript (`.js` ou `.gs`) du script souhaité.
5. Ajustez les variables de configuration (identifiants, seuils, URL de Google Sheets, notifications e-mail).
6. Prévisualisez le script pour valider son exécution sans modifier le compte.
7. Planifiez la fréquence d'exécution selon vos besoins (quotidienne, hebdomadaire, etc.).

---

## ⚠️ Avertissement

Ces scripts proviennent de différentes sources publiques et open source. Pensez toujours à exécuter une prévisualisation (**Preview**) avant d'autoriser des modifications directes sur vos campagnes de production.
