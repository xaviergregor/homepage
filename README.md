# Homepage Personnalisable

Une page d'accueil simple et élégante avec le thème Dracula et réorganisation par glisser-déposer.

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

## ✨ Fonctionnalités principales

- ➕ **Ajouter** des services avec emojis ou images
- ✏️ **Modifier** les services existants (bouton en haut à gauche)
- 🗑️ **Supprimer** des services (bouton en haut à droite)
- 🖐️ **Réorganiser** par glisser-déposer
- 🔍 **Rechercher** parmi vos services
- 🎨 **Personnaliser** avec 8 couleurs Dracula
- 💾 **Sauvegarder** facilement (Ctrl+S)
- 📱 **Interface compacte** - plus de services visibles

## 💡 Guide d'utilisation

### ➕ Ajouter un service

#### Avec un emoji
1. Cliquez sur le bouton **+** (en bas à droite)
2. Remplissez le formulaire :
   - **Nom** : YouTube
   - **URL** : https://youtube.com
   - **Icône** : 🎬 (tapez un emoji)
   - **Couleur** : Choisissez une couleur
3. Cliquez sur **Ajouter**
4. ⚠️ **N'oubliez pas de sauvegarder !** (Ctrl+S)

#### Avec une image personnalisée
1. Cliquez sur le bouton **+**
2. Remplissez nom et URL
3. Cliquez sur **📷 Image**
4. Sélectionnez votre image (PNG, JPG, etc.)
5. L'aperçu s'affiche
6. Choisissez une couleur
7. Cliquez sur **Ajouter**
8. 📷 Une notification vous dit : "Placez 'logo.png' dans le dossier images/"
9. **Copiez votre image** dans le dossier `images/` (avec le même nom)
10. ⚠️ **N'oubliez pas de sauvegarder !** (Ctrl+S)

### ✏️ Modifier un service
1. Passez la souris sur une carte
2. Cliquez sur **✏️** (en haut à **gauche**)
3. Modifiez les informations
4. Cliquez sur **Modifier**
5. ⚠️ **N'oubliez pas de sauvegarder !** (Ctrl+S)

### 🗑️ Supprimer un service
1. Passez la souris sur une carte
2. Cliquez sur **×** (en haut à **droite**)
3. Confirmez la suppression
4. ⚠️ **N'oubliez pas de sauvegarder !** (Ctrl+S)

### 🖐️ Réorganiser les services
1. **Cliquez et maintenez** sur une carte
2. **Glissez** la carte vers sa nouvelle position
3. Vous verrez :
   - La carte devient semi-transparente
   - Une bordure verte apparaît sur la zone de dépôt
   - Le curseur change en 🖐️ (main)
4. **Relâchez** pour déposer la carte
5. ✅ Le service est déplacé !
6. ⚠️ **N'oubliez pas de sauvegarder !** (Ctrl+S)

**Astuce :** Vous pouvez réorganiser vos services par ordre de fréquence d'utilisation, par catégorie, ou comme vous voulez !

### 🔍 Rechercher un service
- Tapez dans la barre de recherche en haut
- Les services sont filtrés en temps réel
- Fonctionne sur le nom et l'URL

## 💾 Sauvegarder vos modifications

**⚠️ Important :** Les modifications sont d'abord sauvegardées dans votre navigateur (localStorage). Pour les rendre **permanentes** et pouvoir les utiliser sur d'autres ordinateurs, vous devez exporter le fichier.

### Méthode 1 : Bouton Sauvegarder 💾
1. Cliquez sur **💾 Sauvegarder** en haut à droite
2. Le fichier `services.json` se télécharge dans vos Téléchargements
3. **Remplacez** l'ancien `services.json` dans votre dossier homepage

### Méthode 2 : Raccourci clavier ⌨️
1. Appuyez sur **Ctrl+S** (ou **Cmd+S** sur Mac)
2. Le fichier `services.json` se télécharge
3. **Remplacez** l'ancien fichier à la racine

### 📥 Charger des services sauvegardés
1. Cliquez sur **📥 Charger** (ou **Ctrl+O** / **Cmd+O**)
2. Sélectionnez votre fichier `services.json`
3. Vos services sont chargés instantanément !

## 🔄 Synchroniser entre plusieurs ordinateurs

### Option 1 : Cloud (Dropbox, Google Drive, OneDrive) ☁️
**Recommandé pour une synchronisation automatique**

