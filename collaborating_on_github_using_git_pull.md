
**How to Collaborate on a Project on GitHub Using the Git Pull Method**

*By Esianyo Dzisenu*

GitHub is a popular platform for hosting and collaborating on code. It provides a number of features that make it easy for developers to work together, including pull requests. A pull request is a way to propose changes to a project that can then be reviewed and merged by other developers.

To collaborate on a project on GitHub using the git pull method without branching, you will need to follow these steps:

1. Create a repository on GitHub.
2. Invite your partner as a collaborator.
3. Clone the repository using your personal access token (PAT).
4. Create file and make changes.
5. Push your changes to the remote repository.
6. Pull changes made by your partner.

**Creating a Repository**

1. Go to the GitHub website and click on the "Create Repository" button.
2. Enter a name for your repository and select the appropriate options.

**Inviting Your Partner as a Collaborator**

1. Go to the repository's "Settings" tab on GitHub.
2. Click on the "Collaborators" button.
3. Enter your partner's GitHub username or email address and click on the "Add Collaborator" button.

**Cloning the Repository**

1. Open your terminal or Git Bash.
2. Run the following command to clone the repository:
   ```
   git clone https://your-personal-access-token@github.com/repo-creator's-username/repository-name.git
   ```

**Creating Files and Making Changes**

1. Navigate to the cloned repository in your terminal (change directory into the cloned repo).
2. Create new file or modify existing one using any text editor.
3. Save your changes.

**Pushing Your Changes to the Remote Repository**

1. Run the following command to add and commit your changes:
   ```
   git add .
   git commit -m "Description of your changes"
   ```
2. Push your changes to the remote repository using the following command:
   ```
   git push origin master
   ```

**Pulling Changes Made by Your Partner**

*Your partner needs to do the following in order to have his repo updated on their computer.*

1. Run the following command to pull your partner's changes:
   ```
   git pull
   ```
   **Or**
   ```
   git pull origin master
   ```
   
 > **NOTE**
 > *Both of you need to repeat the git pull command alternatively until you finish with the project.*
 >  *If your partner pushes and you do not pull before pushing a new file, you will have error doing so.*

**Conclusion**

Collaborating on a project on GitHub using the git pull method without branching allows developers to work together efficiently. By following the steps outlined in this article, you and your partner can easily collaborate on projects, share code changes, and keep your work synchronized. Enjoy collaborating on your projects using GitHub!

**My Social Handles**

* **[YouTube](https://www.youtube.com/@esianyo/featured)**
* **[GitHub](https://github.com/esianyo)**
* **[LinkedIn](https://linkedin.com/in/esianyo)**
* **[Twitter](https://twitter.com/esianyo_)**
* **[Instagram](https://instagram.com/esianyo__)**
* **[Facebook](https://facebook.com/esianyod)**
