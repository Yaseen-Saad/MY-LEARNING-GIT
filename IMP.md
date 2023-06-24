## Important Commands

- `ls` - this command is used to list the files and directories in the current directory
- `touch + fileName` this command is used to create a file
  i.e : `touch index.html`
- `git add + fileName` this command is used to tell git which files to commit
  i.e : `git add index.html`
- `git status` this command is used to check the current status of the repository
  i.e : `git status `

```
    On branch main
        Your branch is based on 'origin/main'

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   IMP.md
        modified:   index.html

```

- `open + fileName` this command is used to open the file
  i.e : `open index.html`

- `git commit -am + message` this command is used as a mix for the `git commit -m ` and the `git add .` command
  i.e : `git commit -am 'HYPERX'`

## Important Notes

##### **conflicts looks like :**


```
$ git pull

> Auto-merging index.html
  CONFLICT (content): Merge conflict in index.html
  Automatic merge failed; fix conflicts and then commit the result.

```
```js
 <<<< HEAD
 "your changes"
 ====
 "The repository changes"
 >>>>> conflict id
```
i.e :

```
<<<<<< HEAD
    <h1 style="color:green">YASEEN</h1>
======
    <h1 style="color:red">YASEEN</h1>
>>>>>> 1ac3239ab6740f07f1c241b2a236e18a2eda2545
```