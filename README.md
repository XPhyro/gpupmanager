# gpupmanager

gpupmanager is a tool that manages the [gpup](https://github.com/int128/gpup) library. gpup normally does not keep logs of what it uploaded, and therefore can upload the same thing more than once. gpupmanager reads the stdout of gpup and keeps its logs, then issues the unuploaded files to gpup the next time it is executed.
