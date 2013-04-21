[company-mode](http://company-mode.github.io/) completion back-end for CMake
scripts.

Installation
===

Install this from [Marmalade](http://marmalade-repo.org/) or [MELPA](http://melpa.milkbox.net/).

Then, in addition to the usual `company-mode` setup, add this to your init file:

```
(eval-after-load 'company
  '(add-to-list 'company-backends 'company-cmake))
```
