
sidebar_position : 1
---

# Introduction au didacticiel

Découvrons **Docusaurus en moins de 5 minutes**.

## Commencer

Commencez par **créer un nouveau site**.

Ou **essayez Docusaurus immédiatement** avec **[docusaurus.new](https://docusaurus.new)**.

### Ce dont vous aurez besoin

- [Node.js](https://nodejs.org/en/download/) version 16.14 ou supérieure :
  - Lors de l'installation de Node.js, il est recommandé de cocher toutes les cases liées aux dépendances.

## Générer un nouveau site

Générez un nouveau site Docusaurus en utilisant le **modèle classique**.

Le modèle classique sera automatiquement ajouté à votre projet après avoir exécuté la commande :

```bash
npm init docusaurus@latest mon-site classique
```

Vous pouvez taper cette commande dans l'invite de commande, Powershell, Terminal ou tout autre terminal intégré de votre éditeur de code.

La commande installe également toutes les dépendances nécessaires dont vous avez besoin pour exécuter Docusaurus.

## Démarrez votre site

Exécutez le serveur de développement :

```bash
cd mon-site
démarrage de l'exécution npm
```

La commande `cd` change le répertoire avec lequel vous travaillez. Afin de travailler avec votre site Docusaurus nouvellement créé, vous devrez y naviguer dans le terminal.

La commande `npm run start` crée votre site Web localement et le dessert via un serveur de développement, prêt à être consulté à l'adresse http://localhost:3000/.

Ouvrez `docs/intro.md` (cette page) et modifiez quelques lignes : le site **se recharge automatiquement** et affiche vos modifications.
