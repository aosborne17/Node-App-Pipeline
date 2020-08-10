
### removing the remote

We want to remove the remote and add our own remote, thus we can point it to our own repository
```commandline
git remote rm origin
```

Now when we run ```git remote --v```, there shouldn't be any remote's

We will now make a repo from which we will have this folder point to, after we have created the repo we run the following
command
```commandline
git@github.com:aosborne17/Node-App-Pipeline.git
```

or for http we could run
```commandline
git remote set-url origin https://github.com/aosborne17/Node-App-Pipeline.git
```

We can now push to github
```commandline
git push -u orgin master