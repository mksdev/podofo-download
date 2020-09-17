Scripts taken from:

* https://danielpocock.com/automatically-mirroring-svn-repositories-to-git-and-github/
* https://github.com/dpocock/sync2git

Ubuntu

```
sudo apt-get install git-core 
sudo apt-get install subversion 
sudo apt-get install git-svn
```

To mirror the repository edit destination `GIT_REPO` in `config.sh`. Run `mirror.sh`. Mirror script can be used in cron job for automatic mirroring feature. Since this repository is not that acive It might be better to just run in manually once a month. 