# software-notes

## Mac operating system
* [iTerm2](https://iterm2.com/): A better alternative to Terminal on mac.
  * [How to set custom shortcuts in iTerm2](https://stackoverflow.com/questions/6205157/iterm-2-how-to-set-keyboard-shortcuts-to-jump-to-beginning-end-of-line).
* [How to add a folder to favourites (at the top-left sidebar) in finder?](https://discussions.apple.com/thread/7160416)

## Latex
* Bibliography
  * Example
    ``` latex
    % inside header
    \usepackage[backend=biber, bibstyle=numeric, sorting=none, natbib=true, defernumbers=true, url = false, maxbibnames=999, giveninits=true, uniquename=false, date=year, isbn=false]{biblatex}
    \addbibresource{mypapers.bib}

    % inside document
    \printbibliography[title=References]
    ```
  * [Bibliography style](https://www.overleaf.com/learn/latex/biblatex_bibliography_styles)
  * [Citation ordering](https://tex.stackexchange.com/questions/51434/biblatex-citation-order)
  * [Highlight specific authors](http://www.hansenlab.org/cv_bibliography_tex)\
  Note-1: This solution requires author annotation in the bibtex entry. I did not find a good way to annotate authors and then export bibtex entries in Mendeley.\
  Note-2: In case of _authoryear_ (e.g. _Saha et al. 2020_) citation, highlighted author names are bolded in the main text too (e.g. _**Saha** et al. 2020_), which is annoying. Numeric citation seems appropriate.
