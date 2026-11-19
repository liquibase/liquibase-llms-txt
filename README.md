# Liquibase documentation for LLMs

This repository holds the Liquibase documentation as plain Markdown. Use it when you want an LLM, coding assistant or other AI tool to answer questions from the Liquibase docs.

The content is the same as the published documentation at [docs.liquibase.com](https://docs.liquibase.com). Nothing here is added, removed or rewritten for AI use. Each file is one page of the site.

## What is in this repository

- **`llms.txt`**: An index of the pages in this repository, with a link and a one-line description for each, following the [llms.txt](https://llmstxt.org) convention.
- **`index.md`**: The documentation home page.
- **Version folders**: Pages are organized by product, then version, then section. For example, the pages under https://docs.liquibase.com/secure/release-notes-5-2-2 are in `secure/5.2.2/release-notes/`. Find the version you use and work down from there. Each version folder has its own `llms.txt` listing only that version's pages.

The repository starts with the home page. More pages are added over time.

Each page begins with YAML frontmatter. The `url` field is the page's full address on docs.liquibase.com, such as `https://docs.liquibase.com/secure/release-notes-5-2-2`, so you can open the page on the site from any file. The `updated` field is when the page last changed.

## How to use it

- **Point a tool at the index.** Give your assistant the raw `llms.txt` at `https://raw.githubusercontent.com/liquibase/liquibase-llms-txt/main/llms.txt` and let it follow the links.
- **Add the files to your context.** Clone the repository and add the folder, or the pages you need, to your assistant's workspace or knowledge base.
- **Use the site-wide index for everything else.** For pages not yet in this repository, start from the curated index at [docs.liquibase.com/llms.txt](https://docs.liquibase.com/llms.txt).

When an answer matters, check it against the page on docs.liquibase.com. The `url` in each file's frontmatter takes you there.

## Keeping up to date

The files update automatically when the documentation is published, so pull regularly to stay current. Pull requests are not accepted, because any change here would be overwritten by the next update. To report a problem with the content, [open an issue](https://github.com/liquibase/liquibase-llms-txt/issues).

## License

Liquibase documentation is © Liquibase, Inc. It is published here for reference and for use with AI tools.
