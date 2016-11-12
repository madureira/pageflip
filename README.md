# pageflip
This is a CSS3 and JavaScript library that will create a digital magazine using all the advantages of HTML5.

**[Live Demo](http://madureira.me)**

## How to use
You just need to include the css:
```html
<link rel='stylesheet' href='page-flip.css'>
```
Also include the javascript file:
```html
<script src="page-flip.js"></script>
```

Then init your pageflip, providing the main element (where you want to put the pageflip) and the pages url.

```js
<script>
  new Pageflip('#myDiv', [
    '/page_001.jpg',
    '/page_002.jpg',
    '/page_003.jpg',
    '/page_004.jpg',
    '/page_005.jpg',
    '/page_006.jpg'
  ]);
</script>
```

> **IMPORTANT:**

> You need to provide an even number of pages!

> For while, the pageflip only accepts images that is: *769x1200* pixels!
