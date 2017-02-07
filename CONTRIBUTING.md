# Contributing guidelines to Awesome Dojo

Contributing to this project is very simple. You can open an [issue](https://github.com/petk/awesome-dojo/issues).

Pull requests are welcome as well:

* Fork a project on GitHub

* Set up your repository and set a remote branch for future updates

  ```bash
  $ git add remote upstream git://github.com/petk/awesome-dojo
  $ git config branch.master.remote upstream
  ```

  That way you can update your repository (when the `upstream` gets updated) and automatically pull `upstream` commits:

  ```bash
  $ git pull
  ```

* Create a new Git branch for instance `patch-1`:

  ```bash
  $ git checkout -b patch-1
  ```

  This ensures that your repository will not need rebasing when the `upstream` gets updated.

* Make changes to the `patch-1` branch

  Changes must include libraries or resources that use [Dojo Toolkit](http://dojotoolkit.org) or any project related to
  [Dojo Foundation](http://dojofoundation.org/). Typos and grammatical corrections are perfectly fine as well.

* Commit and push to your GitHub repository

  ```bash
  $ git add .
  $ git commit -m "my new changes"
  $ git push origin
  ```

* Send a pull request
