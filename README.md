# BackgroundAnimationNetwork

This is the angular version of my Vanilla JS network background animation which you can find here https://github.com/announa/background-animation---network

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.2.

## How to implement the animation into your angular-project

- Create a new angular project with `ng new your-project-name`
- Create a new component for the animation-component running `ng g c animation`
- Create a file <i>Point.class.ts</i> in the folder <i>animation</i>
- Copy the content of <i>Point.class.ts</i> into your <i>Point.class.ts</i>-file
- Create a file <i>Line.class.ts</i> in the folder <i>animation</i>
- Copy the content of <i>Line.class.ts</i> into your <i>Line.class.ts</i>-file
- Copy the content of <i>animation.component.html</i>, <i>animation.component.scss</i> and <i>animation.component.ts</i> into your files with the same name
- Include the animation-component where you want to use it, e. g. in your app-component with `<app-animation></app-animation>`
- For avoiding a white margin around the canvas apply the style-settings of <i>styles.scss</i>