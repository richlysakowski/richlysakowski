## Rich Lysakowski

# ***PORTFOLIO*** Home Page `Template` for Github.com

Author:   Rich Lysakowski, Data Science Maestros, LLC

Updated:  6/11/2022

## INSTRUCTIONS TO USE GITHUB PORTFOLIO HOME PAGE TEMPLATE

Jupyter Notebook is a convenient markdown editor that is familiar to data science and analytics professionals.  Github.com and Jupyter Notebook `Markdown` language are ALMOST identical.  

This Notebook is a STARTER TEMPLATE for you to create Markdown code for your Github.com ***PORTFOLIO*** Home Page.

A separate Jupyter Notebook template exists for you to create ***PROJECT*** home pages for each of your projects.

The Notebook cells below contain ***"boilerplate"*** content to help you create a good looking home page with most  important sections required to discuss and market the projects that you have done. 

## How the Github.com Webserver Displays Your Main Github Home Page

You must have a github repository `endpoint` named `https://www.github.com/accountname/accountname`.
    
If you do not have this repository, then you must first create it, and then put your portfolio `readme.md` file in it. 

Follow these instructions link to create your main account profile `readme.md` repository and file.

https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme


## Edit Template Sections Below for Your Content

### Edit Template Sections Below for Your Content, Project links, and Contact Information 

Linkedin: https://www.linkedin.com

Email:    gmail or other

### Add and link images and icons from an image directory on github

It is better if the images are static and sourced locally from a folder in your github account, in case the remote links break.  

Create an image folder in your github `https://www.github.com/accountname/accountname` repository.

### Verify and Finalize Your Pages, and Repository and Image Links 

#### Open Windows File Explorer to see if the "images" are in the right directory folder.


```python
# This code will open a Windows File Explorer safely.  It works FOR WINDOWS ONLY.

import os
import subprocess
current_path = os.getcwd()
FILEBROWSER_PATH = os.path.join(os.getenv('WINDIR'), 'explorer.exe')

subprocess.run([FILEBROWSER_PATH, '/select,', os.path.normpath(current_path)])
```




    CompletedProcess(args=['C:\\WINDOWS\\explorer.exe', '/select,', 'C:\\Users\\richadmin\\Desktop\\00_PythonWIP_2022\\!0-Github-Portfolio-Project-Examples'], returncode=1)



## POST YOUR GITHUB HOME PAGE

When finished editing your home page content in Jupyter Notebook: 

    1) GO TO JUPYTER NOTEBOOK `FILE` MENU
    2) Select `Download As...` Menu
    3) Save as `Markdown`
    4) Rename this file to simply `readme.md`.
    5) Move this file to your `https://www.github.com/accountname/accountname` repository.
    6) Replace your existing `readme.md` file with this one.  (You may be required to log out and log back in.)
    7) Your new `readme.md` file should appear in your `Overview` section at the top of your Github account home page.
    8) Verify that all repository links correctly open your repositories that you want referenced from your home page.
    
***DELETE THESE INSTRUCTIONS WHEN FINISHED:***

# EXAMPLE - Abraham Parker - Data Scientist and Systems Administrator

<p dir="auto" align="center">
    Data Scientist and Data Analytics Engineer passionate about working with data in many business enviroments.  My technical areas of expertise include application design and development  in Python, SQL, and web (HTML, CSS, Javascript) languages in Docker, Windows, and Linux environments.  I have experience with dozens of Python packages for analytics and web development.  My portfolio includes many projects where I have applied my data analytics, website development, statistics and machine learning skills. <br><br> Contact me to learn more and engage my skills on your project.<br><br>
    <a href="https://www.linkedin.com/in/abraham-parker-4baa6642/" rel="nofollow">
        <img src="https://camo.githubusercontent.com/a80d00f23720d0bc9f55481cfcd77ab79e141606829cf16ec43f8cacc7741e46/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c696e6b6564496e2d3030373742353f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" style="max-width: 100%;"></a>
    <a href="mailto:parkerwellins@gmail.com?subject=[GitHub]%20Hello%20Abraham" >
        <img src="https://camo.githubusercontent.com/571384769c09e0c66b45e39b5be70f68f552db3e2b2311bc2064f0d4a9f5983b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f476d61696c2d4431343833363f7374796c653d666f722d7468652d6261646765266c6f676f3d676d61696c266c6f676f436f6c6f723d7768697465" data-canonical-src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" style="max-width: 100%;"></a>
</p>

## YOUR HOME PAGE BANNER IMAGE

