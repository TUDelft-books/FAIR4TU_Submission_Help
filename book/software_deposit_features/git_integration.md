# Git Integration for Software Uploads

The 4TU.ResearchData repository provides seamless Git integration regardless of the code-hosting platform used (e.g. GitHub, GitLab etc.). This integration allows researchers to efficiently manage software submissions while leveraging Git’s powerful version control capabilities, enhancing the visibility and credibility of their contributions. 

Git integration can be established through the clear instructions provide by 4TU.ResearchData and has several benefits: 

- **Version Control:** Maintain a clear version history, ensuring collaborators and users can access specific versions of the code associated with research outputs.

- **Linking:** Published code on 4TU can be linked to the ‘live’ version on your code-hosting platform.

## Uploading Software Files Using Git Integration

Once you are on the 4TU.ResearchData repository upload interface, you can publish software, including version history and related documentation, by connecting your Git repository with 4TU.ResearchData. 

**This short screencast provides you with a step-by-step demonstration on how to upload software using Git integration. 

<div class="responsive-iframe-container">
    <iframe src="https://youtu.be/embed/NtX72arJiqg" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>

**Below is a summary of the steps you need to follow: **

1. Log into the 4TU.ResearchData repository upload interface to get to ‘DASHBOARD.’ 

2. From the ‘MY DASHBOARD’ tab select ‘ADD NEW DATASET.’ 

3. [(Fill in the metadata fields as suggested in ‘Submission Workflow.’)](/submission_workflow/intro)

4. Once you reach the ‘Files’ section, click on the ‘Software deposit’ tab. There you can see Git commands that you can use to publish your software through Git:

    a. `git remote add 4tu <Git URL provided by the metadata form>`
    - Adds the 4TU remote.

    b. `git push 4tu --all`
    - Uploads all branches and their complete history.

    c. `git push 4tu --tags`
    - Pushes tagged releases that mark significant points in development.

    d. `git remote remove 4tu`
    - Removes a connection with a previous version URL if you publish an updated version of your software.
        - You need to establish a connection with the updated version URL which  is assigned by the metadata form. 

5. In the project terminal window, navigate to your software project folder.

6. Copy `git remote add 4tu <Git URL provided by the metadata form>` (1st command) and paste it in the terminal window. Press enter.

7. Copy `git push 4tu --all` and `git push 4tu --tags` (2nd command) and paste them in the terminal window. Press enter.

8. Copy `git remote remove 4tu` (3rd command) and paste it in the terminal window. Press enter. 
  
9. In ‘Git repository files and branches,’ click the ‘refresh’ (🔄) button to see changes. 

10. Under ‘Git default branch,’ select from the dropdown menu the branch that users land on after cloning the Git repository.

11. Add a Git repository name that will be used as a folder name when cloning the repository.

12. Under ‘Code hosting project URL,’ you can add a link to the ‘live’ version of your code on the  code-hosting platform.

13. Finally, in ‘Git file list,’ check to ensure that all the relevant files are present.  

14. Agree to ‘Terms and agreement,’ save the draft and, then click ‘Submit For Review’’ at the top of the page. 

Your latest version DOI will be the default.  

For more information on managing versions of your published software (also data and collections), see [Updating Deposited Data](/submission_workflow/updating_deposited_data). 

