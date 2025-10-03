# Journal de bord du projet encadré

## Git : mise en pratique (03/10/2025)

Exercice 2.b - Synchroniser depuis le dépôt

Je viens de créer le fichier *journal.md* dans mon dépôt à l'aide du bouton de création de fichier sur Github (dépôt distant). J'ai ensuite fait un commit pour que cette modification soit enregistrée dans le dépôt git mais pour le moment, le dépôt sur mon ordinateur (dépôt local) n'est pas synchronisé avec cette version. Si je crée un fichier journal.md dans mon dépôt local, je m'expose à des conflits que je devrai résoudre à la main en vérifiant chaque ligne du journal à la prochaine synchronisation. Pour savoir depuis mon dépôt local si j'ai des modifications qui pourraient provoquer des conflits, je peux lancer les commandes suivantes dans l'ordre

```
git fetch
git status
```

Pour appliquer les modifications à mon dépôt local dans tous les cas, j'utilise la commande `git pull`, puis je résous les conflits si besoin.
