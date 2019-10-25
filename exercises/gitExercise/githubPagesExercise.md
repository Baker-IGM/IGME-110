# GitHub Pages Exercise

In today's exercise you'll create a GitHub account, add a new repository, upload your files to it, and create a GitHub Page for it.

## Part 1: Creating a GitHub Account and Repository

If you don't already have a GitHub account, go to <https://github.com> to create an account. (You can use whatever userid you'd like, it doesn't have to be your RIT ID if you don't want it to be.)

Once your account has been created and validated, you'll be asked if you want to create a new repository. Create one called 110exercise. Make it public, and initialize it with a README.

![Screenshot of new repo page](newRepo.png)

You'll be taken to the main page of your new repository. Leave it open in the browser while you complete the next steps.

## Part 3: Cloning the Repository to Your Computer

In the top right corner of your repository page, there's a green button that says "Clone or Download". Click that button, and you'll see a URL that you can use to clone the repository to your machine. Copy that URL.

(Cloning creates a copy of the repository that's linked to the master version on GitHub; downloading retrieves copies of the files but doesn't link them to the original repository.)

Launch VS Code, and from the file menu, choose View --> Command Palette.

Type in `git:clone`. You should see that command appear below the entry box; select it, and VS Code will prompt you for the URL that you just copied from GitHub. Paste that in and press Enter.

VS Code will prompt you for a location for your files. Once you've selected a location, VS Code will create a directory for the repository files using the name of the repository, and will retrieve copies of any files in the repository (which right now should just be the README.md file). When it's done, it will ask if you want to open the new repository (either in the current window, or in a new window).

Here's a video showing the cloning process: <https://youtu.be/hNMkIF0klow> 
