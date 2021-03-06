### 0.3.6
* Upgrade highlight.js.
* Upgrade marked.
* Configure embedded languages for build in package.json.
* Update embedded languages:
  * javascript
  * ruby
  * python
  * bash
  * java
  * php
  * perl
  * cpp
  * objectivec
  * cs
  * sql
  * xml
  * css
  * scala
  * coffeescript
  * lisp

### 0.3.5
* Convert slide attributes, i.e. .attribute=value.
* Fix slide content overflow issue.
* Embed more slide and content classes; `.left`, `.center`, `.right`, `.top`, `.middle` and `.bottom`.

### 0.3.4
* Upgrade marked.
* Disable Github Flavored Markdown (GFM) to prevent autolinks, i.e. src attributes for img or iframe tags turning into links.

### 0.3.3
* Expose `config` function.
* Add support for `highlightLanguage` configuration option.
* Add support for `highlightInline` configuration option.

### 0.3.2
* Expose highlighter engine ([kjbekkelund](https://github.com/kjbekkelund)).
* Handle 0 to 3 spaces before # in headings ([kjbekkelund](https://github.com/kjbekkelund)).
* Support headings inside DIVs ([kjbekkelund](https://github.com/kjbekkelund)).
* Use marked instead of Showdown ([kjbekkelund](https://github.com/kjbekkelund)).
* Build remark using Node.js instead of Ruby.
* Run tests using Buster.js instead of Jasmine.

### 0.3.1
* Initial event support ([kjbekkelund](https://github.com/kjbekkelund)).
* Made remark.config a function accepting configuration options.
* Added support for multiple content classes on a single line.

### 0.3.0

* Input Markdown source element should now be of type TEXTAREA instead of PRE.
* Added proper escaping of in-code HTML.
* Made highlight.js styles work on inline code as well as block code.

### 0.2.4

* Made highlight style configurable through `highlightStyle` option.
* Added current slide number to slides.
* Disabled highlighting of inline code without language hinting.

### 0.2.3

* Added full highlight.js supporting a whole bunch of languages.

### 0.2.2

* Simple handling of swiping, e.g. for iPhones ([kjbekkelund](https://github.com/kjbekkelund)).

### 0.2.1

* Fixed non-working links via touch events.
* Fixed non-working resize ([kjbekkelund](https://github.com/kjbekkelund)).

### 0.2.0

* Added slide navigation using page up/down keys and mouse wheel.
* Added touch events in order to support mobile phones ([kjbekkelund](https://github.com/kjbekkelund)).
* Go to the next slide when pressing Space ([kjbekkelund](https://github.com/kjbekkelund)).

### 0.1.2

* Prepending instead of appending default styles to &lt;head&gt; ([kjbekkelund](https://github.com/kjbekkelund)).

### 0.1.1

* Fixed bug with markdown contained in content classes, i.e. `.class[![image](img.jpg)]`.

### 0.1.0

* Initial version.
