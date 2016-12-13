#Portfolio

##wrong items

+ Please put `img` tag in it's own line.

```html

	<div class="logo"><img src="images/images_src/fixed/logo.jpg" alt="logo" /></div>
```

+ Here instead of adding this `hr` you can add use the bottom margin from the div above to produce the same effect :)

```html

	<hr class="divider">
```


+ Prefer to use double quotes instead of single ones.

```css

	 font-family: 'Open Sans Condensed', sans-serif;
```


+ Separate style rules with a blank line.
+ Indentation might seem a little bit too much, but it's not. People will see it.

```css
	a {
	  color: inherit;
	  text-decoration: none;
	  cursor: pointer;  
	}
		a:hover {
			text-decoration: underline;
		}
```