# Projet _Divin'App_

## Description synthétique

Auteur : Marie Le Hir & Clara Bédé Candusso

Date de mise à jour du document : 19 septembre 2026

Pitch :

> _Divin'App_ est une application dédiée à la découverte et à l'apprentissage des pratiques de divination. Elle centralise plusieurs outils, informations et guides dans le but d'éviter aux utilisateurs de devoir consulter plusieurs sites. 
> L'application permet notamment de découvrir des jeux de cartes, d'apprendre à réaliser différents tirages, de consulter leurs significations et d'obtenir de l'aide pour interpréter ses propres tirages grâce à la prise de photo.

Adresse : <https://azrael.sha.univ-poitiers.fr/~cbedecan/M2/Divin'app/>

## Principales caractéristiques

### _Minimum viable product_ (MVP)

- Une page d’accueil permettant d’accéder rapidement aux différents outils de divination 
  - Accès aux outils et jeux de cartes, accès aux guides et aux favoris
  - Une section dédiée aux jeux de cartes 
  - Consultation des différents jeux et présentation de ceux ci 
  - Consultation des cartes et de leurs signification
- Une section dédiée aux guides 
  - Explications des différents outils 
  - Présentation des différents types de tirages
- Une fonctionnalité de prise de photo d’un tirage 
  - Prise d’une photo 
  - Identification des cartes
  - Consultation de la signification des cartes présente


### Scénario d’utilisation

1. L’utilisateur **débutant** découvre l’application et consulte les différents outils de divination.
2. Il sélectionne un **jeu de cartes** et découvre les cartes ainsi que leurs significations.
3. Il consulte un **guide** afin d’apprendre comment réaliser un tirage. (lot 1)
4. L’application lui propose un **tirage guidé** et l’accompagne étape par étape.
5. L’utilisateur réalise son tirage et prendre une **photo de son tirage** pour consulter les informations associées aux cartes. (lot 3)

## Description fonctionnelle

![Maquette de Divin'App](maquette_divin_app.svg)

### Lots

#### Lot 1 : Découverte & apprentissage

- Page d’accueil
  - Création de collection outils
- Page jeux de cartes
  - listes des différents jeux recensés
    - Sélection d'un jeu de cartes
  - Page carte
    - présentation et signification
      - carte en plein écran
      - passage d’une carte à une autre avec un menu déroulant
- Page guides
  - guide étape par étape pour les outils
  - différents type de tirage

#### Lot 2 : Personnalisation & autres pratiques

- Page profil
  - avatar, pseudo, description
- Outils de divination / communication
  - Page pendule et baguettes de sourcier
    - présentation et utilisation des outils
    - accès aux guides correspondants (redirection)
- Personnalisation de l'accueil
  - Outils favoris

#### Lot 3 : Enrichissement

- Prise de photo
  - prendre une photo
  - reconnaissance du tirage
    - demande du domaine
    - affichage de la signification des cartes
- Autres outils : dés, runes, numérologie, heures miroires
