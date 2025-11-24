---
layout: todo
title: To Do
categories: false
author: "Gary Newport"
date: "2025-10-08"
---

# Tasks
<details>
<summary>Land Registry Titles</summary>

- [ ] Title Service (Land Registry or Nimbus)
  - Still not heard anything from Al concerning Nimbus
    - [ ] If we go with Nimbus, which sounds likely as the cost is lower, we will have to rename the project.
    - [ ] If we change the title to a different name, we should investigate using multiple services, so we can support Scotland and Northern Ireland and any other country as they come along.
  - MyKf
    - [ ] Investigate how MyKf will save the data in the hub db
    - [ ] Investigate what MyKf will save in the database
    - [X] Talk to Katy to find out who is the developer
      - Rams Solaiappan
</details>
<details>
<summary>Quarto</summary>

- [ ] Quarto
  - [ ] Plantuml plugin
    - [X] [Diagrams are loaded from files source](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Any raw plantuml diagram ](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Created a LUA PlantUML filter for Quarto ](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Accepts a Puml file as a attribute](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Accepts inline PlantUML code](/Content/Current/posts/2025-10-14/index.qmd)
      - [X] Creates a local puml file if inline code is used
    - [X] [Renders the PlantUML diagram as SVG](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Renders puml files in the current directory.](/Content/Current/posts/2025-10-14/index.qmd)
    - [ ] Works with subdirectories
    - [ ] Direct where to store the generated SVG files
        - Quarto and LUA processing executes relative to the location of the .qmd file. So we will need a method to identify which directory we are in so we can then redirect the output files to a specified subdirectory.
    - [X] [Create a GitHub repo for the filter](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Publish to Quarto extensions](/Content/Current/posts/2025-10-14/index.qmd)
    - [X] [Document the filter as a journal entry](/Content//Journal/posts/PlantumlQuartoFilter/index.qmd)
    - [ ] Echo script rather than create puml file.
        - Executing a 'Echo' command terminates when it reaches a line break. So we will need to replace all line breaks with a special character sequence, e.g. '\n' and then use a script to replace the special character sequence with a line break.
        Currently the directory is littered with intermediate .puml files which are not needed once the diagram has been created.
</details>
<details>
<summary>API First Quarto Integration</summary>

-  API First Quarto Integration
   - [X] [Create a Journal page to document the process](/Content/Journal/posts/APIFirst/index.qmd)
   - [ ] [Investigate the TypeSpec process](/Content/Journal/posts/APIFirst/TypeSpec.qmd)
   - [ ] Investigate the AutoRest process
   - [ ] Create a End to End example
     - [ ] Create a GitHub repo to hold the example
     - [ ] Publish the example to GitHub
   - [ ] Create a Quarto filter to automate the process
     - [ ] Create a GitHub repo to hold the filter
     - [ ] Publish the filter to Quarto extensions
     - [ ] Document the filter as a journal entry
</details>
<details>
<summary>SAD Website</summary>

- [ ] SAD Website
  - [X] [Created a Frontify Quarto Book](/Content/Current/posts/2025-10-20/index.qmd)
  - [X] [Book loaded into GitHub](/Content/Current/posts/2025-10-14/index.qmd)
  - [X] [Book published to GitHub Pages](/Content/Current/posts/2025-10-14/index.qmd)
    - [Book ppublished as a website at https://newportg.github.io/Quarto-Frontify/](/Content/Current/posts/2025-10-14/index.qmd)
   - [ ] Remove any references to KF
</details>
<details>
<summary>Quarto Calendar Template</summary>

- Quarto Calendar Template
  - [X] [Load a calendar with dates from blog posts](/Content/Current/posts/2025-11-04/index.qmd)
  - [X] [Indicate on the calendar days when a posting has occured.](/Content/Current/posts/2025-11-04/index.qmd)
  - [X] [Click on a date and a link is populated with the required page](/Content/Current/posts/2025-11-04/index.qmd)
  - [X] [A div on the page is populated with the blog post.](/Content/Current/posts/2025-11-04/index.qmd)
    - [X] Stop Quarto formating the content page with headers and footers
      - Loads the html and only extracts the content div
    - [ ] Sort out the page structure.
</details>