### INSERT AND PROPERLY SCALE YOUR HOME PAGE BANNER IMAGE

**The cell below is used to import your banner image and properly scale it.**   

How to scale images using Markdown and HTML: 
https://stackoverflow.com/questions/60627697/how-to-shrink-the-size-of-the-image-that-has-opened-in-jupyter-notebook-by-using/60638679#60638679

***Rotating gifs work great and attract and retain attention better than static images.*  

Be careful to select a banner image that is very wide (most of the viewable page width), and not very tall.  Images that are too tall consume too much of your home page header vertical area.  This distracts people and does not let them see your written descriptions immediately.  It forces them to scroll to see your written content, which is risky because people with little time or attention span can become impatient and just move on to another website.**

***DELETE THESE INSTRUCTIONS WHEN FINISHED:***

***IMAGE SCALED TO 45% BUT NOT WIDE ENOUGH***

<img src="images/data-science.jpg" width="45%"/>

***IMAGE TOO BIG***
![welcome_gif](images/data-science.jpg)

***HERE'S AN EXAMPLE OF A ROTATING GIF IMAGE***

***DELETE THIS CELL WHEN FINISHED:***

https://raw.githubusercontent.com/diandramelo/diandramelo/main/welcome.gif

![Welcome!](https://raw.githubusercontent.com/diandramelo/diandramelo/main/welcome.gif)

***banner image rotating gif made smaller***

<img src="https://raw.githubusercontent.com/diandramelo/diandramelo/main/welcome.gif" width="45%"/>

# **Check out my main projects:**

## [Frackaton-Frontend](https://github.com/OctoCode/hackaton-frontend)

Admin template based on Angular 7+, Bootstrap 4 and Nebular

## [Hackathon Backend](https://github.com/OctoCode/hackaton-backend)

Hackaton Copa 2019 (BackEnd) 

## [Hackaton Copa 2019 (AI)](https://github.com/OctoCode/hackaton-ai)

Hackaton Copa 2019 (AI) 

<!--**alg2code/alg2code** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Use Badges and Shields to Highlight Your Skills

#### Creating Shields and Badges

There are several websites that create and serve up badges.  Shields.io lets you reference existing shields or generate new shields and badges.  https://shields.io/category/social  

You will find others using Google Search.

Juputer NB displays these badges on separate lines.  However, GITHUB should display badges within the same `<span>` tag on the same line.  

***DELETE THESE INSTRUCTIONS WHEN DONE.***

<img src="https://img.shields.io/badge/Postgres-DBMS-red">

<span>
<span display="inline" height="20px" class="common__BadgeWrapper-sc-11baoah-3 iwwuaY"><img alt="success" src="https://img.shields.io/badge/-success-success"></span>
<span display="inline" height="20px" class="common__BadgeWrapper-sc-11baoah-3 iwwuaY"><img alt="important" src="https://img.shields.io/badge/-important-important"></span>
<span display="inline" height="20px" class="common__BadgeWrapper-sc-11baoah-3 iwwuaY"><img alt="critical" src="https://img.shields.io/badge/-critical-critical"></span>
<span display="inline" height="20px" class="common__BadgeWrapper-sc-11baoah-3 iwwuaY"><img alt="informational" src="https://img.shields.io/badge/-informational-informational"></span>
<span display="inline" height="20px" class="common__BadgeWrapper-sc-11baoah-3 iwwuaY"><img alt="inactive" src="https://img.shields.io/badge/-inactive-inactive"></span>
</span>

### Computer Operating systems
<p>
    <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"> 
    <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white">
</p>

### Technical Skills
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white">
<img src="https://img.shields.io/badge/Postgres-430098?style=for-the-badge&logo=heroku&logoColor=white">
<img src="https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white">
</p>

### 👨‍💻 Python Libraries
<p>
    <img src="https://img.shields.io/badge/pandas%20-%23150458.svg?&style=for-the-badge&logo=pandas&logoColor=white">
    <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
    <img src="https://img.shields.io/badge/seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white">
    <img src="https://img.shields.io/badge/scikit_learn-7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
</p>

# FINALIZE AND POST YOUR HOME PAGE 

(SEE INSTRUCTIONS ABOVE)

***DELETE THIS CELL WHEN FINISHED EDITING YOUR GITHUB.COM HOME PAGE***


```python
{"Author": "Rich Lysakowski", "Updated": "2022-06-11" }
```




    {'Author': 'Rich Lysakowski', 'Updated': '2022-06-11'}




```python

```
