# slovak-holidays

This package adds [slovak](http://en.wikipedia.org/wiki/Slovakia) holidays to the Emacs calendar.

If you have `org-agenda-include-diary` set to `t`, these will be also listed in the `org-agenda` view.

# Installation

After loading the package, add a call to `(slovak-holidays-add)` somewhere into your `.emacs`.  Note that this must be called *before* Emacs calendar is loaded.

A sample configuration using `use-package`:

``` emacs-lisp
(use-package slovak-holidays
  ;; :ensure t     ; if using package.el
  ;; :straight t   ; if using straight.el
  :config (slovak-holidays-add))
```
