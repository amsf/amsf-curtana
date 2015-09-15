<a name="0.0.5"></a>
## [0.0.5](https://github.com/sparanoid/amsf-curtana/compare/v0.0.4...v0.0.5) (2015-09-15)


### Bug Fixes

* **style:** header not correctly aligned ([e4095f0](https://github.com/sparanoid/amsf-curtana/commit/e4095f0))
* **style:** wrong header children text align ([c464d64](https://github.com/sparanoid/amsf-curtana/commit/c464d64))

### Features

* **docs:** update badge ([7e5c498](https://github.com/sparanoid/amsf-curtana/commit/7e5c498))
* **style:** avoid transition delay ([a810726](https://github.com/sparanoid/amsf-curtana/commit/a810726))
* **style:** minor tweak ([7329c2a](https://github.com/sparanoid/amsf-curtana/commit/7329c2a))
* **style:** wider images for large screens ([a2c328c](https://github.com/sparanoid/amsf-curtana/commit/a2c328c))
* **template:** `scheme-bg-img` works with multiple images ([58d576d](https://github.com/sparanoid/amsf-curtana/commit/58d576d))
* **template:** add `page.scheme-bg-img-local` option ([5f41824](https://github.com/sparanoid/amsf-curtana/commit/5f41824))
* **template:** add `scheme-bg-img` support ([7a49b3e](https://github.com/sparanoid/amsf-curtana/commit/7a49b3e))
* **template:** simplify template structure ([0fbed02](https://github.com/sparanoid/amsf-curtana/commit/0fbed02))
* **template:** use `data-assets-inline` attribute for `grunt-assets-inline` ([9209658](https://github.com/sparanoid/amsf-curtana/commit/9209658))



<a name="0.0.4"></a>
## [0.0.4](https://github.com/sparanoid/amsf-curtana/compare/v0.0.3...v0.0.4) (2015-08-26)


### Bug Fixes

* **style:** add `.no-enlarge` to exclude specific images ([f025749](https://github.com/sparanoid/amsf-curtana/commit/f025749))
* **style:** better image, video, and iframe handling ([b29b2ba](https://github.com/sparanoid/amsf-curtana/commit/b29b2ba))
* **template:** missing post language tag ([89bba5c](https://github.com/sparanoid/amsf-curtana/commit/89bba5c))
* **theme:** code not break in list ([ed09821](https://github.com/sparanoid/amsf-curtana/commit/ed09821))

### Features

* **style:** use `no-intense` instead of `nointese` ([40c197c](https://github.com/sparanoid/amsf-curtana/commit/40c197c))
* **template:** better post / page language support ([414ca4d](https://github.com/sparanoid/amsf-curtana/commit/414ca4d))


### BREAKING CHANGES

* This will break your current layout if you're using `nointense` for your images, please rename the classes to `no-intense`, sorry for the inconvenience.
* Now you can add `.no-enlarge` to images that you'd like to keep it in normal width in smaller devices:
```html
<img class="no-enlarge" src="/ipad-frame-01.png">
```


<a name="0.0.3"></a>
## [0.0.3](https://github.com/sparanoid/amsf-curtana/compare/v0.0.2...v0.0.3) (2015-08-24)


### Bug Fixes

* remove leftovers ([6905844](https://github.com/sparanoid/amsf-curtana/commit/6905844))
* **pages:** avoid production output for example pages ([9c1eaa2](https://github.com/sparanoid/amsf-curtana/commit/9c1eaa2))
* **style:** exclude browser image width ([434c34f](https://github.com/sparanoid/amsf-curtana/commit/434c34f))
* **style:** some images not stretched on mobile devices ([6c7a4d1](https://github.com/sparanoid/amsf-curtana/commit/6c7a4d1))

### Features

* **style:** list minor tweaks ([342a6eb](https://github.com/sparanoid/amsf-curtana/commit/342a6eb))
* **template:** add Google Analytics support ([46b424c](https://github.com/sparanoid/amsf-curtana/commit/46b424c))
* **theme:** rearrange assets ([d14fef1](https://github.com/sparanoid/amsf-curtana/commit/d14fef1))
* **theme:** simplify custom styles ([b209b0e](https://github.com/sparanoid/amsf-curtana/commit/b209b0e))
* **theme:** typographic tweaks ([7a31a22](https://github.com/sparanoid/amsf-curtana/commit/7a31a22))
* **theme:** update blockquotes style ([01995be](https://github.com/sparanoid/amsf-curtana/commit/01995be))
* **theme:** update default page templates ([ecca259](https://github.com/sparanoid/amsf-curtana/commit/ecca259))



<a name="0.0.2"></a>
## [0.0.2](https://github.com/sparanoid/amsf-curtana/compare/v0.0.1...v0.0.2) (2015-08-17)


### Bug Fixes

* **grunt:** release as default task ([db8e928](https://github.com/sparanoid/amsf-curtana/commit/db8e928))
* **style:** missing footnotes styles for Kramdown ([d2f24d6](https://github.com/sparanoid/amsf-curtana/commit/d2f24d6))
* **theme:** missing CSS variables for Kramdown ([b117678](https://github.com/sparanoid/amsf-curtana/commit/b117678))

### Features

* **style:** better code blocks and images size on mobile devices ([8041709](https://github.com/sparanoid/amsf-curtana/commit/8041709))
* **style:** simplify amsf custom style ([d25ed98](https://github.com/sparanoid/amsf-curtana/commit/d25ed98))
* **template:** add page templates ([051be30](https://github.com/sparanoid/amsf-curtana/commit/051be30))
* **theme:** add custom favicon support ([9791178](https://github.com/sparanoid/amsf-curtana/commit/9791178))
* **theme:** better content margin ([57c7a3a](https://github.com/sparanoid/amsf-curtana/commit/57c7a3a))



<a name="0.0.1"></a>
## 0.0.1 (2015-08-12)


### Bug Fixes

* **config:** wrong default value ([71d7c90](https://github.com/sparanoid/amsf-curtana/commit/71d7c90))
* **grunt:** remove missing task ([0a3d2f1](https://github.com/sparanoid/amsf-curtana/commit/0a3d2f1))
* **style:** add missing code block background for Rouge parser ([bd41fb7](https://github.com/sparanoid/amsf-curtana/commit/bd41fb7))
* **template:** image titles not recognized in Safari Reader mode ([dd56837](https://github.com/sparanoid/amsf-curtana/commit/dd56837))
* **template:** wrong theme slug ([02b4a67](https://github.com/sparanoid/amsf-curtana/commit/02b4a67))

### Features

* hello world ([c5fc207](https://github.com/sparanoid/amsf-curtana/commit/c5fc207))
* **docs:** add readme ([8ac925f](https://github.com/sparanoid/amsf-curtana/commit/8ac925f))
* **style:** add missing CSS (Less) lint and comb configs ([88d48af](https://github.com/sparanoid/amsf-curtana/commit/88d48af))
* **style:** reset custom styles ([1f3cf61](https://github.com/sparanoid/amsf-curtana/commit/1f3cf61))
* **template:** add theme basic info ([4b32166](https://github.com/sparanoid/amsf-curtana/commit/4b32166))
* **template:** new syntax for inline assets ([596400b](https://github.com/sparanoid/amsf-curtana/commit/596400b))
* **theme:** use dedicated svg directory outside the jekyll `_includes` ([8aa2de7](https://github.com/sparanoid/amsf-curtana/commit/8aa2de7))


### BREAKING CHANGES

* This will change the way SVG titles got embeded, now SVG titles are inlined into `<img>` tags instead of putting `<svg>` directly into HTML.


