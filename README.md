# Notes for the project

## Learn git (Optional)

_Git is a version control system used to keep track of changes in code, and it is also very useful in this case to collaborate on a project. Its like a google drive for code, the code is always up-to-date with changes others make._

- Learn git and github

  - [Video tutorial](https://youtu.be/2sjqTHE0zok?si=bANJHZ7cXQy0vkqT)

- Getting started
  - [Option 1](https://40dev.com/2023/01/getting-started-with-git-and-github/)
  - [Option 2](https://rogerdudler.github.io/git-guide/)

#### Quick start if not want to learn...

```bash
# - Navigate to the folder you want to clone the project in windows explorer.
# - Right click on empty area and open terminal in the current folder
git clone https://github.com/shivangjhalani/airport-sim.git
# - A folder with name airport-sim will be created
```

## Guidelines

1. Keep the code modular, the project is structured such that it forces you to keep it modular. Since the tasks are divided b/w groups, modularity is necessary to put the whole program together.
2. Create a folder in the `modules` directory with your team number and module name. _Eg: If you are working on check in, and your team number is 3, make a folder named `3-checkin`_.
3. In your module folder, create a file named `checkin.c`, `checkin.h`. The `checkin.c` can have multiple functions but all those functions must be used inside a `checkin()` function. Imagine the `checkin()` fucntion to be the `main()` function of your modukle.
4. All variable names must be `camelCase`, and all function names should be in `snake_case`.
