How do you create and checkout a new branch from command line?

<details>
<summary>using one command</summary>

```bash
# create a new branch and move at the same time
git checkout -b <new-name>
```

</details>

<details>
<summary>using two commands</summary>

```bash
# create the branch and stay where you are
git branch <new-name>

# move to the new branch
git checkout <new-name>
```

</details>
