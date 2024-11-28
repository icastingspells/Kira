
```css
//<ОБНУЛЕНИЕ>--------------------------------------------------
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing: border-box;
  outline: none;
}
@media (hover: hover) {
  .with-fancybox header {
    padding-right: 17px;
  }
}
.fancybox__container {
  max-width: 100%;
}
a {
  text-decoration: none;
  transition: 0.4s;
  color: inherit;
  cursor: pointer;
  &:hover {
    color: inherit;
  }
}

ul,
ol,
li,
p {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

img {
  vertical-align: top;
  max-width: 100%;
  object-fit: cover;
  object-position: center;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: inherit;
  font-size: inherit;
  margin: 0;
  padding: 0;
}

body {
  height: 100%;
  line-height: 125%;
  font-size: $fontSize;
  color: $mainColor;
  font-family: $fontFamily;
  background: #f5f5f5;

  b,
  strong {
    font-weight: 700;
  }

  nobr {
    display: contents;
  }
}

button {
  border: none;
  background: transparent;
  transition: 0.4s;
  font-family: inherit;
  cursor: pointer;

  &:disabled {
    opacity: 0.8;
    pointer-events: none;
  }
}
```

- Блоки с выступами:
	https://htmlbook.ru/blog/treugolniki-cherez-css
- Компрессор видео
	https://www.freeconvert.com/video-compressor/


#Аккордеон

```html
<details>
	<summary>
	</summary>
</details>
```