# date branch

88888 

Fork this repo and make it your own.  You will use it for the remainder of this curriculum to organize, review, and share your notes.  Completing this repo will turn your notes into a powerful study & review tool, a showcase of your knowledge, and substantial practice with organizing and deploying projects to GitHub.
 
Initial setup
* Fork this repo
* Set gh-pages settings to build from "master /docs"
  * This will host your notes live at "user_name".github.io/"repo_name"
* Clone the repo
* Run "npm install -g gitbook && gitbook install" in the cloned directory
* Run "chmod a+x ./scripts/publish.sh" in the cloned directory

To Publish:  
* Type "./scripts/publish.sh" from terminal in your Journal directory

Concepts GitBook:
* Your GitBook will look [something like this](https://elewa-academy.github.io/study-journal-template/).

Quizzes:
* You will use [this quiz plugin](https://github.com/chudaol/gitbook-plugin-quiz) to write self-review quizzes for your notes.  The quizzes will be live and interactive on your journal's url.

Directory Structure Explained: 
```
study-journal
|-- /xx-yy_aa-bb
|
|-- /concepts
|
|-- /docs
|
|-- /quizzes
|
|-- /scripts
|   |-- build.sh    - Build the GitBook into /docs without publishing
|   |-- publish.sh  - Build & push the new notes GitBook to GitHub
|   |-- serve.sh    - Preview your GitBook at localhost:4000 without building
|
|-- .gitignore  - Tell Git not to push your node_modules folder to GitHub
|-- book.json   - A file written in JSON format that configures your GitBook
|-- README.md   - The "cover page" of your repo & GitBook
|-- SUMMARY.md  - Determines what will show up in your GitBook index


```


___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
