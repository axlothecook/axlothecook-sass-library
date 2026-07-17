# axlothecook-sass-library
My own SASS/SCSS library. Bc I don't like Tailwind and Bootstrap, and CSS3 is limiting. 

## What does it do?
Basically a mix of Tailwind and Bootstrap. Offers:
<ul>
  <li>component classes to build general components</li>
  <li>component classes can be modified or ignored all together</li>
  <li>utility attribute classes (padding, display) to modify current or build component classes anew</li>
  <li>a color palette</li>
  <li>users can add their own colors</li>
</ul>


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
5) Make sure to link to your new index.scss file in your custom folder (ie 'styles/index.css') instead of the 'sass-library/index.scss' to use your custom styling. <br>
<br>

## Conventions (for me, when editing the library)

<ul>
- When adding a colour to the `$colors` map in `_variables.scss`, always insert it **alphabetically** within the named-colours section (the theme aliases at the top stay grouped semantically).
- Before adding a colour, check it isn't already in the map under a different name.
</ul>

## If you find any bugs or have questions, open a github issue on the library and I'll try to respond asap.

## Inspo advice
visit [this website](https://getcssscan.com/css-box-shadow-examples) for more box-shadow ideas

## Demo pictures 
Available in demo.html that comes with repo, you can spin it on your own after running gulp and opening the file in the browser.
![image](https://github.com/user-attachments/assets/1cb147df-f6a8-4a71-9290-fa5d41816580)
![image](https://github.com/user-attachments/assets/059d9a59-2315-40b9-9731-7f8209124066)
![image](https://github.com/user-attachments/assets/b04ad6a6-b796-45d0-965d-b85c3bfded27)
![image](https://github.com/user-attachments/assets/26ed1b65-987a-4035-a623-5504ff612cbc)
![image](https://github.com/user-attachments/assets/15dee43b-8867-4d32-9e7e-7b190889fb6e)
