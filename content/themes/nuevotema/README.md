# Mapache for [Ghost](https://github.com/tryghost/ghost/) by GodoFredo

[![Ghost version](https://img.shields.io/badge/Ghost-0.8.x-brightgreen.svg?style=flat-square)](https://ghost.org/)
[![Node version](https://img.shields.io/node/v/uno-zen.svg?style=flat-square)](https://nodejs.org/en/)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](http://bit.ly/DonateMapacheGhost)

> Minimalist Material Design and Elegant theme for [Ghost](https://github.com/tryghost/ghost/).

### Free theme for Ghost

Hello, I created this theme Ghost to see how it works. It is available for free so you can use on your site. It is strictly forbidden commercial use. If you have any suggestions to improve the theme,  you can send me tweet to [@GodoFredoNinja](http://bit.ly/tw-GodoFredoNinja)

![](./documentation/img-one.png)


## Demo
You can see a demo in my [blog](http://bit.ly/GodoFredoNinja-blog).

## Mapache Support for Web Browsers
Mapache supports the following web [browsers](http://caniuse.com/#search=flexbox)

## Featured
- Responsive layout
- Blog navigation
- Page 404
- Page subscribe
- Pagination Infinite Scroll
- Cover images for blog, tag and author
- Social media links
- Post related
- Post format Video
- Post format Image
- Post (5 articles) Featured in sidebar
- Disqus Comments
- Disqus Comments Count
- Sharing Buttons
- Sharing socila media Count
- YouTube, Vimeo, kickstarter -> Video Responsive
- Code syntax Supported [Prismjs](http://prismjs.com/download.html?themes=prism&languages=markup+css+clike+javascript+aspnet+bash+c+csharp+cpp+ruby+css-extras+git+go+java+json+less+markdown+perl+php+php-extras+python+jsx+scss+sql+swift&plugins=line-numbers)


## USE


### Replace icon
Replace icon with these measures `155px * 155px` in `./assets/img/icon.png`



## Mapache settings

- Create [Api key Disqus](https://disqus.com/api/docs/)
- You have to enable via a checkbox on the labs page in your Ghost admin panel.

![](./documentation/img-two.png)




``` html
<script>
/* Social Media Links*/
var social_link = {
	'google': 'https://...',
	'youtube': 'https://...',
	'instagram': 'https://...',
	'snapchat': 'https://...',
	'dribbble': 'https://...',
	'github': 'https://...',
	'linkedin':'https://...',
	'spotify':'https://...',
	'codepen':'https://...',
	'behance':'https://...',
	'flickr':'https://...',
	'pinterest':'https://...',
	'feed':'https://...',
}

/*Youtube button subscribe for post video format*/
var youtube = {'YOUR_CHANNEL_NAME':'YOUR_CHANNEL_ID'}

/*Disqus for Comments*/
var disqus_shortname = 'YOUR_DISQUS_SHORTCUT_HERE';
var disqusPublicKey = "YOUR_DISQUS_API_KEY";
</script>
```

![](./documentation/img-three.png)


## Add Style Theme

```html
<!-- Theme indigo -->
<link rel="stylesheet" href="/assets/css/themes/indigo.css"/>
<!-- Theme dark blue -->
<link rel="stylesheet" href="/assets/css/themes/dark-blue.css"/>
<!-- Theme blue semi dark -->
<link rel="stylesheet" href="/assets/css/themes/blue-semi-dark.css"/>
<!-- Theme blue -->
<link rel="stylesheet" href="/assets/css/themes/blue.css"/>
<!-- Theme Grey -->
<link rel="stylesheet" href="/assets/css/themes/grey.css"/>
<!-- Theme dark cyan -->
<link rel="stylesheet" href="/assets/css/themes/dark-cyan.css"/>
<!-- Theme purple -->
<link rel="stylesheet" href="/assets/css/themes/purple.css"/>
<!-- Theme teal -->
<link rel="stylesheet" href="/assets/css/themes/teal.css"/>
<!-- Theme Green -->
<link rel="stylesheet" href="/assets/css/themes/green.css"/>

<!-- For theme white add two-color logo 230px * 130px -->

<!--
	***** 230px *****
	*				*
	***************** 130px
	*				*
	*****************
-->


<link rel="stylesheet" href="/assets/css/themes/white.css"/>

```

![](./documentation/img-four.png)


### Edit Sidebar

`./partials/sidebar.hbs`

```html

<div class="widget">
	<div class="title-primary">...your title...</div>
	... your content ...
</div>

<!-- Add your content here - block fixed -->
<div class="widget">
	<div class="fixed">
		... your content fixed ...
	</div>
</div>

```


### Excerpt

```html
<p class="excerpt">... Your Excerpt...</p>
```

![](./documentation/excerpt.png)

### Buttons
```html
... <a class="external">Your link external</a> ...

<a class="btn external">link external</a>

<a class="btn btn-download">download</a>

<a class="btn btn-download-cloud">download</a>
```
![](./documentation/buttons.png)


### Warning - Note - Success
```html
<p class="warning"> ... your text warning ... </p>

<p class="note"> ... your text note ... </p>

<p class="success"> ... your text success ... </p>
```
![](./documentation/note.png)


### PrismJS code syntax  

Add the alias according to what you need ` ```xxx ` for example for sass ` ```scss ` [List language Prismjs](http://prismjs.com/#languages-list)

![](./documentation/code.png)

## Video Post Format
if you want to have a video format, you only have to add a tag `video` the first video will move to large size

![](./documentation/video.png)

## Image Post Format
if you want to have a image format, you only have to add a tag `photo` the image Featured will move to large size

### Credits
- [Normalize](https://necolas.github.io/normalize.css/)
- [Jquery.ghostHunter](https://github.com/jamalneufeld/ghostHunter)
- [Prismjs](http://prismjs.com/)  It supports the following [link](http://prismjs.com/download.html?themes=prism&languages=markup+css+clike+javascript+aspnet+bash+c+csharp+cpp+ruby+css-extras+git+go+java+json+less+markdown+perl+php+php-extras+python+jsx+scss+sql+swift&plugins=line-numbers)

## Copyright & License

Copyright (c) 2016 GodoFredo - Released under the [MIT license](LICENSE).
