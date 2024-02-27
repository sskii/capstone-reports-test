\tableofcontents

# Hello, world

You can download a PDF version of the Markdown you commited and pushed by clicking the check icon next to the commit name, clicking through to the tick section, switching to the 'Summary' view in the sidebar, scrolling down to the 'Artifacts' section, and downloading the generated file `render.pdf`.[^1]

[^1]: In future it may be more convenient to set the action up to commit directly to the repo, but this will do for a demo.

## Trying this out

Feel free to push test commits to try this out. The action responds to pushes on any branch, so feel free to create your own.

## Why Markdown?

Being a plain text format, Markdown is portable and plays well with Git. We have to use Git and GitHub anyway according to the manual, so keeping all of our collaboration in one place should make things more efficient.

Using an automated workflow to generate a PDF, the format required for our final deliverable, at regular intervals means we'll be able to recover from any mistakes more easily. This will be usefull when the deadlines eventually loom.

Perhaps the biggest advantage is that LaTeX is used as a backend, giving us a whole lot of functionality. We don't have to worry about its verbose syntax and frequent errors quite as much this way, but we still get automated section numbering, figure numbering, cross-referencing, the ability to include images by referencing files (not by copying them in), automated tables of contents, plotting functionality, and so forth. Importantly, our PDF will always conform to their prescribed template, which is something that the coordinators seem to be quite picky about, at least given what they've written in the coursebook.

A workflow also frees each individual team member up to use their favourite Markdown editor for the job, or even to edit on the GitHub website directly. All in all, we should hopefully not end up like the unfortunate fellow in \autoref{fig:notus}.

![Hopefully not any of us! \label{fig:notus}](https://thumbs.dreamstime.com/z/crying-man-modern-technology-26675651.jpg)

## Why it may be ill-advised

I can see that perhaps a shared Word doc might still be better, and that depends on the preference of the team. However, we're all ECSE, so a Markdown and GitHub workflow might suit us well. Yes, it's definitely overkill for the first deliverables, but these do present a good opportunity for everyone to give this a try.

The reports that we'll have to produce towards the end of the semester will be relatively more involved and will require images and plots and code snippets and the like. Having the ability to distribute the work between team members and have changes automatically cascade through to the final PDF might be worth the extra initial effort. We'll be able to work offline when needed. We'll be able to update a single image in the repo to update it in the final report, without having to delete it, drag and drop it back in, and then reformat it every single time. That's the end goal and the reason to consider a workflow like this despite the risks associated with a tool we're a little less familar with now.

# Tricks

Syntax highlighting comes for free.

```c
#include <stdint.h>

int main(void) {

	// code goes here

	return 0;
}
```