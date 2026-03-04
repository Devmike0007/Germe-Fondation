# Germe Fondation — Site statique institutionnel

Site web officiel prêt pour publication. Version responsive et accessible (WCAG AA).

## 📱 Améliorations implémentées

### Responsive Design
- ✅ Mobile-first avec breakpoints à 768px et 480px
- ✅ Typographie fluide avec `clamp()` (adapté à chaque écran)
- ✅ Espaces tactiles optimisés (min 44×44px)
- ✅ Grilles CSS flexibles et adaptatives

### Accessibilité (A11y)
- ✅ Métadonnées complètes (description, theme-color)
- ✅ Aria-labels sur les éléments de navigation
- ✅ `aria-current="page"` pour l'onglet actif
- ✅ Contraste des couleurs optimisé (WCAG AA)
- ✅ Focus states visibles pour le clavier

### Design & UX
- ✅ Thème vert nature cohérent (#2b8a3e)
- ✅ Navigation sticky avec sticky positioning
- ✅ Animations fluides (transitions 0.2s)
- ✅ Liens interactifs email/WhatsApp/Instagram
- ✅ Meilleure hiérarchie visuelle

## 🚀 Démarrage rapide

Ouvrir la page d'accueil :

\`\`\`powershell
# Windows PowerShell
Start-Process index.html
\`\`\`

Ou ouvrir directement `index.html` depuis l'explorateur.

## 📋 Avant publication

1. **Remplacez les placeholders contact** dans `contact.html` :
   - `[ton-email]` → votre email réel
   - `[ton-numero]` → votre numéro WhatsApp (format : +33612345678)

2. **Vérifiez le logo** : `logo.jpeg` est en place à la racine

3. **Testez sur mobile** : Ouvrir dans navigateur, appuyer sur F12 → mobile preview

## 📁 Structure du projet

\`\`\`
gerem/
  ├── index.html          # Accueil
  ├── about.html          # À propos
  ├── mission.html        # Notre mission
  ├── values.html         # Valeurs
  ├── partenariats.html   # Partenariats
  ├── contact.html        # Contact
  ├── logo.jpeg           # Logo de la fondation
  ├── assets/css/style.css # Stylesheet unique
  └── README.md
\`\`\`

## 🌐 Pages disponibles

| Page | URL | Description |
|------|-----|-------------|
| Accueil | `index.html` | Héro + engagement + vision |
| À propos | `about.html` | Qui sommes-nous + vision |
| Mission | `mission.html` | Mission + piliers d'action |
| Valeurs | `values.html` | 5 valeurs fondamentales |
| Partenariats | `partenariats.html` | Collaboration & objectifs |
| Contact | `contact.html` | Formulaire & liens sociaux |

## 🔧 Personnalisation

- **Couleurs** : Modifier `:root` dans `style.css`
- **Typographie** : Changer font-family en tête du CSS
- **Contenu** : Éditer les fichiers HTML directement

## ✨ Bonus

- Stylesheet minimal (8kb) → chargement ultra-rapide
- Pas de dépendances externes
- Compatible avec tous les navigateurs modernes
- Prêt pour CDN et compression
# Germe-Fondation
