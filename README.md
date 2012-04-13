# Emacs Major Mode for Handlebars

Based on mustache-mode https://github.com/mustache/emacs

## Installing

In your shell:

    mkdir -p ~/.emacs.d/vendor
    cd ~/.emacs.d/vendor
    curl --location -O https://raw.github.com/danielevans/handlebars-mode/master/handlebars-mode.el

In your Emacs config (normally ~/.emacs):

    (add-to-list 'load-path "~/.emacs.d/vendor/")
    (require 'handlebars-mode)
