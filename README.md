# TP 1 : Création d'un projet Maven avec Hibernate et H2

Ce projet est une application Java basique développée dans le cadre du cours **Hibernate & JPA**. Il illustre la mise en place d'un projet Maven utilisant Hibernate comme ORM et la base de données relationnelle H2.

---

## 🎯 Objectifs du TP

- **Création du projet Maven** : Structuration de l'application.
- **Configuration des dépendances** : Intégration d'Hibernate et du pilote H2 via `pom.xml`.
- **Configuration ORM/Base de données** : Paramétrage du fichier `hibernate.cfg.xml` (ou `persistence.xml`).
- **Modélisation** : Création d'une entité JPA minimale annotée.
- **Opérations CRUD** : Implémentation des fonctionnalités fondamentales d'insertion et de lecture en base de données.

---

## 🛠️ Prérequis & Technologies

- **Java Development Kit (JDK)** : 11 ou plus récent
- **Build Tool** : Apache Maven
- **ORM Framework** : Hibernate (JPA)
- **Database** : H2 (Base de données en mémoire / fichier local)
- **IDE** : IntelliJ IDEA / Eclipse / VS Code

---

## 📁 Structure du Projet

```text
TP1_HIBER_H2/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── tp/
│   │   │           ├── model/         # Entités JPA (ex: Produit.java / Personne.java)
│   │   │           ├── util/          # Classe utilitaire HibernateSession / JPA
│   │   │           └── Main.java      # Classe principale d'exécution
│   │   └── resources/
│   │       └── hibernate.cfg.xml      # Configuration d'Hibernate et H2
└── pom.xml                            # Gestion des dépendances Maven
```
<img width="1391" height="527" alt="Affich3tp1maven" src="https://github.com/user-attachments/assets/79919927-ed52-4dc9-a54d-8ecf61538796" />
<img width="1291" height="872" alt="Affich2tp1maven" src="https://github.com/user-attachments/assets/3afe5acd-49d4-4bbf-9633-ea3420f4bb3f" />
<img width="1266" height="782" alt="Affi1maventp1" src="https://github.com/user-attachments/assets/296561b5-ab2f-4705-82e9-0453066ab0b6" />
