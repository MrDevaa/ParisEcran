# Paris Ecran 🎭🎥

## 📖 Description
Paris Ecran est un site de réservation inspiré des fonctionnalités de plateformes comme CGR, développé en PHP avec une base de données MySQL. Ce projet vise à simplifier la gestion des spectacles, des réservations et des interactions utilisateur, tout en offrant des fonctionnalités avancées pour l'administration et les statistiques.

## Fonctionnalités ✅

| N°  | Fonctionnalité demandée                                                                           | Réalisation |
|-----|--------------------------------------------------------------------------------------------------|-------------|
| 1   | Créer un utilisateur (s'inscrire)                                                               | ✔️          |
| 2   | Associer un artiste à un spectacle                                                              | ✔️          |
| 3   | Créer un spectacle                                                                              | ✔️          |
| 4   | Effectuer une réservation pour un spectacle donné                                               | ✔️          |
| 5   | Modifier le mot de passe d'un utilisateur                                                       | ✔️          |
| 6   | Ajouter une place à une réservation si le paiement n'a pas encore été effectué                  | ✔️          |
| 7   | Augmenter le prix des spectacles d'un jour donné de 10%                                         | ✔️          |
| 8   | Afficher la liste des lieux de spectacle                                                        | ✔️          |
| 9   | Afficher les spectacles par arrondissement                                                      | ✔️          |
| 10  | Afficher les salles par arrondissement                                                          | ✔️          |
| 11  | Afficher les spectacles en cours pour une catégorie donnée                                      | ✔️          |
| 12  | Afficher le nombre de spectacles par catégorie                                                  | ✔️          |
| 13  | Afficher le nombre moyen de places réservées par les inscrits                                   | ✔️          |
| 14  | Afficher la distribution statistique des réservations de places                                 | ✔️          |
| 15  | Afficher le taux de remplissage des salles par spectacle                                        | ✔️          |
| 16  | Lister les artistes ayant participé avec un artiste donné à au moins deux spectacles différents  | ✔️          |
| 17  | Lister les metteurs en scène travaillant dans un théâtre donné                                  | ✔️          |
| 18  | Afficher les trois catégories de spectacles les plus réservées                                  | ✔️          |
| 19  | Recommander des spectacles à un utilisateur                                                     | ✔️          |
| 20  | Lister les théâtres triés par note moyenne des spectacles                                       | ✔️          |
| 21  | Trouver les artistes ayant tenu au moins trois fonctions différentes                            | ✔️          |
| 22  | Lister les recettes par spectacle                                                              | ✔️          |
| 23  | Identifier les spectacles complets parmi ceux ne se jouant plus                                | ✔️          |
| 24  | Trouver les artistes préférés des spectateurs                                                  | ✔️          |
| 25  | Supprimer une réservation                                                                      | ✔️          |
| 26  | Annuler un spectacle                                                                           | ✔️          |
| 27  | Créer un spectacle avec des dates et une salle associée                                        | ❌          |
| 28  | Supprimer un compte utilisateur                                                               | ✔️          |
| 29  | Ajouter une réaction à un commentaire                                                         | ✔️          |
| 30  | Trouver les trois théâtres les plus proches d'un point géographique                            | ✔️          |
| 31  | Trouver les commentaires avec plus de 5 "likes"                                              | ✔️          |
| 32  | Rechercher des spectacles correspondant à des mots dans le synopsis                           | ✔️          |

## Technologies utilisées 💻

### Technologies avec badges

- ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
- ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
- ![phpMyAdmin](https://img.shields.io/badge/phpMyAdmin-6C78AF?style=for-the-badge&logo=phpmyadmin&logoColor=white)
- ![Composer](https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white)
- ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
- ![Javascript](https://img.shields.io/badge/logo-javascript-blue?logo=javascript)

## Instructions pour installer le projet 🛠️

1. Clonez le dépôt :
    ```bash
    git clone https://github.com/Woodiss/ParisEcran.git
    ```

2. Configurez la base de données MySQL :
    - Importez le fichier `.sql` fourni via phpMyAdmin pour créer la base de données et ses tables nécessaires.

3. Configurez le fichier `DBAL/Connector.php` avec vos informations de connexion à la base de données.

4. Installez les dépendances avec Composer :
    ```bash
    composer install
    ```

5. Configurez le fichier `.env` avec vos informations de connexion à la base de données.

6. Lancez le serveur PHP :
    ```bash
    php -S localhost:8000 -t public
    ```

7. Accédez à l'application via votre navigateur :
    [http://localhost/parisecran](http://localhost/parisecran)

## Collaborateurs 👨‍💻👩‍💻

| Nom                | Prénom             | Poste                 |
|--------------------|--------------------|-----------------------|
| À compléter        | À compléter        | À compléter           |

---

## 💬 Remerciements

- Lorem ipsum


## 📜 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](./LICENSE) pour plus de détails.


Merci d'utiliser **Paris Ecran** ! Pour toute suggestion ou problème, n'hésitez pas à ouvrir une issue sur GitHub. ✨

 © 2024  - Paris Ecran - Web2 . All rights reserved.

