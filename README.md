# jQuery serialcursor - An innovative animated cursor

## About jQuery serialcursor
This plugin provides perpertual effect around the cursor to impress your visitors. Note that jQuery serialcursor is shared for inspirational and development purpose.

Dependencies: [Greensock GSAP](https://github.com/greensock/GSAP), [Paper.js](https://github.com/paperjs/paper.js/), and [simplex-noise.js](https://github.com/jwagner/simplex-noise.js).

## Demonstration
See the [project page](https://github.meunierkevin.com/jquery-serialcursor/) for a demonstration.


## Compatibility
jQuery serialcursor has been tested in: IE, Edge, Chrome, Firefox, and Safari.


## Self-Hosted
[Download](https://github.com/kevinmeunier/jquery-serialcursor/archive/master.zip) and save one of two available files to include serialcursor to your page, either the [development](https://github.com/kevinmeunier/jquery-serialcursor/blob/main/dist/jquery.serialcursor.js) or the [minified](https://github.com/kevinmeunier/jquery-serialcursor/blob/main/dist/jquery.serialcursor.min.js) version. Also, you can visit the [project page](https://github.meunierkevin.com/jquery-serialcursor/) to copy what you need.
```HTML
<script src="gsap.min.js"></script>
<script src="paper-core.min.js"></script>
<script src="simplex-noise.min.js"></script>
<script src="jquery.serialcursor.min.js"></script>
<link href="jquery.serialcursor.css" rel="stylesheet">
```
Due to the lightweight CSS code, it's recommended to copy/paste the CSS code into your general stylesheet.

Make sure [jQuery](http://jquery.com) is properly loaded before using jQuery serialcursor. 


## Basic Usage
The basic usage of serialcursor is pretty easy, just start using jQuery serialcursor by calling it after page load.
```JS
$(document).ready(function(){
  // jquery.serialcursor initialisation
  $('#serialcursor').serialcursor();
});
```

  
## Configuration Parameters
The following configurations is available by default:

Name               | Type       | Default                                        | Description
------------------ | ---------- | ---------------------------------------------- | -----------
stateDataAttr      | *string*   | *'data-serialcursor-state'*                    | Attribute to identify the draggable elements
strokeColor        | *string*   | *'rgba(255, 255, 255, .4)'*                    | Color of the border
strokeWidth        | *integer*  | *1*                                            | Border width
noiseScale         | *integer*  | *150*                                          | Speed of the noise
noiseRange         | *integer*  | *4*                                            | Range of the noise
htmlCursor         | *string*   | See [jquery.serialcursor.js](https://github.com/kevinmeunier/jquery-serialcursor/blob/main/dist/jquery.serialcursor.js) | HTML of the main element
htmlInner          | *string*   | See [jquery.serialcursor.js](https://github.com/kevinmeunier/jquery-serialcursor/blob/main/dist/jquery.serialcursor.js) | HTML of the inner element
htmlPointer        | *string*   | See [jquery.serialcursor.js](https://github.com/kevinmeunier/jquery-serialcursor/blob/main/dist/jquery.serialcursor.js) | HTML of the default pointer
htmlGrab           | *string*   | See [jquery.serialcursor.js](https://github.com/kevinmeunier/jquery-serialcursor/blob/main/dist/jquery.serialcursor.js) | HTML of the grab pointer


## Bugs / Feature request
Please [report](http://github.com/kevinmeunier/jquery-serialcursor/issues) bugs and feel free to [ask](http://github.com/kevinmeunier/jquery-serialcursor/issues) for new features directly on GitHub.

## Credits
The magnetic effect has been inspired by [Stefan Kaltenegger](http://www.stk.works/) from Tympanus.


## License
jQuery serialcursor is licensed under [MIT](http://www.opensource.org/licenses/mit-license.php) license.
