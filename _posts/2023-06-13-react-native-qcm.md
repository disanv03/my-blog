---
layout: post
title: "Application QCM en ReactNative"
thumbnail: /assets/images/qcm-react.jpg
tags: project
---

<!-- <div style="display: flex;">
  <a href="https://github.com/disanv03/qcm_reactNative">
    <img src="{{site.baseurl}}/assets/images/qcm-react.jpg" alt="QCM App Screenshot" style="width: 200px; height: auto;">
  </a>
  <div style="margin-left: 10px;">
  
    Un jeu de quiz interactif, développé en React Native. Il utilise l'API Open Trivia Database pour récupérer des questions à choix multiples, et intègre un `timer` pour ajouter un défi supplémentaire.

    Ce projet est une belle illustration d'utilisation des hooks React `useState` et `useEffect` pour le gestion d'état et la récupération des données.

    [Lien vers le code source](https://github.com/disanv03/qcm_reactNative)
    
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
