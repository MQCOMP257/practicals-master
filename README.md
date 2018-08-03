# COMP257 Practicals 2018

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MQCOMP257/practicals-2018/master)

This repository contains practical notebooks for COMP257/ITEC657 2018.  

The link above to Binder will let you run these notebooks on the [mybinder.org](https://mybinder.org) service, but not that you can't save your work there so it's just for experimentation.

To update your repository when I make changes to this one you need to add a 'remote':

```
git remote add upstream https://github.com/MQCOMP257/practicals-2018.git
```

then each time you want to get new changes:

```
git pull --rebase upstream master
```

Note that the `--rebase` option is not something you would normally use with `git pull`. It is useful 
in this special case when you are pulling changes from an upstream repository and you've made your
own commits locally. 
