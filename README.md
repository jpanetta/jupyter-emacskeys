## Emacs-style keybindings for Jupyter notebook

This Jupyter notebook extension provides emacs-style key bindings
for navigation within cells (Ctrl-A, Crtl-E, Ctrl-W, Ctrl-D, Ctrl-K,
Ctrl-Y).

### Installation
```
pip install jupyter-emacskeys
```

JP: I couldn't get `pip3 install -e .` to work, but the following did work:
```
python3 setup.py build
python3 setup.py install --user
```

### Requirements
- jupyter notebook v4 or later
