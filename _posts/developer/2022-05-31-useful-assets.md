---
title: A page of assets to copy and paste
date: 2022-03-29 17:03:00 +1
author:
  name: King Pwalo
  link: https://pwalo.github.com
categories: [documentation,code]
tags: [no-use,sample,practice]
pin: true
---

### Block Quote Icons

> 💡- Light Bulb => Usually used with **Tip:**  
> ℹ️ - info => it turns out **Info:** renders better than it previews  
> ⚠️ - Warning => add some comment like **Warning:** or **Caution:**  
> 📝 - Note => This is a **Note:**  
> 🤓 - Nerd Face =>  Usually when it complies and/or renders


> ℹ️ **Info:** Need more?  get them at <a href="https://emojipedia.org" target="_blank">emojipedia</a>  

### Usefull websites

<a href="https://www.markdownguide.org/cheat-sheet/" target="_blank">Markdown Cheat Sheet</a>  
<a href="https://techno-tim.github.io/posts/jekyll-docs-site/" target="_blank">Techno Tim Jekyll Guide</a>  
<a href="https://github.com/cotes2020/jekyll-theme-chirpy" target="_blank">Jekyll Chirpy Theme Git Repo</a>

### Cloning a repo to local machine

cd to a folder or mkdir where you would like to save your local copy repos eg: `cd documents` or 
```bash
mkdir ~/Code  
cd ~/Code
```  

Clone the repo with `git clone git@github.com:<repo_user>/<repo_name>.git`

### Running, building and pushing code from WSL CLI

#### Run 

To run a site on localhost (usually while creating/testing)  
```bash
cd <root_folder_of_local_repo>
bundle exec jekyll s --verbose
```

You should see something like this:

> Server address: http://127.0.0.1:4000/  
> [2022-05-31 22:00:58] INFO  WEBrick::HTTPServer#start: pid=11113 port=4000  
> Server running... press ctrl-c to stop.

Use your browser to navigate to <a href="http://127.0.0.1:4000/" target="_blank">localhost:4000</a>  to see your site running  

#### Build
To build your site in html and find it in the `_site` folder  
```bash
JEKYLL_ENV=production bundle exec jekyll b
```
If you were sucessful you should see something like:  
> Configuration file: /home/username/repo.github.io/_config.yml  
 Theme Config file: /home/username/gems/gems/jekyll-theme-chirpy-5.1.0/_config.yml  
            Source: /home/username/repo.github.io  
       Destination: /home/username/repo.github.io/_site  
 Incremental build: disabled. Enable with --incremental  
      Generating...  
                    done in 0.459 seconds.  
 Auto-regeneration: disabled. Use --watch to enable.  

#### Prepare, commit and push to Github

Check for any outstanding commits or issues with `git status`  

Add all changes to the commit queue with `git add .`  

Prepare the commit and add a comment with `git commit -m "Useful comment here"`  

Finally push the commit to the repo with `git push` 
