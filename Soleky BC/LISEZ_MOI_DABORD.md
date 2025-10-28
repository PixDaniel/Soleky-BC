# 📚 DOCUMENTATION SOLEKY - BON DE COMMANDE AUTOMATISÉ

## 🎯 VOUS AVEZ REÇU 4 FICHIERS

### 1. **bon_commande_soleky_v1.html** ✅
**C'EST QUOI ?** Le bon de commande fonctionnel (Version 1 - Standalone)
**POUR QUOI ?** Utilisation immédiate sans configuration
**COMMENT ?** Double-cliquez dessus, il s'ouvre dans votre navigateur

### 2. **guide_installation_n8n_soleky.md** 📘
**C'EST QUOI ?** Guide complet pour installer l'automatisation
**POUR QUOI ?** Mettre en place emails + stockage Google Sheets
**COMMENT ?** Suivez étape par étape (45 min de configuration)

### 3. **workflows_n8n_soleky.md** 🔧
**C'EST QUOI ?** Les 4 workflows n8n en format JSON
**POUR QUOI ?** À importer dans n8n.cloud
**COMMENT ?** Copier-coller les codes JSON dans n8n

### 4. **guide_visuel_workflows.md** 🎨
**C'EST QUOI ?** Schémas et explications visuelles
**POUR QUOI ?** Comprendre comment tout fonctionne
**COMMENT ?** Lecture pour comprendre l'architecture

---

## 🚀 PAR OÙ COMMENCER ?

### Option A : Usage immédiat (5 minutes) ⚡
```
1. Ouvrir bon_commande_soleky_v1.html
2. Tester la création d'un BC
3. C'est tout ! Vous avez un BC fonctionnel
```

**⚠️ Limites :**
- Pas d'emails automatiques
- Compteur BC stocké localement (un navigateur = un compteur)
- Pas de sauvegarde centralisée

**✅ Avantages :**
- Fonctionne immédiatement
- Pas de configuration
- Gratuit à 100%

---

### Option B : Installation complète (1h30) 🏗️
```
1. Lire guide_installation_n8n_soleky.md
2. Créer les comptes (n8n, Brevo, Google)
3. Importer les workflows depuis workflows_n8n_soleky.md
4. Configurer le bon de commande V2 (fourni séparément)
5. Tester le système complet
```

**✅ Avantages :**
- Emails automatiques (OTP + accusés)
- Stockage Google Sheets centralisé
- Compteur BC fiable (synchronisé)
- Historique complet
- Tableau de bord statistiques
- 100% gratuit aussi !

---

## 📊 COMPARAISON RAPIDE

| Fonctionnalité | Version 1 (V1) | Version 2 avec n8n |
|----------------|----------------|--------------------|
| Création BC | ✅ | ✅ |
| Signature sécurisée | ✅ | ✅ |
| Calculs automatiques | ✅ | ✅ |
| Export PDF/CSV | ✅ | ✅ |
| **Emails OTP** | ❌ Manuel | ✅ Automatique |
| **Accusés réception** | ❌ Manuel | ✅ Automatique |
| **Stockage centralisé** | ❌ Local | ✅ Google Sheets |
| **Compteur BC fiable** | ⚠️ Local | ✅ Centralisé |
| **Historique** | ❌ | ✅ Complet |
| **Tableau de bord** | ❌ | ✅ Stats & graphiques |
| **Coût** | 0 € | 0 € |
| **Configuration** | 0 min | 90 min |

---

## 💡 MA RECOMMANDATION

### Pour démarrer TOUT DE SUITE :
✅ **Utilisez la V1** (bon_commande_soleky_v1.html)
- Testez-la
- Formez votre équipe
- Validez que ça répond à vos besoins

### Puis, quand vous aurez 1h30 devant vous :
✅ **Passez à la V2 automatisée**
- Suivez le guide_installation_n8n_soleky.md
- Configurez tranquillement
- Profitez de l'automatisation complète

---

## 🔧 PERSONNALISATION DE LA V1

### Ajouter votre logo
Ouvrez le fichier HTML, cherchez la ligne **625** :
```javascript
const CONFIG_LOGO = {
    url: 'https://votre-site.com/logo.png',  // ← Mettez l'URL de votre logo
    fallbackText: 'SOLEKY'
};
```

### Modifier les produits
Ligne **645**, section `PRODUCTS` :
```javascript
const PRODUCTS = [
    {
        ref: 'SK-001',
        name: 'Votre produit',
        formats: ['250 ml', '500 ml'],
        parfums: ['Nature', 'Coco'],
        prices: { '250 ml': 7500, '500 ml': 12000 }
    },
    // Ajoutez vos produits ici
];
```

---

## 🆘 BESOIN D'AIDE ?

### Documentation technique
- **n8n :** https://docs.n8n.io
- **Brevo :** https://developers.brevo.com
- **Google Sheets API :** https://developers.google.com/sheets

### Support communautaire
- **Forum n8n :** https://community.n8n.io
- **Stack Overflow :** Tag [n8n] ou [google-sheets-api]

---

## ✅ CHECKLIST DE DÉMARRAGE

### Phase 1 : Test immédiat (V1)
- [ ] Ouvrir bon_commande_soleky_v1.html
- [ ] Créer un BC de test
- [ ] Tester la signature
- [ ] Exporter en PDF et CSV
- [ ] Former l'équipe

### Phase 2 : Automatisation (V2) - Optionnel
- [ ] Lire guide_installation_n8n_soleky.md
- [ ] Créer compte n8n.cloud
- [ ] Créer compte Brevo
- [ ] Préparer Google Sheets
- [ ] Importer les 4 workflows
- [ ] Configurer les credentials
- [ ] Tester chaque workflow
- [ ] Intégrer au bon de commande
- [ ] Test complet end-to-end

---

## 🎉 RÉSUMÉ

Vous avez maintenant :
1. ✅ Un bon de commande fonctionnel (V1)
2. 📘 Tous les guides pour l'automatiser (V2)
3. 🔧 Les workflows prêts à l'emploi
4. 🎨 Des schémas pour comprendre

**Commencez simple (V1), puis automatisez quand vous êtes prêt (V2) !**

---

## 📞 INFORMATIONS PROJET

**Date :** Octobre 2025  
**Version :** 1.0  
**Pour :** Soleky - Yellowfield Organic Products  
**Contact :** contact@soleky.com  

**Développé par :** Assistant Claude (Anthropic)  
**Licence :** Usage libre pour Soleky

---

**BON COURAGE ET BONNE UTILISATION ! 🚀🌿**
