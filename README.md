# prework-study-guide
Boot Camp Prework Study Guide for Students

Some questions:
1. How to remove a file that was created during creation of a repo?
2. When setting up the .ssh/config file , I came across the following:

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/using-ssh-agent-forwarding

Warning: You may be tempted to use a wildcard like Host * to just apply this setting to all SSH connections. That's not really a good idea, as you'd be sharing your local SSH keys with every server you SSH into. They won't have direct access to the keys, but they will be able to use them as you while the connection is established. You should only add servers you trust and that you intend to use with agent forwarding.

In that case above, what are the server we will be using that we trust?

3. After setting the ssh key, why I can not see the option to use ssh during login to Github?
4. When opening the VS Code from CLI in Mac, Explorer is not displayed and the prework-study-guide repo not displayed to?
5. Find and educate myself more on "Branching"
6. Explain the following:
   amrshehata@Amrs-MBP prework-study-guide % git status
   On branch main
   Your branch is up to date with 'origin/main'.

   Untracked files:
  (use "git add <file>..." to include in what will be committed)
	assets/
	index.html
7. Not sure what has happened here:

   amrshehata@Amrs-MBP prework-study-guide % git pull origin main
remote: Enumerating objects: 14, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 12 (delta 8), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (12/12), 2.94 KiB | 251.00 KiB/s, done.
From github.com:WFlorida2/prework-study-guide
 * branch            main       -> FETCH_HEAD
   96d64d4..db7d38a  main       -> origin/main
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.

8. How I ended up with 2 prework-study-guide as shown on my VSC explorer screen?
9. How to use Version Control to save our work (Very important to memorise):
    https://bootcampspot.instructure.com/courses/5650/pages/2-dot-4-6-use-git-version-control-to-save-our-work?module_item_id=1132101

   
10. We use the -m flag to associate a message with our commit. Commit messages should be short descriptive messages of the changes implemented. Once completed, our Git repository is now up to date with our working directory!

You should see the following output in your terminal:

[feature/add-html 46a625e] added code to HTML file
1 file changed, 47 insertions(+)
create mode 100644 index.html  ( This line was not present)


REMEMBER : Saving and tracking changes to the repository is an extremely important part of building any coding project.
