# ShortcutCSS

Minimalist CSS classes for styling speedup.


## Usage

Replace styling for dummy Elements used for layout purposes and reduce your CSS complexity and size.
Use its features when it is certain the Element styling will be always the same.

Include ShortcutCSS
```
<link rel="stylesheet" href="css/shortcutcss.css">
```

Change your HTML from this:	
```
<style>
	.container
	{
		position: relative;
		text-align: center;
		width: 100%;			
	}

	.centered
	{
		position: relative;
		display: inline-block;
	}

	.title
	{		
		font-family: sans-serif;
		font-size: 20px;
	}		
</style>

<div class="container">
	<div class="centered">
		<span class="title">Centered Text</span>
	</div>
</div>
```

to this:
	
```
<style>	
	.title
	{		
		font-family: sans-serif;		
	}		
</style>

<div class="rel tc fw">
	<div class="ib rel">
		<span class="title fs20">Centered Text</span>
	</div>
</div>
```


