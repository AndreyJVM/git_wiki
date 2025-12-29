## Git command
```shell
curl -sSL https://raw.githubusercontent.com/AndreyJVM/git_wiki/main/install_config_git.sh \
    -o /tmp/install_config_git.sh \
    && sudo bash /tmp/install_config_git.sh
```

```shell
git config --global user.name "Andrey Vorobev"
```
```shell
git config --global user.email "Andrey.Vorobev.AQA@gmail.com"
```

```shell
git push origin main -f
```
```shell
git remote -v
git remote set-url origin "new_URI"
```
```shell
git add -f ./target/site/jacoco/
git commit -m "Add jacoco"
git push origin main
```
```shell
git rm --cached <file name>
```
```shell
git stash push --include-untracted
git merge origin/main main
```