```
1. Placez le dossier mon-homepage/ dans votre cloud
2. Sur chaque ordinateur, ouvrez homepage.html depuis le cloud
3. Après modifications, sauvegardez (Ctrl+S)
4. Remplacez services.json dans le dossier cloud
5. Le cloud synchronise automatiquement vers tous vos appareils
```

**Avantage :** Les images sont aussi synchronisées !

### Option 2 : Clé USB 💾
**Idéal pour emporter partout**

```
1. Copiez le dossier complet sur votre clé USB
2. Sur n'importe quel PC, ouvrez homepage.html depuis la clé
3. Travaillez normalement
4. Sauvegardez (Ctrl+S)
5. Remplacez services.json sur la clé
```

### Option 3 : Export/Import manuel 📤📥
**Simple pour synchronisation occasionnelle**

```
Sur l'ordinateur 1 :
1. Sauvegardez (Ctrl+S)
2. Envoyez services.json par email/chat

Sur l'ordinateur 2 :
1. Téléchargez services.json
2. Chargez-le (Ctrl+O)
```

**⚠️ Note :** Avec cette méthode, pensez aussi à copier le dossier `images/` si vous avez des images personnalisées !

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

**Champs :**
- `name` : Nom du service (affiché sur la carte)
- `url` : URL complète avec https://
- `icon` : Emoji (🎬) OU chemin vers image (images/logo.png)
- `iconType` : "emoji" ou "image"
- `color` : Code couleur hexadécimal

**💡 Astuce :** L'ordre dans le fichier JSON correspond à l'ordre d'affichage des cartes !

## 🎨 Couleurs Dracula disponibles

| Nom | Code | Aperçu |
|-----|------|--------|
| Gris (Comment) | `#6272A4` | 🟦 |
| Rouge (Red) | `#FF5555` | 🟥 |
| Vert (Green) | `#50FA7B` | 🟩 |
| Cyan | `#8BE9FD` | 🔵 |
| Violet (Purple) | `#BD93F9` | 🟣 |
| Rose (Pink) | `#FF79C6` | 🩷 |
| Jaune (Yellow) | `#F1FA8C` | 🟨 |
| Orange | `#FFB86C` | 🟧 |

## ⚙️ Fonctionnement technique

### Chargement des services (ordre de priorité)
1. **services.json** à la racine (si présent)
2. **localStorage** du navigateur (sauvegarde automatique)
3. **Services par défaut** (6 services de démonstration)

### Système de sauvegarde
- **Automatique** : Chaque modification → localStorage du navigateur
- **Manuelle** : Vous exportez → services.json (Ctrl+S)

**Pourquoi ce système ?**
- ✅ Vos modifications ne sont jamais perdues (localStorage)
- ✅ Vous contrôlez quand sauvegarder le fichier
- ✅ Pas de téléchargements intempestifs
- ✅ Simple et transparent

## 🆘 Dépannage

### ❌ Les services disparaissent après un refresh
**Cause :** Pas de `services.json` à la racine  
**Solution :** 
```
1. Sauvegardez avec Ctrl+S
2. Placez services.json dans le même dossier que homepage.html
3. Rechargez la page
```

### 🖼️ Une image ne s'affiche pas
**Causes possibles :**
- L'image n'est pas dans le dossier `images/`
- Le nom ne correspond pas exactement (sensible à la casse)
- Le chemin dans services.json est incorrect

**Solution :**
```
1. Vérifiez que l'image est dans images/
2. Ouvrez services.json
3. Cherchez "icon": "images/votre-image.png"
4. Vérifiez que le nom est identique (majuscules/minuscules)
```

### 💾 J'ai perdu mes services !
**Si vous avez sauvegardé avant :**
```
1. Retrouvez votre fichier services.json
2. Ctrl+O pour le charger
3. Tout est restauré !
```

**Si vous n'avez pas sauvegardé :**
```
1. Ouvrez la console (F12)
2. Allez dans Application → Local Storage
3. Cherchez 'homepage_services'
4. Copiez le contenu
5. Ou supprimez-le pour restaurer les services par défaut
```

### 🔄 Restaurer les services par défaut
```javascript
// Méthode 1 : Via la console (F12)
localStorage.removeItem('homepage_services');
// Rechargez la page (F5)

// Méthode 2 : Supprimez services.json et rechargez
```

