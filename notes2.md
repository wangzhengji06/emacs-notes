## Auto Indent

Select the region and use <Tab> to auto indent it.

## Find Package

C-h f to find the package where a function belongs. (help for functions)

```Lisp
(use-package display-line-numbers
  :ensure nil
  :hook
  ((text-mode . display-line-numbers-mode)
   (prog-mode . display-line-numbers-mode)))
```
