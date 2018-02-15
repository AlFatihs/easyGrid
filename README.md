# easyGrid

_A simple CSS Grid system_

`easyGrid` is a lightweight, super-simple and cross-browser HTML grid library for you to use in your projects.

## Basic Usage

1. Include the stylesheet on your document's `<head>`
2. Additionally you need 'viewport' meta tag on your document's `<head>`

```html
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="easygrid.min.css">
</head>
```
 
```html
<div class="col-12-small col-06-mid col-03-large">A block</div>
```
or with 'row'

```html
<div class="row">	
   <div class="col-12-small col-06-mid col-03-large">A block</div>
</div>
```
or as short-hand

```html
<div class="row">	
   <div class="col-12-s col-06-m col-03-l">A block</div>
</div>
```

## License

easyGrid is licensed under the MIT license. (http://opensource.org/licenses/MIT)
