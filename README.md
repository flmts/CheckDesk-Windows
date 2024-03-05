
## Présentation : 
Le projet CheckDesk est un projet réalisé dans le cadre d'un mastère en informatique à l'école d'ingénieurs 3IL. Ce projet a pour but de permettre la configuration ainsi que le monitoring de différents parcs informatiques. 
CheckDesk est un projet comprenant 4 parties distinctes mais communicante entre elles, toutes réalisés en dotnet : 

* **CheckDesk-API** : Partie central du projet, elle permet la centralisation des trois autres parties afin quelles communiques entre elle grâce à la BDD.
* **CheckDesk-WEB** : Partie métier du projet, la partie web est l'application de gestion de l'ensemble du projet. Elle permet de configurer TOUT sur l'application. Réalisé avec Blazor server, nous pouvons également visualiser 
* **CheckDesk-Windows** : Application à déployer sur les ordinateurs à monitorer, elle permet la récolte des informations du desktop, elle a été développé avec WPF.
* **CheckDesk-Mobile** : Application mobile développé en dotnet MAUI, permet la visualisation des données récolté sur les ordinateurs, c'est tout.
