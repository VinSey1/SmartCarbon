# SmartCarbon
## Introduction
Projet effectué dans le cadre du cours "Méthodes Agiles" du M1 IM/MIAGE de l'Université de Haute-Alsace.
Le but étant de développer en 2 semaines les 3 différentes étapes d'un projet agile qui sont :
 - La conception
 - Le développement
 - Les tests

Le projet est une application visant à calculer l'emprunte carbone des utilisateurs avec un système de questions/réponses, et de pouvoir comparer les résultats entre l'ensemble des utilisateurs.
## Installation
Ce projet a été fait avec Cordova, qui s'installe comme suit (procédure pour Windows 10) :
- Installer Gradle via ce lien (v7.3.3) : https://gradle.org/releases/
- Ajouter la variable d'environnement GRADLE_HOME sur le dossier d'installation
- Installer jdk1.8.0_202 via ce lien : https://www.oracle.com/fr/java/technologies/javase/javase8-archive-downloads.html
- Ajouter la variable d'environnement JAVA_HOME sur le dossier d'installation
- Ajouter la variable d'environnement _JAVA_OPTIONS avec comme valeur -Xmx512M
- Installer Android Studio (pas nécessaire si vous possédez la dernière version)
- Créer un nouveau projet (à supprimer plus tard)
- Aller dans Tools/SDK Manager
- Changer la location pour un dossier android-sdk
- Cocher :
  - Dans SDK Platforms : Android API 32, Android 12, Android 11, Android 8
  - Dans SDK Tools (cocher "Show packages details") : Android SDK Build-Tools 31, 30.0.3 et 30.0.2; Android Emulator; Android SDK Platform-Tools
- Installer NodeJS
- Ajouter la variable d'environnement ANDROID_SDK_ROOT sur le dossier android-sdk
- Ajouter au path :
  - %JAVA_HOME%\bin
  - %ANDROID_SDK_ROOT%\
  - %ANDROID_HOME%\emulator
  - %ANDROID_HOME%\platform-tools
  - %ANDROID_HOME%\tools\bin
  - %GRADLE_HOME%\bin
  - "Votre dossier d'installation NodeJS"
## ...
