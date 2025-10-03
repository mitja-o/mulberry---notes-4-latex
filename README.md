# 🍓 mulberry notes ~ notes, todo's and more for LaTeX

> [!NOTE]
> Mark your TODO's and other notes in the LaTeX document, with a subjective style.
>
> - Make your manuscript annotations eye catchy like a berry in a forest 🫐.

This package is tailored for my subjective way of leaving notes in LaTeX documents.   
It aims at simplicity, author traces, and visual clues. 

Feel free to try it out and use it if you like it!

## Getting started

```tex
% Enable the marks
\usepackage{mulberry-notes}

% This will hide all the marks, useful for final manuscript views
% \usepackage[hidden]{mulberry-notes}

\begin{document}

Hey there!
\todoM{Make a better introduction} 
Welcome to the mulberry todo marks.

\noteM{This is just a note.}

\end{document}
```

<!-- TODO: add a preview -->


## Features

The feature set is very basic but keeps expanding and open for new ideas.  

See all available features in the [documentation](./mulberry-notes-manual.md).

### Adding new features

The core principle: 
  - **_keeping it simple_** (to develop and use).
    - also, I try not to use external dependencies (to keep this package as free from interferences as possible). 

> [!IMPORTANT]
> Feel free to submit feature requests as issues or PRs! 😊

## Inspiration

With huge thanks for inspiration from 

- [`zebra-goodies`](https://github.com/xueruini/zebra-goodies)

<!-- TODO: extend the list -->

