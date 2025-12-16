---
layout: essay
type: essay
title: "Design Patterns"
date: 2025-12-04
published: false
labels:
  - Software Engineering
  - Problem Solving
---

<H1>Coding Smart</H1>

Software development and programming on the surface can seem to be a lot of complex problem solving. While it is hard to program, and even harder to become an efficient programmer, design patterns are one of many tools that can help bridge that gap. Using design patterns allows the developer to put numerous problems into categories that makes them easier to approach in the future. Utilizing these design patterns allows for the creation of code which is straightforward to interpret from an outsider’s point of view. Furthermore, design patterns are not cut-and-paste code you can apply but rather ideas and concepts that guide you to the solution. Code created in this way lets other developers work with the code without fear of breaking it or causing some larger issue. A simple example of a popular easy to understand design pattern is the prototype. The problem the prototype is trying to solve is when you want to make exact copies of an object without relying on its class. By using the Prototype pattern programmers are able to duplicate objects without making new ones from scratch. Using methods like clone, you encapsulate this entire process inside the object itself.

<H2>Avoidng the Lava Flow!</H2>

As previously mentioned, using design patterns allows us to create code that reuses solutions and adheres to proper structure. This is helpful but in the pursuit of well-designed code it can lead you to over-engineering, or misusing patterns. This combined with poor documentation can lead to an anti-pattern known as the lava flow. Lava flow can be easily understood as code that is poorly designed, poorly documented, but could still possibly work that gets deployed into the production environment. This code is subsequently worked on and continues to sit there. If a time may come when someone may need to change this code, due to the poor optimization, over engineering or poor documentation caution must be taken in fear that changing something could cause a ripple effect.

<H2>Design Patterns in Practice</H2>

When working with databases a prominent design pattern my team used was the Observer design pattern. For example our component “RoutesMapClient” which displays route data onto a map, observes changes in the “routes” array, and automatically updates to display the changes. At the time during the creation of the page I was unaware of the observer design pattern explicitly but my team used it anyways. When any of us refer back to these uses of patterns in our project due to the well designed structure it is easy to work with highlighting the strengths of design patterns.
