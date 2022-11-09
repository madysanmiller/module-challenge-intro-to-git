## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?

"Git is the most popular distributed version control system. Git is commonly used for both open source and commercial software development, with significant benefits for individuals, teams and businesses."
2. What is the difference between Git and GitHub?

Git is a software hosted on a local system using command lines, and Github is a web service that uses a graphic interface.
3. Why do we create a branch?

Branches make it possible to fix bugs,develope new features, or experiment with your repo without having to worry about the changes others are making to the repo.
4. What is the purpose of a Pull Request?

To let others know that changes have been made to a branch of the repo, once the pull request has been opened others can review and discuss the changes as well as as add follow up changes before the branch is merged with the original repo.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.

The easiest way to switch branches on Git is to use the “git checkout” command and specify the name of the branch you want to switch to.
 $ git checkout <existing_branch> $ git checkout -b <new_branch>
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?

Fetch: downloads all the changes needed to represent the given remote branch.
Merge: merges two branches together by creating new commits or fast-forwarding (or a combination). It doesn't change any commits you have made.
Pull: ust git fetch followed by git merge
7. What is a merge conflict?

"Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file."
8. How do you resolve a merge conflict?

The answer is to long to type out so im going to insert the github.docs page for the answer.

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line 
