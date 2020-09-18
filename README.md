# script-google-calendar-to-float

## Installation

* Télécharger et dézipper googleCalendarToFloat.zip
* Se rendre sur https://developers.google.com/calendar/quickstart/python
* Cliquer sur "Enable the Google Calendar API" (paragraphe "Step 1")
* Laisser le nom par défaut du projet et cliquer sur "next"
* Laisser la valeur par défaut (Desktop app) et cliquer sur "create"
* Cliquer sur "download client configuration"
* Mettre le fichier téléchargé (credentials.json) dans le même dossier que l'éxecutable dézippé précedemment
* Double-cliquer sur l'éxecutable pour lancer le programme

## Fonctionnement de l'éxecutable

### Premier usage

* Lors de la première utilisation, l'éxcutable ouvrira une fenêtre de navigateur pour accéder à votre compte Google
* Une fois connecté, un nouveau fichier (token.pickle) apparaitra dans le même dossier que votre éxecutable

### Import des évènements Google Calendar dans Float

* Le programme vous demandera d'abord votre adresse mail afin de vous identifier sur Float
* Il vous sera ensuite demandé de rentrer la date de début puis de fin de la période sur laquelle les évènements Calendar seront transférés dans Float
* Si un évènement ne peux pas être relié automatiquement au bon projet dans Float, il apparaitra alors sous le projet "FLOAT - Non attribué"
