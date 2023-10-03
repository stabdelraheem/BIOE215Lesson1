#### Bryan 2017

-   What problems can `setwd()` cause in your scripts and how do RStudio projects address them?

    -   Scripts are not "self-contained" nor "portable". For collaborators who are trying to run code on their machines, scripts will not work if the code references files and folders that exist on the creator's original machine unless the collaborator goes in and manually changes each file path. This even applies to the original creator of a script if they use a new computer, update the machine, or just exist.

-   When you call `rm(list=ls())`, what is removed from your environment?

    -   Objects from your environment (i.e. dfs that you run in a session).

-   What's left over that restarting your R session would remove?

    -   Any packages that were called with `library()`, any options that were set (i.e. `sringsAsFactors = TRUE/FALSE`).

-   What's the keyboard shortcut for restarting your R session?

    -   `Cmnd + shift + 0`

#### Bryan 2018

-   The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? Which happen remotely?

    -   Commit occurs locally. Push and Pull happen remotely.

-   Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)?

    -   Word and excel documents are binary files that are stored as a set of files on your computer that is then processed and displayed for the user using a GUI, and is therefore human-readable. Source code files (i.e. .txt, .md, .html, .Rmd, .csv) are smaller text files in which information is stored and configured much more simply. Although text files don't exist in a format that is "casually" readable, they are important and easier to track diffs than in large binary files.

-   Why is Markdown useful for GitHub repos?

    -   Markdown is a lightweight markup language that uses HTML conventions. The `index.md` file, if updated regularly, can serve as a homepage for a code project on GitHub with minimal effort to create auxiliary pages and structures. R Markdown also includes chunks of code embedded in explanations and is a great way to create interactive code projects that walk a user through beginning to end.
