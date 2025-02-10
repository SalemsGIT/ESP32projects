Cahier des Charges : Serveur Web sur ESP32

1. Objectif

Créer un serveur web embarqué sur l'ESP32 permettant de contrôler les GPIOs depuis une interface web accessible via un navigateur.

2. Fonctionnalités

a. Connexion Wi-Fi

L'ESP32 doit se connecter à un réseau Wi-Fi défini.

Afficher dans la console l'état de la connexion et l'adresse IP obtenue.

b. Serveur Web

Héberger une page web accessible via l'adresse IP de l'ESP32.

Afficher une interface permettant de contrôler les GPIOs.

Actualiser l’état des GPIOs en temps réel.

c. Contrôle des GPIOs

Permettre d’allumer et d’éteindre une LED (ou un autre composant) via des boutons sur l’interface web.

Mettre à jour l’état des GPIOs en fonction des interactions de l’utilisateur.

3. Contraintes Techniques

Utilisation du framework ESP-IDF.

Développement en langage C.

Utilisation du Wi-Fi station mode pour connecter l’ESP32 au réseau.

Interface web simple en HTML/CSS avec des requêtes HTTP pour interagir avec l’ESP32.

4. Matériel Nécessaire

ESP32-WROOM-32

LED (optionnel, peut utiliser la LED interne du GPIO 2)

Câbles de connexion (si besoin)

5. Améliorations Futures

Ajouter une API REST pour interagir avec le serveur via JSON.

Afficher un journal des actions effectuées.

Ajouter un mode Access Point (AP) pour configurer le Wi-Fi directement depuis la page web.

Specifications: ESP32 Web Server

1. Objective

Create an embedded web server on the ESP32 to control GPIOs via a web interface accessible through a browser.

2. Features

a. Wi-Fi Connection

The ESP32 must connect to a specified Wi-Fi network.

Display the connection status and the assigned IP address in the console.

b. Web Server

Host a web page accessible via the ESP32's IP address.

Display an interface to control GPIOs.

Update the GPIO status in real-time.

c. GPIO Control

Allow turning an LED (or another component) on and off via buttons on the web interface.

Update the GPIO status based on user interactions.

3. Technical Constraints

Use the ESP-IDF framework.

Develop using C language.

Use Wi-Fi station mode to connect the ESP32 to the network.

Simple web interface in HTML/CSS with HTTP requests to interact with the ESP32.

4. Required Hardware

ESP32-WROOM-32

LED (optional, can use the built-in LED on GPIO 2)

Connection wires (if needed)

5. Future Enhancements

Add a REST API to interact with the server via JSON.

Display a log of performed actions.

Add an Access Point (AP) mode to configure Wi-Fi directly from the web page.

