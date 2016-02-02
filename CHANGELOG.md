<a name="0.0.11"></a>
## [0.0.11](https://github.com/sparanoid/amsf-curtana/compare/v0.0.10...v0.0.11) (2016-02-02)


### Bug Fixes

* **styles:** missing custom `hr` css scope ([0813fb8](https://github.com/sparanoid/amsf-curtana/commit/0813fb8))

### Features

* **style:** update `::selection` style ([bd9e3f4](https://github.com/sparanoid/amsf-curtana/commit/bd9e3f4))



<a name="0.0.10"></a>
## [0.0.10](https://github.com/sparanoid/amsf-curtana/compare/v0.0.9...v0.0.10) (2015-12-20)


### Bug Fixes

* **styles:** missing padding variable for offset elements ([ca8b2c7](https://github.com/sparanoid/amsf-curtana/commit/ca8b2c7))

### Features

* **styles:** add position offset for `pre` and `table`, break Less into files ([d391e6f](https://github.com/sparanoid/amsf-curtana/commit/d391e6f))



<a name="0.0.9"></a>
## [0.0.9](https://github.com/sparanoid/amsf-curtana/compare/v0.0.8...v0.0.9) (2015-12-19)


### Bug Fixes

* **styles:** missing custom footnote decorations color ([3a612c6](https://github.com/sparanoid/amsf-curtana/commit/3a612c6))

### Features

* **styles:** brand new spliter for `hr` and `.footnotes` ([c997877](https://github.com/sparanoid/amsf-curtana/commit/c997877))
* **template:** experiments with custom data (Words and Reading time Open Graph support) ([bb64703](https://github.com/sparanoid/amsf-curtana/commit/bb64703))



<a name="0.0.8"></a>
## [0.0.8](https://github.com/sparanoid/amsf-curtana/compare/v0.0.7...v0.0.8) (2015-12-04)


### Bug Fixes

* **amsf:** missing title whitespace ([34f4156](https://github.com/sparanoid/amsf-curtana/commit/34f4156))
* **style:** Don't always show horizontal scrollbar ([1a20c24](https://github.com/sparanoid/amsf-curtana/commit/1a20c24)), closes [#2](https://github.com/sparanoid/amsf-curtana/issues/2)
* **styles:** make line numbers not selectable ([d3d6e26](https://github.com/sparanoid/amsf-curtana/commit/d3d6e26))

### Features

* **style:** gapless border for blockquotes, fixes https://github.com/amsf/amsf-curtana/issue ([ae9cdcf](https://github.com/sparanoid/amsf-curtana/commit/ae9cdcf))
* **style:** smaller blockquotes font size ([9280796](https://github.com/sparanoid/amsf-curtana/commit/9280796))
* **styles:** add basic `lineno` support ([049f08c](https://github.com/sparanoid/amsf-curtana/commit/049f08c))
* **styles:** avoid calculating code color ([092f6ff](https://github.com/sparanoid/amsf-curtana/commit/092f6ff))
* **styles:** update default code color ([5ffcaeb](https://github.com/sparanoid/amsf-curtana/commit/5ffcaeb))
* **styles:** use brand-new fully automatic generated syntax highlighting ([08876e8](https://github.com/sparanoid/amsf-curtana/commit/08876e8))
* **template:** disable `jekyll-last-modified-at` for dev mod for better performance ([fae1386](https://github.com/sparanoid/amsf-curtana/commit/fae1386))


### BREAKING CHANGES

* Now paragraphs in a blockquote will get a single gapless border on the left side, you don't need special markup to achieve this now:
```markdown
> … these mean that in many fields the rule will be: Build it, and they will come.
>
> Paul Graham
```
* This will change your syntax highlighting color scheme, you can now tweak it with `@code-color`, have fun.


<a name="0.0.7"></a>
## [0.0.7](https://github.com/sparanoid/amsf-curtana/compare/v0.0.6...v0.0.7) (2015-10-17)


### Features

* **style:** remove abbr styles ([1ced313](https://github.com/sparanoid/amsf-curtana/commit/1ced313))
* **style:** tweak default code color ([d1471a5](https://github.com/sparanoid/amsf-curtana/commit/d1471a5))
* **template:** add `mask-icon` support for Safari ([aaa76b8](https://github.com/sparanoid/amsf-curtana/commit/aaa76b8))
* **template:** add modified date support ([93309fa](https://github.com/sparanoid/amsf-curtana/commit/93309fa))
* **template:** use `user.less` and `user.js` ([f9f5503](https://github.com/sparanoid/amsf-curtana/commit/f9f5503))
* **template:** use variable for mask-icon color ([952357d](https://github.com/sparanoid/amsf-curtana/commit/952357d))



<a name="0.0.6"></a>
## [0.0.6](https://github.com/sparanoid/amsf-curtana/compare/v0.0.5...v0.0.6) (2015-09-27)


### Bug Fixes

* **styles:** accidentally reset styles to previous version ([738faa8](https://github.com/sparanoid/amsf-curtana/commit/738faa8))

### Features

* **style:** better fontstack variables ([80430fc](https://github.com/sparanoid/amsf-curtana/commit/80430fc))
* **styles:** add `.screenshot-mac` helper class ([7444196](https://github.com/sparanoid/amsf-curtana/commit/7444196))
* **styles:** update font stack order ([84abf4f](https://github.com/sparanoid/amsf-curtana/commit/84abf4f))
* **styles:** update text decoration ([68e4e17](https://github.com/sparanoid/amsf-curtana/commit/68e4e17))
* **template:** disable language tag for post list ([fbc3e37](https://github.com/sparanoid/amsf-curtana/commit/fbc3e37))


### BREAKING CHANGES

* You have to double check if you're overriding `@sans-serif`, `@serif`, or `@monospace` to use custom fontstacks, these variables have been changed to `@fontstack-sans-serif`, `@fontstack-serif`, and `@fontstack-monospace`.


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


