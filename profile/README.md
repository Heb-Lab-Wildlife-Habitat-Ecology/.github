# Welcome to the Heb Lab Git Hub Page

Here you will find code associated with Heb Lab projects and papers


## Adding code to the Heb Lab Organization

There are a few ways to add code to the Heb Lab Organization page. 

1. Create a repository directly on the organization page and connect it to your local repo the same you would as from your personal page

2. Fork a repository from someone's personal page -- you can not fork a repo from your own account into an organization you are apart of.

3. Below is a method I like for adding code to both my personal account page AND the organization page:

  - First, create a new repository in the organization's GitHub. You can make it the same name as your personal repository
  
  - Then, in your local repository (R project on your computer), add the organization's repo as a new remote by running the following in your terminal:

```r
git remote add org_repo https://github.com/org-name/repo-name.git
```

*Note the https above will be replaced with the organization repo address found when you created the new repo
Example: 
![screenshot](images/Git%20Hub%20Repo%20Address.png)

3. After you commit changes in your local repository, push changes to both your personal account and the organization account. You can run the following in your terminal to add to push to the organization repo:

```r
git push org_repo main
```

My flow is to push to my personal account using the intergrated GIT tab in R studio and then push to the organization repo using the above command line function in the r terminal





<sub>make changes to this page in the .github/profile/README.md file</sub>
