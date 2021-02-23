# Transforms

> The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

- Transform Syntax
 > 1. `-webkit-transform:`
 > 2. `-moz-transform:`
 > 3. `-o-transform:`
 > 4. `transform:` 

 - 2D Transforms
 > 2D Rotate ` transform: rotate(20deg);`
 > 2D Scale `transform: scale(.75);`
 > 2D Translate `transform: translateX(-10px);` `  transform: translateY(25%);` `  transform: translate(-10px, 25%);`
 > 2D Skew `  transform: skewX(5deg);`
 > 2D Cube Demo `  transform: rotate(-45deg) skew(15deg, 15deg);` `  transform: rotate(-15deg) skew(-15deg, -15deg) translate(50%, 100%);`

> Transform Origin `  transform-origin: 100% 100%;`
> Perspective `transform: perspective(200px)`

- 3D Transforms
 > 3D Rotate `  transform: perspective(200px) rotateX(45deg);`
 > 3D Scale `  transform: perspective(200px) scaleZ(1.75) rotateX(45deg);`
 > 3D Translate `  transform: perspective(200px) translateZ(-50px);`
 > Back face Visibility `backface-visibility: hidden; `
 > Transform Style  `  transform-style: preserve-3d;`

 # Transitions & Animations

 - Transitions
 > `transition-property: background;`
  `transition-duration: 1s;`
  `transition-timing-function: linear;`

  - Transitional Property

  - Animation Name

  - Transition Duration
 
  - Transition Timing
  
  - Transition Delay

  > - Shorthand Transitions
  >> `  transition: background .2s linear, border-radius 1s ease-in 1s;`

  - Animations Keyframes
> `@keyframes slide {`
  `0% {`
    `left: 0;`
   ` top: 0;`
  `}`
 ` 50% {`
    `left: 244px;`
   ` top: 100px;`
  `}`
  `100% {`
    `left: 488px;`
    `top: 0;`
 ` }`

`}`

- Timing Function
>   `animation-timing-function: ease-in-out;`

- Animation Iteration
> `  animation-iteration-count: infinite;`

- Animation Direction
>  `  animation-direction: alternate;`

- Animation Play State
> `  animation-play-state: paused;`

- Animation Fill Mode
> `  animation-fill-mode: forwards;`


# TRANSITIONS
1. Fade in
2. Change color
3. Grow & Shrink
4. Rotate elements
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border










