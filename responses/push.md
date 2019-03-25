A push is required to make changes to a remote Git repository. Attempting a push will ensure that you don't have any trouble doing this in class.

### :keyboard: Activity: Try a push

1. Open your shell.
1. Navigate into the repository's directory:
    ```shell
    cd {{ repoName }}
    ```
1. Create an empty commit:
    ```shell
    git commit --allow-empty -m "my empty commit"
    ```
2. Push the commit.
    ```shell
    git push
    ```
3. Enter the result of your push command in a comment.

Your shell may ask you to authenticate with you  username and password. This is your GitHub username and password. Enter it when the prompt appears. The credentials will be encrypted and stored in your machine's [credential helper](https://help.github.com/en/articles/caching-your-github-password-in-git). 

<hr>
<h3 align="center">I'll respond when I detect a comment on this issue.</h3>