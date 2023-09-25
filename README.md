# Ass-10-Animation


## [Live Website Link!] [https://bagheladarsh007.github.io/Ass-10-Animation/?authuser=0](https://bagheladarsh007.github.io/Ass-10-Animation/)

### UI Structure
![270157381-c680ec46-6f16-4ea0-bf8e-741910e396cb](https://github.com/bagheladarsh007/Ass-10-Animation/assets/142333682/fd7dab13-5780-4039-a20f-1a1be66ffe3f)




### CSS Explanation

#### CSS Selector: `*`

| Property   | Value      | Explanation                                                                             |
| ---------- | ---------- | --------------------------------------------------------------------------------------- |
| box-sizing | border-box | Specifies that padding and border are included in the element's total width and height. |
| padding    | 0          | Sets the padding of all elements to 0.                                                  |
| margin     | 0          | Sets the margin of all elements to 0.                                                   |

Explanation: The `*` selector targets all elements on the page, applying these CSS properties to all elements.

---

#### CSS Selector: `body`

| Property         | Value  | Explanation                                                           |
| ---------------- | ------ | --------------------------------------------------------------------- |
| min-height       | 100vh  | Sets the minimum height of the `body` to 100% of the viewport height. |
| display          | grid   | Uses grid layout for the `body`.                                      |
| place-content    | center | Centers the content within the grid container.                        |
| background-color | #000   | Sets the background color of the `body` to black.                     |

Explanation: The `body` selector styles various aspects of the page body, including layout and background color.

---

#### CSS Selector: `.container`

| Property            | Value                                                      | Explanation                                                                      |
| ------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------- |
| display             | flex                                                       | Uses flexbox layout for elements with the `.container` class.                    |
| justify-content     | space-between                                              | Distributes space evenly between flex items along the main axis.                 |
| -webkit-box-reflect | below 1px linear-gradient(transparent, transparent, #0004) | Applies a reflective effect below `.container` elements using a linear gradient. |

Explanation: The `.container` class styles elements with a flex layout and adds a reflective effect.

---

#### CSS Selector: `.container img`

| Property         | Value                             | Explanation                                                     |
| ---------------- | --------------------------------- | --------------------------------------------------------------- |
| max-width        | 350px                             | Sets the maximum width of `img` elements to 350 pixels.         |
| transform-origin | center                            | Sets the transformation origin to the center of `img` elements. |
| transform        | perspective(800px) rotateY(20deg) | Applies a 3D perspective rotation to `img` elements.            |
| transition       | 0.5s                              | Specifies a 0.5-second transition for `img` elements.           |
| border-radius    | 5px                               | Adds a 5-pixel border radius to `img` elements.                 |
| box-shadow       | 0 0 8px #808080                   | Adds a shadow to `img` elements.                                |

Explanation: The `.container img` selector styles images within `.container` elements.

---

#### Hover States for `.container` and `.container img`

| Property               | Value                                                  | Explanation                                                                                             |
| ---------------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- |
| `.container:hover img` | opacity: 0.3                                           | Reduces the opacity of `img` elements within hovered `.container` elements to 0.3.                      |
| `.container img:hover` | transform: perspective(800px) rotateY(0deg) opacity: 1 | Restores the perspective and opacity of `img` elements when hovered, effectively removing the rotation. |

Explanation: These hover states define transitions and effects when hovering over `.container` elements and their child images.

![270157331-7edc0fc2-4c37-43a9-8916-519f0bdef7bd](https://github.com/bagheladarsh007/Ass-10-Animation/assets/142333682/f8dae573-8bb3-431a-b55c-30857644ed22)
