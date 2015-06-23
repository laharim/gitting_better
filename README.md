## Gitting Better
We use git everyday, but sometimes forget that there's more than just push & pull

### Git Core
* **Commit:** code changes + parents + who dunnit + why
* **ref:** just a reference
* **HEAD:** ref to current commit
* **branch:**  named reference to some commit
* **tag:**  named reference to some commit
* **remote:** repository where you'll look for commits

### Getting started
* Fork this repo!

1. **Question 1:** Look at the initial commit in the repo. What's it's parent?
2. Create a new branch, call it something creative like `new_branch_<your_name>`
3. Push it up to **your** remote.
4. Add a file in new_branch, called new_file.txt, and push it up. Take note of the commit sha
  3. **Question 2:** How do you find a commit's sha from the command line? in git ui?
5. Oops! You meant to put something in new_file.txt. `echo 'hello' > new_file.txt`
6. You don't want everyone to know how dumb you are
  3. **Question 3:** How do you fix your dumb commit without anyone knowing?
  3. Is the sha from your fixed commit the same as the on from your dumb commit?
7. You've discovered that your project collaborators can't push commits to branches on your remote.
  3. **Question 4:** How do you 'move' a branch from your remote to a different one (you can practice by attempting to move it to mine)
8. What about amending multiple commits?
  3. Maybe you're bad at committing. Maybe you put 'wip' as your commit
     message 9x in a row. Either way, it's time to make things prettier.
  2. Checkout the branch `terrible_commit_history`
  3. Look at the history
  4. Rewind to a point before your terribleness started
  5. Consolidate to commits that make sense
  6. Push em up

### Credit where it's due
These exercises come from a lecture [Kyle Hargraves](https://github.com/pd) gave at [Enova](https://www.enova.com/) 4/15/15. You can find the slides [here](https://docs.google.com/presentation/d/1atduyqxDJNBv6U9QwIEGdsYMvRUmw54HSFXk0lfYfHc) if you're an Enova employee. Otherwise.. well, you're outta luck :)
