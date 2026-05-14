# Lab 10 — Navigation Drawer + Fragments Android

## Présentation

Application Android démontrant l'utilisation d'un menu latéral de navigation (Navigation Drawer) avec gestion dynamique de plusieurs fragments dans une seule activité.

---

## Structure du projet

| Fichier | Rôle |
|---------|------|
| MainActivity.java | Activité principale + gestion du drawer |
| BlankFragment.java | Fragment 1 (fond rose) |
| BlankFragment2.java | Fragment 2 (fond bleu) |
| FragmentList.java | Fragment avec liste d'éléments |
| activity_main.xml | Layout principal avec DrawerLayout |
| fragment_blank.xml | Layout Fragment 1 |
| fragment_blank2.xml | Layout Fragment 2 |
| nav_menu.xml | Menu de navigation |

---

## Fonctionnalités

| Fonctionnalité | Description |
|---|---|
| Navigation Drawer | Menu latéral glissant |
| Fragment 1 | Fond rose avec texte |
| Fragment 2 | Fond bleu avec texte |
| Fragment List | Liste de 10 éléments |
| Toolbar | Barre d'action avec toggle |
| Back Press | Ferme le drawer si ouvert |

---

## Personnalisation HC

- Palette : violet foncé / jaune
- Items liste préfixés `📱`
- Variable drawer : `hcDrawerLayout`

---

## Démonstration



https://github.com/user-attachments/assets/06b86a2e-ecd0-4fd1-8702-4b385a3c3832


---

## Technologies utilisées
- Android Studio
- Java
- DrawerLayout
- NavigationView
- FragmentManager
- MaterialComponents
