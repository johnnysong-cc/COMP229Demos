# GitHub quirks of authorization
GitHub supports connection from local repos via HTTPS and SSH. For HTTPS connection, the url provided does not work any more and needs to be changed using the following command:
```bash
git remote set-url orgin https://[username]@github.com/[username]/[reponame]
```
A prompt for pernal access token may show up if there is no personal access token in the global configuration file of Git.
