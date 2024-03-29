---
title: Notes de mise à jour
description: Dernières notes de mise à jour pour Adobe Experience Platform Debugger.
keywords: debugger ; extension experience cloud debugger ; chrome ; extension ; notes de mise à jour
uuid: 47a5d6f3-c074-4ad5-ad4b-e6030496689b
exl-id: 3eed44da-5f85-413e-a783-3a0df03a2baf
source-git-commit: a442fa56589003dad4ca9896ef601349fb93d280
workflow-type: tm+mt
source-wordcount: '287'
ht-degree: 91%

---

# Notes de mise à jour

## Version 1.3.0 - 28 janvier 2022

* Ajout du lien À propos pour afficher la version actuelle et les notes de mise à jour.
* Ajout d’un bouton (bascule) pour afficher les accès post-traités pour les requêtes Analytics. Le bouton (bascule) est disponible dans la section Analytics.
* Correction d’un problème de session de débogage à distance lorsque la session était fermée en dehors de Debugger.
* Correction d’une notification d’erreur visible dans l’onglet Transactions Edge du SDK web.
* Correction d’un problème lié aux balises d’Adobe dans l’avertissement d’obsolescence de la page lorsque Debugger accédait à l’objet _satellite.
* Correction de certains cas dans lesquels une instance AppMeasurement était introuvable sur la page.
* Correction d’un problème de connexion à la page qui se produisait lors de la première ouverture de la fenêtre de Debugger.

## Version 1.2.0 - 26 octobre 2021

* Afficher les événements de tous les onglets du navigateur dans la vue réseau. Pour afficher uniquement les événements de l’onglet actif, sélectionnez l’icône de verrouillage dans le coin inférieur droit de Debugger.
* Mise à jour de l’image de marque.

## Version 1.1.0 - 5 octobre 2021

* Visualisation du débogage à distance : organisez les événements de débogage à distance dans un diagramme de flux visuel dans le SDK web d’Adobe Experience Platform > section Transactions Edge.
* L’organisation IMS du SDK Web Adobe Experience Platform utilisée sur la page doit correspondre à l’organisation connectée lors du démarrage d’une nouvelle session de débogage à distance.
* Affiche uniquement les transactions Edge pour l’onglet connecté. Les journaux de Target Trace sont toujours disponibles dans la section Journaux > Edge.
* Autorisation du remplacement de la configuration de l’ID de flux de données distinct pour chaque instance du SDK web d’Adobe Experience Platform sur la page. Ajout du bouton (bascule) d’activation du débogage.
* Correction d’un problème en raison duquel le jeton d’Adobe Target Trace n’était pas toujours envoyé avec les sessions de débogage à distance pour le SDK web d’Adobe Experience Platform.

## Version 1.0.0 - 5 mai 2021

* Première version principale d’Experience Platform Debugger. Destiné à remplacer l’Experience Cloud Debugger.
