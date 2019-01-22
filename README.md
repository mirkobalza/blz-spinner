# blz-spinner
Fully customizable loading spinner for AngularJS

Instructions
------------
In order to use *blz-spinner* you need AngularJS. 
First of all inject the module `'blz.spinner'` into the module in which you want to use it.
Then you can start using it! Use the tag `<blz-spinner></blz-spinner>` in your template. The spinner will be displayed vertically and horizontally centered relative to the parent.
This tag accepts 3 optional attributes:
* `show`: *optional (but recommended)*. Boolean that shows/hides the spinner. If not specified, the spinner will be hidden.
* `custom`: *optional*. JSON object that allow you to customize the spinner. In this object you can specify:
  * `showText`: *optional*. boolean that shows/hides a text at the bottom of the spinner. By default the displayed text is *Loading*;
  * `text`: *optional*. String that overrides the default text;
  * `textColor`: *optional*. String that sets the css 'color' attribute of the text. By default the color is white;
  * `textSize`: *optional*. String that sets the css 'fontSize' attribute of the text. By default the size is 24px;
  * `font`: *optional*. String that sets the css 'font-family' attribute of the text
  * `speedCurve`: *optional*. String that sets the rotation speed curve (css 'animation-timing-function' attribute) of the spinner. By default it is linear;
  * `seconds`: *optional*. Number that sets how many seconds a rotation takes (css 'animation-duration' attribute). By default it is 1.5;
  * `iterationCount`: *optional*. Number or string that specifies how many rotations will be performed (css 'animation-iteration-count' attribute). By default it is `infinite`.
  * `direction`: *optional*. String that sets the direction of the rotation (css 'animation-direction' attribute). By default it is 'normal';
  * `background`: *optional*. Boolean that shows/hides the blurred background behind the spinner. By default it is true;
  * `backgroundColor`: *optional*. String that specifies the color of the blurred background. By default it is 'black';
  * `circle`: *optional*. String that sets the color of the spinner circle. By default it is 'grey';
  * `bar`: *optional*. String that sets the color of the rotating bar of the spinner. By default it is 'white';
  * `height`: *optional*. Number that sets the height of the spinner. By default it is 80;
  * `width`: *optional*. Number that sets the width of the spinner. By default it is 80;
  * `thickness`: *optional*. Number that sets the thickness of the spinner. By default it is 10;
  * `imageUrl`: *optional*. String that specifies an image url to override the default spinner. Note that if you use a custom image, the other attributes will be ignored;
* `theme`: *Not implemented yet*.
