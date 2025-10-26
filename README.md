# Homepage Personnalisable

Une page d'accueil simple et élégante avec le thème Dracula.

## 📁 Structure des fichiers

```
mon-homepage/
├── homepage.html          ← La page d'accueil
├── services.json          ← Vos services
└── images/               ← Vos images
    ├── logo.png
    └── icon.jpg
```

## 🚀 Démarrage rapide

1. **Téléchargez les fichiers** dans un dossier
2. **Créez un dossier** `images/`
3. **Ouvrez** `homepage.html` dans votre navigateur

C'est tout ! 🎉

## 💡 Utilisation

### Ajouter un service
1. Cliquez sur **+**
2. Remplissez le formulaire (nom, URL, icône, couleur)
3. Cliquez **Ajouter**
4. **Sauvegardez** avec Ctrl+S (ou bouton 💾)
5. Remplacez l'ancien `services.json`

### Modifier un service
1. Passez la souris sur une carte
2. Cliquez sur **✏️** (en haut à gauche)
3. Modifiez et validez
4. **N'oubliez pas de sauvegarder !** (Ctrl+S)

### Supprimer un service
1. Passez la souris sur une carte
2. Cliquez sur **×** (en haut à droite)
3. Confirmez
4. **N'oubliez pas de sauvegarder !** (Ctrl+S)

### Ajouter une image personnalisée
1. Cliquez sur **📷 Image**
2. Choisissez votre image
3. La notification vous indique où la copier
4. Copiez l'image dans le dossier `images/`

## 💾 Sauvegarder vos modifications

**Important :** Les modifications sont d'abord sauvegardées dans votre navigateur (localStorage). Pour les rendre permanentes :

### Méthode 1 : Bouton Sauvegarder
1. Cliquez sur **💾 Sauvegarder** en haut à droite
2. Le fichier `services.json` se télécharge
3. Remplacez l'ancien fichier à la racine

### Méthode 2 : Raccourci clavier
1. Appuyez sur **Ctrl+S** (ou Cmd+S sur Mac)
2. Le fichier `services.json` se télécharge
3. Remplacez l'ancien fichier à la racine

### Charger des services
1. Cliquez sur **📥 Charger** (ou Ctrl+O)
2. Sélectionnez votre `services.json`
3. Vos services sont chargés !

## 🔄 Synchroniser entre ordinateurs

### Option 1 : Cloud (Dropbox, Google Drive, etc.)
```
1. Placez tout le dossier dans votre cloud
2. Sur chaque ordinateur, ouvrez homepage.html
3. Après modifications, sauvegardez (Ctrl+S)
4. Le cloud synchronise automatiquement
```

### Option 2 : Clé USB
```
1. Copiez le dossier complet sur la clé
2. Travaillez normalement
3. Sauvegardez (Ctrl+S)
4. Remplacez services.json sur la clé
```

### Option 3 : Manuel
```
1. Sur PC 1 : Sauvegardez (Ctrl+S)
2. Transférez services.json (email, etc.)
3. Sur PC 2 : Chargez (Ctrl+O)
```

## 📋 Format du fichier services.json

```json
{
  "services": [
    {
      "name": "YouTube",
      "url": "https://youtube.com",
      "icon": "🎬",
      "iconType": "emoji",
      "color": "#FF5555"
    },
    {
      "name": "Mon Blog",
      "url": "https://monblog.com",
      "icon": "images/logo.png",
      "iconType": "image",
      "color": "#BD93F9"
    }
  ]
}
```

## 🎨 Couleurs disponibles

- Gris : `#6272A4`
- Rouge : `#FF5555`
- Vert : `#50FA7B`
- Cyan : `#8BE9FD`
- Violet : `#BD93F9`
- Rose : `#FF79C6`
- Jaune : `#F1FA8C`
- Orange : `#FFB86C`

## ⚙️ Fonctionnement

### Chargement des services
1. **services.json** (si présent à la racine)
2. **localStorage** (sauvegarde du navigateur)
3. **Services par défaut** (si rien n'existe)

### Sauvegarde
- **Automatique** : dans localStorage du navigateur
- **Manuelle** : exportez vers services.json (Ctrl+S)

## 🆘 Dépannage

**Les services disparaissent après un refresh ?**
- Vous n'avez pas de `services.json` à la racine
- Créez-en un avec Ctrl+S

**Une image ne s'affiche pas ?**
- Vérifiez qu'elle est dans le dossier `images/`
- Vérifiez le nom exact (sensible à la casse)

**J'ai perdu mes services !**
- Si vous avez sauvegardé : Ctrl+O pour charger services.json
- Sinon, vérifiez localStorage (F12 → Application → Local Storage)

**Comment restaurer les services par défaut ?**
```javascript
// Ouvrez la console (F12) et tapez :
localStorage.removeItem('homepage_services');
// Rechargez la page (F5)
```

## ⌨️ Raccourcis clavier

- **Ctrl+S** : Sauvegarder (télécharge services.json)
- **Ctrl+O** : Charger (importe services.json)

## 🌐 Définir comme page d'accueil

### Chrome/Edge
```
Paramètres → Au démarrage → Ouvrir une page spécifique
file:///C:/chemin/vers/mon-homepage/homepage.html
```

### Firefox
```
Paramètres → Accueil → URL personnalisée
file:///C:/chemin/vers/mon-homepage/homepage.html
```

## ✨ Avantages

✅ **Simple** - Un seul fichier HTML
✅ **Portable** - Fonctionne partout
✅ **Hors ligne** - Pas besoin d'internet
✅ **Léger** - Aucune dépendance
✅ **Personnalisable** - Couleurs et icônes
✅ **Images** - Nom original conservé
✅ **Rapide** - Cartes compactes

## 📝 Notes importantes

- **Pensez à sauvegarder** après chaque modification (Ctrl+S)
- Les notifications vous rappellent de sauvegarder
- Le bouton **✏️** est à **gauche** de la carte
- Le bouton **×** est à **droite** de la carte
- Les images gardent leur nom original

Bonne navigation ! 🚀
