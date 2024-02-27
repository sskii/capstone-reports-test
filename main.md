# Hello, world

You can download a PDF version of the Markdown you commited and pushed by clicking the check icon next to the commit name, clicking through to the tick section, switching to the 'Summary' view in the sidebar, scrolling down to the 'Artifacts' section, and downloading the generated file `render.pdf`.[^1]

[^1]: In future it may be more convenient to set the action up to commit directly to the repo, but this will do for a demo.

## Trying this out

Feel free to push test commits to try this out. The action responds to pushes on any branch, so feel free to create your own.

## Why Markdown?

Because all our work is stored in plain text and supporting files, Git (which we have to use anyway) works wonders for version control. Keeping all of our collaboration in one place should make things quicker. Having a cached PDF for every commit means that we will be able to recover from any mistakes much more readily, useful when deadlines eventually loom.

Because the GitHub Action uses \LaTeX  as an intermediate step, we'll get all of its power without the verbose syntax and frequent errors. We will also be sure to always conform to the coordinators' template, something they seem particularly picky about in this course.

This workflow also frees each individual team member up to use their favourite Markdown editor for the job, or even to edit on the GitHub website directly.

All in all, we should hopefully not end up like the unfortunate fellow in \autoref{fig:notus}.

![Hopefully not any of us! \label{fig:notus}](https://thumbs.dreamstime.com/z/crying-man-modern-technology-26675651.jpg)