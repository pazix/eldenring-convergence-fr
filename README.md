# 🇫🇷 Traduction française du mod The Convergence pour Elden Ring

Ce repository propose une traduction complète en français du célèbre mod **The Convergence** pour Elden Ring.

Tous les textes, objets, descriptions, menus et tutoriels sont adaptés dans le respect du style original d'Elden Ring et de la terminologie officielle française.

## 📁 Structure du patch

Le dossier `frafr` contenu dans ce repository est prêt à l'emploi.

Vous n'avez qu'à le copier directement dans `...\ConvergenceER\mod\msg\` pour profiter de la traduction FR du mod.

```
eldenring-convergence-fr/
│
├── frafr/
│   ├── item_dlc02.msgbnd.dcx
│   ├── menu_dlc02.msgbnd.dcx
│   └── ... (autres fichiers)
├── README.md
└── (autres fichiers éventuels)
```

## 🚀 Installation du patch FR pour The Convergence

### Prérequis

- Le mod **The Convergence** pour Elden Ring installé via **Mod Engine 2**
- Avoir téléchargé ce patch de traduction française (`frafr`)

### Étapes d'installation

1. **Téléchargez ce repository**
   
   Cliquez sur le bouton `Code` > `Download ZIP` (ou utilisez `git clone`).

2. **Fermez Elden Ring et Mod Engine 2**
   
   Assurez-vous qu'aucun processus du jeu ou du mod n'est ouvert.

3. **Accédez au dossier d'installation du mod The Convergence**
   
   Le chemin ressemble généralement à :
   ```
   ...\ConvergenceER\mod\msg\
   ```

4. **Copiez le dossier `frafr` du patch**
   
   - Ouvrez le dossier téléchargé, repérez le dossier `frafr`
   - Collez le dossier `frafr` dans le répertoire :
   ```
   ...\ConvergenceER\mod\msg\
   ```
   
   Le résultat attendu doit être :
   ```
   ...\ConvergenceER\mod\msg\frafr\
   ```
   (à côté des dossiers existants comme `engus`, `jpnjp`, etc.)

5. **Vérifiez que tous les fichiers `.msgbnd.dcx` sont bien présents dans `frafr`**
   
   Exemples : `item_dlc02.msgbnd.dcx`, `menu_dlc02.msgbnd.dcx`, etc.

6. **Lancez Elden Ring via Mod Engine 2**
   
   Utilisez le script `launchmod_eldenring.bat` fourni par Mod Engine 2.

7. **Sélectionnez la langue "Français" dans les options du jeu**
   
   Les textes, objets, menus, descriptions du mod s'afficheront alors en français.

## ℹ️ À propos de la traduction

Cette traduction française a été générée principalement via l'API **ChatGPT** (modèle OpenAI GPT-4.1), en utilisant un workflow automatisé :

1. **Détection et extraction automatique** de tous les textes du mod
2. **Traduction IA EN → FR**, avec une attention particulière au style et à la terminologie officielle d'Elden Ring
3. **Relecture humaine ponctuelle** sur certaines sections clés (objets, tutoriels…)

### ⚠️ Note importante

Bien que la qualité générale de la traduction soit bonne (notamment sur les descriptions longues et les tutoriels), il peut subsister :

- Quelques erreurs de traduction "mot à mot"
- Certains textes très courts ou composés d'un seul mot qui n'ont pas été traduits (ou mal détectés lors de l'extraction automatique)
- Des formulations ou tournures qui peuvent sembler inhabituelles (surtout sur les lignes de 1 à 3 mots)

L'outil d'IA utilisé pour détecter la langue ou trouver les nouveaux textes du mod peut avoir des difficultés sur les phrases très courtes. 

Si vous trouvez des oublis ou des coquilles, n'hésitez pas à ouvrir une **issue** ou proposer une correction via une **pull request** : c'est un patch communautaire !

## 🤝 Contribution

Vous pouvez contribuer à l'amélioration continue de la traduction !

Si vous repérez une faute, un oubli ou une tournure étrange, merci de :

- **Ouvrir une issue** sur le repository
- Ou **proposer directement une correction** via une pull request

La communauté pourra ainsi affiner et perfectionner la traduction au fil des mises à jour du mod.

**Merci de votre aide et bon jeu à tous !**

## 💬 Remerciements

Merci à la communauté du modding Elden Ring, aux créateurs du mod **The Convergence**, et à tous les testeurs français !