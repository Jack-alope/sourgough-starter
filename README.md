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
baseURL = "https://example.com"
languageCode = "en-us"
title = "Your Name"
theme = "sourgough-starter"
relativeURLs = true

[markup.goldmark.renderer]
    unsafe= true

[params]
#------------- Config -------------------
    scholarLink = true
    scopusLink = true
    dimensionsLink = true
    dimensionCitations = true
    backgroundPath = "images/SA_back.png"
    googleScholar = 'XXXX' # These are needed only if set to true above
    scopusID = 'XXXX'
    dimensionsID = 'XXXX'
    footerOffset = -60

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
    url = ""
    pre = "fab fa-orcid"

  [[menu.about]]
    identifier = "researchgate"
    name = "ResearchGate"
    url = ""
    pre = "fab fa-researchgate"

  [[menu.about]]
    identifier = "medium"
    name = "Medium"
    url = ""
    pre = "fab fa-medium-m"

  [[menu.about]]
    identifier = "googlescholar"
    name = "Google Scholar"
    url = ""
    pre = "fas fa-graduation-cap"

#----------- Text Links -------
  [[menu.link]]
    identifier = "email"
    name = "email@example.com"
    url = "mailto:email@example.com"

  [[menu.link]]
    identifier = "resume"
    name = "resume"
    url = ""

[taxonomies]
  authors = "authors"
```
###### Use
Now you are ready to use this template. See this [example repo](https://github.com/Jack-alope/sourgough-example) or my [personal repo](https://gitlab.com/Jack-alope/sourgough) to see it in use. 

## Built and Maintained By
[Jack F. Murphy](https://jack.engineering)
