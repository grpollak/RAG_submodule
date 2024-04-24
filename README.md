# Table of Contents
1.  [RAG LaTeX submodule:](#org9a8bce7)
    1.  [Adding it as a submodule:](#org1532e58)
    2.  [Include the submodule into a LaTeX formularyETH:](#org3172ee7)
        1.  [In order to include figures add to graphicspath](#org3084e32)


# RAG LaTeX submodule:

Retrieval-augmented generation (RAG) and Agent Based Systems

## Adding this submodule to a LaTeX formulary:

    cd <path to formulary/folder>
    git submodule add git@github.com:grpollak/formularyETH.git/RAG_submodule.git

## Include the submodule into a LaTeX [formularyETH](https://github.com/git@github.com:grpollak/formularyETH.git):
``` tex
\section*{RAG Background}
    \input{RAG_submodule/RAG.tex}
```
### In order to include figures add to graphicspath
``` tex
\graphicspath{
    ...
    {RAG_submodule/figures/}
}
```

