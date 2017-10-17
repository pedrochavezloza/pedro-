# [shgysk8zer0.github.io](https://shgysk8zer0.github.io)

A responsive, progressive about / portfolio & blog page built using Jekyll

- - -
[![Build Status](https://travis-ci.org/shgysk8zer0/shgysk8zer0.github.io.svg?branch=master)](https://travis-ci.org/shgysk8zer0/shgysk8zer0.github.io)
[![GitHub license](https://img.shields.io/badge/license-AGPL-blue.svg)](https://raw.githubusercontent.com/shgysk8zer0/shgysk8zer0.github.io/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/shgysk8zer0/shgysk8zer0.github.io.svg)](https://github.com/shgysk8zer0/shgysk8zer0.github.io/releases)
[![GitHub issues](https://img.shields.io/github/issues/shgysk8zer0/shgysk8zer0.github.io.svg)](https://github.com/shgysk8zer0/shgysk8zer0.github.io/issues)
[![GitHub forks](https://img.shields.io/github/forks/shgysk8zer0/shgysk8zer0.github.io.svg)](https://github.com/shgysk8zer0/shgysk8zer0.github.io/network)
[![GitHub stars](https://img.shields.io/github/stars/shgysk8zer0/shgysk8zer0.github.io.svg)](https://github.com/shgysk8zer0/shgysk8zer0.github.io/stargazers)

[![GitHub stars](https://img.shields.io/github/stars/shgysk8zer0/shgysk8zer0.github.io.svg?style=social&label=Star)](https://github.com/shgysk8zer0/shgysk8zer0.github.io#fork-destination-box)
[![GitHub followers](https://img.shields.io/github/followers/shgysk8zer0.svg?style=social&label=Follow)](https://github.com/shgysk8zer0)
[![Twitter Follow](https://img.shields.io/twitter/follow/shgysk8zer0.svg?style=social&label=Follow)](https://twitter.com/shgysk8zer0)
[![Tweet](https://img.shields.io/twitter/url/https/github.com/shgysk8zer0/shgysk8zer0.github.io.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=%5Bobject%20Object%5D)

[![Screenshot](https://i.imgur.com/Ers0Xql.png)](https://shgysk8zer0.github.io)

## Features
- [Progressive Web App](https://developer.mozilla.org/en-US/Apps/Progressive)
[`manifest.json`](https://github.com/shgysk8zer0/shgysk8zer0.github.io/manifest.json)  
[`service-worker.js`](https://github.com/shgysk8zer0/shgysk8zer0.github.io/service-worker.js)
- [Responsive Design](https://developer.mozilla.org/en-US/Apps/Progressive/Responsive) using `@media` queries, `rem` / `vw` units
- [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
using `srcset` & `sizes`
- [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
`display: grid`
- [SVG icons](https://css-tricks.com/svg-sprites-use-better-icon-fonts/) using
`<symbol>`s & `<use xlink:href="...">`
- [ECMAScript modules](https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)
```javascript
	// script.js
	import {myClass} from './myClass.js';

	export default class $ {
		constructor(query, base = document) {
			this.els = [...base.querySelectorAll(query)];
		}

		// ... Some more methods here

		animate(keyframes, opts = 600) {
			this.els.forEach(el => el.animate(keyframes, opts));
		}
	};
```

- CSS [custom properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
```css
	@import url("./vars.css");

	:root {--my-var: red;}
	.my-class {color: var(--my-var);}
```
- CSS [animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)
& JavaScript [Animations API](https://developer.mozilla.org/en-US/docs/Web/API/Element/animate)
```javascript
	import {$} from './script.js';

	$('.fade-in').animate([
		{opacity: 0},
		{opacity: 1},
	], {
		duration: 600,
		easing: 'ease-in',
	});
```
- Content-Security-Policy ([*CSP*](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy))
- [SEO](https://search.google.com/structured-data/testing-tool#url=https%3A%2F%2Fshgysk8zer0.github.io)
via [structured data](https://schema.org/)

```html
<address itemprop="homeAddress" itemtype="http://schema.org/PostalAddress" itemscope>
	<!-- Address info here with appropriate `itemprop`s -->
</address>
```
- Built using Jekyll & GitHub Pages

## The links you're looking for
- [Issues](https://github.com/shgysk8zer0/shgysk8zer0.github.io/issues)
- [Pull Requests](https://github.com/shgysk8zer0/shgysk8zer0.github.io/pulls)
- [Code of Conduct](./docs/CODE_OF_CONDUCT.md)
- [Contributing Guidelines](./docs/CONTRIBUTING.md)

## Contact Info
- Email: [chris@chriszuber.com](mailto:chris@chriszuber.com)
