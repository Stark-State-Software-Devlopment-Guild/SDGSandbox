###### [back](../../README.md)
An Introduction to GitHub Web Client
-------------
### What is Github?
###### From the [Hello World][0] GitHub Guide:

>GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

### How Does it Work?

Github utalizes an object called a repository for organizing a project. Each repository can conain file folders and any files needed for the project. GitHub controls collaberation and version controling through the concept of branches.

#### Branches

Upon creation of a repostitory github creates one default branch called master. Master is the branch that your finalized finished project files are held on. When developing a new feature or adding files to the project repository they are added on a new branch.

###### Lets Create a New Branch in the Sandbox Repository:
> 1. First click the dropdown menu that says "Branch: master"
> 
>     ![alt text][img1]
> 1. In the text box witin the menu add "feature/\<your username\>"
> 
>     ![alt text][img2]
> 1. Press enter! This creates a new branch with the name "feature/\<your username\>".
>     ###### Note: This new branch contains any files that were in the master branch.
>     ![alt text][img3]

#### Commits

When adding, deleting, or editing files GitHub keeps track of these changes through commits. Commits are GitHubs way of knowing when your added files or changes are essentially "final", or ready to .

###### Lets Change and Commit those changes on our Branch
> 1. Click on the README.md file when on your branch
>
>      ![alt text][img4]
> 1. Click the pencil on the far top right to enter the GitHub web text editor.
>
>      ![alt text][img5]
> 1. Edit the line near the bottom that says \<your username\> to read your GitHub username like below
>    ```markdown
>    SDG Sandbox
>    ===========
>    
>    About
>    -----
>    
>    Repository is used for crash course learning of new concepts and technology, as well as to help people get aquainted with over git, github, and git-flow concepts. Code is not overly **maintained** or **protected**.
>    
>    ### Contributors
>    + QualebTheTurtle
>    ```
> 1. Scroll to the bottom of the page where you see this box
>
>      ![alt text][img6]
>    <sub><b>Note:</b> Edit the top box to a short quick comment of the changes this smaller top box is called the commit message box the bottom box is for a lengthier description of the changes or additions it is called the description box. Wite both a short and a long explanation for your changes in the respective text boxes.<sub>
> 
> 1. Click the Commit changes button
> 
###### After creating a Commit you can Veiw the Changes
> 1. Click the Code tab at the top right of the page.
>
>      ![alt text][img7]
> 1. Click Commits. This shows the list of all the commits made for the branch your currently on.
>
>      ![alt text][img8]
> 1. Click the top option. This is the most recent commit.
>      ###### Note: Your commit message is like a title at the top folowed by the description underneath.
>      ![alt text][img9]



[0]: https://guides.github.com/activities/hello-world/ "GitHub Hello World"
[img1]: ../img/step1.png "Tutorial img 1 shows branch step 1 visual taken by Caleb Wagner."
[img2]: ../img/step2.png "Tutorial img 2 shows branch step 2 visual taken by Caleb Wagner."
[img3]: ../img/step3.png "Tutorial img 3 shows branch step 3 visual taken by Caleb Wagner."
[img4]: ../img/step4.png "Tutorial img 4 shows commits step 1 visual taken by Caleb Wagner."
[img5]: ../img/step5.png "Tutorial img 5 shows commits step 2 visual taken by Caleb Wagner."
[img6]: ../img/step6.png "Tutorial img 6 shows commits step 4 visual taken by Caleb Wagner."
[img7]: ../img/step7.png "Tutorial img 7 shows commit changes step 1 visual taken by Caleb Wagner."
[img8]: ../img/step8.png "Tutorial img 8 shows commits step 2 visual taken by Caleb Wagner."
[img9]: ../img/step9.png "Tutorial img 9 shows commits step 3 visual taken by Caleb Wagner."
