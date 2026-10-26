# Embemail
# Embemail 📬

Ma propre messagerie, créée de zéro et sans rien payer.

## C'est quoi ?
Comme Gmail, mais c'est moi qui l'ai faite. Chaque personne a une adresse du type
**nom.4821@ember.nv** : le nombre est un matricule unique, donc deux personnes
peuvent avoir le même nom sans se mélanger.

## Ce que ça fait
- Créer un compte avec un nom et un mot de passe
- Envoyer et recevoir des messages
- Réception, favoris, envoyés, archives, corbeille
- Recherche, répondre, transférer

## Petite précision
L'extension **.nv** n'existe que dans mon système (une vraie extension publique
coûte environ 227 000 $). Ça marche entre comptes Embemail, pas avec Gmail.

## Comment ça marche (pour les curieux)
Écrit en Python, tourne sur une tablette Android avec Termux.
- `ember.py` : serveur mail et comptes
- `web.py` : le site

Pas besoin de comprendre le code pour regarder les captures d'écran ci-dessus.
