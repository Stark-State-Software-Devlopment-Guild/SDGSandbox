###### [back](../../README.md)
An Introduction to GitHub Web Client
-------------
## What is Github?
##### From the [Hello World][0] GitHub Guide:

>GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## How Does it Work?

Github utalizes an object called a repository for organizing a project. Each repository can contain file folders and any files needed for the project. GitHub controls collaberation and version controling through the concept of branches.

### Branches

Upon creation of a repostitory github creates one default branch called master. Master is the branch that your stable finished project files are held on. When developing a new feature or adding files to the project repository they are added on a new branch.

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

### Commits

When adding, deleting, or editing files GitHub keeps track of these changes through commits. Commits are GitHubs way of knowing when your added files or changes are essentially "final", or ready for release.

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
>    <sub><b>Note:</b> Edit the top box to a short comment of the changes this smaller top box is called the commit message box the bottom box is for a lengthier description of the changes or additions it is called the description box. Wite both a short and a long explanation for your changes in the respective text boxes.<sub>
> 
> 1. Click the Commit changes button
> 
###### After creating a Commit you can Veiw the Changes
> 1. Click the Code tab at the top left of the page.
>
>      ![alt text][img7]
> 1. Click Commits. This shows the list of all the commits made for the branch your currently on.
>
>      ![alt text][img8]
> 1. Click the top option. This is the most recent commit.
>      ###### Note: Your commit message is like a title at the top folowed by the description underneath.
>      ![alt text][img9]

### Merging and Pull Requests
Once your feature is finished and tested you probably want your additions to be commented on by peers, and added to the master branch. <sub>Recall: Master branch is the branch that includes all the files to be included in the final version of your project.</sub> To include the changes and additions you've made on your current branch, you would need to "merge" your working branch with master. Before a merge can take place in GitHub a pull request must be made<sub>(master and develop branches are protected in all SDG repositories)</sub>. A pull request can be commented on by any project contrubutor, member or anyone with a github account. A pull request also shows any file additions and subtractions side by side.

###### Lets Create a Pull Request for our Current Branch to Master:
> 1. Click the pull requests tab to the right of the code tab.
>
>      ![alt text][img10]
> 1. Click the new pull request button
> 
>      ![alt text][img11]
> 1. Under Comparing changes there are two dropdown menus to compare changes between branches. From the dropdown menu starting with "base:" select the master branch, select your branch from the other dropdown. A green checkmark should appear to the right indicating that the two branches are able to merge with no conflicts. Once you ensure that the checkmark has apeared click the "Create pull request" button.
>
>      ![alt text][img12]
> 1. Notice the box similar to the one from commiting. It shows the same message and description as the last commit. Edit this to illistrate all the differences between the compareing branches. Click "Create pull request".
>
>      ![alt text][img13]
> 1. Notice the box next to the branching symbol. This box will look different than the one shown, since you dont have the ablity to merge with the comparing branch it will all be greyed out.
>
>      ![alt text][img14]
> 1. Notice that you(and anyone else) can actively create comments for the pull request. While it may not be required in every repository, it is generally encouraged to give comments and critiques to pull requests.
>
>      ![alt text][img15]


[0]: https://guides.github.com/activities/hello-world/ "GitHub Hello World"
[img1]: ../img/step1.png "Tutorial img 1 shows branch step 1 visual taken by Caleb Wagner."
[img2]: ../img/step2.png "Tutorial img 2 shows branch step 2 visual taken by Caleb Wagner."
[img3]: ../img/step3.png "Tutorial img 3 shows branch step 3 visual taken by Caleb Wagner."
[img4]: ../img/step4.png "Tutorial img 4 shows commits step 1 visual taken by Caleb Wagner."
[img5]: ../img/step5.png "Tutorial img 5 shows commits step 2 visual taken by Caleb Wagner."
[img6]: ../img/step6.png "Tutorial img 6 shows commits step 4 visual taken by Caleb Wagner."
[img7]: ../img/step7.png "Tutorial img 7 shows commit changes step 1 visual taken by Caleb Wagner."
[img8]: ../img/step8.png "Tutorial img 8 shows commit changes step 2 visual taken by Caleb Wagner."
[img9]: ../img/step9.png "Tutorial img 9 shows commit changes step 3 visual taken by Caleb Wagner."
[img10]: ../img/step10.png "Tutorial img 10 shows merge/pull requests step 1 visual taken by Caleb Wagner."
[img11]: ../img/step11.png "Tutorial img 11 shows merge/pull requests step 2 visual taken by Caleb Wagner."
[img12]: ../img/step12.png "Tutorial img 12 shows merge/pull requests step 3 visual taken by Caleb Wagner."
[img13]: ../img/step13.png "Tutorial img 13 shows merge/pull requests step 4 visual taken by Caleb Wagner."
[img14]: ../img/step14.png "Tutorial img 15 shows merge/pull requests step 5 visual taken by Caleb Wagner."
[img15]: ../img/step15.png "Tutorial img 15 shows merge/pull requests step 6 visual taken by Caleb Wagner."
