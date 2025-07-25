# Node.js Application avec Déploiement AWS via Terraform et Docker

## Description

Ce projet est une application Node.js simple déployée sur une instance EC2 d'AWS. L'infrastructure est provisionnée avec Terraform, et le déploiement est automatisé via GitHub Actions. L'application est empaquetée dans un conteneur Docker et exécutée sur EC2.

## Fonctionnalités

- **Application Node.js** : Serveur Express simple.
- **Infrastructure AWS** : Provisionnement d'EC2, IAM, et groupes de sécurité avec Terraform.
- **CI/CD** : Automatisation du déploiement avec GitHub Actions.
- **Docker** : Conteneurisation de l'application.

## Prérequis

- **Node.js** et **npm** installés localement.
- Compte AWS avec les permissions nécessaires.
- Terraform installé.
- Clé SSH publique et privée pour l'accès à EC2.
- Secrets configurés dans GitHub Actions :
    - `AWS_ACCESS_KEY_ID`
    - `AWS_SECRET_ACCESS_KEY`
    - `AWS_TF_STATE_BUCKET_NAME`
    - `AWS_SSH_KEY_PRIVATE`
    - `AWS_SSH_KEY_PUBLIC`

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/ines312692/Complete_CI-CD_with_Terraform_and_AWS.git
   cd  Complete_CI-CD_with_Terraform_and_AWS
