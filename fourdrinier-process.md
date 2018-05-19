# Fourdrinier Process

Notes on the entire idea-to-paper pipeline, as perceived by a low-level goblin (grad student).

### Results Procedure
1. Pray to the Supervisor for an idea. Or, if you're feeling bold enough, come up with one.
2. Before anything else, do a literature search about the idea. If it exists, return to step 1. Repeatedly revisit this step, in case you do stumble upon the same idea.
3. Iterate only on the datasets that you'll be dealing with, or at least close proxies. For example, do not iterate on CIFAR-10, hoping that the same techniques will surely apply to neural language modeling. Instead, opt for a smaller subset of the same dataset, or datasets within the same task (e.g., PTB instead of WikiText-103 for language modeling).
4. [Use the wastebasket](https://terrytao.wordpress.com/career-advice/use-the-wastebasket/): If an idea fails repeatedly and you've milked it dry, either adjust the idea or return to step 1.

### Writing Procedure
1. Get the actual results--depending on the paper, this step generally takes the longest.
2. A bit before the final results arrive, draw mockups for the result tables and charts to commit yourself to the story.
3. In the following order, write the results, discussion, methodology, background and related work, and conclusion sections, leaving the [introduction for last](https://github.com/lintool/guide/blob/master/writing-a-research-paper-with-me.md).
4. Revise the paper: At this stage, the Supervisor will chew up your terrible writing multiple times, and leave a Red Ink Sea in His or Her wake. You must address all of their comments.
5. Submit and start preparing for the next paper.

### Content
#### Introduction and Abstract
- At least briefly, justify each and every claim, even if it seems to "make sense" to you. You must make sure it makes sense to the Guardians of the Galaxy (reviewers).
- State the most appealing result in the abstract and introduction.
- **Sell** the idea--make the reviewers care about your damn problem.
- Use the opening paragraphs of the introduction to state the problem, declare its importance, and relate it to your sub-topic, e.g., smart software keyboards to neural networks to neural language models--with justifications along the way. Ease the introduction into your specific approach, and finish off with the contribution statement.
- A contribution is becoming the first to achieve an important task, be it application or theory. Merely doing something is **not** a contribution. For example, "first to evaluate 1 + 1" is a contribution statement--"evaluating 1 + 1" is not.

### Fluency
- Use bullet points and paragraph headers precisely. Whenever they don't seem to fit, work textual constructs like these into prose.
- Use paragraph headers for small groups of parallel ideas. For slightly larger groups, use subsections.

### Formatting
#### Text
- Get rid of orphan lines, e.g., "The quick brown fox jumped over the lazy\n**dog.\n\n**"
- Use `{\smallskip \noindent \bf <paragraph header>}` for formatting paragraph headers.
- Footnotes go after the end of the sentence.
#### Tables
- `booktabs` is great for making tables.
- Favor short captions with descriptions in prose over long captions.
- On every page, place tables at the top, followed by other figures, then text.

### Useful Resources
- [Supervisor's Guide to the Galaxy](https://github.com/lintool/guide)
