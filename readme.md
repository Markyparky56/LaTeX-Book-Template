# $\LaTeX$ Book Template

Memoir-based latex document, styled for long-form writing

## Recommended Setup

This template should work with any latex setup, in theory, but has only been tested with MikTex on Windows 10, with editing performed within VS Code using the latex-workshop extension.

With that in mind, install:

1. [MikTex](https://miktex.org/download)
2. [VS Code](https://code.visualstudio.com/)

The recommended VS Code Extensions are:
1. LaTeX Workshop
2. LaTeX language support
3. LaTeX Utilities
4. Spell Right
5. LTeX (potentially abandoned, keeping an eye on [neo-ltex](https://github.com/neo-ltex/vscode-ltex))

If you pay for Grammarly, you can get _mostly_ functional support via the (unofficial) Grammarly extension. But Grammarly has slated the API for shutdown, so it may stop working at any time. Otherwise, you will have to copy your chapters in/out of the Grammarly web app. This isn't as painful as it used to be, but it can still get confused by the LaTeX syntax sometimes; it's not perfect. I've been curious about trying ProWritingAid for a while now.

## How does this work?

First, clone or fork the repository. You can hide it behind a private repository to backup your work without everyone being able to read your work-in-progress writing.

With MikTex install and LaTeX Workshop installed, open the repository folder in VS Code. To test it works, open _book.tex_ then select the $\TeX$ icon in the sidebar. LaTeX Workshop can take a few seconds to boot up, depending on your other extensions and how laboured your PC is. Select Build LaTeX project from the command list that should have opened. In the bar at the bottom of the screen you should see a little icon saying it's building. If this is the first time you've tried to build a latex document you may have a few pop-ups from MikTex asking to install packages. Okay these, and you can tell it to always install missing packages if you're a trusting person.

If everything goes well you should now have a _book.pdf_ sitting next to _book.tex_. Congrats! 

You can now rename _book.tex_ to whatever you want to call your book, throw away the dummy chapters, and begin writing your own stories!

_book.tex_ is just one way to structure your book. Additional styling is entirely up to you. I am no LaTeX wizard so will leave that up to you to explore. I have only included what I found useful to structure my novel while drafting it. 
