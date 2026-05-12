# axlothecook-sass-library
My own SASS/SCSS library. Bc I don't like Tailwind and Bootstrap, and CSS3 is limiting.


## How to customize values?
1) Create a separate folder for css, call it whatever you'd like, I usually call it 'custom-styles'. <br>
2) Inside create a index.scss file. This is where all of your custom code will be written. <br>
3) Add custom code. It can look like this: <br>
```json
$primary: indigo;
$base-padding: 0.75rem;
$base-font-size: 5px;

@import 'sass-library';
```
<br>
4) Add '@import sass-library' after all of the code you've added. <br>
5) Make sure to link to your new index.scss file in your custom folder (ie 'custom-styles/index.css') instead of the 'sass-library/index.scss' to use your custom styling. <br>
<br>

## Conventions (for me, when editing the library)

<ul>
- When adding a colour to the `$colors` map in `_variables.scss`, always insert it **alphabetically** within the named-colours section (the theme aliases at the top stay grouped semantically).
- Before adding a colour, check it isn't already in the map under a different name.
</ul>

## If you find any bugs or have questions, open a github issue on the library and I'll try to respond asap.

## Inspo advice
visit [this website](https://getcssscan.com/css-box-shadow-examples) for more box-shadow ideas