### 🖐️ Le glisser-déposer ne fonctionne pas
**Vérifications :**
- Cliquez bien et maintenez sur la carte (pas sur les boutons ✏️ ou ×)
- Assurez-vous que le navigateur est à jour
- Testez avec la souris si vous utilisez un trackpad

### 🌐 Définir comme page d'accueil du navigateur

#### Chrome / Edge
```
1. Paramètres → Au démarrage
2. Ouvrir une page spécifique ou un ensemble de pages
3. Ajouter une page
4. Entrez : file:///C:/chemin/vers/mon-homepage/homepage.html
```

#### Firefox
```
1. Paramètres → Accueil
2. Page d'accueil et nouvelles fenêtres
3. Adresses web personnalisées
4. Entrez : file:///C:/chemin/vers/mon-homepage/homepage.html
```

#### Safari (Mac)
```
1. Préférences → Général
2. La page d'accueil
3. Entrez : file:///Users/votre-nom/mon-homepage/homepage.html
```

## ⌨️ Raccourcis clavier

| Raccourci | Action |
|-----------|--------|
| **Ctrl+S** (Cmd+S) | Sauvegarder (télécharge services.json) |
| **Ctrl+O** (Cmd+O) | Charger un fichier services.json |
| **F12** | Ouvrir la console développeur |
| **F5** | Recharger la page |

## ✨ Avantages

✅ **Simple** - Un seul fichier HTML, aucune installation  
✅ **Portable** - Fonctionne sur Windows, Mac, Linux  
✅ **Hors ligne** - Pas besoin d'internet pour l'utiliser  
✅ **Léger** - Aucune dépendance, aucun framework  
✅ **Personnalisable** - 8 couleurs et emojis/images  
✅ **Images** - Nom original conservé (pas de renommage)  
✅ **Rapide** - Cartes compactes, interface réactive  
✅ **Réorganisable** - Glisser-déposer intuitif  
✅ **Sauvegarde flexible** - localStorage + export manuel  
✅ **Multi-navigateurs** - Partagez via services.json  

## 📝 Notes importantes

- ⚠️ **Pensez à sauvegarder** après vos modifications (Ctrl+S)
- 💡 Les notifications vous rappellent de sauvegarder
- ✏️ Le bouton **modifier** est à **gauche** de la carte
- × Le bouton **supprimer** est à **droite** de la carte
- 🖐️ Cliquez et glissez sur la carte pour la déplacer
- 📷 Les images gardent leur **nom original**
- 💾 L'ordre des services est conservé dans services.json

## 🎯 Cas d'usage

### 👤 Usage personnel
- Page d'accueil personnalisée du navigateur
- Accès rapide à vos outils quotidiens
- Organisation par catégories (travail, loisirs, etc.)

### 👥 Équipe / Famille
- Partagez services.json via cloud
- Tout le monde a les mêmes raccourcis
- Chacun peut personnaliser son ordre

### 🏢 Professionnel
- Dashboard d'outils internes
- Liens vers documentation
- Environnements de dev (staging, prod, etc.)

## 🔐 Confidentialité et Sécurité

- ✅ **100% local** - Aucune donnée envoyée sur internet
- ✅ **Pas de tracking** - Aucune analytics
- ✅ **Open source** - Tout le code est visible dans homepage.html
- ✅ **Vos données** - Restent sur votre ordinateur

## 📦 Que contient le téléchargement ?

```
✅ homepage.html (un seul fichier de ~30 KB)
✅ services.json (votre base de données)
✅ README.md (ce guide)
```

**Dossier à créer vous-même :**
```
📁 images/ (pour vos images personnalisées)
```

Bonne navigation ! 🚀✨

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

### Réorganiser les services
1. **Cliquez et maintenez** sur une carte
2. **Glissez** la carte à l'emplacement souhaité
3. **Relâchez** pour déposer
4. **N'oubliez pas de sauvegarder !** (Ctrl+S)

Le curseur change en 🖐️ pour indiquer que vous pouvez déplacer la carte !

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
✅ **Réorganisable** - Glisser-déposer les cartes

## 📝 Notes importantes

- **Pensez à sauvegarder** après chaque modification (Ctrl+S)
- Les notifications vous rappellent de sauvegarder
- Le bouton **✏️** est à **gauche** de la carte
- Le bouton **×** est à **droite** de la carte
- Les images gardent leur nom original

Bonne navigation ! 🚀
