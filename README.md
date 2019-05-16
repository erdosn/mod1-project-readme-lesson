
### Objectives
YWBAT 
* convert a notebook to a readme.md
* explain the purpose of readme.md on github

### Outline
* Look at some samples of readme.md files from students
* Convert a jupyter notebook into a md file
* rename that file to README.md

```
jupyter nbconvert --to markdown lesson-plan.ipynb

# lose the original markdown file

mv lesson-plan.md README.md

# to keep both
cp lesson-plan.md README.md
```

### Assessment
