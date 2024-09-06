![version](https://img.shields.io/static/v1?label=emacs4oscer/&message=0.2&color=brightcolor)
[![license: mit](https://img.shields.io/badge/license-mit-blue.svg)](https://opensource.org/licenses/mit)


# Emacs init.el for the Schooner Supercomputer at the University of Oklahoma

## Introduction

This configuration file has several features, including line numbers, syntax highlighting, and support for code snippets.
It also supports writing in LaTeX via the AUCTeX package.
It uses Prot's EF-themes package by default.

## Why use this approach

The default version of Emacs on Schooner is too old to support the current version of yasnippets.
This is the most popular package for managing code snippets in Emacs.
It is hard to work in Emacs without it.

The current major release of Emacs is now available in Anaconda.
Anaconda makes installing Emacs on remote machines a breeze.
I installed Emacs version 29 using Mamba in January 2024.

## Precaution

Please keep your Emacs use while working in a login node.



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

## Tramp
You can always do lightweight editing of files on schooner with your local Emacs by logging in with the tramp package in Emacs.


## Update history

|Version      | Changes                                                                      | Date                 |
|:-----------:|:----------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |   Added funding and update table. Med extensive edits of the README.md file. | 2024 September 6     |



## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH: P20 GM103640 and P30 GM145423 (PI: A. West)


