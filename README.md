
#Jquery vertical slider
___

Jquery Mobile don't allow to display slider vertically. I need it to working on a project, then I continued the work of @elmundio87

![](http://blog.damienromito.fr/wp-content/uploads/2011/12/verticalSlider-300x256.jpg)



## Usage 


1 - Add plugin after jquery mobile

```html
<script src="http://code.jquery.com/jquery-1.6.4.min.js"></script>
<script src="http://code.jquery.com/mobile/1.0/jquery.mobile-1.0.min.js"></script>
<script src="vertical-slider.jquery.js"></script>
```


2 - Add input with the attribute `type="range"`and specify the sliderOrientation  attribute with `vertical` or `horizontal`

```html
<input type="range" name="slider" id="slider-0" value="50" step="5" min="0" max="100"  sliderOrientation="vertical" />
```

3 - Enjoy


**Don't use it in a scrollable view, it's makes no sens for the user experience (double vertical scroll actions). XD**
