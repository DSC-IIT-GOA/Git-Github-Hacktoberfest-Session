# Git Comand To Be Used!

## Clone any Repository

- In place of `<GitHub Repository>` add the GitHub Repository's URL

```{r eval=FALSE}
git clone <GitHub Repository>
```

## Initialise Git

```{r eval=FALSE}
git init -b main
```

## add a file

- In place of `<file name>` add the file name

```{r eval=FALSE}
git add <file name>
```

## add all files

```{r eval=FALSE}
git add .
```

## To view the status

```{r eval=FALSE}
git status
```

## To commit

- `-m` is for writing the commit in the command line itself

```{r eval=FALSE}
git commit -m "commit message"
```

## Add remote

- `origin` is like a place holder for the `<Address of the repository(.git)>`

```{r eval=FALSE}
git remote add origin <Address of the repository(.git)>
```

## Check remote

```{r eval=FALSE}
git remote
```

## check remote url

```{r eval=FALSE}
git remote -v
```

## push the repo

- Copy past this line of code

- push your commits on branch `<branch name>`

```{r eval=FALSE}
git push -u origin <branch name>
```

## See Log

```{r eval=FALSE}
git log
```

## Create Another Branch

- Create a new branch with name `<new branch name>`

```{r eval=FALSE}
git branch <new branch name>
```

## Change Branch

- Jump from the current branch to another branch `<branch name>`

```{r eval=FALSE}
git checkout <branch name>
```
