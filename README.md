# GitHub Workshop 2026 CSS TAR UMT

This is a demo repository for **GitHub Workshop 2026**, hosted by **Computer Science Society TAR UMT**.

This repository is used as a reference to show how a `README.md` file can be written properly using **Markdown** and simple **HTML**.

---

## What is a README?

A `README.md` file is usually the first page people see when they open a GitHub repository.

A good README helps people understand:

* What the project is about
* How to install or run the project
* What features are included
* Who contributed to the project
* Where to find important files or releases

---

## 1. Markdown Headings

Markdown uses `#` symbols to create headings.

```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

Example:

# Heading 1

## Heading 2

### Heading 3

---

## 2. Text Formatting

Markdown can be used to format text easily.

```md
**Bold text**

*Italic text*

~~Strikethrough text~~

`Inline code`
```

Example:

**Bold text**

*Italic text*

~~Strikethrough text~~

`Inline code`

---

## 3. Lists

### Unordered List

```md
- Create repository
- Create branch
- Create pull request
- Merge pull request
```

Example:

* Create repository
* Create branch
* Create pull request
* Merge pull request

### Ordered List

```md
1. Create a repository
2. Add project files
3. Commit changes
4. Push to GitHub
```

Example:

1. Create a repository
2. Add project files
3. Commit changes
4. Push to GitHub

---

## 4. Links

You can add links using Markdown.

```md
[Visit GitHub](https://github.com)
```

Example:

[Visit GitHub](https://github.com)

---

## 5. Images

Images can be added using Markdown.

```md
![TAR UMT Intranet Background](https://www.tarc.edu.my/assets/css/images/bg3.jpg)
```

Example:

![TAR UMT Intranet Background](https://www.tarc.edu.my/assets/css/images/bg3.jpg)

> Recommended folder structure:

```txt
github-workshop-2026/
├── README.md
├── assets/
│   └── workshop-banner.png
└── src/
```

---

## 6. Tables

Tables are useful for showing project information clearly.

```md
| Topic | Description |
|---|---|
| Repository | A place to store project files |
| Branch | A separate version of the project |
| Pull Request | A request to merge changes |
| Release | A published version of the project |
```

Example:

| Topic        | Description                        |
| ------------ | ---------------------------------- |
| Repository   | A place to store project files     |
| Branch       | A separate version of the project  |
| Pull Request | A request to merge changes         |
| Release      | A published version of the project |

---

## 7. Code Blocks

Use code blocks to show commands or source code.

### Example: Git command

```bash
git status
git add .
git commit -m "Update README"
git push
```

### Example: HTML code

```html
<h1>Hello GitHub</h1>
<p>This is written using HTML.</p>
```

---

## 8. Task Lists

Task lists are useful for tracking project progress.

```md
- [x] Create repository
- [x] Add README
- [ ] Create branch
- [ ] Open pull request
- [ ] Create release
```

Example:

* [x] Create repository
* [x] Add README
* [ ] Create branch
* [ ] Open pull request
* [ ] Create release

---

# Using HTML in README

GitHub README also supports some basic HTML. This is useful when Markdown is not enough.

---

## 9. Center an Image using HTML

```html
<p align="center">
  <img src="https://www.tarc.edu.my/assets/css/images/bg3.jpg" alt="" width="600">
</p>
```

Example:

<p align="center">
  <img src="https://www.tarc.edu.my/assets/css/images/bg3.jpg" alt="" width="600">
</p>

---

## 10. Resize an Image

Markdown does not directly support image resizing, so HTML is useful here.

```html
<img src="https://www.tarc.edu.my/assets/css/images/bg3.jpg" alt="" width="200">
```

Example:

<img src="https://www.tarc.edu.my/assets/css/images/bg3.jpg" alt="" width="200">

---

## 11. Dropdown Section using HTML

The `<details>` tag can be used to hide and show extra information.

```html
<details>
  <summary>Click to view GitHub workflow</summary>

  1. Create a branch  
  2. Make changes  
  3. Open a Pull Request  
  4. Review changes  
  5. Merge into main  

</details>
```

Example:

<details>
  <summary>Click to view GitHub workflow</summary>

1. Create a branch
2. Make changes
3. Open a Pull Request
4. Review changes
5. Merge into main

</details>

---

# Example Assignment README Template

Students can use this structure for their own assignment project.

```md
# Project Name

## Project Description

Briefly explain what the project is about.

## Features

- Feature 1
- Feature 2
- Feature 3

## Technologies Used

- HTML
- CSS
- JavaScript
- GitHub

## Installation

Explain how to install or set up the project.

## Usage

Explain how to run or use the project.

## Screenshots

Add screenshots of the project here.

## Team Members

| Name | Role |
|---|---|
| Student A | Project Leader |
| Student B | Developer |
| Student C | Documentation |

## Release

The final version of this project can be downloaded from the GitHub Releases section.
```

---

# Good README Tips

A good README should be:

* Clear and easy to read
* Not too empty
* Not too messy
* Updated when the project changes
* Useful for both team members and lecturers

---

# Practice Activity

Try to edit this README by adding:

* Your name
* One image
* One table
* One code block
* One task list
* One HTML image with custom width

After editing, commit your changes and create a Pull Request.
