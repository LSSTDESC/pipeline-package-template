# pipeline-package-template

[cookiecutter](https://cookiecutter.readthedocs.org/en/latest/) template for DESC Pipeline packages

### Usage:
```
cookiecutter https://github.com/LSSTDESC/pipeline-package-template
```

After creating your repository, `cd` into it and do
```
git init
git add .
git commit -m "initial commit"
```
It is now ready for [pushing to GitHub](https://help.github.com/articles/create-a-repo/) and connecting to [Travis CI](https://travis-ci.org/).

You'll want to check that the package is set up the way you want it by browsing the files that `cookiecutter` made. Here are some things to watch out for:

* The LICENSE file adopts the BSD license recommended by the CI group, with the following Copyright statement that you might want to edit:
```
Copyright (c) 2018, the {{cookiecutter.repo_name}} contributors on GitHub, https://github.com/LSSTDESC/{{cookiecutter.repo_name}}/graphs/contributors.
All rights reserved.
```


### Feedback, License etc

If you have comments, suggestions or questions, please [write us an issue](https://github.com/LSSTDESC/pipeline-package-template/issues).

This is open source software, available for re-use under the modified BSD license.
