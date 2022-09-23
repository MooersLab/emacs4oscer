# Emacs init.el for the Schooner Supercomputer at the University of Oklahoma

This conifguration file has number of features including line numbers, syntax highlighting, and support for code snippets.
It also supports writing in LaTeX via the AUCTeX package.
It uses Prot's EF-themes package by default.
It works on Schooner as of September 2022 with Emacs version 28.2. 

I installed the latter via anaconda in my home directory.
The default version of Emacs on Schooner is too old to support the current version of yasnippets.

The default storage site for this file is `~/.emacs.d/init.el`.
Edit the path in near the top of init.el if you use a different location.

The file has three sections:

- Configuration for the *package* package and the repositories of packages.
- Basic configuration without extra packages.
- Configuration of specific packages listed in alphabetical order.

I store my manually installed packages (e.g., git cloned from GitHub repos) in `~/.emacs.d/elisp`.
I store my snippets in `~/.emacs.d/snippets`.
