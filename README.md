# Junior Seminar (CS580/INFM580) Assignment 02

Using Hugo and Netlify to Design an Online Research Notebook

**Assigned** : Tuesday 31 January 2023

**Due** : Tuesday 7 February 2023

## Objectives

* To learn how to set up a Hugo and Netlify to create a website which will play the part of a research notebook.
* To learn to use this online research notebook to record your ideas and implementations as you develop your ideas. 

![Hugo logo](graphics/hugo.png)
Figure 1: Figure 1: Hugo: a popular open-source static site generator. Read more about [Hugo](https://gohugo.io/) to find tutorials and information about building a website. Also, see [Course Resources](https://www.oliverbonhamcarter.com/resources/) for some quick notes about setting up Hugo projects.

### Preparation

In this assignment, we will be setting up an online research notebook in which you are to record the progress in your research. For this task, we will use Hugo (see Figure 1 above) and Netlify (Figure 2, below). For many of your assignments, you will use your website to add your progressive thinking, article summaries, a bibliography, implementations and other aspects of your work.

If you not familiar with how to create a public website (i.e., creating website’s public repository with GitHub, and using Hugo and Netlify) then see [Course Resources](https://www.oliverbonhamcarter.com/resources/) for some quick notes about setting up Hugo projects. You are also encouraged to complete online searches for information, tutorials and other resources to help you.


![Netlify logo](graphics/netlify.png)

Figure 2: Netlify: Publish your project online from a GitHub repository. Read more about [Netlify](https://www.netlify. com/) to find out how to publish your website from GitHub. See [course Resources](https://www.oliverbonhamcarter.com/resources/) for some quick notes about setting up Netlify projects.

### While Working

As you are working on your lab, you are to commit and push regularly. The commands are
the following.

``` bash
git add -A
git commit -m ‘‘Your notes about commit here’’
git push
```

## Part 1: Build a public notebook using Hugo, add initial posts

Tuesday's class will be spend on creating and setting up the research website.

You are to familiarize yourself with the tools described above and use them to create your online research notebook. See [Course Resources](https://www.oliverbonhamcarter.com/resources/) for some quick notes about setting up Hugo and Netlify projects.

* Follow online documentation, supplied script files and other materials available using search engines
  + Set up Hugo site, using GitHub
  + Deploy on Netlify
  + Record the address of your working website for your site to submit for this assignment.
  + Send the address out to the **Discord** channel to communicate the link to your colleagues.
* Your web site must have two (2) initial posts
  1. An autobiography (min 50 words) to introduce yourself.
  2. A brief introduction (min 250 words) which has been written in clear and meaningful language to introduce your research interest area(s).

## Part 2: Showcase your work!

* Thursday's class will be spent to create content for the website. This content will center around the article and your research area.

  + Find a seminal article that is closely related to your idea. You are asked to include a new post on your website where you introduce, discuss and reference some important points about this article.
  + Be sure to tie this article in with your own work. 
     + Your writing here will be about 200 to 250 words.


**During the next lab**, we will have another round of short presentations where you are to introduce your completed online research notebook and introduce the article that you chose above that touches on your own interests.
* Please allow yourself about three or four minutes for this presentation.
  + Introduce and showcase your website
  + Introduce your article using your website page(s) and discuss the main points of the article.

---

### Required Deliverables

* **Tuesday**: 
  + Prepare and set up your research notebook.
  + Begin writing your posts
  + Answer questions in `writing/reflection.md` 
* **Thursday** Class:
  + Finish writing your posts.
  + Find an article to address.
  + Answer questions in `writing/reflection.md` 
* **Thursday** Lab:
  + Deliver your three or four minute lightning talk to introduce your research notebook and your article.


### Checks for GatorGrader

For immediate feedback on submissions, we will be using Gator Grade to inform the of missing components in the submission. As you submit, you will notice that there is a thick red X that will change to a green check mark when all components have been included in the submission. You are encouraged to click on the red X to find a listing of the components to address.

## Project Assessment

The grade that a student receives on this assignment will have the following components.

- **GitHub Actions CI Build Status [up to 20%]:**: For the repository associated with this assignment students will receive a checkmark grade if their last before-the-deadline build passes. This is only checking some baseline writing and commit requirements as well as correct running of the program. An additional reduction will given if the commit log shows a cluster of commits at the end clearly used just to pass this requirement. An addition reduction will also be given if there is no commit during lab work times. All other requirements are evaluated manually.

- **Mastery of Technical Writing [up to 50%]:**: Students will also receive a checkmark grade when the responses to the writing questions presented in the `reflection.md` reveal a proficiency of both writing skills and technical knowledge. To receive a checkmark grade, the submitted writing should have correct spelling, grammar, and punctuation in addition to following the rules of Markdown and providing conceptually and technically accurate answers.

- **Presentation [up to 30%]:**
Students will receive a checkmark grade for presentations. Student must be present to receive credit for group's presentation.
## GatorGrade

You can check the baseline writing and commit requirements for this lab assignment by running department's assignment checking `gatorgrade` tool. To use `gatorgrade`, you first need to make sure you have Python3 installed (type `python --version` to check). If you do not have Python installed, please see:

- [Setting Up Python on Windows](https://realpython.com/lessons/python-windows-setup/)
- [Python 3 Installation and Setup Guide](https://realpython.com/installing-python/)
- [How to Install Python 3 and Set Up a Local Programming Environment on Windows 10](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-windows-10)

Then, if you have not done so already, you need to install `gatorgrade`:

- First, [install `pipx`](https://pypa.github.io/pipx/installation/)
- Then, install `gatorgrade` with `pipx install gatorgrade`

Finally, you can run `gatorgrade`:

`gatorgrade --config config/gatorgrade.yml`

## Seeking Assistance

* Extra resources for using markdown include;
  + [Markdown Tidbits](https://www.youtube.com/watch?v=cdJEUAy5IyA)
  + [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Do not forget to use the above git commands to push your work to the cloud for the instructor to grade your assignment. You can go to your GitHub repository using your browser to verify that your files have been submitted. Please see the TL’s or the instructor if you have any questions about assignment submission.

Students who have questions about this project outside of the lab time are invited
to ask them in the course's Discord channel or during instructor's or TL's office hours.
