# zombies-website
This is an ongoing project that aims to create a website for the *After the Zombie Apocalypse* (PHYS-140) course at Saint Mary's College of California. It will primarily showcase student projects and tutorials.
## Contributors
#### Program Manager
* Professor Boyda - [eboyda](https://github.com/eboyda)

#### Developers
* Guy Whittall-Scherfee - [gsw2](https://github.com/gsw2)
* Robert Posada - [robertposada](https://github.com/robertposada)
* Jung Kim - [kjungsoo](http://github.com/kjungsoo)
* Kevin Nguyen - [Nagoogin](https://github.com/Nagoogin)

## Task List (Tentative)
- [ ] Collect and choose images/backgrounds for the site.
- [ ] Finalize site content (sections/text).
- [ ] Create basic layout for page(s) in **html**.
- [ ] Create style guide and consolidate in single **css** file.

#### Helpful Links
* [w3schools](http://www.w3schools.com/)
* [css-tricks](https://css-tricks.com/)

## Directions for getting a local repository on your machine
1. Fork the repository for a copy on your account.
2. Go to your fork and copy the link to the repo.
3. In your terminal/shell, change directories using the `cd` command to get to your designated gitHub directory. If you don't have a dedicated gitHub directory yet, create one.
4. Proceed to clone the repo into a local repository on your machine using `git clone link-name-here`. The code in the terminal/shell should look as follows:
```
Kevins-MacBook-Pro:~ kevinnguyen$ cd Desktop/Repos/
Kevins-MacBook-Pro:Repos kevinnguyen$ git clone https://github.com/Nagoogin/zombies-website.git
Cloning into 'zombies-website'...
remote: Counting objects: 9, done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 9 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (9/9), done.
Checking connectivity... done.
Kevins-MacBook-Pro:Repos kevinnguyen$
```

## Directions for pushing changes to your fork
1. Make sure the files that you edited are inside your local repository. You can check changes using the command `git status`. 
2. When you're ready to push changes to your gitHub account, add the files to be changed using the command `git add file-name` or alternatively, you can use `git add .` to stage all changed files to be committed and pushed.
2. To commit your changes type `git commit -m "commit-message-here"`. The commit message should be short and descriptive, as well a full sentence.
3. Finally, push your changes to your fork of the repository online by entering the command `git push origin master`. A typical stream of commands would look as follows:

```
Kevins-MacBook-Pro:zombies-website kevinnguyen$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
Kevins-MacBook-Pro:zombies-website kevinnguyen$ git add .
Kevins-MacBook-Pro:zombies-website kevinnguyen$ git commit -m "Test commit to show git commands"
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
Kevins-MacBook-Pro:zombies-website kevinnguyen$ git push origin master
Everything up-to-date
Kevins-MacBook-Pro:zombies-website kevinnguyen$
```
Of course, when you do this, there will be actual changes to commit to your fork.


