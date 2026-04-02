### csai-autonomous-navigation

## Setup
How to clone and setup the github repository. 

## Branches and Pull Requests
Please use branches and pull requests when completing tasks so that our working code remains intact and our work doesn't become overwritten. 
If you already know how this works, feel free to skip. 

### Branching Setup
1. Next to `main` on the repository homepage, click `Branches`.
2. Make a new branch by clicking `New Branch` with source `main` and give it an legible title with your last name somewhere (ex. Torriani-Autonomous-Team)
3. On your local cloned repo, type in the terminal `git pull` to acknowledge your new branch and `git checkout <your branch>` to select your branch.
4. Whenever you push your code with `git push`, make sure that you are on your branch such that code doesn't get overwritten (I will add safeguards though just in case)

### Pull Requests
1. When you've completed a task that is ready to be incorporated, go to the repository homepage and click `Pull Requests`.
2. Click `New Pull Request` and set the `base` branch to `main` and the `compare` branch to your branch.
3. Give your pull request a clear title and description of what changes you made and select me as a reviewer.
4. Click `Create Pull Request`.

## Commit Message Formalities
Please commit reasonably regularly and use general commit message structure so that it's easier for me to review work and add it in. 
Most importantly, use "feat" when introducing a new feature/new code and "fix" when debugging. For example:
> "feat * added motion detection script"
> "fix * fixed bug in motion detection script"

