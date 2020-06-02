# Clojure Refactor from Ivy

Clone the repository:
```
cd ~/.emacs.d/site-packages
git submodule add https://github.com/wandersoncferreira/cljr-ivy
```

Add the package to your load path:

```elisp
(add-to-list 'load-path "~/.emacs.d/site-packages/cljr-ivy")
(require 'cljr-ivy)
```

This assumes you have a `site-packages` folder inside your `emacs.d`.

Now you need to bind the `cljr-ivy` command to some keybinding, I recommend:

`(global-set-key (kbd "C-c C-m")`

