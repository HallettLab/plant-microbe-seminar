# Plant-Microbe Seminar

This repository houses the Plant-Microbe Seminar website, which is shared among members through Github and hosted by Netlify. 

## Initial set-up

1) Create a Github user name and share it with Lauren, who can add you to the Hallett Lab organization page and as a contributor to this site.

2) Install R and RStudio (and git, if using a PC)

3) Within R, install the package blogdown by running the following script in the console:
`install.packages("blogdown")`

then load the package using the script:
`library(blogdown)`

4) Install hugo. The blogdown function has a helper function to do this in R. Run the following script:
`blogdown::install_hugo()`

5) Clone the repository. Using the terminal, navigate to the location you would like the website folder stored in. Copy the web URL from the green "Clone or download" tab on the repository homepage, and clone it to your local drive by entering `git clone thewebURL` in the terminal. In this case, it would be:
`git clone https://github.com/HallettLab/plant-microbe-seminar.git`

### Notes for PC users
1. Pull up command prompt in Windows
2. Type in dir to pull up your directory with your files and folders
3. Type cd (spac)e and type in the folder you want to save it to (such as Documents): cd Documents
4. Type git clone (space) then paste the link from github of the repository you want to clone
5. Check your Documents folder (or wherever you have decided to save the repository), it should be there!


## Adding a blog post

1) Open the plant-microbe-seminar.RProj (always open the project file, don't just open individual files)

2) Pull! Always pull before you make changes, and before you push.  You can pull by clicking on the blue down button on the Git tab of RStudio.

Alternatively, you can pull updated files to your local drive by navigating to the lab website folder in the terminal, and entering:
`git pull`

3) Create the page. I recommend using the blogdown AddIn. Go to Tools -> AddIns -> New Page and click on that. Title the post with Author, year, and journal. The AddIn will autopopulation the Filename accordingly. Designate the subdirectory to the folder for the current topic theme. Choose the current topic theme as the category for the post, and tag the post with appropriate key words. Make sure to also tag *your name* so that Krista and Lauren can easily locate all of your blog entries. The default is a .md not .Rmd page, so let's keep with that.

4) Preview your changes! You can do this by running the following script in the console:
`blogdown::serve_site()`

Do NOT use the Preview tab in RStudio. If you accidentally do, delete the html file it creates!

The website should appear in the Viewer tab of RStudio. You can open it in a browser by clicking on the arrow-to-browser icon on the upper left of the Viewer tab.

5) When you are satisifed, share your updates. 

First, pull again (using the blue down arrow on the Git tab). 

Second, add your changes. In RStudio, this can be done by clicking on the Staged checkbox in the Git tab.  

Third, commit your changes. Click on the Commit button in the Git tab, then add a message that succinctly describes your changes, and press Commit.  

Fourth, push your changes. Click on the green up arrow. It may ask you for your Github user name and password (or your token, now that Github is on a token system). 


