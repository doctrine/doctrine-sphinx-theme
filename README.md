This is the common Sphinx Theme for all Doctrine Project Documentations.

Use this by adding a submodule to your docs folder:

    git submodule add https://github.com/doctrine/doctrine-sphinx-theme.git _theme

Add this folder to the conf.py property:

    html_theme_dir = ['_theme']
