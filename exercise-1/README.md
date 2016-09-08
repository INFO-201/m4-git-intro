# Exercise-1

The purpose of this exercise is to practice the steps you'll need to use in future exercises. We'll begin by configuring your GitHub account for your machine (which you'll only need to do once), and then move through the steps of working with Git and GitHub (which will soon become second nature).

1. If you haven't already, configure your name and email address for your GitHub account using the terminal.

  ```bash
  # Set your name
  git config --global user.name "YOUR NAME"

  # Set GitHub email - make sure it matches your account online
  git config --global user.email "YOUR EMAIL"
  ```

2. Fork this repository (`info-201/m4-git-intro`) to your own GitHub account by clicking the `fork` button on the GitHub interface.

  ```bash
  #  Click the `fork` button to fork it to your account
  ```

3. Using your terminal, clone **your forked repository** to your machine (make sure you're in the desired directory on your terminal)

  ```bash
  # Enter a desired directory
  cd ~/Documents

  #  Get the URL by clicking the "Clone or Download" button on GitHub, then clicking the clipboard icon

  # Clone the repository
  git clone https://github.com/YOUR-USER-NAME/m4-git-intro
  ```

4. On your machine, open up this file (`exercise-1/README.md`) in a text editor of your choice

  ```bash
  # Open up the file
  ```

5. In the `README.md` file, make an ordered list of what you ate for breakfast today

  ```
  1. Coffee
  2. Banana
  3. Cheerios
  ```

6. Using your terminal, add and commit the changes you've made to your repository

  ```bash
  # Make sure that you're in the cloned repository
  cd m4-git-intro

  # Add changes from all files in the repository
  git add .

  # Commit changes making sure to include a descriptive message
  git commit -m "DESCRIPTIVE MESSAGE HERE"
  ```

7. Push changes up to GitHub

  ```bash
  # Push changes
  git push origin master
  ```
