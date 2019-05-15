# Application Web de chat vidéo en pair à pair utilisant WebRTC

Dépôt de départ du projet "Développement d’une application de chat vidéoP2P avec WebRTC"

## Rappel du sujet

L'objectif de ce projet est de développer une application web de chat en pair à pair permettant à minima :
- Un échange vidéo & audio entre plusieurs individus
- Une gestion de salles de discussion

Suivant les envies du groupe, le sujet pourra évoluer pour inclure d'autres fonctionnalités comme : 
- Messagerie instantannée
- Partage d'écran
- Envoi de fichiers
- Développement d'aspects "techniques" / "ingénierie logicielle" comme l'intégration continue avec par exemple la plateforme CI/CD de Gitlab + heroku

Le sujet est à découper en deux "sprints" (au sens agile du terme), à définir par le groupe d'étudiants, en accord avec l'encadrant / product owner.

## Projet de départ

Ce projet vous est proposé pour démarrer vos développements. Il utilise un certain nombre d'outils (npm, webpack...) déjà configuré et supposé vous aider à commencer plus rapidement. Libre à vous cependant de l'ignorer et d'en utiliser d'autres.

Le contenu est celui d'un [tutoriel](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Simple_RTCDataChannel_sample) de Mozilla. Il illustre le fonctionnement de certaines parties de l'API WebRTC en local (sans _STUN/TURN server_).

Par soucis de simplicité, aucun framework n'a été prévu. Encore une fois, si vous êtes à l'aise avec un framework en particulier, libre à vous de l'utiliser (tant qu'il est justifié :) )

### Installation 
Ce projet nécessite l'installation d'une version récente de [NodeJS](https://nodejs.org/en/) et NPM.

Une fois le projet téléchargé, vous pouvez télécharger ses dépendances avec `npm install`.

Pour l'utilisation de dépendances _node_ coté navigateur, [webpack](https://webpack.js.org/) est utilisé ici. Pour lancer le serveur de développement, utiliser `npm run start`.

Il est conseillé d'utiliser un navigateur récent ! (OK sur la dernière version de Firefox)

## Livrables attendus
Fin de sprint 1 :
- Ce qui a été fait / ce qu'il reste à faire (dont démo si possible ?)

Fin de sprint 2 (fin de projet) :
- Les sources documentées de votre projet (une archive ou un lien vers un dépôt type github / gitlab). Par "documenté", il est surtout entendu une explication "macro" de l'architecture de votre projet, de comment le lancer (si cela change du projet actuel) / l'utiliser, des choix d'implémentations (si besoin est). 
- Une documentation sur WebRTC : ce que vous en avez compris, ce que vous en avez fait... Possibilité de l'inclure dans le dépôt du projet (documentation markdown ou via des fonctionnalités de Wiki comme disponible sur Github).
- De magnifiques slides pour la soutenance !

## Ressources

### Outils de développement
[Débuter avec Webpack : créez votre project starter complet !](https://medium.com/@ZeFifi/d%C3%A9buter-avec-webpack-partie-1-import-export-et-compilation-ffd45bb3943d)

### WebRTC
Documentation d'introduction à WebRTC : 
- [Introduction to WebRTC protocols](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Protocols)
- [Getting Started with WebRTC](https://www.html5rocks.com/en/tutorials/webrtc/basics/)
- [WebRTC in the real world: STUN, TURN and signaling](https://www.html5rocks.com/en/tutorials/webrtc/infrastructure/)

Si besoin :
- [Real time communication with WebRTC (codelab Google)](https://codelabs.developers.google.com/codelabs/webrtc-web/#0)
