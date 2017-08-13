# coffeecss

## Adding coffeecss to your website

``` html
<link rel="stylesheet" type="text/css" href="helpers.css" />
```

## Text align
``` html
<div class="left">
	Text aligned to the left
</div>
```


``` html
<div class="right">
	Text aligned to the right
</div>
```


``` html
<div class="center">
	Text centered
</div>
```


``` html
<div class="justify">
	Justified text
</div>
```


## CSS Tables
``` html
<div class="table" style="width: 500px;height: 80px;">
	<div>
		<div>1st Column</div>
		<div>2nd Column</div>
		<div>3rd Column</div>
	</div>
</div>
```

### CSS Table align
Using the class .top, .middle and .bottom with the .table class, you can align all the columns of the table.
``` html
<div class="table top" style="width: 500px;height: 80px;">
	<div>
		<div>Column #1</div>
		<div>Column #2</div>
		<div>Column #3</div>
	</div>
</div>
```

If you use .top, .middle or .bottom inside the CSS table, you can modify the default align
``` html
<div class="table top" style="width: 500px;height: 80px;">
	<div>
		<div class="middle">Column #1</div>
		<div class="bottom">Column #2</div>
		<div>Column #3</div>
	</div>
</div>
```
