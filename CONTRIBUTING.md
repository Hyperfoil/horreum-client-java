# 🧑‍💻 Contributor flow
There are some steps that you need to follow before making any contribution in this project, the following steps are important to get start.

**Note:** If you don't know how to set up this project locally? Please first Checkout the [README.md](./README.md) to set up the project locally and then follow the steps.

## Follow the Steps

- [Fork the repository](https://github.com/Hyperfoil/horreum-client-java/fork)
- Clone the project locally 

``` 
git clone https://github.com/<username>/horreum-client-java.git 
``` 
**Note:** And in the place of `<username>` you have to add your GitHub username.

- Create a new branch

```
git checkout -b <your branch_name>
```

After creating new branch start making your changes and once the changes done then push your changes in your fork version of project which is know by default `origin `

- Push your changes

```
git push origin <your branch_name>
```

Now you can check your change in your fork version and then create a `pull_request` and wait for the review. The project maintainer will review your PR and then they will merged it. If you want to support, please give a ⭐

### Things to remember before making changes

Before making any contribution make sure your local master keep up-to-date with upstream master. To do that type the following commands.

- First add upstream
```
git remote add upstream https://github.com/Hyperfoil/horreum-client-java.git
```
- Pull all changes from upstream
```
 git fetch upstream
```
- Keep your fork up-to-date
```
  git rebase -i upstream/main
```
- Creating a branch
```
git checkout -b myfeature main
```
