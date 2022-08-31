[//]: # (<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>)
[//]: # (<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>)

<!-- Styling -->
<style>
    label {
        display: block;
    }
    form input {
        display: block;
        padding: .5rem;
    }
    .contact-icons {
        width: 25px;
    }
    #collab-cards {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-evenly;
        padding: 2rem;
    }
    .collaborator-card {
        width: 25%;
        background: #eee;
        padding: 1rem;
    }
    .collaborator-card > p {
        font-weight: bold;
        margin-top: .5rem;
    }
    .collaborator-card > article {
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    .social-contacts > a {
        width: 10%;
        margin-right: 1rem;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>
<!-- End Styling -->

# family-directory
## A family directory where a user can easily and quickly find known and yet to be known members of their family. Immediate family, in-laws, extended family - see everyone you're related to here!
&thinsp; &thinsp;
## How You Can Collaborate With Us
#### Contact me or anyone of the Project Owners or Engineering Leads via anyone of the contact methods below and we may then invite you as a collaborator to the project, as well as the projects Discord server and kanban board. 
&thinsp;
### 1. `cd` into the local directory you'll want to work from.
- `$ cd Desktop/`
### 2. Clone the github repository.
- `$ git clone https://github.com/richardxessien/family-directory.git`
### 3. `cd` into local repository.
- `$ cd family-directory/`
### 4. Create a new branch.
- `$ git checkout -b branch-name`
### 5. After making your changes and before pushing your code to the remote repository, ensure you pull the latest changes to avoid possible merge conflicts.
- `$ git pull origin main`
### 6. Stage changes that are to be committed. Multiple files
- `$ git add file-name(s)` or `$ git add .`
### 7. Commit your changes.
- `$ git commit -m "Short Description of Change(s) Made"`
### 8. Push changes to remote repository via your branch
- `$ git push origin branch-name`

&thinsp;
##### **Pull requests will be reviewed by 2 Engineering Leads before merging.***

&thinsp;
## Collaborators
&thinsp;
<section id="collab-cards">
    <div class="collaborator-card">
        <img src="./collaborator-avatars/essien-richard.jpg" alt="Photo of Richard Essien">
        <p>Essien, Richard<br>| <em>Project Owner</em><br>| <em>Lead Engineer</em></p>
        <article class="social-contacts">
            <a href="https://twitter.com/richardxessien"><img src="./icons/twitter-svgrepo-com.svg" alt="twitter icon"></a>
            <a href="https://linkedin.com/in/richardxessien"><img src="./icons/linkedin-svgrepo-com.svg" alt="linkedin icon"></a> 
            <a href="https://m.me/richardxessien"><img src="./icons/facebook-svgrepo-com.svg" alt="facebook icon"></a>
            <a href="https://github.com/richardxessien"><img src="./icons/github-svgrepo-com.svg" alt="github icon"></a>
        </article>
    </div>
    <div class="collaborator-card">
        <img src="./collaborator-avatars/meyers-lewis.jpg" alt="Photo of Lewis Meyers">
        <p>Meyers, Lewis<br>| <em>Lead Engineer</em></p>
        <article class="social-contacts">
            <a href="https://twitter.com/Lew_SE_"><img src="./icons/twitter-svgrepo-com.svg" alt="twitter icon"></a>
            <a href="https://www.linkedin.com/in/lewis-meyers-21500272"><img src="./icons/linkedin-svgrepo-com.svg" alt="linkedin icon"></a> 
            <a href="https://m.me/lewis.meyers.58"><img src="./icons/facebook-svgrepo-com.svg" alt="facebook icon"></a>
            <a href="https://github.com/LewCodeSE"><img src="./icons/github-svgrepo-com.svg" alt="github icon"></a>
        </article>
    </div>
</section>