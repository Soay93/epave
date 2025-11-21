# Epave – Site vitrine de récupération d’épaves (Rhône & Marseille)

Ce dépôt contient un **prototype de site vitrine** pour un service de récupération d’épaves gratuit, intervenant sur le Rhône et la région de Marseille.  
Le projet a été réalisé pour une personne âgée souhaitant promouvoir son activité, mais il n’a pas pu être mené jusqu’au bout à cause de difficultés de communication (changement de pays, absence de téléphone).

Malgré son statut de prototype, ce projet illustre la mise en place d’un site vitrine moderne, responsive et orienté conversion (appel, email, informations pratiques).

---

## Objectifs du projet

- Présenter clairement le **service d’enlèvement d’épaves gratuit**.  
- Mettre en avant les **zones d’intervention** (Rhône & Marseille).  
- Détailler les **modalités et documents nécessaires** pour la prise en charge d’un véhicule.  
- Faciliter la prise de contact via :
  - un bouton d’appel téléphonique,
  - un lien d’envoi d’e-mail,
  - des informations claires et rassurantes (processus, témoignages, FAQ).

---

## Fonctionnalités principales

- **Page d’accueil “Accueil.html”**
  - Section hero avec un message clair et un bouton d’appel à l’action (“Demander un enlèvement”).
  - Présentation des **zones d’intervention** avec un slider visuel (Rhône, Marseille).
  - Bloc **Services** : enlèvement de véhicules, véhicules rouillés/brûlés/immergés, recyclage écologique, etc.
  - Section **Processus** : étapes de la prise en charge pour rassurer l’utilisateur.
  - Section **Modalités** avec lien vers une page dédiée expliquant les documents à fournir.
  - **Témoignages** clients avec carrousel défilant automatiquement.
  - **FAQ** avec questions fréquentes sur l’enlèvement d’épaves.
  - Section **Contact** avec boutons rapides pour appeler ou envoyer un e-mail.

- **Page “modalite.html”**
  - Rappel des **documents nécessaires** (carte d’identité, certificat de non-gage, carte grise, etc.).
  - Informations pratiques sur le jour de l’enlèvement.

- **Navigation**
  - Menu de navigation avec **version mobile** (menu hamburger).
  - Défilement fluide vers les différentes sections de la page.

- **Animations**
  - Animations d’apparition des titres, cartes de services, etc. via `animate.css`.
  - Carrousel de témoignages en JavaScript (duplication des cartes pour un défilement continu).

---

## Technologies utilisées

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript
- **Librairies externes**
  - [Animate.css](https://animate.style/) pour les animations.
  - [Font Awesome](https://fontawesome.com/) pour les icônes (téléphone, réseaux sociaux, services).

Il n’y a **pas de backend** : le site est un pur site statique, pensé pour être hébergé facilement.

---

## Structure du projet

```text
epave/
├── Accueil.html        # Page d’accueil principale
├── Accueil.css         # Styles associés à l’accueil
├── Accueil.js          # Logique frontend (menu, slider, témoignages, etc.)
├── accueil2.html       # Variante/test de mise en page de l’accueil
├── accueil2.css        # Styles associés à la variante d’accueil
├── modalite.html       # Page des modalités (documents nécessaires)
├── modalite2.html      # Variante/test de la page de modalités
├── modalite.css        # Styles associés aux modalités
├── marseille.jpg       # Visuel utilisé pour la zone de Marseille
├── rhone.jpg           # Visuel utilisé pour la zone du Rhône
├── image.png           # Image générique (illustration)
└── 1.png               # Ressource supplémentaire (ex : logo/visuel)

