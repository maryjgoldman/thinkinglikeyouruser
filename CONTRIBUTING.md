# Contributing to Thinking Like Your User

Thanks for helping make _Thinking Like Your User_ better! This guide is for busy scientific software developers, and it gets better every time someone tells us what worked, what didn't, and what's missing.

You don't need to be a UX expert to contribute. Some of the most useful feedback comes from folks who are new to UX.

## Ways to contribute

### Tell us how it went

Tried something from the guide? We'd love to hear what you tried and what happened, even if it didn't work out. Fill out the [4-question feedback form](https://docs.google.com/forms/d/e/1FAIpQLSeXgPqSMPzVHtSN2SO8_KGXazvpAF37zTXsCiUuQG1GHUnDmg/viewform?usp=sharing&ouid=103269107596360137668). It takes about 2 minutes.

### Open an issue

[Open an issue](https://github.com/maryjgoldman/thinkinglikeyouruser/issues/new) if you:

* Found a broken link, typo, or something confusing
* Think a topic is missing
* Have a resource, paper, or example that would fit the guide
* Disagree with something and want to talk it through

Please include the page you're talking about and, if you can, a sentence or two on why it matters for you or your users.

### Suggest a change with a pull request

For small fixes like typos or broken links, feel free to open a pull request directly. For bigger changes, such as a new page or section, please open an issue first so we can talk about whether it fits before you spend time writing it.

## What fits in the guide

Before you suggest new content, it helps to know what the guide is and isn't trying to be (see [Before you begin](docs/before-you-begin.md)):

* **Quick, practical methods.** Things a busy developer can do with little time, few resources, and little training.
* **Mostly GUI tools.** UX applies to APIs, CLIs, and documentation too, but the guide focuses on graphical interfaces.
* **Not comprehensive.** We'd rather cover a few methods well than every method briefly. Linking out to good resources is often better than adding a new section.

## Style guide

* **Friendly and informal.** Write to the reader as "you." Short sentences and plain language please.
* **Sentence-case headings.** For example, "Making a design," not "Making a Design."
* **Guide title.** Write it as _Thinking Like Your User_, in italics.
* **AI notes.** Advice that depends on current AI tools goes in an info box with the month and year, so readers know how fresh it is:

  ```markdown
  {% hint style="info" %}
  AI note (Month Year): Your note here.
  {% endhint %}
  ```
* **Spelling.** Use "skillset" (one word) and "GitHub" (capital H).
* **Links.** Link to other pages with relative paths to the `.md` file, such as `[Making a design](making-a-design.md)` or `[Surveys](researching-your-users/researching-your-users-without-talking-to-them.md#surveys)`.

## How the repository works

This guide is published with [GitBook](https://www.gitbook.com/), which syncs with this repository.

* **Only the `docs/` folder is published.** Files at the repository root, like this one, `README.md`, and `AGENTS.md`, don't appear on the site.
* **New pages need to be added to `docs/SUMMARY.md`**, which controls the site's table of contents.
* **Don't remove GitBook formatting.** Keep the frontmatter at the top of some pages (the `---` block), `{% hint %}` blocks, and the `&#x20;` characters GitBook adds at the end of some lines.
* **Commits titled `GITBOOK-<number>`** come from edits made in the GitBook editor. If your pull request touches the same lines, you may need to update it after the latest GitBook sync.

## License

_Thinking Like Your User_ is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE.md). By contributing, you agree that your contributions will be licensed under the same terms.
