# linux-emacs-setup

My current Emacs setup. Based on  the following excellent article:
http://tuhdo.github.io/c-ide.html

Setup:
Everything should install autmatically upon opening emacs. Currently requires making a separate custom/setup-computer-specific.el file, it should look something like:

(defconst local-python-path "/path/to/desired/python interpreter")

(provide 'setup-computer-specific)
