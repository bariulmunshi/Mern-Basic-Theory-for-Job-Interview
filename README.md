#  Table of content
- [Basic understanding MERN](#basic-understanding-mern)
- [project]()
   -  [project-1]
- [custom CSS{var(--root name can be any css style)}](#custom-css)
- [gap properies](#gap-properties)
- [Git and Github](#git-and-github)
  - [Difference Between Git Vs GitHub](#difference-between-git-vs-github)
  - [Git and GitHub Basic QA](#git-and-github-basic-qa)

# custom CSS
```sh
   custom CSS{var(--root name can be any css style)} 

  `Example`
  step 1::root {
            --primary-color: green;
            --secondary-color: red;
            --single-border: 2px solid blue;
        }
  step 2::color: var(--primary-color) or border-bottom: var(--single-border) or background-color: var(--primary-color); 
  background-color: var(--secondary-color);

  step 2:: for better understanding
  h1 {
            color: var(--primary-color)
        }
```

# box shadow
```sh
css style :box-shadow: 0px 6px 50px 0px rgba(0, 0, 0, 0.06);
```

# gap properties
```sh
 .container {
  display: flex;
  ...
  gap: 10px;
  gap: 10px 20px; /* row-gap column gap */
  row-gap: 10px;
  column-gap: 20px;
}
```

# Git and GitHub
## Difference between Git vs GitHub
| Option |  Git      | GitHub    |
| -----------   | ------------- | -------- |
| 1. purpose   | source code management       |  code store/code hosting platform for version control and collaboration.  |
| 2   | Test2         | Toronto  |
## Git and GitHub Basic QA
- What is the main purpose of git branching? 
 ```sh
  Separate a small feature from the main code.
 ```
- Which Command is used to check the list of branches?
 ```sh
  > git branch
 ```
- Which command will you use to create a new branch named new-branch?
 ```sh
  >git checkout -b new-branch
 ```

# Basic understanding MERN
- Optimize images for better loading(photopea,adobe-photoshop,tinypng), types of images {svg(scale-able),GIF(animation) png, jpg,jpeg
(colorful),webp(fast-loading),iso(icon), Sprite(use game developers),}  
- CSS Overflow (overflow-x: hidden;), ellipsis(tooltip:title,white-space: nowrap; & overflow: hidden;)
- visibility(display: none; visibility: hidden; )
- width: calc(100% - 200px); height: calc(100% - 200px);
