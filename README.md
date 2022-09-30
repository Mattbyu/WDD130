/* if you are using any Google fonts change the font names below to your fonts. 
Any spaces in your font name should be replaced with a +. 
Fonts are separat/* if you are using any Google fonts change the font names below to your fonts. 
Any spaces in your font name should be replaced with a +. 
Fonts are separated by a | */
@import url('https://fonts.googleapis.com/css?family=IM+Fell+French+Canon+SC|Lato');

:root {
  /* change the values below to your colors from your palette */
  --primary-color: #396E94;
  --secondary-color: #E7C24F;
  --accent1-color: #A43312;
  --accent2-color: white;

  /* change the values below to your chosen font(s) */
  --heading-font: "IM Fell French Canon SC";
  --paragraph-font: Lato, Helvetica, sans-serif;

  /* these colors below should be chosen from among your palette colors above */
  --headline-color-on-white: black;  /* headlines on a white background */ 
  --headline-color-on-color: white; /* headlines on a colored background */ 
  --paragraph-color-on-white: black; /* paragraph text on a white background */ 
  --paragraph-color-on-color: white; /* paragraph text on a colored background */ 
  --paragraph-background-color: black;
  --nav-link-color: #396E94;
  --nav-background-color: #E7C24F;
  --nav-hover-link-color: #E7C24F;
  --nav-hover-background-color: #396E94;
}


/*  Look around below...but DON'T CHANGE ANYTHING! */
html {
  background-color: var(--primary-color);
}
body {
  max-width: 940px;
  margin: 0 auto;
  background-color: white;
  padding: 1em;
}
img {
  max-width: 100%;
}
h1, h2, h3, h4, h5, h6 {
  font-family: var(--heading-font);
  color: var(--headline-color-on-white);
}
header {
  padding: 1em;
