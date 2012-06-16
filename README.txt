Art Bollocks Mode highlights those pesky weasel words that slip into
writing.

To add this to your Emacs:

(add-to-list 'load-path "/wherever/you/extracted/artbollocks-mode")
(require 'artbollocks-mode)
(add-hook 'text-mode-hook 'artbollocks-mode)
