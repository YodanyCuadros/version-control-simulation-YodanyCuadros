# Project Reflection: Git Version Control Simulation

I kept to a careful process for this project that simulated actual Git collaboration. As instructed, I started by making a new GitHub repository called `version-control-simulation-YodanyCuadros` and did not initialize it with a README.

After that, I made a new feature branch called `feature/header` and cloned the repository to my local computer. I staged the file using `git add`, added a straightforward `index.html` file with a basic header structure, and committed the change with a comment to this branch.

After that, I went back to the `main` branch and made a new branch called `feature/footer`. In this branch, I added a footer section to the same `index.html` file and also committed the change.

I went back to `feature/header` and changed the footer section there to mimic a merge conflict. I then attempted to merge the `feature/header` into `main` after merging the `feature/footer` branch into `main`, which caused a planned conflict.

I opened `index.html`, located the Git-marked conflicting code, and manually resolved the conflict by selecting which changes to retain. To finish the merge, I staged and committed the fixed file. I made sure I was properly managing changes and keeping track of any unresolved conflicts throughout the process by using `git status`.

After resolving everything locally, I pushed the updated `main` branch to GitHub and created a pull request from `main` to a new branch named `review/main`. I included a clear description of the changes I made.

This project helped reinforce my understanding of Git fundamentals, especially around branching, conflict resolution, and collaborative workflows through pull requests. It showed me how important clear commit messages and a clean history are for team-based development.
