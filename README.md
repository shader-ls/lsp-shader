[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/lsp-shader.svg)](https://jcs-emacs.github.io/jcs-elpa/#/lsp-shader)

# lsp-shader
> LSP Clients for ShaderLab

[![CI](https://github.com/shader-ls/lsp-shader/actions/workflows/test.yml/badge.svg)](https://github.com/shader-ls/lsp/actions/workflows/test.yml)

## 💾 Quickstart

```elisp
(use-package lsp-shader
  :ensure t
  :hook (text-mode . (lambda ()
                       (require lsp-shader)
                       (lsp))))  ; or lsp-deferred
```

## 🔧 Configuration

`lsp-shader` supports following configuration. Each configuration is described
in detailed in [shader-ls Settings](https://github.com/shader-ls/shader-language-server#-settings).

- `ShaderLab.CompletionWord` via lsp-shader-completion-word

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone or make pull requests to this repository. Or you can
clone the project and establish your branch of this tool.
Any methods are welcome!
