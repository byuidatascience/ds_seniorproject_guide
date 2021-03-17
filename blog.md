# Data Science Blog

You will be responsible for creating a public blog about your senior project and your other data science work. You are required to write at least four posts over the semester to earn an A in the course. 

## Post ideas

I would recommend reading posts from the internet of others that post about data science work.  I have enjoyed the data science articles from medium.com.  The posts do not need to be long, but they should be clear and provide insight.  You could write posts on the following ideas about your project.

- Using API's in R or Python
- How to rip data from a website
- A summary of a new package you are learning
- Your project proposal if appropriate
- Cleaning data
- Advanced use of functions within a package
- latest technology you are learning

### BYU-I Data Science Alumni Blogs

- [Avery Robbins](https://codingwithavery.com/)
- [Callan Mix](https://callanmix.github.io/blog.html)
- [Cannon Bray Medium Post](https://cannon-m-bray.medium.com/understanding-and-identifying-unfairness-in-machine-learning-80178a16357c)
- [Gustavo Hideo Medium Post](https://medium.com/analytics-vidhya/create-your-first-video-face-recognition-app-bonus-happiness-recognition-78463a3f1f9)
- [McKay Davis R package](https://mckaymdavis.github.io/klustR/articles/creating_the_package.html)
- 

## Blog creation

We strongly recommend using the [Distill R package](https://rstudio.github.io/distill/blog.html) to create your blog. They provide clear guidance on how to use the Distill package.  You will also want to leverage the [usethis package](https://usethis.r-lib.org/) to publish your blog on [Github pages](https://pages.github.com/) using github.io. 


### Connect to your github

The section's information is taken from [yuzar-blog](https://yuzar-blog.netlify.app/posts/2020-12-26-how-to-create-a-blog-or-a-website-in-r-with-distill-package/)

#### 1. Create new repository in your new distill blog project

- Go back to RStudio and run `use_git()` in order to create a new local Git repository
- then answer two questions:
  - “Is it ok to commit them?” Don’t commit by typing 3 for “No”, or “Nope” or similar.
  - “A restart of RStudio is required to activate the Git pane Restart now?” Restart by typing 2 for “Yes” or “Yup”.

```
usethis::use_git() 
```

After restart you’ll see a new “Git” tab appear between the “Build” and “Tutorial” tabs. That’s gut!

- click on the “Git” tab and you’ll see empty boxed under “Staged”, lot’s of yellow question marks under “Status” and the file-names under “Path”.

#### 2. Stage and Commit

- check all the boxes and press “Commit” button, which is (vertically) between the “Status” and “History” tabs. A colourful window will pop up. This window describes all the changes you are about to make to your blog.
- Find the “Commit message” box and **definitely** describe what changes you have done (e.g. “First commit”), because then you’ll always be able to get back to the previous version, in case something stops working. That’s what they call - a version control.
- press “Commit”
- wait until you see the “Close” button and close “Git commit”
- forget the other pop up window and go back to RStudio.

#### 3. Run “usethis::use_github()” to connect a local repository to Github

```
usethis::use_github() 
```

A new repository will be automatically created on your Github profile and the new browser window with your Github will pop up.

- If you’ll be asked: “Which git protocol to use?”, choose the one with “https” and if you’ll then be asked: “Are title and description ok?”, agree to proceed.

**NOTE:** if something (e.g. Github Personal Access Token) doesn’t work, get back to the [Happy Git and GitHub for the useR](https://happygitwithr.com/) book and work through it if you still didn’t. You’ll only need it once!

### Github pages settings

Please follow Github's directions (https://pages.github.com/).
