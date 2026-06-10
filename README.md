LAB 8 - Threads, AsyncTask et Handler
Petite application Android native en Java qui montre comment executer un traitement long sans bloquer l'interface utilisateur.

L'application contient un bouton pour lancer un Thread avec Runnable, un bouton pour lancer une AsyncTask, un bouton Toast immediat pour verifier que l'UI reste reactive, et une barre de progression mise a jour depuis le thread principal avec Handler.post(...), View.post(...) et les callbacks d'AsyncTask.

Lancer
Ouvrir ce dossier dans Android Studio, puis lancer l'application.

Depuis PowerShell :

.\gradlew.bat assembleDebug

