<!DOCTYPE html>
    <body>
        <html>
            <center>
            <h3> My first Project </h3>
            <h2><p>First steps with GitHub and Unix Shell</p></h2>
                
                <p>What Is GitHub, and What Is It Used For?</p>
                <img src="www\githubpic.png" alt="funny logo" width="600" height="200">

            </center>         

            <p>Have you ever worked on a Word document with somebody else that may be stored in say, Dropbox, only to discover that you both worked on it at the same time? What happens? Often, you override each other’s changes, download conflicting copies or simply lose your collaborator’s work. Git helps developers alleviate all of these issues.

                Git also tracks the history of changes to a project’s source code, including what specifically has been changed, who has changed what and when. This is called <b>Version Control.</b></p>



            <h4>What The Heck is Version Control?</h4>
                    <p><b>Version control</b> is “a system that records changes to a file or set of files over time so that you can recall specific versions later.” 
                
                    It allows you to track what you and your colleagues have worked on so you don’t clash with or override each other’s changes. Even when developers work on each other’s files at the same time, Git’s version control system will inform them that they’re about to overwrite somebody else’s work!</p>



            <h4>So where does ‘GitHub’ come into it?</h4>
                    <p>Depending on who you talk to, GitHub can be referred to as multiple different things:</p>
                        <ul>
                            <li>A publishing tool</li>
                            <li>A version control system</li>
                            <li>A collaboration tool</li>
                        </ul>
                    <p>Ultimately, <b>GitHub is all of these things combined and more.</b>

                        GitHub allows developers to host their files in a ‘Git Repository’ so that other people can collaborate on projects with them, whether they are open for public contribution (open source) or closed for specific colleagues to work on a private project. The idea is not dissimilar to the way Google Docs lets you host your word processing and spreadsheet files and opens them up for collaboration, though developers do not work on the same documents together in real time or make changes directly in the browser.                         
                        One of the most common misconceptions about GitHub is that non-technical professionals, such as marketers, perceive the platform as purely a tool for developers. Interestingly, GitHub’s social dynamics and resource-sharing capabilities far more closely resemble that of a social network - and all marketers can appreciate the power and utility of social networks.  
                        GitHub’s thriving community of 12 million+ members can ”favorite” repositories they like, make comments on them, monitor and subscribe to different authors and repositories for updates or simply make a copy of somebody else’s content (source code) and start hacking together their own changes and improvements to them. </p>


            <h3><b><i>Git and GitHub Glossary [Infographic]</i></b></h3>



                        <center>
                            <img src="www\infographic.png" alt="infographic picture" width="500" height="2100">
                        </center>


                        <center>
                            <h2><b>Git-Workflow</b></h2>
                        </center>
                        <img src="www\12.png" alt="confused" style="float: left; margin-right: 25px;" />
                            <p><a href="#>What is version control?">Version control</a></p>
                            <p><a href="#What is Git?">Git</a></p>
                            <p><a href="#Repository?">Repository</a></p>
                            <p><a href="#Creating an Issue">Creating an Issue</a></p>
                            <p><a href="#Assigning an Issue">Assigning an Issue</a></p>
                            <p><a href="#Closing an Issue">Closing an Issue</a></p>
                            <p><a href="#The GitHub Flow">The GitHub Flow</a></p>
                            <p><a href="#Creating a Branch">Creating a Branch</a></p>
                            <p><a href="#Committing a file">Committing a file</a></p>
                            <p><a href="#Opening a Pull Request">Opening a Pull Request</a></p>
                            <p><a href="#Merging a Pull Request">Merging a Pull Request</a></p>
                            <p><a href="#Summing up">Summing up</a></p>








            <b><i><a id=">What is version control?">Version control</a></i></b>
                    <p>Version control is a system that helps developers track and manage changes to a software projects' code. As projects grow, the need for version control becomes vital — especially in a collaborative project. We can work safely by using what's known as branching and merging.
                    Branching allows us to duplicate our source code (aka ‘the repository’), so we can safely make changes without affecting the entire project. Once the changes have been reviewed and approval is agreed upon, we merge our branch into the master to update our official code. If any bugs are identified— we have the option to revert back to our original code, as our changes have been tracked.</p>



            <b><i><a id="What is Git?">Git</a></i></b>
                    <p>Git and Github are not synonymous! Git is a specific open-source version control system created by Linus Torvalds in 2005. It’s the program that actually tracks your changes, and ensures the entire code-base is available on each developer's computer. GitHub however, is simply hosting your repositories (as well as providing some additional functionality).</p>
           
        

            <b><i><a id="Repository?">Repository</a></i></b>
                <p>A GitHub repository (or “repo”) can be thought of as the root folder for your project. It contains all your project files and gives you the ability to access each file's revision history. If you’re working in a team you can give other people access to your repository for project collaboration.
                    Let's create our first repository! Make sure you're signed in to GitHub, then:
                    <OL> 
                    <LI>In the upper-right corner, click the settings + icon & then New repository
                    <LI>Give your repository a name
                    <LI>Add a description if you like
                    <LI>Choose between creating a public or private repository (either is fine)
                    <LI>Select Initialize this repository with a README (eg. “My first repo!”)
                    <LI>Click Create repository!
                    <LI>Add files to your repository ~
                            ~ We’re only testing so it really doesn't matter what you add. Find an HTML file for example, and add it to your repository via the Upload files button.</p>
                    </OL>



            <b><i><a id="Creating an Issue">Creating an Issue</a></i></b>
                <p>Issues are how we track the tasks, enhancements, and bugs in our projects. They’re meant to be shared amongst your team to facilitate discussion for review as well as for managing task delegation. If you open an issue on a project managed by someone else, it’ll stay open until either you close it (for example if you figure out the problem) or if the repo owner closes it. When you create an issue, be sure to give a clear explanation of the task at hand. Let’s create an issue in our repository:
                    <OL>
                        <LI>In your repository, select the Issues tab
                        <LI>Click the New Issue button
                        <LI>Give your issue the title ‘Setup GitHub pages’
                        <LI>Give a clear description e.g. ‘Need to setup GitHub Pages in this repository’
                        <LI>Click Submit new issue</p>
                    </OL>



            <b><i><a id="Assigning an Issue">Assigning an Issue</a></i></b>
                <p>We need to assign issues so our team members know who’s job it is to handle the task!

                    On the right side of the screen, under the “Assignees” section, click the settings icon and select yourself
                    Let’s resolve our first issue! We want to setup GitHub pages. But for now, our focus on completing the task:
                    <OL>
                        <LI>Click on the Settings tab in your repository
                        <LI>Scroll down to the “GitHub Pages” section
                        <LI>From the “Source” drop-down, select master branch
                        <LI>Click Save</p>
                    </OL>



            <b><i><a id="Closing an Issue">Closing an Issue</a></i></b>
                <p>Now you’ve completed the task — you can go ahead and close it! You can delete an issue on GitHub, however closing it tells your team members that the task has been completed. To close:</OL>p>
                    <UL>
                        <LI>Open up your completed issue and click Close issue</p>
                    </UL>



            <b><i><a id="The GitHub Flow">The GitHub Flow</a></i></b>
                <p>Now that we know how to work with issues, it’s time to look at the GitHub Flow. Simply put its a workflow where we can experiment with new ideas safely, without the risk of compromising our project. This is primarily achieved through the use of branching. 
                    By default, our project lives on the master branch — any changes to the master will update directly to our project (This can be dangerous is you haven’t properly reviewed your changes!).
                    When we want to experiment with a new feature, or even fix an issue, we create a new branch on the project. The branch will initially be a duplicate of your master, now when you make changes —they’ll reflect only on the branch.
                    While working on changes, you’ll commit the changes to your branch. When you’re satisfied that the changes are complete, its time to open a pull request. From here your team will discuss and further refine the project changes. Once the changes have been approved, the branch will be merged onto the master branch. Let’s go through an example of this process now! Creating a Branch </p>



            <b><i><a id="Creating a Branch">Creating a Branch</a></i></b>
                <p>Open your repository and click the Code tab
                    <OL>
                        <LI>Click Branch: master in the drop-down
                        <LI>In the field, enter a name for your branch (e.g. ‘development’)
                        <LI>Click Create branch
                        <LI>Now that you’ve created a branch, you can modify your project without changing the deployed master branch.
                    </OL>
                        A note on forks — A fork is different from a branch in that it allows you to clone another repo in your own account. It essentially allows you to start a new project based on a previous project.<p>
                        
            

            <b><i><a id="Committing a file">Committing a file</a></i></b>
                <p>Now we can safely work within our branch, let’s create a file and make our first commit.</p>
                    <OL>
                        <LI>Make an edit (anything! just add a simple comment to your code) to one of the files you had added to the repository earlier
                        <LI>Give the commit a name and description
                        <LI>Make sure your newly created (development) branch is selected
                        <LI>Click Commit changes
                    </OL>
                        <p>You’ve made your first commit! The next step is to share the changes with your team via a pull request.</p>



            <b><i><a id="Opening a Pull Request">Opening a Pull Request</a></i></b>
                <p>A pull request is where we share our proposed project changes with our team — with the intent of discussing & revising them before applying the changes to the master branch.</p>
                    <OL>
                        <LI>Open the Pull requests tab and click New pull request
                        <LI>In the base: drop-down menu, ensure the master branch is selected
                        <LI>In the compare: drop-down menu, select the development branch you created earlier
                        <LI>Click Create pull request
                        <LI>Now enter a title for your pull request, for example, “Add my changes”
                        <LI>Add an accurate description of the changes you made
                        <LI>Click Create pull request!
                    </OL>
                        <p>Your team members now have the ability to discuss and review your proposed changes. Once everyone is happy and the changes are approved— it’s time to merge to master.
                        Note: If you forked a repo and made changes, you can create a pull request to merge your changes from there as well.</p>



                <b><i><a id="Merging a Pull Request">Merging a Pull Request</a></i></b>
                    <OL>
                            <LI>Inside of your Pull request, click Merge pull request
                        <LI>Click Confirm merge
                        <LI>Once your branch has been merged, you don’t need it anymore. You can click Delete branch!
                    </OL>



                <b><i><a id="Summing up">Summing up</a></i></b>
                        <p>And that’s it! You’ve learned how to work collaboratively on projects using GitHub. GitHub is an amazing tool to take advantage of! You can now create repositories and issues, create branches, fork projects and make commits, submit pull requests for review, and merge to the master branch. Not bad!</p>


                       
            <center>
                 <h2><p>Unix Shell</p></h2>
            
                     <p>What Is Unix Shell, and What Is It Used For?</p>
                        <img src="www\21.png" alt="funny logo" width="1000" height="200">
            </center>

        <p>A Unix shell is a command-line interpreter or shell that provides a command line user interface for Unix-like operating systems. The shell is both an interactive command language and a scripting language, and is used by the operating system to control the execution of the system using shell scripts.[2]
        Users typically interact with a Unix shell using a terminal emulator; however, direct operation via serial hardware connections or Secure Shell are common for server systems. All Unix shells provide filename wildcarding, piping, here documents, command substitution, variables and control structures for condition-testing and iteration.</p>

            <center>
                <a href="http://mally.stanford.edu/~sr/computing/basic-unix.html">Basic UNIX commands</a>
            </center>

            <b><p><h3>Change Directories Within Command Prompt</h3></p></b>
                <p>It’s not always convenient to open File Explorer and drag and drop. That’s why it’s cool that you can also type a command to change directories right in Command Prompt.
                    RELATED: 10 Useful Windows Commands You Should Know 
                    Say, for example, you’re in your user folder, and there’s a “Documents” directory in the next file path. You can type the following command in Command Prompt to switch to that directory:<p>
                    
                    <b><p>cd Documents </b></p>
                    
                        <p>Note that this only works if you’re in the immediate file structure. In our case, that would be (user folder) > Documents. In our current directory, we wouldn’t be able to use this method to jump to a directory nested two levels down.  
                        So, let’s say we’re currently in the user folder and want to go to the “How-To Geek” folder, which is nested in “Documents.” If we try to jump straight to “How-To Geek” without first going to “Documents,” we get the error shown in the image below.</p>

            <center>
                    <img src="www\11.png" alt="command prompt" width="500" height="200">
            </center>
                    <p>Let’s take things one directory at a time, for now. As we mentioned previously, we’re currently in our user folder. We type <b>cd Documents</b> in Command Prompt to visit “Documents.”</p>


            <center>
                <img src="www\31.png" alt="command prompt" width="500" height="200">
            </center>
                <p>We’re now in the “Documents” folder. To move down another level, we type cd on the command line followed by the name of that directory.</p>


                <center>
                    <img src="www\41.png" alt="command prompt" width="500" height="200">
                </center>



    </body>
</html>