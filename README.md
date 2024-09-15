# 🤖 Leak’s Land Bot

Le **bot Leak’s Land** est un outil puissant conçu pour répondre aux besoins variés des utilisateurs de la plateforme.

Pour les **propriétaires de serveurs**, il offre une **surveillance avancée** afin de protéger les données et de **prévenir les fuites** de contenus importants ou exclusifs.

Il peut aussi être utilisé par des **petits groupes d'amis** cherchant à automatiser certaines tâches au sein de leur serveur, simplifiant ainsi la gestion quotidienne.

Enfin, le bot peut être exploité pour **créer des clones de serveurs existants**, facilitant la **réplication de communautés** ou la **revente d'accès à des serveurs** similaires à des prix plus attractifs.

---

## ✨ Fonctions Exclusives
- **Clonage de serveur avec nettoyage automatique** basé sur l'inactivité ou l'accès aux salons, accompagné d'une **filtration avancée des mots bannis** pour les catégories et salons.
- **Détection et reproduction instantanée des pings** grâce à la **synchronisation intelligente des rôles**.
- **Récupération automatique des messages** liés grâce à la détection des liens pointant vers d'autres messages.
- **Correspondance automatique des salons** grâce à la détection des liens pointant vers d'autres salons, avec une vérification rapide de leur existence sur le serveur.
- **Ajout automatique des nouveaux salons détectés**, pour une gestion simplifiée et fluide.
- **Suppression automatique des serveurs supprimés**, si synchronisés, garantissant un environnement toujours à jour.
- **Réglage personnalisé des délais de scrutation** pour chaque salon, permettant une **optimisation des ressources** tout en réduisant l'impact du rate limit.
- Chaque salon **scrapé est une instance autonome**, dotée de son propre **système de surveillance** qui vous **alerte en cas de dysfonctionnement** !

---

## ⚙️ Installation

**1 - Récupération du token et mise en place**

- Ouvrez un navigateur en mode navigation privée.
- Puis suivez ce tutoriel via ce site pour obtenir le token.
- Fermez la fenêtre sans vous déconnecter ; si vous vous déconnectez avant, vous grillez le token.
- Exécutez la commande /token pour l'ajouter. Attention, cette action n'est possible qu'une seule fois. En cas de modification future, consultez le chef.


**2 - Ajout du serveur à scraper**
- Commencez par exécuter la commande /listservor et copiez l'ID du serveur cible.
- Ensuite, exécutez la commande /addservor, là aussi unique. Votre instance ne permet le scraping que d'un seul serveur.


**3 - Ajout des salons**

Vous avez le choix, soit manuellement :
- Exécutez /listroomall.
- Sélectionnez les ID qui vous intéressent.
- Puis exécutez /addroom ou /addcat.
- Attention, cela désactive la fonction clone et lance immédiatement le scraper.

Sinon automatiquement avec une base de filtration :
- Exécutez /listroom pour une vue préfiltrée.
- Si vous souhaitez exclure davantage de salons ou catégories, utilisez les commandes /seebw, /addbw, /delbw.
- Une fois satisfait de la liste, lancez la commande /clone et admirez la magie.
- Après la création des salons, le bot vérifiera les accès aux salons et leur activité pour effectuer un nettoyage.
- Il est donc important à ce niveau de bien prendre les rôles sur le serveur cible pour voir tous les salons.
- Pour finir, le bot se lancera et commencera à scraper.


**4 - Ajout des rôles**
- Pourquoi ? Car le bot analyse les pings sur le serveur distant et les reproduit localement, c'est comme si vous y étiez !
- Exécutez la commande /syncroles.
- Ensuite, exécutez la commande /roles.
- Parfois, le bot affichera un message demandant une synchronisation s'il détecte des rôles inconnus.


**Finito ! Il ne vous reste plus qu'à inviter vos amis, leur attribuer le rôle lmembres ! Rock'N Roll !**

---

## 🛠️ Commandes

```code
/initialise
```
Le bot vous invitera à faire cette commande en arrivant sur le serveur, c’est le début de l’aventure avec la création des rôles et salons techniques.

```code
/Installation
```
La commande affiche l’aide à l’installation, les fonctions exclusives et les informations additionnelles.

```code
/commandes
```
Affiche la liste des commandes qui suivent.

```code
/addtoken
```
Ajout du token du compte scraper (Voir /installation).

```code
/listservor
```
Liste les salons disponibles sur le serveur du compte scraper.

```code
/addservor
```
Ajout de l'id du serveur à scraper, attention possible une unique fois.

```code
/listroom
```
Liste des salons disponibles sur le serveur du compte scraper basée sur la liste ban word.

```code
/listallroom
```
Liste complètes des salons disponibles sur le serveur du compte scraper.

```code
/clone
```
Si vous désirez lancer un clone complet d’un serveur, possible une seule fois après initialisation.

```code
/start
```
Pour forcé manuellement le lancement du scraper.

```code
/stop
```
Pour forcé manuellement l'arrêt du scraper, vous devrez patienter 10 minutes avant de start.

```code
/addroom
```
Si vous désirez ajouter un salon précis manuellement.

```code
/delroom
```
Si vous désirez supprimer un salon précis manuellement.

```code
/addcat
```
Si vous désirez ajouter une catégorie entière de salons manuellement.

```code
/delcat
```
Supprimer une catégorie et tous les salons qu'elle contient.

```code
/seemsg
```
Si vous désirez récupérer un message précis manuellement., s'il est dans les 100 derniers messages du dit salon.

```code
/seeroom
```
Renvoie les 50 derniers messages d’un salon précis.

```code
/ping
```
Avec ou sans pièce jointe, si vous voulez faire parler le compte scraper.

```code
/syncroles
```
Syncronisation des rôles du serveur distant sur ce serveur.

```code
/roles
```
Génération du salon avec les roles.

```code
/delay
```
Délai par défaut entre deux vérifications, 120s par défaut...

```code
/delayroom
```
Modifier le délai par défaut d'un salon.

```code
/seedelayroom
```
Voir le délai d'un salon.

```code
/seebw
```
Voir la liste des mots exclus.

```code
/addbw
```
Ajouter un mot à la liste des mots exclus.

```code
/delbw
```
Supprime un mot de la liste des mots exclus.

---

## 🚀 Comment obtenir le bot ?

➡️ https://t.me/+idYEvIRMSQRhOWFk
