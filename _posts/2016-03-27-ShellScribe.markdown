---
layout: default
img: shell_scribe.png
category: Projects
title: ShellScribe
concepts: 
- Shell
- Scribe
description: |
---
ShellScribe (SS) is a developer tool that takes the pain out of documenting code.  The idea is that as developers are moving from Stack Overflow post to Stack Overflow post putting together their code it's very easy to lose track of what snippets do what, where they came from, who made them, etc.  SS aims to keep track of this by keeping tabs on what sites developers found useful and used code from.  SS will run in the background on the user's computer, and if the user finds something useful, they can open up an SS shell and input the site they took code from and a brief description on what it was, and SS, together with Sphinx, will format this input as clean, professional documentation.  Further enhancements on this project could be made to auto-detect usual code copying actions (user opens Stack Overflow page/copies text from a page and pastes it in a text editor), and this sort of action would automatically fire SS's document builder that will attempt to build a description based on a site's meta data/the text that was taken.