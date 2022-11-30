# simon-javascript

This implementation of Simon demonstrates the use of basic JavaScript for interactivity and makes the application completely functional. The application has a login (home), game play, high scores, and about page. Each page contains a header that provides navigation between the pages, and a footer that references the source repository.

You can view this application running here: [Example Simon JavaScript](https://simon-javascript.cs260.click)

## Study this code

First, get familiar with what this code teaches.

- Clone this repository to your development machine.
  ```sh
  git clone https://github.com/webprogramming260/simon-javascript.git
  ```
- Review the code and get comfortable with everything it represents.
- View the code in your browser by hosting it using the VSCode LiveServer extension.
- Make modifications to the code as desired. Experiment and see what happens.

## Make your own version

- Create a new GitHub repository named `simon-javascript`.
- Clone the repository to your development environment.
- In your `simon-javascript` directory create your own version of the project. Refer to the example class project repository if you get stuck.
- Set the footer link to point to your code repository. (e.g. https://github.com/yourname/simon-javascript)
- Periodically commit and push your code to your repository as you hit different milestones. (4 commits are required for full credit.)
- Periodically deploy to your production environment using a copy of the `deploy.sh` script found in the [example class project](https://github.com/webprogramming260/simon-javascript/blob/main/deploy.sh). Take some time to understand how it works.
  ```sh
  ./deploy.sh -k <yourpemkey> -h <yourdomain> -s simon-javascript
  ```
- Update your `simon-javascript` repository README.md to record and reflect on what you learned.
- When you have completed your version. Do a final push of your code and deploy to your production environment using the `deploy.sh` script.
- Make sure your project is visible from your production environment (e.g. https://simon-javascript.yourdomain).
- Submit the URL to your production environment for grading using the Canvas assignment page.

## Grading Rubric

- 60% - Valid game play
- 20% - Capture and store username in scores
- 10% - At least four Git commits for the project (Initial, milestone, ..., milestone, final)
- 10% - Notes in your GitHub repository README.md about what you have learned
