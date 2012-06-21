Flask Sphinx Themes
===================

This repository contains sphinx styles for CDNZZ related projects doc base on <a href="https://github.com/mitsuhiko/flask-sphinx-themes">flask-sphinx-themes</a>. To use this style in your Sphinx documentation, follow
this guide:

1. put this folder as _themes into your docs folder.  Alternatively
   you can also use git submodules to check out the contents there.
2. add this to your conf.py:

   sys.path.append(os.path.abspath('_themes'))
   html_theme_path = ['_themes']
   html_theme = 'flask'

