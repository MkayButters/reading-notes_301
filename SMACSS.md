## Responsive Web Design

Responsive Web Design is all about building wesbite suitable for all users devices.
- Responsive Websites react quickly and positively to any change.

Responsive Web Design is broken down in three parts

1. __Flexible Layouts__;
    - It is the practice of building he layout of a website with a flexible grid, capable of dynamically resizing to any width.

    - Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.

2. __Media Queries__

    - Built as an extension to media types commonly hen targeting and including styles.

    - Used to import export files from different style sheets.

    - Use the @media inside the css to choose either to change all, only, or not properties of the page.

        - The @media feature has many different modes and ascpects to use including ; landscape(the display is wider than taller), min/max width height, resolution (determines resolution of the photo by specifiying how many dots appear per pixel or cm)

 3. __Flexible Media__

    - Flexible media means that the images, videos, or other types of media are scalable and change as the size of the page changes.

    - To get embedded media to be fully responsive, the embedded element needs to be absolutely positioned within a parent element.
    
    - Below is an example of css code block using flexible media;
    `figure` {
  `height: 0;`
  `padding-bottom: 56.25%; /* 16:9 */`
  `position: relative;`
  `width: 100%;`
}
`iframe`{
  `height: 100%;`
  `left: 0;`
  `position: absolute;`
  `top: 0;`
 ` width: 100%;`
}


## Float

- Float is a CSS positioning property.

- In web design, page elements with the CSS float property applied to them are just like the images in the print layout where the text flows around them. 

- Floats sister property is `clear`

    - `clear` has four valid values
        1. _both_ which  clears floats coming from either direction
        2. _left_
        3. _right_
        4. _none_ which is the defualt
        5.  _Inherit_ but it is not supported in Internet Explorer 

        [<===BACK](README.MD)