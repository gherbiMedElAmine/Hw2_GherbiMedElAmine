# GHERBI - Programme de multiplication de matrices avec MPI

## Introduction

Bienvenue dans le programme GHERBI, un programme de multiplication de matrices parallèle utilisant MPI (Message Passing Interface). Ce programme est conçu pour être exécuté sur un cluster ou une machine avec prise en charge de MPI.

## Prérequis

- Un environnement MPI installé sur votre machine ou cluster.
  
dans votre terminal :

sudo apt-get update

sudo apt install build-essential

sudo apt-get install openmpi-bin openmpi-doc libopenmpi-dev

## Compilation

Pour compiler le programme, exécutez la commande suivante dans le répertoire du programme :

make

## Exécution

make run=number 

## Nettoyage

make clean

## Notes

-Assurez-vous que l'environnement MPI est configuré correctement.

-Le programme génère des matrices aléatoires pour les tests, vous pouvez ajuster cela selon vos besoins dans le fichier main.c.

-N'oubliez pas de consulter les commentaires dans le code source pour plus de détails sur l'implémentation.


