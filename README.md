# Git-Branching
## How to remove the Branches (dev, test) Locally and remotely?

-  In order to delete a Local branch we use the command:
`git branch -d brach_name` ie : `git branch -d dev`

-  To delete a Remote branch we use the command:
`git push origin :branch_name` ie : `git push origin :dev`
---------------------------------------------------------------------------------------

## **Annotated** tags *VS* **lightweight** tags.

```
- **Annotated** tags provide more context than **lightweight tags** *(which are just references to commits)*.

- **Annotated** tags allow you to track who created the tag and when.

- They are more suitable for release management or marking important changes.

**lightweight** tag in Git is a simpler type of tag compared to an annotated tag.
 It is essentially a pointer to a specific commit in your Git history, and it doesn't contain any additional information (such as tagger name, date, or message).
```
---------------------------------------------------------------------------------------

## When to use Rebase?.

```
-  Rebase is often used to maintain a clean, linear history.
-  This is especially useful in collaborative environments where you want to avoid a messy commit history created by merges.
-  It avoids creating merge commits and shows a linear progression of changes.
```

---------------------------------------------------------------------------------------
## How to list tags.

We can list all tags using the command ` git tag `

---------------------------------------------------------------------------------------

## How to delete tag locally and remotely? 
-  To delete remote tag `git push origin --delete v1.0`
-  To delete local tags `git tag -d v1.0`
-  
---------------------------------------------------------------------------------------

## Add an image in the README.md file.  
(/images/logo.png)





