# Emacs init.el for the Schooner Supercomputer at the University of Oklahoma

## Introduction

This conifguration file has number of features including line numbers, syntax highlighting, and support for code snippets.
It also supports writing in LaTeX via the AUCTeX package.
It uses Prot's EF-themes package by default.
It works on Schooner as of September 2022 with Emacs version 28.2
I updated to Emacs vesion 29 using Mamba in January 2024.
I installed it its own conda environment.
Take care to keep your Emacs use lightweight while working in a login node.

The default version of Emacs on Schooner is too old to support the current version of yasnippets.

## .emacs.d

The default storage site for this file is `~/.emacs.d/init.el`.
Edit the path near the top of *init.el* if you use a different location.

## Organization of init.el

The `init.el` file has three sections:

- Configuration for the *package* package and the repositories of packages.
- Basic configuration without extra packages.
- Configuration of specific packages listed in alphabetical order.

## Subfolders in .emacs.d

I store my manually installed packages (e.g., git cloned from GitHub repos) in `~/.emacs.d/manual-packages`.
I store my snippets in `~/.emacs.d/snippets`.
