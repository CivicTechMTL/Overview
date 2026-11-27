# GitHub 101

[English](GITHUB-101.md) · **Français**

Un guide en langage simple pour les personnes qui n'ont jamais utilisé GitHub.
Pas besoin de coder ni d'installer quoi que ce soit : tout ce qui suit
fonctionne dans votre navigateur Web.

> L'interface de GitHub est en anglais. Les noms des boutons sont donc donnés
> en anglais, avec leur traduction entre parenthèses.

## Qu'est-ce que GitHub?

GitHub est un site Web où les gens conservent des projets partagés et y
travaillent ensemble. Imaginez un Google Drive partagé avec un historique
intégré : chaque modification est enregistrée, on peut voir qui a changé quoi
et pourquoi, et rien ne se perd.

Civic Tech Montréal utilise GitHub pour garder ses projets, sa documentation
et ses notes d'organisation en mode ouvert, afin que tout le monde puisse les
lire et proposer des améliorations.

## Termes clés

| Terme | Ce que ça veut dire |
|---|---|
| **Dépôt (*repository*, *repo*)** | Un dossier de projet. Il contient des fichiers et tout leur historique. Cette page se trouve dans le dépôt *Overview*. |
| **README** | La page d'accueil d'un dépôt. Elle s'affiche automatiquement quand on ouvre le dépôt. |
| **Markdown (.md)** | La mise en forme simple utilisée dans la plupart des fichiers ici. `**gras**`, `# Titre`, `- élément de liste`. |
| **Commit** | Une modification enregistrée, avec un court message qui explique ce qui a changé. |
| **Branche (*branch*)** | Une copie séparée des fichiers où l'on peut faire des modifications sans toucher à la version principale. La version principale s'appelle `main`. |
| **Fork** | Votre propre copie du dépôt de quelqu'un d'autre, utilisée quand vous n'avez pas la permission de le modifier directement. GitHub en crée une automatiquement pour vous. |
| **Demande de fusion (*pull request*, PR)** | Une demande pour ajouter vos modifications à la version principale. D'autres personnes peuvent la réviser, la commenter et l'approuver avant qu'elle soit fusionnée. |
| **Fusion (*merge*)** | L'intégration des modifications approuvées dans `main`. |
| **Ticket (*issue*)** | Une tâche, une question, une idée ou un rapport de bogue. Tout le monde peut en ouvrir un pour lancer une discussion. |
| **Révision (*review*)** | Quand une personne lit une demande de fusion et l'approuve ou suggère des modifications. |
| **Organisation** | Un compte de groupe qui possède plusieurs dépôts. Le nôtre est [CivicTechMTL](https://github.com/CivicTechMTL). |

## Votre première contribution, étape par étape

### Étape 1 : Créez un compte
Allez sur [github.com/signup](https://github.com/signup) et créez un compte
gratuit.

### Étape 2 : Ouvrez un ticket (pour demander, suggérer ou signaler)
1. Allez dans le dépôt qui vous intéresse (par exemple, celui-ci).
2. Cliquez sur l'onglet **Issues** (tickets), puis sur **New issue** (nouveau
   ticket).
3. Donnez-lui un titre clair et décrivez votre idée ou votre question.
4. Cliquez sur **Submit new issue** (soumettre le ticket). Une personne de
   l'équipe vous répondra.

### Étape 3 : Proposez une modification à un fichier
1. Ouvrez le fichier que vous voulez modifier.
2. Cliquez sur l'icône ✏️ (crayon) en haut à droite du fichier.
   Si vous n'avez pas les droits de modification, GitHub créera un fork pour
   vous : c'est normal.
3. Faites vos modifications. Utilisez l'onglet **Preview** (aperçu) pour voir
   le résultat.
4. Cliquez sur **Commit changes…** (enregistrer les modifications) et écrivez
   un court message (par ex. « Corriger le lien Slack brisé »).
5. Choisissez **Create a new branch** (créer une nouvelle branche), ou
   **Propose changes** (proposer les modifications) si vous êtes sur un fork.

### Étape 4 : Ouvrez une demande de fusion
1. GitHub affichera un bouton **Create pull request** (créer une demande de
   fusion) : cliquez dessus.
2. Expliquez ce que vous avez changé et pourquoi. Si c'est lié à un ticket,
   écrivez `Closes #12` (avec le numéro du ticket) pour les relier.
3. Cliquez sur **Create pull request**.

### Étape 5 : Répondez aux commentaires
Une personne qui révise votre demande peut la commenter ou demander des
modifications. Vous pouvez continuer à modifier la même branche : votre
demande de fusion se met à jour automatiquement. Une fois approuvée, elle est
fusionnée. 🎉

## Pour aller plus loin

- [Hello World](https://docs.github.com/fr/get-started/using-github/hello-world) : le tutoriel officiel de GitHub pour débuter
- [Introduction to GitHub](https://github.com/skills/introduction-to-github) : un cours interactif gratuit (moins d'une heure, en anglais)
- [Glossaire GitHub](https://docs.github.com/fr/get-started/learning-about-github/github-glossary) : la liste complète des termes
- [Glossaire de la tech civique](https://github.com/CivicTechMTL/Organizing/blob/main/Resources/Glossaire%20de%20la%20tech%20civique.md) : les termes de tech civique que nous utilisons

Vous êtes bloqué·e? Demandez sur [Slack](https://join.slack.com/t/civictechmontreal/shared_invite/zt-3sx2os89v-6rIwr2sNmhl6r2FZvyPoCQ)
ou lors d'une rencontre. Tout le monde a commencé ici.
