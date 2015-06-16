# ShortcutCSS

Minimalist CSS classes for styling speedup.


## Usage

Replace styling for dummy Elements used for layout purposes and reduce your CSS complexity and size.
Use its features when it is certain the Element styling will be always the same.

Include ShortcutCSS
```html
<link rel="stylesheet" href="css/shortcutcss.css">
```
```html
<link rel="stylesheet" href="css/shortcutcss.min.css">
```

Change your HTML from this:	
```html
<style>
	.container
	{
		position: relative;
		text-align: center;
		width: 100%;			
		background-color: rgba(255,229,229,1.0);
	}
	
	.centered
	{
		position: relative;
		display: inline-block;
	}
	
	.title
	{	
		font-size: 20px;
		color: rgba(255,76,76,1.0);
	}			
</style>

<div class="container">
	<div class="centered">
		<span class="title">Centered Text</span>
	</div>
</div>
```

to this:
	
```html
<style>	
	.title
	{		
		font-family: sans-serif;		
	}		
</style>

<div class="rel tc bk-red90 fw">
	<div class="ib rel">
		<span class="title fs20 t-red30">Centered Text</span>
	</div>
</div>
```


