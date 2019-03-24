# Syncthing Ignore Patterns
If you use [Syncthing](https://syncthing.net/) and there are some files should not be synchronized to other devices, a file called .stignore can be created containing file patterns to ignore. The ```.stignore``` file must be placed in the root of the folder. The ```.stignore``` file itself will never be synced to other devices, although it can #include files (in our case is ```.stglobalignore``` file) that are synchronized between devices. All patterns are relative to the folder root.

More Infos about ignore patterns from official syncthing website: [Syncthing ignore patterns](https://docs.syncthing.net/users/ignoring.html)

---

### There are two ways to use this ignore patterns function:

* Just copy all ```.stglobalignore``` contents in to ```Folders``` ⇢ ```Edit``` ⇢ ```Ignore Patterns``` window

    or
* Copy both ```.stignore``` and ```.stglobalignore``` directly into your folder root

    or

* Paste following code into ```Folders``` ⇢ ```Edit``` ⇢ ```Ignore Patterns``` window and copy the ```.stglobalignore``` into folder root
    ```     
    // .stignore

    #include .stglobalignore
    ```

---