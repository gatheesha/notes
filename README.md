---

title: Introduction

type: docs

---
# 🧠 gaths-notes vault  
**LOOKING FOR CONTRIBUTORS**

Welcome to **gaths-notes**, a personal and **collaborative knowledge base** built with Obsidian. This repository contains well-organized academic notes designed for students following the **BICT program at the Faculty of Technology, University of Sri Jayewardenepura**. 

A website version of this vault generated with hugo is also available for easier browsing.

🌐 **Website:** https://gatheesha.github.io/notes/

## Purpose
This project serves as a digital second brain — a structured and detailed archive of notes and coursework.
- University coursework and notes for each module
- Productivity workflows using Obsidian, Hugo, Git, and CI integration with GitHub Actions

The goal is to create a high-quality, cross-linked resource for study, review, reference, and sharing.

## Contributing to Notes Vault
Pre-requisites: Markdown editor of your choice, [Obsidian](https://obsidian.md/) is recommended and [Git](https://git-scm.com)

To contribute:

- Clone the repository:

   ```bash
   git clone https://github.com/gatheesha/gaths-notes.git
   ```

- Open the `content/` directory as an Obsidian vault.

   > (Still looking for a way to rename the vault internally without changing the folder name.)

- Follow the existing folder structure. Add new folders for new modules or update existing ones.

- Use Obsidian-flavored Markdown. Add YAML frontmatter if needed.

- Templates are available in the `templates/` directory:
   - `template-_index.md`: for module overview/index pages
   - `template-lecture.md`: for lecture note pages

- Ensure consistency in formatting, headings, and tags. Use Obsidian backlinks where helpful.

- Commit your changes and submit a pull request with a clear description.

> Notes should be fact-checked and cited if they are based on lectures, textbooks, or other academic sources.

## Contributing to the Website
Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/)(Extended), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/gatheesha/gaths-notes.git

# Change directory
cd gaths-notes

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

- The static website is built using [Hugo](https://gohugo.io/) with the [Hextra theme](https://imfing.github.io/hextra/).

- Modify content under the root or `content/` directory as needed. Use `_index.md` files for section overviews.

- Do **not** modify the `public/` directory — it is auto-generated.

- Commit your changes and open a pull request.

- For theme-specific changes or custom layouts, refer to the [Hextra documentation](https://imfing.github.io/hextra/docs/).

## Useful Links

- [Obsidian](https://obsidian.md/)
- [Hugo](https://gohugo.io/)
- [Hextra Theme](https://imfing.github.io/hextra/)
- [Markdown Guide](https://www.markdownguide.org/)

## License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this project with attribution.

## Todo List

### Website

- [x] Update README
- [ ] Add root index page
- [ ] Add `_index.md` files for modules
- [ ] Fix image and asset handling
- [ ] Hide `templates/` from navigation
- [ ] Refactor folder structure

### Notes

- [ ] Software Engineering 1 - Week 0
- [ ] Software Engineering 1 - Week 1
- [ ] Fundamentals of Programming - Week 0
- [ ] Fundamentals of Programming - Week 1
- [x] Computer Organization and Architecture - Week 0
- [ ] Computer Organization and Architecture - Week 1
- [ ] Mathematics 1 - Week 0
- [ ] Mathematics 1 - Week 1
- [ ] Statistics - Week 0
- [ ] Statistics - Week 1
- [ ] Physics - Week 0
- [ ] Physics - Week 1

### Miscellaneous (To be Confirmed)

- [ ] Communication Skills - Week 0
- [ ] Communication Skills - Week 1
- [ ] Ethics - Week 0
- [ ] Ethics - Week 1

> Made with ❤️ by Gatheesha Nipulma and J'pura contributors.  
Thank you for helping make knowledge open and accessible!
