# Notes for the Metagenomics and Amplicon Sessions at the masters in plant breeding (CIHEAM)

## Authoring
To edit the materials, you can just add/edit Markdown files (using normal markdown or [Quarto flavoured Markdown](https://quarto.org/docs/authoring/markdown-basics.html)) in the `sessions/` directory.

To preview your changes, you need to [install Quarto](https://quarto.org/docs/get-started/).

And run `quarto preview .` in this directory.

### Callout blocks
Quarto supports [callout blocks](https://quarto.org/docs/authoring/callouts.html) to make certain text stand out.
There are defaults like "tip", "note", "warning".
We also have custom callouts for "step" and "question". 
They can be used like this:

````markdown
# A section
This is some ordinary text.
::: {.callout-tip}
This is a tip
:::

::: {.callout-tip}
# Hint!
This is a tip with a custom title
:::

::: {.callout-step .callout-tip}
# Run MultiQC
This is a special "step" callout detailing what the participant should do next,
e.g.
```bash
run --some --code
```
:::

And finally
::: {.callout-question .callout-tip}
This is a question the participant should think about?
:::

````
