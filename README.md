# Syncthing Ignore Patterns
More Infos about [Syncthing ignore patterns](https://docs.syncthing.net/users/ignoring.html).

There are two ways to use this ignore patterns function:

* Just copy all ```.stglobalignore``` contents in to ```Folders -> Edit -> Ignore Patterns``` window

    or

* Paste following code into ```Folders -> Edit -> Ignore Patterns``` window and copy the ```.stglobalignore``` into folder root
    ```     
    // .stignore

    include .stglobalignore
    ```