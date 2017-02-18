# Site collaborators guide

## Prepare your environment

clone the site repository:
```
git clone https://github.com/secjamcom/secjamcom.github.io.git secjam
cd secjam
```

change the branch:
```
git checkout review
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

The same rules applied on the cheatsheets. Except the tools. To add a new tool to the Tools and Projects page you have to add a new YAML item in the \_data/tools.yml file.

## Push your contribution to git

First update your local branch:
```
git pull
bundle update
```

For example, to push your contribution:
```
git add -A
git commit -a -m 'Added new XY article'
git push -u origin review
```

## Init a pull request

The easiest way to do that is to log in on github.com and on the project review branch init a pull request.

Therefore, we automatically notified of your changes we can review, discuss, fix your changes and after all if the request accepted the changes automatically added to master branch.
