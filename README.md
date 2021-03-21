# Sourgough Starter

Like a sourdough starter but built on Go.  

## Built With 
[![Hugo](https://img.shields.io/badge/Hugo-%5E0.80.0-ff4088?style=flat-square&logo=hugo)](https://gohugo.io/)

## How to Use
###### Install [hugo](https://gohugo.io)
```
brew install hugo
```
###### Create Site 
```
hugo new site sitename
```
###### Clone this theme into themes
```
cd sitename/themes
git clone https://github.com/Jack-alope/sourgough-starter.git
```
###### Edit `sitename/config.toml`
Example config.toml
```toml
baseURL = "https://jack.engineering"
languageCode = "en-us"
title = "Jack F. Murphy"
theme = "sourgough-starter"
relativeURLs = true

[markup.goldmark.renderer]
    unsafe= true

[params]
#------------- Config -------------------
    scholarStats = true
    plumxStats = true
    backgroundPath = "images/SA_back.png"
    googleScholar = 'RwMPs-8AAAAJ'
    footerOffset = -75

#-------------- Defined ------------
    css= ["css/sourgough.css"]

[menu]
#----- Navbar links ------
  [[menu.main]]
    identifier = "about"
    name = "About"
    url = "/about/"

  [[menu.main]]
    identifier = "publications"
    name = "Publications"
    url = "/publications/"

  [[menu.main]]
    identifier = "projects"
    name = "Projects"
    url = "/projects/"

#----- NavBottom Links ------
  [[menu.bot]]
    identifier = "github"
    name = "Github"
    url = "https://github.com/jack-alope/"
    pre = "fab fa-github"

  [[menu.bot]]
    identifier = "gitlab"
    name = "Gitlab"
    url = "https://gitlab.com/jack-alope/"
    pre = "fab fa-gitlab"

  [[menu.bot]]
    identifier = "linkedin"
    name = "LinkedIn"
    url = "https://www.linkedin.com/in/jackmurphyf/"
    pre = "fab fa-linkedin-in"

  

#-------- About section links ----- 
  [[menu.about]]
    identifier = "ordcidid"
    name = "OrcidID"
    url = "https://orcid.org/0000-0002-0417-7298"
    pre = "fab fa-orcid"

  [[menu.about]]
    identifier = "researchgate"
    name = "ResearchGate"
    url = "https://www.researchgate.net/profile/Jack_Murphy20"
    pre = "fab fa-researchgate"

  [[menu.about]]
    identifier = "medium"
    name = "Medium"
    url = "https://medium.com/@jack.f.murphy"
    pre = "fab fa-medium-m"

  [[menu.about]]
    identifier = "googlescholar"
    name = "Google Scholar"
    url = "https://scholar.google.com/citations?user=RwMPs-8AAAAJ&hl=en"
    pre = "fas fa-graduation-cap"

#----------- Text Links -------
  [[menu.link]]
    identifier = "email"
    name = "jack@mrph.dev"
    url = "mailto:jack@mrph.dev"

  [[menu.link]]
    identifier = "resume"
    name = "resume"
    url = "https://resume.jack.engineering"

[taxonomies]
  authors = "authors"
```
###### Use
Now you are ready to use this template. See this [example repo](https://github.com/Jack-alope/sourgough-example) or my [personal repo](https://gitlab.com/Jack-alope/sourgough) to see it in use. 

## Built and Maintained By
[Jack F. Murphy](https://jack.engineering)
