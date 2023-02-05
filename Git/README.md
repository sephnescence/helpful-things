# git

After having checked out a git repo, make sure your `user.name` and `user.email` configuration is correct. For example, I reformatted my Mac and after checking out this repo, whenever I want to commit to it again it complains about my configuration.

I've have limited success with `git config --global -e` not actually persisting without continually re-opening new tabs in VSCode's terminal

Instead try doing this
```
git config --global user.name "John Doe" && \
git config --global user.email johndoe@example.com
```