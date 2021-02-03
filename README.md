# HTML Bio Page Assignment
The purpose of this assignment is to get used to the workflow between GitHub, GitHub Desktop, and your code editor, Visual Studio Code. By the end of this assignment you'll have made two commits to your repository and made your first webpage live on the web. If you get stuck, refer to Rebecca's [GitHub Guide](https://docs.google.com/document/d/1UJz0KHW8agZvQcuNPHYwsxsU28qfdy7WXoIthzzvAfU/).

## Install necessary software
1. Install [GitHub Desktop](https://desktop.github.com/) and [Visual Studio Code](https://code.visualstudio.com/) if you have not already. Once you do this, you won't need to do it again for the course.

## Setup GitHub Desktop
To use GitHub we'll need to do a little one-time configuration to make sure your account is talking to your computer. Here's what you need to do:
1. Launch GitHub Desktop
1. Connect your GitHub account and login. The software should automatically prompt you to do this the first time you login, but if not  you can access this within the preferences window (on a Mac under the GitHub Desktop menu). You’ll see a “Configure Git” step which is how your contributions will be attributed. Be sure to use your first name and last initial so that I can see your contributions easily. It will also request your email address—be sure to use the one associated with your GitHub account.
1. Connect to Visual Studio Code editor. Go to Preferences > Integrations and choose Visual Studio Code from the External Editor menu (it will only be available if you’ve installed it already. If you use a different code editor it will be visible here as an option instead). I recommend checking all of the boxes in this particular window.

## Your Actual Assignment
Once you have your digital workspace setup you can do the actual assignment. 
### Open the repository on your computer
1. Navigate to “code” tab of your assignment repository in GitHub (online) if you are not already there.
1. Click the “code” button.
1. Choose “Open with GitHub Desktop”. This will launch GitHub Desktop on your computer.
1. Verify where you’d like to store a local copy on your computer (I recommend keeping all of your repositories in the same place on your computer. On a Mac the default location is a GitHub folder inside of the documents folder). Don’t edit the content under “Repository URL or GitHub username and repository. You can choose a location for the files stored on your local computer under “local path” or keep it in the default location.
1. When you are done, choose “clone.” This will take a minute because it is downloading a copy of all of the files in the repository hosted on GitHub.
1. You'll see a message that says "No Local changes." Under it you will find the opton to "Open the repository in your external editor" you should see Visual Studio code as an option. Click that to launch your project in Visual studio code where you will actually edit the code of the assignment.

### Edit files locally
1. Edit the content.
    1. Navigate to the index.html file.
    1. Replace the text "your name" with your actual name. Do not delete any of the tags.
    1. Replace the text "your bio" with a short 1 paragraph (3-5 sentence) bio that you are willing to share publicly. Pro tip: Write the paragraph in a text editor like Google Docs or MS Word so that you can have it spell-checked and then paste it into the index.html file.
    1. Save your file (File > save or command + S). 
    
### Commit version to your repository
_Remember that a commit is like getting a snapshot of the repository at a particular moment in time that you can get back to at some point in the future if you need to. Make commits after making a set of related changes/updates to files._
1. Commit your change. 
    1. Navigate back to GitHub Desktop
    1. Click on the changes tab
    1. Title the name of your commit "update bio content"
    1. Click the "commit to main" button.
    
### Sync changes to the cloud
1. Push change to server
    1. In GitHub Desktop make sure the main branch is selected.
    1. Click the "push origin" button
1. Confirm your change was made by looking at your repository on github.com

### Make your webpage live
1. Set up the directory for the live site
    1. Navigate to your repository folder on your computer. The default loaction on a Mac is in a GitHub folder in the documents folder.
    1. In that folder create a new folder called "docs". Note that case matters. Use all lowercase letters.
    1. Make a copy of your index.html file and add it to the docs folder. Note that you will now have two copies of the same file. One that is in the main directory of your repository and one that is in the docs folder. The docs folder is really hosting space. Think of it as entirely separate from your regular repository. You should only put final copies of work in this folder.
    1. Navigate back to GitHub Desktop.
    1. Click the changes tab and title the new commit "make site live"
    1. Click the commit button.
    1. Push repository to origin like you did above.
    1. Open your gitHub repository in the browser. You should now see a docs folder under the code tab.
1. Make docs folder hosting space
    1. Navigate to "settings" and scroll down to "GitHub Pages". This is where we turn that docs folder into the hosting space we mentioned above. Under Branch choose "main" and under select folder choose "/docs" then click save. You will then see a message in that section appear that says "your site is published at...". The URL you see there is your live website. Click that link to see your site in the browser. This is the URL you will need to submit in Blackboard.
