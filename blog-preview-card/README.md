# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
    - [AI Collaboration](#ai-collaboration)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [https://bdeweer.github.io/blog-preview-card/](https://bdeweer.github.io/blog-preview-card/)
- Live Site URL: [https://bdeweer.github.io/blog-preview-card/](https://bdeweer.github.io/blog-preview-card/)

## My process

### Built with

- Pure HTML
- Pure CSS

### What I learned

J'ai appris plisieurs choses par rapport à la façon dont se gèrent les fonts (.ttf).
Un site pratique pour analyser des fonts : [fontdrop](https://fontdrop.info)
Dans le dossier 'static' les font sont de poids fixes.
Dans le dossiers parent (fonts), les fonts sont dits 'Variable'. C'est-à-dire qu'ils gèrent plusieurs poids. 
Il est de bonne pratique de tout gérer avec les fonts 'Variable' si disponibles.
L'onglet 'network' du navigateur permet de vérifier si les fonts sont bien chargés.
Un font 'italic' ne sera pas chargé s'il n'est pas sollicité par le code html.

La propriété font-display: swap; permet d'afficher le texte avec une font de secours en attendant le chargement de la font demandé. Cela a pour avantage de ne jamais avoir de texte illisible.

```css
.container {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  max-width: 384px;
  max-height: 522px;
  padding: var(--spacing-300);
  border: 1px solid black;
  border-radius: 10px;
  box-shadow: 5px 5px 0 rgba(0, 0, 0, 1);
  box-sizing: border-box;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development
Je veux continuer à comprendre les bonnes pratiques HTML et CSS.

### Useful resources

- [Font Drop](https://fontdrop.info/) - Cela m'a aidé à comprendre comment fonctionne les fonts


### AI Collaboration

J'utilise ChatGPT et Claude pour m'aider à améliorer le code


## Author

- Website - [Bertrand Deweer](https://www.your-site.com)
- Frontend Mentor - [@bdeweer](https://www.frontendmentor.io/profile/bdeweer)
- Twitter - [@bdeweeronx](https://x.com/bdeweeronx)
