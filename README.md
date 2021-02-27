# Music-bot
Un code complet à télécharger pour un robot musical. Utilisation d'un module (discord-player) 🎧

Vous cherchez un code pour un robot musical? Ce code entièrement open source est fait pour votre projet !

### ⚡ Installation

Eh bien, commençons par télécharger le code.
Allez dans le dossier `config` puis le fichier `config.json`.
Pour que le bot puisse démarrer, veuillez compléter le fichier avec vos informations d'identification comme suit:

```js
{
    "game": "GAME",
    "prefix": "PREFIX",
    "token_bot": "TOKEN"
}
```

Rappel :

- `game`, le statut du bot.
- `prefix`, le préfixe qui sera défini pour utiliser le bot.
- `token_bot`, le token du bot disponible sur le [Discord Developers](https://discordapp.com/developers/applications) section.

Pour personnaliser les emojis, allez dans le fichier `emojis.json`.
Les emojis sont déjà définis par défaut mais vous pouvez les modifier si vous le souhaitez.

```js
{
    "music": ":musical_note:",
    "queue": ":bar_chart:",
    "error": ":x:",
    "success": ":white_check_mark:"
}
```

Dans la console, tapez «npm install» pour installer toutes les dépendances.

Pour démarrer le bot:

```
#Avec Node
node index.js

#Avec pm2
pm2 start index.js --name "MusicBot"
```

Tout ce que vous avez à faire est d'allumer votre bot!

### 🎵 Commandes musicales

```
play <name>, jouer de la musique dans un canal vocal.
pause, mettre en pause la musique actuelle.
resume, remet la musique actuelle en marche.
queue, voir les chansons suivantes.
clear-queue, supprimer la musique suivante.
shuffle, pour mélanger la file d'attente.
nowplaying, voir la musique en cours.
loop, pour activer ou désactiver la fonction de répétition.
volume <1 - 100>, changer le volume.
skip, passer à la musique suivante.
stop, arrêtez toute musique.
filter <filter>, ajouter / supprimer un filtre.
w-filters, voir les filtres.
```

### 💡 Commandes générales

```
ping, voir la latence du bot.
help, voir la liste des commandes disponibles.
debug, voir le nombre de connexions vocales.
```vv

