# Notes for the project

We have 1 month(?) to complete :)

## Guidelines

1. Keep the code modular, the project is structured such that it forces you to keep it modular. Since the tasks are divided b/w groups, modularity is necessary to put the whole program together.
2. Create a folder in the `modules` directory with your team number and module name. _Eg: If you are working on check in, and your team number is 3, make a folder named `3-checkin`_.
3. In your module folder, create a file named `checkin.c`, `checkin.h`. The `checkin.c` can have multiple functions but all those functions must be used inside a `checkin()` function. Imagine the `checkin()` fucntion to be the `main()` function of your modukle.
4. All variable names must be `camelCase`, and all function names should be in `snake_case`.

## Getting started

1. Create an account on github.
2. Go to the top of this page and click on the fork button OR click on this link - [Fork this repo](https://github.com/shivangjhalani/airport-sim/fork). A copy of this repository will be created on your own account. No need to edit the Repository name field.
   ![Screenshot from 2024-04-17 15-26-09](https://github.com/shivangjhalani/airport-sim/assets/137867387/31326b14-e079-42d9-b739-c2d9542c126c)
   ![Screenshot from 2024-04-17 15-26-31](https://github.com/shivangjhalani/airport-sim/assets/137867387/3894353d-2c59-4502-ae77-5411fce9d309)
3. Copy the link to your github repo.
   ![Screenshot from 2024-04-17 15-30-15](https://github.com/shivangjhalani/airport-sim/assets/137867387/f4a0cae4-20b3-418c-b96f-9f66f6d3bb50)
4. Navigate to the folder you want to clone the project in windows explorer.
5. Right click on empty area and open terminal in the current folder and enter this command. A folder will be created with the repository code inside it.

```bash
git clone <copied_url>
```

6. Remember, this is just a clone, the code on this wont be automatically updated whenever the main repository code changes. If you want to update your clone, sync your cloned repo and in the terminal, enter this command.
   ![Screenshot from 2024-04-17 15-28-22](https://github.com/shivangjhalani/airport-sim/assets/137867387/dfe2e307-d6b3-4bd6-adfc-2b2b7cb934fc)

```bash
git pull
```

7. Continue the work... It's a good practice to commit and push your changes from time to time, if not, just commit and push your code by using `git add .` and `git commit -m "<commit_message>"` and `git push`. You might need to go to the Learn git section below in order to understand what you are doing here.
8. All the code that you write on your computer will live there only locally. After your team has completed the work, you must create a `PULL request` in order to upload your code to the main repository.

## Learn git

Git is a very handy tool that you should learn. Its gonna help you a lot in future, might as well learn it rn.
_Git is a version control system used to keep track of changes in code, and it is also very useful in this case to collaborate on a project. Its like a google drive for code, the code is always up-to-date with changes others make._

- Learn git and github, Watch the video tutorial or read. Its recommended to watch the video tutorial if you can take out time.
  - [Git guide](https://rogerdudler.github.io/git-guide/)
  - [Video tutorial](https://youtu.be/2sjqTHE0zok?si=bANJHZ7cXQy0vkqT)
  - [Small blog](https://40dev.com/2023/01/getting-started-with-git-and-github/)
