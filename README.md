<div align="center">
  
![SCSS Mixins](https://user-images.githubusercontent.com/33424294/57123425-152da600-6d82-11e9-985f-d8772413d588.png)
<br/><br/><br/>
**SCSS Mixins** is an SCSS library that will help you to code for multiple browsers.<br>
It provides easy functions to code CSS attributes for each browsers.
<br/><br/><br/>
![SCSS Mixins](https://user-images.githubusercontent.com/33424294/57124141-dea55a80-6d84-11e9-8057-b5af27fa471d.jpg)

</div>

## Installation

Juts add the "SCSS-Mixins.scss" file in your project and add this line in your SCSS file :
```scss
@import "your_path/SCSS-Mixins.scss";
```

## Usage

Here are some examples of what you can do :

```scss
@include transform(translate(-50%, -50%));
@include transition(opacity, 0.2s, linear);
@include border-radius(2px);
@include user-select(none);
@include transition(none);
```

## Features

- [keyframes](//developer.mozilla.org/fr/docs/Web/CSS/@keyframes){:target="_blank"}
