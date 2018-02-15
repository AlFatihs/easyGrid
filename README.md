# easyGrid

_A simple CSS Grid system_

`easyGrid` is a lightweight, super-simple and cross-browser HTML grid library for you to use in your projects.

## Basic Usage

1. Include the stylesheet on your document's `<head>`
2. You need to using 'viewport' meta tag on your document's `<head>` for proper works

```html
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="easygrid.min.css">
</head>
```
3. Use class methods on your HTML

```html
<div class="col-06-large">A block</div>

<div class="row">	
   <div class="col-12-small col-06-mid col-03-large">
      This column appears full in small display, half in medium display and one-fourth in large display
   </div>
</div>
```

or as short-hand

```html
<div class="row">	
   <div class="col-12-s col-06-m col-03-l">A block</div>
</div>
```

3. Available classes:

| Small Display     |  Medium Display    |    Large display    |    Any Display      |
| ----------------- | ------------------ | ------------------- |---------------------|
| `col-01-s`        | `col-01-m`         | `col-01-l`          | `col-01`            |
| `col-02-s`        | `col-02-m`         | `col-02-l`          | `col-02`            |
| `col-03-s`        | `col-03-m`         | `col-03-l`          | `col-03`            |
| `col-04-s`        | `col-04-m`    	   | `col-04-l`   	     | `col-04`            |
| `col-05-s`        | `col-05-m`         | `col-05-l`     	   | `col-05`            |
| `col-06-s`        | `col-06-m`      	 | `col-06-l`    	     | `col-06`            |
| `col-07-s`        | `col-07-m`         | `col-07-l`          | `col-07`            |
| `col-08-s`        | `col-08-m`   		   | `col-08-l`      	   | `col-08`            |
| `col-09-s`        | `col-09-m`     	   | `col-09-l`          | `col-09`            |
| `col-10-s`        | `col-10-m`     	   | `col-10-l`          | `col-10`            |
| `col-11-s`        | `col-11-m`     	   | `col-11-l`          | `col-11`            |
| `col-12-s`        | `col-12-m`     	   | `col-12-l`          | `col-12`            |


## License

easyGrid is licensed under the MIT license. (http://opensource.org/licenses/MIT)
