# Recipes
## What might they
## look like?

---

## Recipe Files

Maybe files that sit along side your HTML files might work?


```html
<header>
	<h1>Test</h1>
</header>
```

```
use: h5bp, eve
use: google-analytics(code=UA-XXXXX-X)
```
---

## Some "Pretend" HTML Tags

```html
<use>h5bp</use>
<use>eve</use>
<use code="UA-XXXXX-X">google-analytics</use>
<header>
	<h1>Test</h1>
</header>
```

<small>A great suggestion from [@johnallsopp](http://twitter.com/johnallsopp) was to replace the `<use>lib</use>` tag
with potentially a `<link rel="use">lib</link>` tag instead.</small>

---

## Then we merge?
### HTML, Snippets, etc

Experimental Library: [htmlmerge](https://github.com/DamonOehlman/htmlmerge)


_This doesn't __yet__ implement the functionality that I'm proposing here, but it can take 2+ html fragments and push them together and produce optimized output._
