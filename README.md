# git_client

Graphical Git client module for UliCMS.

## Requirements

* UliCMS 2019.2 and later
* the git executable file must be contained in $PATH
* The patch HttpStatusCode422 is required for UliCMS 2019.2

### Usage

With git_client you can versionize your UliCMS site using a git repository.
The module can only handle existing repositories.
It doesn't support to create new repositories.

The version 1.0 supports the following commands
* git add
* git commit
* git push
* git pull
* git fetch
* git checkout
* git branch