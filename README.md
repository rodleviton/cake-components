# Cake Components
Perfectly baked and decorated components for any application.

## Background of project
Complex web applications are no longer created as a collection of views that represent an entire page/route. Instead developers are taking queues from the functional programming paradigm and composing components to form complex application views. The component architecture has been spearheaded by the Open Source JavaScript library [React](https://facebook.github.io/react/) and the miriad of 'React' like libraries such as [Inferno](https://github.com/infernojs/inferno), [Preact](https://github.com/developit/preact) etc... 

## What is a component

## What is Cake?
Cake is not so much a 'thing' but more of an approach to building highly reusable, semantic and easily themeable components. 

## Anatomy of a Cake component

1. Base
Just like any good cake base recipe this should never change once perfected. The base of a Cake Component should be semantically correct, accessible and not include extra markup to achieve bespoke design requirements. The base is the foundation to which we apply the rest of the ingredients on top of.

```
[component-name].base.html
```

2. Filling
```
[component-name].filling.js
```

3. Sprinkles
```
[component-name].sprinkles.css
```
