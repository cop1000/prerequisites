It didn't look like you were able to push successfully. This may be because you are behind a firewall and need to use a proxy.

### :keyboard: Activity: Use a proxy

1. Confirm that you need to use a proxy with your organization's technical support team. You will need to know:
    - the proxy URL
    - whether the proxy needs authentication
    - if the proxy needs authentication, you'll need to know the username and password.
1. If you proxy:
    - **Does not require authentication:**: type the following into a shell window, replacing `YOUR.PROXY.SERVER` with the proxy's URL:
        ```shell
        git config --global http.proxy https://YOUR.PROXY.SERVER:8080
        ```
    - **Requires authentication:** type the following into a shell window, replacing `YOUR.PROXY.SERVER` with the proxy's URL, and `YOUR_PROXY_USERNAME` and `YOUR_PROXY_PASSWORD` with the credentials needed to authenticate into the proxy:
        ```shell
        git config --global http.proxy https://YOUR_PROXY_USERNAME:YOUR_PROXY_PASSWORD@YOUR.PROXY.SERVER:8080
        ```
1. Navigate into the repository's directory:
    ```shell
    cd {{ repoName }}
    ```
1. Try the push again:
    ```shell
    git push 
    ```

If you'd rather bypass this step, type "bypass".

<hr>
<h3 align="center">I'll respond when I detect a comment on this issue.</h3>