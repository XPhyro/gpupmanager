# gpupmanager

gpupmanager is a tool that manages the [gpup](https://github.com/int128/gpup) library. gpup normally does not keep logs of what it uploaded, and therefore can upload the same thing more than once. gpupmanager reads the stdout of gpup and keeps its logs, then issues the unuploaded files to gpup the next time it is executed.

# Important note

This tool is designed for personal usage, and is in no way a shipped product. There are no config files or passed arguments, if you would like to use your own directory structure, then you will have to edit the source, which should not be too hard.

# License

gpupmanager is provided as is. See the file [LICENSE](LICENSE) for more information.
