---
layout: post
title: "Application Quiz Game"
thumbnail: /assets/images/quiz-game.png
tags: project
---

<!-- <div style="display: flex;">
  <a href="https://github.com/disanv03/qcm_reactnative">
    <img src="{{site.baseurl}}/assets/images/qcm-react.jpg" alt="qcm app screenshot" style="width: 200px; height: auto;">
  </a>
  <div style="margin-left: 10px;">
  
    un jeu de quiz interactif, développé en react native. il utilise l'api open trivia database pour récupérer des questions à choix multiples, et intègre un `timer` pour ajouter un défi supplémentaire.

    ce projet est une belle illustration d'utilisation des hooks react `usestate` et `useeffect` pour le gestion d'état et la récupération des données.

    [lien vers le code source](https://github.com/disanv03/qcm_reactnative)
    
  </div>
</div> -->


| | |
|---|---|
| ![QCM App Screenshot]({{site.baseurl}}/assets/images/qcm-react.jpg) | <span style="font-size: 20px;">Un jeu de quiz interactif, développé en React Native. On utilise l'API Open Trivia Database pour récupérer des questions à choix multiples, et on intègre une `timer` pour ajouter un défi supplémentaire au jeu.</span> <br><br> <span style="font-size: 20px;">Ce projet est une belle illustration d'utilisation des hooks React `useState` et `useEffect` pour le gestion d'état et la récupération des données.</span> <br><br> [Lien vers le code source](https://github.com/disanv03/qcm_reactNative) |


```javascript
// Extrait de code pour récupérer des données à partir d'une API
useEffect(() => {
  fetch("https://opentdb.com/api.php?amount=10&category=9")
    .then(response => response.json())
    .then(data => setQuestion(data.results))
    .catch((e) => console.log("Error: " + e));
}, []);
```
