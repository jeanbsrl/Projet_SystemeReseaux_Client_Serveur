# Projet Système Réseaux

Le but de ce projet est de réaliser une application client/serveur TCP/IP simplifiée.

Nous allons avoir un serveur qui permet à des clients de partager des fichiers images : un
client pourra récupérer des fichiers images disponibles sur le serveur, ou placer sur le serveur
des fichiers à mettre à disposition des autres clients.

Toutefois, le serveur vérifiera, avant d'accepter un nouveau fichier, que celui-ci est
admissible.

# Compilation/Exécution

Pour utiliser le programme, il faut :

Se placer dans le repertoire du Makefile
Compiler en executant "make"
Pour lancer le client, se déplacer dans le répertoire Client et exécuter bin/Client
Pour lancer le serveur, se déplacer dans le répertoire Server et exécuter bin/Serveur

L'exécutable du Client prend 2 paramètres : le nom de la machine, et le numéro de port
L'exécutable du Serveur prend 1 paramètre : le numéro de port

ATTENTION : avant de lancer les programmes, vérifier qu'un répertoire tmp est présent dans le répertoire Server (sinon le créer)

# Autrices et Auteurs

CABROL Camille

FRANCES Tom

GOURDON Jérémie

BOU SERHAL Jean

L3 MIAGE, 2021-2022