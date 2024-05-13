# Hands-On Assignment: Git, GitHub, And Open Source Exploration

### Prerequisites

   * A GitHub account
   * Git installed on your local machine.
   * A code editor of your choice

## Clone an open source repository

* Clone this repository using ```git clone https://github.com/me-and-company/readme-template.git``` command

## Fork the cloned repository

* click the fork button and rename the forked repository to avoid confusion ![Alt text](https://www.gitkraken.com/wp-content/uploads/2021/11/github-how-to-fork-button-github-1024x385.png)




## Manage branches

* create a new branch named feature-update using
     ``` git branch feature-update ```

and switch to the new banch using
     ``` git checkout feature-update ```

## Make changes and commit the changes

* Add a file or documentation to the readme
* Add changes to the remote repository 

   * stage the new change by 
      ``` git add .``` command and commit them with 
      ``` git commit -m " commit message" ```


## Merge Changes

* switch back to the master brach 
     ``` git checkout master ```
* Merge your branch into main with 
     ``` git merge feature-update```


# Managing Conflicts

### Create conflict
   
   * Modify the same file in both the local repository and forked repository
     and commit changes in both

### Resolve conflict

   * Create a new branch to resolve conflicts ``` git checkout -b conflict-resolution ```
   * Do a pull request ``` git pull ``` then a push request to solve the conflict ``` git push ```



# Github Pages

### Enabling GitHub Pages:

   * Create an HTML file e.g ( index.html ) in the forked repository.
     Go to the repository's settings on GitHub, scroll down to the GitHub Pages section, select the master branch as the source, and save.

### Accessing the Published Page:

    Visit ( https://github.com/mojahma/readme-template-git-commands.git) in a browser to view the published HTML page


## Additional Documentation and Acknowledgments

  #### Exploring Open Source Projects:
  * Search GitHub for projects of interest.
  * Explore the project's README, issues, and contribution guidelines.
  ![Alt text](https://learntheweb.courses/topics/github-issues/issues-tab.jpg)

  #### Opening an Issue:
  *  Click on the "Issues" tab of the chosen repository.
  *  Click "New Issue" and fill out the form with a descriptive title and detailed description.


  ### Challenge faced 

  * I had problems but the git documentation came to the rescue




# PLP Africa 
# 00 Million Devs For Africa
