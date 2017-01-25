# flycheck-dogma [![MELPA](https://melpa.org/packages/flycheck-dogma-badge.svg)](https://melpa.org/#/flycheck-dogma)

[flycheck][] checker for [dogma][].

## Installation

You can install this package from [Melpa][]

```
M-x package-install RET flycheck-dogma RET
```

## Usage

Ensure that `dogma` is installed in your project.

Then, in your `init.el`:

```elisp
(eval-after-load 'flycheck
  '(flycheck-dogma-setup))
(add-hook 'elixir-mode-hook 'flycheck-mode)
```

## Thanks

* [@lpil][] for [dogma][].
* [@lunaryorn][] for [flycheck][].

[flycheck]: http://www.flycheck.org/
[dogma]: https://github.com/lpil/dogma
[@lpil]: https://github.com/lpil
[@lunaryorn]: https://github.com/lunaryorn
[Melpa]: http://melpa.milkbox.net/
