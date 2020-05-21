# OCIAM Battery Group Website

## Instructions for use

1. Clone into the repository. In a terminal, navigate to the repository where you want to install this (can be any repository) then:
```
$ git clone https://github.com/jonchapman1/oxford-battery-maths-website.git
$ cd oxford-battery-maths-website
```
2. Run the website locally using hugo:
```
$ hugo/hugo server
```
then open a web browser and go to the link indicated in the terminal (probably http://localhost:1313/).
3. Make any changes by editing the markdown files in [content](./content/) or the [config file](./config.toml). If `hugo server` is still running (hasn't been terminated by Ctrl+C or closing the terminal) then these changes will be visible immediately on http://localhost:1313/.
4. Add your changes to GitHub:
```
$ git add path/to/files/changed
$ git commit -m "a useful commit message"
$ git push origin master
```

Instructions for publishing to a live website will be added at a later date
