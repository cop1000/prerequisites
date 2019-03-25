I wasn't able to confirm that the clone occurred, but that's OK, I'm just a :robot:

By default, the clone command uses [HTTPS authentication](https://help.github.com/en/articles/which-remote-url-should-i-use#cloning-with-https-urls-recommended). However, in some cases, you may be unable to clone with HTTPS and you may have to [clone with SSH instead](https://help.github.com/en/articles/connecting-to-github-with-ssh).

### :keyboard: Activity: Try cloning with SSH

1. Check for an [existing SSH key](https://help.github.com/en/articles/checking-for-existing-ssh-keys).
1. If you don't already have an SSH key, [generate a new SSH key and add it to the SSH agent](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).
1. [Add the new SSH key](https://help.github.com/en/articles/adding-a-new-ssh-key-to-your-github-account) to your GitHub account.
1. [Test](https://help.github.com/en/articles/testing-your-ssh-connection) your SSH connection. 
1. Try to clone this repository using the SSH url by typing the following into your shell:
    ```ssh
    git clone {{ sshUrl }}
    ```
1. Paste in the response from your shell. 

If you'd rather bypass this step, type "bypass".

<hr>
<h3 align="center">I'll respond when I detect a comment on this issue.</h3>