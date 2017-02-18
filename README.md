# Site collaborators guide

## Prepare your environment

clone the site repository:
```
git clone https://github.com/secjamcom/secjamcom.github.io.git secjam
cd secjam
```

change the branch:
```
git checkout -b review
```

check the branch:
```
git branch
```

install the site dependencies:
```
bundle install
```

start the site on your host:
```
bundle exec jekyll serve
```

## Create a new article, cheatsheet, tool

You can create a new file anywhere in the \_articles folder, just make sure the file extension is a '.md' file and all front matter specific metadata filled up with data, like the sample articles.

Don't forget to 'git add' your file to the review branch and commit when you finished your article.

The same rules works on the cheatsheets. However, to add a new tool to the Tools and Projects page you have to add a new YAML item in the \_data/tools.yml file.
