# Emacs Major Mode for Handlebars

Based on mustache-mode https://github.com/mustache/emacs

## Installing

In your shell:

    cd ~/.emacs.d/vendor
    curl --location -O https://raw.github.com/danielevans/handlebars-mode/master/handlebars-mode.el

In your Emacs config:

    (add-to-list 'load-path "~/.emacs.d/vendor/handlebars-mode.el")
    (require 'handlebars-mode)
